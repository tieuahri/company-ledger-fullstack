
# Company Ledger — Fullstack (React + Express + PostgreSQL)

Fullstack mẫu theo yêu cầu: **Create React App + MUI + Tailwind + react-router-dom** ở frontend và **Express + JWT + cấu trúc router/controller** ở backend.

## Cấu trúc thư mục
```
company-ledger-fullstack/
  backend/
    src/
      app.js
      server.js
      config/
      middleware/
      routes/
      controllers/
      services/
      utils/
  frontend/
    src/
      index.jsx
      App.jsx
      routes/
      components/
      layouts/
      pages/
      services/
      styles/
    tailwind.config.js
    postcss.config.js
    craco.config.js
```

---

## Cách chạy nhanh (dev)

### 1) Backend
```bash
cd backend
cp .env.example .env   # sửa chuỗi kết nối PG
npm install
npm run dev
```

### 2) Frontend
```bash
cd ../frontend
npm install
npm start
```

Frontend chạy ở http://localhost:3000 và Backend ở http://localhost:4000.

---

## Tạo GitHub repo & push

```bash
# ở thư mục gốc
git init
git add .
git commit -m "Initial fullstack scaffold"
git branch -M main
# tạo repo trống trên GitHub trước, ví dụ: https://github.com/<yourname>/company-ledger-fullstack
git remote add origin https://github.com/<yourname>/company-ledger-fullstack.git
git push -u origin main
```

---

## Ghi chú
- Đây là scaffold tối thiểu để bạn bắt đầu phát triển; đã có các route mẫu khớp với API mà ta bàn.
- Bạn có thể thay đổi UI theo MUI/Tailwind ngay trong `frontend/src/pages/*`.
