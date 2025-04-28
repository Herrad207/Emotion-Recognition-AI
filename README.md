Bước 1: Tải và cài đặt Anaconda
Truy cập trang chủ Anaconda và tải phiên bản phù hợp với hệ điều hành của bạn (Windows/Mac/Linux).
Cài đặt Anaconda bằng cách làm theo hướng dẫn.

Bước 2: Tạo môi trường mới trong Anaconda
Môi trường riêng biệt giúp bạn quản lý các thư viện dễ dàng hơn.
Mở Anaconda Prompt (hoặc Terminal nếu dùng Mac/Linux).
Gõ lệnh sau để tạo môi trường mới:
conda create --name cnn_env python=3.8
cnn_env là tên môi trường (bạn có thể đổi tên khác nếu muốn).
python=3.8 chỉ định phiên bản Python.
Kích hoạt môi trường:
conda activate cnn_env

Bước 3: Cài đặt các thư viện cần thiết
Trong môi trường đã kích hoạt, cài đặt TensorFlow/Keras:
pip install tensorflow matplotlib numpy
tensorflow: Thư viện chính để xây dựng mô hình CNN.
matplotlib: Để vẽ biểu đồ hoặc hiển thị ảnh.
numpy: Thư viện xử lý dữ liệu số.

2. Viết mã Python cho kiến trúc CNN cơ bản
Mở Jupyter Notebook hoặc IDE yêu thích
Bạn có thể sử dụng Jupyter Notebook (được tích hợp sẵn trong Anaconda) hoặc bất kỳ trình soạn thảo nào như VSCode, PyCharm.
Cần cài đặt jupyter trước khi mở : conda install jupyter

4. Chạy chương trình
Chạy trực tiếp trên Jupyter Notebook
Nhấn tổ hợp phím Shift + Enter trên từng ô lệnh để chạy mã.
Chạy qua file Python (.py)
Nếu bạn lưu mã vào file tên là cnn_model.py, hãy chạy lệnh sau trong terminal:
python cnn_model.py

Thực hiện cài đặt Fer2013 tại : https://www.kaggle.com/datasets/deadskull7/fer2013?resource=download
