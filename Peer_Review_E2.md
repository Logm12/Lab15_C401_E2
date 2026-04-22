# PEER REVIEW - E2
**Member**
- Nguyễn Văn Đạt - 2A202600411
- Cao Chí Hải - 2A202600011
- Bùi Hữu Huấn - 2A202600353
- Nguyễn Doãn Hiếu -2A202600144
- Mạc Phạm Thiên Long - 2A202600384
- Nguyễn Tuấn Khanh - 2A202600409
- Phan Hoài Linh - 2A202600278
---

## Phiếu chấm 1 đội

**Zone:** 7 | **Đội chấm:** E2  
**Đội được chấm:** D3 | **Tên dự án:** Đề tài Gợi ý BĐS  

| Tiêu chí | Tối đa | Điểm cho |
| :--- | :--- | :--- |
| Hiểu bài toán và bối cảnh enterprise | 15 | 12 |
| Lựa chọn kiến trúc triển khai | 20 | 16 |
| Cost analysis | 20 | 16 |
| Cost optimization | 15 | 12 |
| Reliability & scaling | 10 | 8 |
| Định hướng Track Phase 2 | 10 | 0 |
| Trình bày và phản biện | 5 | 4 |
| **Tổng** | **95** | **68** |

**1 điểm mạnh nhất của đội:** Đội đã xác định rõ chân dung người dùng (user) và thiết kế hệ thống gợi ý có khả năng tích hợp linh hoạt với nhiều nguồn dữ liệu bất động sản phức tạp.

**1 điểm cần cải thiện nhất:** Phần Cost (Cost analysis) cần cải thiện: Đội chưa bóc tách rõ chi phí ngầm  cho việc liên tục huấn luyện lại mô hình gợi ý theo thời gian thực khi dữ liệu nhà đất thay đổi. Phần xác định chi phí còn khá mơ hồ

**1 câu hỏi/phản biện dành cho đội:** Các bạn dùng metrics gì để xác định tính khả thi của bài toán này?

**1 đề xuất nếu đội tiếp tục sang Phase 2:** Không có
**Badge:**: Best Critical Feedback
---

## Phiếu chấm 1 đội

**Zone:** 7 | **Đội chấm:** E2  
**Đội được chấm:** D2 | **Tên dự án:** Đề tài AI hỗ trợ tuyển sinh cho trường HUST  

| Tiêu chí | Tối đa | Điểm cho |
| :--- | :--- | :--- |
| Hiểu bài toán và bối cảnh enterprise | 15 | 15 |
| Lựa chọn kiến trúc triển khai | 20 | 16 |
| Cost analysis | 20 | 12 |
| Cost optimization | 15 | 12 |
| Reliability & scaling | 10 | 8 |
| Định hướng Track Phase 2 | 10 | 0 |
| Trình bày và phản biện | 5 | 4 |
| **Tổng** | **95** | **67** |

**1 điểm mạnh nhất của đội:** Đội có sự thấu hiểu xuất sắc về bối cảnh enterprise, nhận diện rõ ràng được đặc thù tải dữ liệu dạng thời vụ (traffic spike) của hệ thống tuyển sinh vào các đợt công bố điểm.

**1 điểm cần cải thiện nhất:** Phần Reliability và scaling cần cải thiện: Chưa trình bày được kịch bản lỗi (failure scenarios) và cơ chế fallback cụ thể khi lượng truy cập tăng vọt làm quá tải giới hạn rate limit của các API LLM; Phần scale và cost optimization còn vô lý so với bài toán.

**1 câu hỏi/phản biện dành cho đội:** Trong trường hợp lưu lượng truy cập tăng gấp 20 lần vào ngày công bố điểm chuẩn của HUST, hệ thống sẽ thực hiện auto-scaling các node xử lý NLP như thế nào và điều này sẽ tác động ra sao đến bài toán Cost optimization trong những ngày cao điểm đó?

**1 đề xuất nếu đội tiếp tục sang Phase 2:** Không có

---

## Phiếu chấm 1 đội

**Zone:** 7 | **Đội chấm:** E2  
**Đội được chấm:** D1 | **Tên dự án:** Vinmec Elite Assistant

| Tiêu chí | Tối đa | Điểm cho |
| :--- | :--- | :--- |
| Hiểu bài toán và bối cảnh enterprise | 15 | 12 |
| Lựa chọn kiến trúc triển khai | 20 | 16 |
| Cost analysis | 20 | 16 |
| Cost optimization | 15 | 9 |
| Reliability & scaling | 10 | 8 |
| Định hướng Track Phase 2 | 10 | 8 |
| Trình bày và phản biện | 5 | 4 |
| **Tổng** | **95** | **65** |

**1 điểm mạnh nhất của đội:** Kiến trúc triển khai thể hiện sự cẩn trọng cao đối với bảo mật, đội đã chọn phương pháp Hybrid Cloud có logic phù hợp để giữ an toàn cho dữ liệu y tế nội bộ.

**1 điểm cần cải thiện nhất:** Phần cost optimization cần cải thiện: Chiến lược tối ưu chi phí chưa thể hiện rõ được việc cân nhắc trade-off giữa chất lượng phản hồi của AI (tính chính xác y tế) và chi phí duy trì tài nguyên phần cứng lớn.

**1 câu hỏi/phản biện dành cho đội:** Với tính chất nghiêm ngặt của hệ thống y tế, nếu môi trường cloud chính gặp sự cố mạng diện rộng, giải pháp dự phòng (Disaster recovery) của đội được thiết kế thế nào để đảm bảo hệ thống hỗ trợ tại Vinmec không bị gián đoạn (reliability)?

**1 đề xuất nếu đội tiếp tục sang Phase 2:** Không có
