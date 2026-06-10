# Bài 13. AI Trong Sales

## Câu hỏi bản chất

> Dùng AI để bán tốt hơn hay chỉ nói nhanh hơn?

## Tình huống mở bài

Một đội sales dùng AI tạo hàng trăm tin nhắn tiếp cận phụ huynh. Tin nhắn trôi chảy, lịch sự, có tên người nhận, nhưng conversion vẫn thấp. Khi xem lại, các tin đều nói chung về "AI học tập cá nhân hóa", không dựa trên insight thật, không có giới hạn claim và không giúp sales hiểu phản đối của khách.

AI tăng tốc việc sai thì chỉ giúp sai nhanh hơn.

## Vì sao bài này quan trọng

AI có thể hỗ trợ sales nghiên cứu, viết tin nhắn, tóm tắt cuộc gọi, phân loại phản đối, tạo proposal và cập nhật CRM. Nhưng AI không thay thế discovery, phán đoán fit, đạo đức bán hàng và trách nhiệm với claim.

## Nguyên lý first principles

AI trong sales nên dùng để tăng tốc 4 việc:

```text
Chuẩn bị tốt hơn
-> Ghi nhớ tốt hơn
-> Cá nhân hóa có kiểm soát
-> Học từ dữ liệu nhanh hơn
```

Con người vẫn quyết định khách có phù hợp không, claim nào được nói, deal nào nên chốt và kỳ vọng nào phải bảo vệ.

## Kiến thức nền chi tiết

AI mạnh ở việc xử lý ngôn ngữ và dữ liệu bán hàng. Nó có thể tóm tắt notes, rút ra pain, đề xuất câu hỏi discovery, tạo phiên bản follow-up, phân nhóm objection, soạn proposal nháp và tạo battlecard cho sales. Những việc này tiết kiệm thời gian và giúp sales nhất quán hơn.

Nhưng AI dễ tạo ra nội dung nghe hợp lý mà không đúng dữ liệu thật. Nếu đầu vào là ghi chú mơ hồ, AI sẽ suy diễn. Nếu không có guardrails, AI có thể viết claim quá mức. Nếu sales dùng AI để cá nhân hóa giả tạo, khách có thể thấy thiếu chân thật.

AI sales workflow cần có dữ liệu đầu vào, mục tiêu, người kiểm duyệt, claim được phép nói, claim không được nói, dữ liệu nhạy cảm không được đưa vào và tiêu chuẩn đầu ra. Với dữ liệu khách hàng, cần đặc biệt cẩn trọng về quyền riêng tư, nhất là dữ liệu trẻ em trong use case giáo dục.

AI nên được gắn vào playbook, không dùng tự phát. Ví dụ: AI tóm tắt discovery theo khung pain-impact-decision-next step; AI tạo follow-up dựa trên template đã duyệt; AI phân tích lost reason hằng tuần; AI gợi ý cập nhật objection matrix nhưng con người duyệt.

## Thuật ngữ cần hiểu sâu

| Thuật ngữ | Định nghĩa ngắn | Giải thích đời thường | Bản chất | Ví dụ đúng | Ví dụ sai | Dễ nhầm với |
|---|---|---|---|---|---|---|
| AI sales assistant | Trợ lý AI sales | Công cụ hỗ trợ sales viết, tóm tắt, phân tích | Tăng tốc công việc lặp lại | Tóm tắt call notes thành CRM fields | Để AI quyết định chốt | Salesperson |
| Guardrails | Ranh giới sử dụng | Điều được phép/không được phép | Bảo vệ claim và dữ liệu | Không hứa "AI giúp con giỏi chắc chắn" | Tạo nội dung tự do | Prompt |
| Call summary | Tóm tắt cuộc gọi | Ghi lại ý chính sau trao đổi | Giữ dữ liệu sales | Pain, objection, next step | Tóm tắt chung chung | Transcript |
| Personalization | Cá nhân hóa | Điều chỉnh theo bối cảnh khách | Làm thông điệp liên quan hơn | Nhắc đúng lớp học và vấn đề con | Chèn tên vào tin spam | Automation |

## Khung tư duy trực quan

| Công việc sales | AI hỗ trợ | Con người quyết định |
|---|---|---|
| Chuẩn bị call | Tóm tắt khách, gợi ý câu hỏi | Câu hỏi nào phù hợp |
| Outreach | Draft phiên bản tin nhắn | Thông điệp có thật và tôn trọng không |
| Discovery | Tóm tắt pain/impact | Khách có fit không |
| Proposal | Soạn nháp đề xuất | Claim, giá, điều khoản |
| Review pipeline | Nhóm objection/lost reason | Ưu tiên sửa playbook |

## Ví dụ đời thường

AI giống một trợ lý ghi chép và soạn nháp rất nhanh. Nếu người quản lý không nói rõ điều gì đúng, điều gì cấm, trợ lý có thể viết rất tự tin nhưng sai lời hứa.

## Use case 1: Công ty mới

Startup AI giáo dục có thể dùng AI để:

- Tóm tắt 20 cuộc phỏng vấn phụ huynh.
- Nhóm phản đối: giá, thói quen học, niềm tin AI, dữ liệu trẻ em.
- Tạo 5 phiên bản tin nhắn follow-up sau trial.
- Soạn proposal gói 3 tháng dựa trên dữ liệu học thật.

Guardrails: không đưa dữ liệu trẻ em nhạy cảm vào công cụ không kiểm soát; không hứa kết quả học tập chắc chắn; mọi claim hiệu quả phải có dữ liệu.

## Use case 2: Công ty đã có

Công ty smart home có thể dùng AI để:

- Tạo FAQ đại lý từ phản đối thật.
- Tóm tắt feedback sau lắp đặt.
- Phân loại lỗi theo thiết bị, câu lệnh, mạng, kỳ vọng.
- Soạn script demo theo từng nhóm khách.

Guardrails: không nói loa hiểu mọi câu lệnh, không tạo danh sách tính năng chưa phát hành, mọi tài liệu đại lý phải qua sales, marketing, R&D và CS duyệt.

## Lỗi người mới thường mắc

- Dùng AI trước khi có dữ liệu khách thật.
- Để AI viết claim không kiểm chứng.
- Cá nhân hóa giả tạo gây mất niềm tin.
- Đưa dữ liệu nhạy cảm vào công cụ không kiểm soát.
- Tự động hóa follow-up mà không hiểu deal stage.

## Bài tập ứng dụng

Lập AI Sales Workflow:

| Công việc | AI hỗ trợ gì? | Dữ liệu đầu vào | Guardrails | Người duyệt | Tiêu chuẩn đầu ra |
|---|---|---|---|---|---|
| Outreach |  |  |  |  |  |
| Discovery summary |  |  |  |  |  |
| Follow-up |  |  |  |  |  |
| Proposal |  |  |  |  |  |
| Pipeline review |  |  |  |  |  |

## Bài tập review

Một đội sales để AI tự viết và gửi follow-up sau mọi cuộc gọi, không kiểm tra stage, không kiểm duyệt claim. Review rủi ro và thiết kế lại workflow.

## Tiêu chí đánh giá

| Mức độ | Biểu hiện |
|---|---|
| Yếu | Dùng AI để spam nhanh hơn |
| Đạt | Dùng AI để soạn nháp và tiết kiệm thời gian |
| Tốt | Có dữ liệu đầu vào, guardrails và người duyệt |
| Xuất sắc | AI giúp sales học nhanh hơn, cá nhân hóa đúng hơn và cải tiến playbook có kiểm soát |

## Checklist tự review

1. AI dùng dữ liệu khách thật hay giả định?
2. Có dữ liệu nhạy cảm nào không nên đưa vào AI không?
3. Claim AI tạo có cần kiểm chứng không?
4. Ai duyệt đầu ra trước khi dùng với khách?
5. Kết quả AI có cập nhật CRM/playbook không?

## Hành động 30-90 phút

Viết một prompt tạo follow-up sau discovery gồm: ICP, pain, impact, objection, claim được nói, claim không được nói, next step và tone. Sau đó tự review đầu ra theo guardrails.

## Liên hệ với bài trước và bài sau

Bài trước xây sales playbook. AI nên tăng tốc playbook đó, không thay thế nó. Bài sau là đồ án cuối khóa, nơi người học tổng hợp toàn bộ thành kế hoạch sales hoàn chỉnh.
