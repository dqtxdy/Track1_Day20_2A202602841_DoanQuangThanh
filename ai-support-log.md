# AI Support Log

| Bước | Tôi dùng AI để làm gì | Tôi quyết định/kiểm tra lại gì |
|---|---|---|
| Đọc brief | Đối chiếu GUIDE với rubric và chuyển yêu cầu thành checklist cho Metrics Pack. | Tôi giữ GUIDE làm nguồn chuẩn và dùng project/use case đã chọn là UniPilot — Academic Task & Deadline Management. |
| Chốt hành vi | Nhờ AI hỗ trợ diễn đạt core job, phân biệt core action với UI action và xác định completion semantics. | Tôi giữ Core Action là hoàn thành một academic task và xác nhận completion; AI output không được tính là value. |
| Soạn Metrics Pack | Dùng AI để dựng nội dung và bố cục HTML cho cadence, metrics, retention, loop và tracking. | Tôi rà definitions theo cùng core value event `academic_task_completed`; các time window được ghi là hypothesis, không phải benchmark. |
| Audit tracking | Dùng AI rà consistency hai chiều và áp dụng correction bỏ event riêng `first_academic_task_created` theo yêu cầu audit. | Tôi kiểm tra first occurrence của `academic_task_created` làm Activation start, giữ đúng 5 core events và rà mapping cùng acceptance criteria. |
| Rà denominator và submission | Dùng AI cập nhật task readiness để chỉ tính task đã capture trong UniPilot, sửa heading event count 6 thành 5 và chuẩn bị entry point cùng log nộp bài. | Tôi kiểm tra các mẫu số không đòi hỏi biết task ngoài hệ thống, đối chiếu lại với GUIDE và giữ quyền quyết định cuối cùng. |

