# Chatbot Hỗ Trợ Sinh Viên – Đại Học Văn Lang

**Xây dựng tập dữ liệu và triển khai mô hình chatbot phục vụ công tác sinh viên**

---

## 1. Giới Thiệu Dự Án

Trong bối cảnh cạnh tranh ngày càng gay gắt của ngành giáo dục đại học, việc nâng cao hiệu quả hỗ trợ sinh viên đóng vai trò quan trọng trong việc cải thiện chất lượng đào tạo và tăng cường sự hài lòng của người học. Dự án này nhằm phát triển một hệ thống chatbot thông minh dựa trên các mô hình ngôn ngữ lớn (LLM) kết hợp với cơ chế **Retrieval-Augmented Generation (RAG)**. Hệ thống hướng đến việc cung cấp phản hồi chính xác, nhanh chóng và phù hợp với ngữ cảnh, từ đó hỗ trợ tối ưu hóa quy trình tư vấn và giải đáp các thắc mắc của sinh viên tại trường Đại học Văn Lang.

---

## 2. Mục Tiêu Dự Án

- **Xây dựng bộ dữ liệu:** Thu thập và xử lý dữ liệu câu hỏi – trả lời dựa trên tài liệu chính thức và thông tin nội bộ của trường.
- **Tinh chỉnh mô hình LLM:** Điều chỉnh và tối ưu hóa mô hình ngôn ngữ lớn (ví dụ: ChatGPT, DeepSeek, LLaMA) để phù hợp với ngữ cảnh công tác sinh viên.
- **Triển khai hệ thống RAG:** Áp dụng cơ chế Retrieval-Augmented Generation nhằm cải thiện hiệu suất truy xuất và độ chính xác của phản hồi.
- **Đánh giá và triển khai thử nghiệm:** Sử dụng các chỉ số đánh giá như Recall@k, BLEU, ROUGE… để đo lường hiệu quả của hệ thống trước khi ứng dụng thực tế.

---

## 3. Nội Dung Nghiên Cứu & Phương Pháp

### 3.1 Thu Thập và Tiền Xử Lý Dữ Liệu

- Xác định nguồn dữ liệu: FAQ, tài liệu học thuật, thông tin từ hệ thống hỗ trợ sinh viên.
- Tiền xử lý: Làm sạch, chuẩn hóa định dạng và cấu trúc dữ liệu cho phù hợp với yêu cầu huấn luyện.

### 3.2 Nghiên Cứu và Tinh Chỉnh Mô Hình LLM

- Khảo sát các mô hình LLM hiện có như ChatGPT, DeepSeek, LLaMA.
- Áp dụng các kỹ thuật tinh chỉnh (fine-tuning, LoRA, QLoRA, …) để cải thiện khả năng phản hồi trong bối cảnh chuyên biệt.

### 3.3 Triển Khai Hệ Thống RAG

- Phân tích và tích hợp cơ chế Retrieval-Augmented Generation (RAG) vào hệ thống.
- So sánh hiệu quả của các phương pháp truy xuất thông tin (BM25, FAISS, Hybrid Search).

### 3.4 Đánh Giá Hiệu Quả

- Sử dụng các chỉ số như Recall@k, BLEU, ROUGE để đo lường chất lượng phản hồi.
- Thử nghiệm hệ thống trên nhóm người dùng thực tế và thu thập phản hồi để hoàn thiện mô hình.

---
