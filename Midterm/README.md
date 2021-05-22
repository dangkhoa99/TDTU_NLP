<div align="center">
  <h1>Project Giữa kỳ</h1>
  <h3>Môn: Nhập môn Xử lý ngôn ngữ tự nhiên</h3>
</div>

## 1.	Mục tiêu
Xây dựng chương trình (tool) gán nhãn từ loại (POS tagger) cho tiếng Việt.
Kết quả đạt được là chương trình, có 2 chức năng:
-	Đánh giá độ chính xác trên tập Test: tỉ lệ số từ gán nhãn đúng trên tổng số từ
-	Input vào một câu tiếng Việt, cho ra nhãn của từng từ trong câu, ví dụ.
(lưu ý, sử dụng thêm Library để Word Segmentation cho tiếng Việt. Tự tìm Library)
o	Câu input: “Dù khá đắt nhưng tôi vẫn đồng ý.”
o	Kết quả: “Dù/C khá/R đắt/A nhưng/C tôi/P vẫn/R đồng_ý/V ./.”

## 2.	Dữ liệu cho trước
-	File traing: “vi_train.pos”
-	File test: “vi_test.pos”
-	File hướng dân thông tin về nhãn POS: “Thon tin nhan tu loai-v2.pdf”

## 3.	Đánh giá 
(tổng 11 điểm)
-	(6 điểm) Xây dựng được mô hình thực hiện được mục tiêu, có thể tự code hoặc dùng thư viện hoặc open source, sử dụng Hidden Markov Model. 
o	Tự code (1.5 điểm)
-	(1.5 điểm )Sử dụng thêm phương pháp phân loại:
o	Phân loại: sử dụng Maximum Entropy Model (Logistic Regression), SVM.
-	 (2.0 điểm )Trình bày lý thuyết về Conditional Random Fields và sử dụng thư viện (hoặc open source) để giải quyết bài toán trên. 

## 4.	Nộp bài
Cho các kết quả vào thư mục, nén lại và nộp. Tên thư mục là Họ tên và MSSV
-	Chương trình: file họ_tên_mssv_model.jpynb
o	Nếu có nhiều chương trình thì bổ sung thông tim Model vào tên file
-	Slide: 
o	các kết quả test của các model
o	lý thuyết về CRFs
