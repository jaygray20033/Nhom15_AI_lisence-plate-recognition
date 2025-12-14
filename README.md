# Nhận dạng biển số xe - Nhóm 15

## Mô tả

Dự án nhận dạng ký tự trên biển số xe sử dụng mạng nơ-ron tích chập (CNN) và KNN.

## Cấu trúc thư mục

```
├── mainhuanluyen+chay.ipynb    # Notebook huấn luyện và chạy model
├── data/
│   ├── train/                  # Dữ liệu huấn luyện (class_0 đến class_Z)
│   ├── char_12.jpg             # Ảnh test
│   └── anhnghiengmoi.jpg       # Ảnh test nghiêng
```

## Yêu cầu

- Python 3.x
- TensorFlow/Keras
- OpenCV
- NumPy
- scikit-learn

## Cách sử dụng

1. Mở file `mainhuanluyen+chay.ipynb` trên Google Colab
2. Mount Google Drive
3. Chạy các cell để huấn luyện và test model

## Tính năng

- Nhận dạng 36 ký tự (0-9, A-Z)
- Xử lý ảnh nghiêng
- Tách ký tự từ biển số

## Thành viên nhóm

- Nhóm 15
