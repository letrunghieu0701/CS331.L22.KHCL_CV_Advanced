# CS331.L22.KHCL_CV_Advanced

Link: https://drive.google.com/drive/folders/1R2yBOZyqp55qt8Nv9l6ZO5nZ9BhtL_Bw?usp=sharing
Link trên chỉ có thể mở được với những người có email của Trường Đại học Công nghệ thông tin, Đại học Quốc gia Thành phố Hồ Chí Minh
Link Google Drive bao gồm: Code, dataset
- File:
+ sample_submission.csv: dùng để tạo file submit kết quả lên Kaggle
+ train.csv: chứa tên của các ảnh train và nhãn của từng ảnh
+ test.csv: chứa tên của các ảnh test
-Thư mục:
+ Code: code của đồ án
+ images: ảnh nguyên gốc từ Kaggle
+ Resized_224x224: Ảnh đã được resize và pad thêm pixel để có kích thước 224x224
	* Full_dataset: tất cả ảnh của thư mục images mà đã được resize và pad
	* test: giống như thư mục Full_dataset nhưng chỉ chứa ảnh test
	* train: Ảnh cho tập train, cũng giống như Full_dataset, nhưng các ảnh đã được cho vào đúng thư mục label của từng ảnh
+ Crop_with_Canny:
	* Full_dataset: tất cả ảnh của thư mục images mà đã được cắt bằng cách áp dụng Canny
	* Test_Resized_224x224: Ảnh cho tập test, ảnh đã được cắt bằng Canny và sau đó được resize và pad
	* Train_Resized_224x224: Ảnh cho tập train, cũng giống như Test_Resized_224x224, nhưng các ảnh đã được cho vào đúng thư mục label của từng ảnh
+ Models: Chứa các model đã được train sẵn và file chứa kết quả predict của tập test
+ Final: Chứa báo cáo word (docx và pdf), slide (pptx và pdf), file code và file nội dung file README này
+ Tham_Khao: Vài tài liệu tham khảo của nhóm

Nếu link Google Drive không vào được hoặc người đọc có thắc mắc, xin liên hệ email: 18520738@gm.uit.edu.vn
