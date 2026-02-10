# Vocabulary Learner

단일 HTML 기반 어휘 학습 웹앱입니다.  
React 18, Tailwind CSS, Web Speech API, localStorage 사용.  
오프라인에서도 (최초 로드 후) 동작합니다.

## 기능

- **3권의 책**: Number the Stars (150단어), Chip War (100단어), Essential EAL Vocabulary (100단어)
- **하루 15단어**: 매일 15개만 공부하고, 그날 공부한 단어만 퀴즈로 복습
- **스터디 모드**: 발음 버튼, IPA, 뜻, 예문 3개, "공부함" 저장
- **퀴즈**: 객관식(한국어 뜻) / 빈칸 채우기 (오늘 분량만 출제)
- **진행 저장**: localStorage에 총 학습 단어 + 날짜별 오늘 분량 저장

## 사용법

1. [GitHub Pages](https://YOUR_USERNAME.github.io/Words/) 에서 `index.html` 열기  
   또는 로컬에서 `index.html` 을 브라우저로 열기
2. 책 선택 → "오늘 15단어 공부" → 15개 모두 "공부함" 클릭
3. "오늘의 퀴즈"로 복습

## 배포 (GitHub Pages)

1. 이 저장소를 본인 GitHub에 푸시
2. **Settings → Pages → Source**: `Deploy from a branch`
3. **Branch**: `main` / **Folder**: `/ (root)` → Save
4. 잠시 후 `https://<사용자명>.github.io/Words/` 로 접속
