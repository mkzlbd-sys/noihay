# Nói Hay 회화 / Nói Hay – Luyện giao tiếp

베트남어·영어 생활 회화 연습 앱 (한 파일짜리 웹 페이지)
Ứng dụng luyện giao tiếp tiếng Việt · tiếng Anh (một trang web duy nhất)

## 주소 / Đường dẫn

- 앱 파일 / Tệp ứng dụng: `noihay.html`
- 무료 공개 주소 / Địa chỉ công khai miễn phí (GitHub Pages): https://mkzlbd-sys.github.io/noihay/
  - 깃허브에서 고치면 1~2분 뒤 자동 반영 / Sửa trên GitHub, 1–2 phút sau tự cập nhật.
  - 이 주소에서는 AI 회화 탭이 안 됨 (표현 연습·시험·성조·듣기는 됨) / Ở địa chỉ này tab Hội thoại AI không hoạt động (luyện mẫu câu, kiểm tra, thanh điệu, nghe vẫn dùng được).
- AI 회화까지 되는 주소 / Địa chỉ có cả Hội thoại AI (claude.ai, chỉ dùng cá nhân): https://claude.ai/artifact/UoUQj4xq5HChpbFUk4u7qN

## 기능 / Tính năng

- 학습 언어 3가지 / 3 chế độ học: Tiếng Việt / English / **VI + EN**
  - VI + EN: 한 화면에서 보고, 듣고, 시험까지 / xem, nghe và kiểm tra trên cùng một màn hình.
  - 영어 가리기 / Che tiếng Anh: 베트남어를 보고 영어를 먼저 말해 본 뒤 확인 / nhìn tiếng Việt, tự nói tiếng Anh trước rồi mới xem đáp án.
  - 발음 확인 / Kiểm tra phát âm: 🎤 버튼 → 단어별로 맞음·거의 맞음·안 들림 표시 (브라우저 음성 인식, 마이크 허용 필요) / bấm 🎤, hệ thống báo từng từ đúng, gần đúng hoặc không nghe thấy (cần cho phép micro).
  - 단계 통과 기록은 언어별로 따로 저장 / Tiến độ qua màn được lưu riêng cho từng ngôn ngữ.
- 휴대폰 화면 / Màn hình điện thoại: 연습 카드가 목록 위에 먼저 보임, 표현을 누르면 카드로 자동 이동 / thẻ luyện tập hiện trên danh sách, bấm một câu sẽ tự cuộn tới thẻ.
- 화면 언어 / Ngôn ngữ giao diện: 위쪽 `한국어 | Tiếng Việt` 버튼 / nút `한국어 | Tiếng Việt` ở đầu trang. 고정된 버튼·제목만 바뀜 (안내문·시험 결과는 아직 한국어) / chỉ đổi nút và tiêu đề cố định (thông báo, kết quả kiểm tra vẫn bằng tiếng Hàn).

## 휴대폰·아이패드에서 편집하는 법 / Cách chỉnh sửa trên điện thoại, iPad

1. 깃허브에서 `noihay.html`을 연다 / Mở `noihay.html` trên GitHub.
2. 연필 모양(편집) 버튼을 누른다. 키보드가 있으면 `.` 키로 큰 편집기(github.dev) / Bấm biểu tượng bút chì (Edit). Nếu có bàn phím, bấm phím `.` để mở trình soạn thảo lớn (github.dev).
3. 고친 뒤 **Commit changes**(저장) / Sửa xong bấm **Commit changes** để lưu.

## 자주 고치는 곳 / Những chỗ hay sửa

- 문장 추가·수정 / Thêm, sửa câu: `const SCENES`
  - 한 줄 형식 / Định dạng một dòng: `["한국어 뜻","베트남어","한글 발음","English"]`
- 베트남어 단어 풀이 / Giải nghĩa từ tiếng Việt: `const GLOSS`
- 영어 단어 풀이 / Giải nghĩa từ tiếng Anh: `const GLOSS_EN`
- 시험 통과 점수 / Điểm qua bài kiểm tra: `const PASS = 80`

## claude.ai 게시본에 반영하기 / Cập nhật bản đăng trên claude.ai

깃허브에서 고친 내용은 claude.ai 게시본에 저절로 반영되지 않는다 (깃허브 페이지 주소는 자동 반영).
PC의 클로드 코드에 "회화 앱 깃허브에서 받아서 다시 게시해줘"라고 하면 된다.

Nội dung sửa trên GitHub không tự cập nhật sang bản claude.ai (địa chỉ GitHub Pages thì tự cập nhật).
Hãy nhờ Claude Code trên máy tính: "회화 앱 깃허브에서 받아서 다시 게시해줘" (lấy ứng dụng từ GitHub rồi đăng lại).
