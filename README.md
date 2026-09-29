# Nói Hay 회화

베트남어·영어 생활 회화 연습 앱 (한 파일짜리 웹 페이지)

- 앱 파일: `noihay.html` (이 파일 하나에 화면·문장·단어 풀이가 다 들어 있음)
- 무료 공개 주소(깃허브 페이지): https://mkzlbd-sys.github.io/noihay/
  - 깃허브에서 고치면 1~2분 뒤 이 주소에 저절로 반영된다.
  - 이 주소에서는 AI 회화 탭이 작동하지 않는다. 표현 연습·시험·성조·듣기는 된다.
- AI 회화까지 되는 주소(claude.ai, 본인만): https://claude.ai/artifact/UoUQj4xq5HChpbFUk4u7qN

## 아이패드·휴대폰에서 편집하는 법

1. 깃허브에서 `noihay.html`을 연다.
2. 연필 모양(편집) 버튼을 누른다. 키보드가 있으면 `.` 키를 누르면 큰 편집기(github.dev)가 열린다.
3. 고친 뒤 **Commit changes**(저장)를 누른다.

## 자주 고치는 곳

- 문장 추가·수정: `const SCENES` 부분
  - 한 줄 형식: `["한국어 뜻","베트남어","한글 발음","English"]`
- 베트남어 단어 풀이: `const GLOSS`
- 영어 단어 풀이: `const GLOSS_EN`
- 시험 통과 점수: `const PASS = 80`

## claude.ai 게시본에 반영하기

깃허브에서 고친 내용은 claude.ai 게시본에는 저절로 반영되지 않는다(깃허브 페이지 주소에는 저절로 반영됨).
PC의 클로드 코드에 "회화 앱 깃허브에서 받아서 다시 게시해줘"라고 하면 된다.
