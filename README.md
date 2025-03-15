# Emotion-Recognition-AI
Hệ thống nhận diện cảm xúc từ khuôn mặt sử dụng AI.

## Công nghệ sử dụng
- Python
- PyTorch (framework)
- NumPy, Pandas (xử lý dữ liệu).
- Matplotlib, Seaborn (trực quan hóa dữ liệu).
- OpenCV (nếu cần xử lý ảnh khuôn mặt trước khi đưa vào mô hình).

## Cài đặt các thư viện cần thiết
python -m pip install --upgrade pip
pip install torch torchvision torchaudio numpy pandas matplotlib seaborn opencv-python

## Google Colab
Mục tiêu: Chuẩn bị nền tảng để chạy mã nguồn AI hiệu quả.
Các bước thực hiện:
Tạo một tài khoản Google Drive (nếu chưa có) để lưu trữ mã nguồn và dataset.
Thiết lập Google Colab:
Kiểm tra khả năng sử dụng GPU trên Google Colab. 
Kích hoạt GPU trong Google Colab:
- Vào menu: Runtime > Change runtime type.
- Chọn Hardware accelerator là GPU.

Viết một đoạn code mẫu kiểm tra TensorFlow/PyTorch hoạt động bình thường trên GPU:
import tensorflow as tf
print("GPU is", "available" if tf.config.list_physical_devices('GPU') else "NOT AVAILABLE")

git clone https://github.com/Herrad207/Emotion-Recognition-AI
