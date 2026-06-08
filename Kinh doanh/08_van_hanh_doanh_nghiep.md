# Bài 8. Vận hành là khả năng giao giá trị ổn định

## Mục tiêu học tập

Sau bài này, người học có thể:

- Giải thích vì sao bán được chưa đủ, doanh nghiệp phải giao giá trị ổn định.
- Thiết kế quy trình vận hành đơn giản với đầu vào, đầu ra, owner và chỉ số.
- Phân biệt lỗi sản phẩm, lỗi quy trình, lỗi con người và lỗi kỳ vọng.
- Lập bản đồ quy trình giao giá trị.

## Câu hỏi bản chất

> Doanh nghiệp có thể lặp lại việc tạo giá trị với chất lượng ổn định không?

## Tình huống mở bài

Startup AI giáo dục có 100 người dùng đầu tiên. Phụ huynh nhắn hỏi nhiều, trẻ học không đều, báo cáo đôi khi sai, founder phải xử lý từng trường hợp thủ công. Cùng lúc, công ty smart home bán loa qua đại lý nhưng lỗi phát sinh từ nhiều nguồn: thiết bị, mạng, cloud, AI, app, cách lắp đặt và kỳ vọng khách hàng.

Bán được chỉ mở đầu cho bài toán vận hành.

## Nguyên lý first principles

Vận hành là khả năng biến lời hứa giá trị thành trải nghiệm thật, lặp lại được, đo được và cải tiến được.

Vận hành tốt giúp:

- Giảm lỗi.
- Tăng sự hài lòng.
- Giảm chi phí.
- Tăng khả năng mở rộng.
- Tạo niềm tin.

Nếu không vận hành được, tăng trưởng chỉ làm lỗi xuất hiện nhiều hơn.

## Kiến thức nền chi tiết

Doanh nghiệp không chỉ là sản phẩm và marketing. Doanh nghiệp là một hệ thống giao giá trị. Hệ thống đó gồm con người, quy trình, công cụ, dữ liệu, tiêu chuẩn chất lượng, cơ chế phản hồi và quyết định cải tiến. Khi khách mua, doanh nghiệp phải onboarding, giao hàng, triển khai, hỗ trợ, xử lý lỗi, thu tiền, theo dõi chất lượng và duy trì niềm tin.

Vận hành bắt đầu bằng việc mô tả quy trình. Mỗi quy trình cần có đầu vào, các bước chính, người phụ trách, đầu ra, chỉ số đo và rủi ro. Nếu không có owner rõ, lỗi sẽ bị đẩy qua lại. Nếu không có chỉ số, doanh nghiệp không biết chất lượng đang tốt hay xấu. Nếu không có cách phân loại lỗi, đội sản phẩm không học được từ phản hồi khách hàng.

Ở giai đoạn đầu, vận hành có thể thủ công nhưng không được mù mờ. Founder có thể tự gọi khách, tự đọc feedback, tự xử lý lỗi, nhưng cần ghi lại mẫu lỗi, nguyên nhân và giải pháp. Chính dữ liệu vận hành ban đầu giúp sản phẩm trưởng thành.

Khi mở rộng, vận hành cần chuẩn hóa. Công ty phải có checklist, tài liệu, SLA hỗ trợ, quy trình escalations, báo cáo chất lượng và cơ chế cập nhật sản phẩm. Chuẩn hóa không phải để làm doanh nghiệp cứng nhắc, mà để giảm phụ thuộc vào trí nhớ cá nhân và đảm bảo khách hàng nhận trải nghiệm tương đối ổn định.

## Thuật ngữ cần hiểu sâu

| Thuật ngữ | Định nghĩa ngắn | Giải thích đời thường | Bản chất | Ví dụ đúng | Ví dụ sai | Câu hỏi kiểm tra |
|---|---|---|---|---|---|---|
| Quy trình | Chuỗi bước tạo đầu ra | Làm việc theo cách có thể lặp lại | Biến nỗ lực cá nhân thành hệ thống | Checklist lắp loa trước bàn giao | Ai nhớ gì làm nấy | Nếu đổi người, việc có chạy được không? |
| Owner | Người chịu trách nhiệm cuối | Ai phải đảm bảo việc xong | Tránh lỗi không ai nhận | Một người phụ trách xử lý lỗi AI | Cả team cùng chịu trách nhiệm chung | Khi lỗi xảy ra, ai quyết định? |
| SLA | Cam kết mức dịch vụ | Bao lâu phải phản hồi/xử lý | Quản lý kỳ vọng và ưu tiên | Phản hồi lỗi nghiêm trọng trong 2 giờ | Hứa "hỗ trợ nhanh" chung chung | Khách biết chờ bao lâu không? |
| Feedback loop | Vòng phản hồi cải tiến | Lỗi và phản hồi quay lại sản phẩm | Học từ thực tế vận hành | Đại lý gửi log lỗi theo mẫu | Đọc tin nhắn rồi quên | Feedback có thành cải tiến không? |

## Khung tư duy trực quan

```text
Bán hàng -> Onboarding/Triển khai -> Khách dùng -> Hỗ trợ -> Đo chất lượng -> Phân loại lỗi -> Cải tiến
```

## Ví dụ đời thường

Một quán ăn ngon nhưng giao món lúc nhanh lúc chậm, nhân viên mỗi người nói giá khác nhau, khách phàn nàn không ai xử lý, thì không thể mở rộng bền vững. Vận hành là cách quán đảm bảo món ăn, thời gian, thái độ và xử lý sự cố đủ ổn định mỗi ngày.

## Use case 1: Công ty mới

Startup AI giáo dục cần quy trình tối thiểu:

- Onboarding phụ huynh và học sinh.
- Theo dõi trẻ có học ngày đầu không.
- Nhắc phụ huynh nếu trẻ bỏ học 2 ngày.
- Ghi nhận lỗi bài tập hoặc báo cáo.
- Phỏng vấn phụ huynh sau 7 ngày.
- Tổng hợp dữ liệu retention và phản hồi.

Founder nên trực tiếp tham gia để hiểu vì sao trẻ không học: bài quá khó, giao diện khó dùng, phụ huynh quên nhắc, hay giá trị chưa đủ rõ.

## Use case 2: Công ty đã có

Công ty smart home cần vận hành bài bản hơn:

- Checklist điều kiện kỹ thuật trước khi bán loa.
- Tài liệu câu lệnh được hỗ trợ.
- Quy trình đại lý lắp đặt và bàn giao.
- Mẫu ghi nhận lỗi gồm thiết bị, mạng, câu lệnh, thời gian, log.
- SLA hỗ trợ khách đầu tiên.
- Báo cáo lỗi hằng tuần cho R&D và product.

Điểm quan trọng là không để đại lý hứa quá mức hoặc tự xử lý lỗi không có dữ liệu.

## Lỗi người mới thường mắc

- Nghĩ vận hành chỉ cần sau khi có nhiều khách.
- Không ghi nhận lỗi có cấu trúc.
- Không phân biệt lỗi kỹ thuật với lỗi kỳ vọng.
- Không có owner cho quy trình quan trọng.
- Tăng trưởng trước khi hệ thống hỗ trợ sẵn sàng.
- Không tính chi phí vận hành vào mô hình kinh doanh.

## Bài tập ứng dụng

Thiết kế bảng vận hành:

| Quy trình | Người phụ trách | Đầu vào | Đầu ra | Chỉ số đo | Rủi ro |
|---|---|---|---|---|---|
| Bán hàng |  |  |  |  |  |
| Triển khai/onboarding |  |  |  |  |  |
| Hỗ trợ khách hàng |  |  |  |  |  |
| Xử lý lỗi |  |  |  |  |  |
| Cải tiến sản phẩm |  |  |  |  |  |

## Bài tập review

Review tình huống:

> "Có khách phàn nàn sản phẩm lỗi. Sales nói do khách dùng sai. Kỹ thuật nói do sales hứa quá. Product nói chưa nhận đủ dữ liệu."

| Nội dung review | Nhận xét |
|---|---|
| Thiếu quy trình nào? |  |
| Thiếu dữ liệu nào? |  |
| Ai nên là owner? |  |
| Cần phân loại lỗi ra sao? |  |
| Cải tiến hệ thống thế nào? |  |

## Tiêu chí đánh giá

| Mức | Biểu hiện |
|---|---|
| Yếu | Chỉ nói chung chung về chăm sóc khách hàng |
| Đạt | Có quy trình chính, owner và chỉ số cơ bản |
| Tốt | Có phân loại lỗi, dữ liệu đầu vào, SLA và vòng phản hồi |
| Xuất sắc | Thiết kế vận hành vừa đủ cho giai đoạn, kiểm soát rủi ro mở rộng và liên kết với tài chính/sản phẩm |

## Checklist tự review

- Khách mua xong sẽ đi qua những bước nào?
- Mỗi bước ai chịu trách nhiệm?
- Lỗi được ghi nhận bằng dữ liệu gì?
- Chỉ số nào cho biết chất lượng đang giảm?
- Quy trình có chạy được khi số khách tăng gấp 5 không?

## Hành động nhỏ trong 30-90 phút

Vẽ quy trình từ lúc khách quan tâm đến lúc khách nhận giá trị đầu tiên. Đánh dấu 3 điểm dễ lỗi nhất và viết cách ghi nhận dữ liệu cho từng điểm.

