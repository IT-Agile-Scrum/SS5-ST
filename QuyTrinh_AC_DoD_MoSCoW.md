# Bài tập sáng tạo: Quy trình quản lý AC – DoD – MoSCoW

## Bối cảnh

Đội RikkeiGo nhận story mới từ Marketing, Chăm sóc khách hàng và Vận hành. Scrum Master Lan cần thiết kế một quy trình dùng được cho mọi story để Product Owner Đức xem xét trước khi đưa vào Sprint.

## Phần 1 – Quy trình 5 bước

### Bước 1: Ghi nhận và làm rõ story

- **Việc cần làm:** Người đề xuất ghi mục tiêu, người dùng được hưởng lợi, giá trị kinh doanh và thời điểm mong muốn.
- **Người chịu trách nhiệm:** Người đề xuất phối hợp với Product Owner.
- **Điều kiện sang bước 2:** Story có mục tiêu rõ ràng, không chỉ là một ý tưởng chung chung.

### Bước 2: Viết Acceptance Criteria

- **Việc cần làm:** Product Owner và Developers viết từ 3 đến 7 tiêu chí theo mẫu **Given – When – Then**.
- **Người chịu trách nhiệm:** Product Owner chịu trách nhiệm nội dung; Developers kiểm tra khả năng hiểu và thực hiện.
- **Điều kiện sang bước 3:** Các bên thống nhất đủ AC, không còn câu mô tả mơ hồ.

### Bước 3: Kiểm tra Definition of Done

- **Việc cần làm:** Đối chiếu story với DoD chung: đã code, đã review, đã test, xử lý lỗi, cập nhật tài liệu cần thiết và sẵn sàng phát hành.
- **Người chịu trách nhiệm:** Developers thực hiện kiểm tra kỹ thuật; Scrum Master hỗ trợ giải thích DoD.
- **Điều kiện sang bước 4:** Story có thể kiểm thử và có đường đi rõ ràng để đạt DoD.

### Bước 4: Gán nhãn MoSCoW theo giá trị phát hành

- **Việc cần làm:** Product Owner xếp Must, Should, Could hoặc Won’t cho **một lần phát hành cụ thể**. Không gán Must chỉ vì một bộ phận yêu cầu lớn tiếng.
- **Người chịu trách nhiệm:** Product Owner quyết định; Scrum Master làm rõ tiêu chí và ghi lại lý do.
- **Điều kiện sang bước 5:** Có nhãn, lý do, điểm ước lượng và thứ tự ưu tiên.

### Bước 5: Sẵn sàng đưa vào Sprint

- **Việc cần làm:** Product Owner sắp xếp story trong Product Backlog. Khi Sprint Planning, Developers kiểm tra năng lực và cam kết phần phù hợp.
- **Người chịu trách nhiệm:** Product Owner quyết định phạm vi; Developers xác nhận khả năng; Scrum Master bảo vệ quy trình.
- **Điều kiện hoàn tất:** Story đứng đúng vị trí trong backlog và chỉ vào Sprint khi đã rõ AC, DoD và nhãn MoSCoW.

## Phần 2 – Xử lý tình huống

### Tình huống 1: Marketing muốn đưa “Tặng mã giới thiệu bạn bè” vào Sprint đang chạy

Quy trình không cho đưa story mới vào Sprint ngay giữa chừng khi story chưa có AC. Lan ghi nhận yêu cầu, đưa story về backlog, tổ chức làm rõ AC và để Đức đánh giá cho Sprint tiếp theo; chỉ khi có lý do khẩn cấp và cả Product Owner lẫn Developers thống nhất thay đổi phạm vi thì mới xem xét đổi story tương đương.

Ví dụ một AC theo Given–When–Then:

> **Given** khách hàng đã đăng nhập và có mã giới thiệu hợp lệ  
> **When** khách nhập mã khi hoàn tất chuyến đi đầu tiên của người bạn được giới thiệu  
> **Then** hệ thống ghi nhận mã, áp phần thưởng đúng điều kiện và hiển thị thông báo thành công.

### Tình huống 2: Cả ba bộ phận đều nói yêu cầu của mình là Must

Lan không quyết định theo số người ủng hộ. Cô yêu cầu từng bộ phận chứng minh tác động đối với bản phát hành, rủi ro nếu không làm và giải pháp tạm thời; sau đó Đức dùng cùng một tiêu chí để chốt nhãn, đồng thời giữ Must khoảng 60% năng lực.

Ví dụ: yêu cầu “sửa lỗi thu sai tiền khách” được gắn **Must** vì rủi ro trực tiếp với tiền và niềm tin khách hàng. Yêu cầu “giao diện trang trí khuyến mãi” được gắn **Could** hoặc **Won’t** nếu giao diện hiện tại vẫn dùng được; lý do được ghi rõ để Marketing biết khi nào có thể xem lại.

## Kết quả

Quy trình này tạo ra một cổng kiểm tra đơn giản: story phải rõ mục tiêu, có 3–7 AC, phù hợp DoD, có nhãn MoSCoW và được Product Owner chốt trước khi vào Sprint. Nhờ vậy, yêu cầu mới vẫn được tiếp nhận nhưng không làm Sprint đang chạy mất kiểm soát.
