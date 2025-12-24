# BizFlow – Backend

## Giới thiệu
Backend của hệ thống BizFlow, cung cấp API và xử lý nghiệp vụ cho Web và Mobile.

## Cấu trúc thư mục
```text
bizflow-backend/
├── src/
│   ├── controllers/     # Xử lý request/response
│   ├── services/        # Xử lý nghiệp vụ
│   ├── models/          # Mô hình dữ liệu
│   ├── routes/          # Khai báo API
│   ├── middlewares/     # Middleware
│   └── configs/         # Cấu hình hệ thống
├── tests/               # Kiểm thử
├── docs/                # Tài liệu kỹ thuật
├── .env.example         # File môi trường mẫu
├── .gitignore
└── README.md
