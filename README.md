
# Hàn Ngữ Min Jun - 90 Bài Chuẩn - Website Hoàn Chỉnh

## 🌟 Tính năng:

### 1. 90 Bài học chia đúng (không tạp nham):
- **Sơ cấp 1**: 15 bài, 47 mẫu ngữ pháp, 882 từ vựng
- **Sơ cấp 2**: 15 bài, 41 mẫu, 725 từ
- **Trung cấp 3**: 15 bài, 30 mẫu, 1865 từ
- **Trung cấp 4**: 15 bài, 20 mẫu, 2067 từ
- **Cao cấp 5**: 15 bài, 15 mẫu, 2075 từ
- **Cao cấp 6**: 15 bài, 15 mẫu, 2661 từ

Mỗi bài có:
- **Từ vựng**: List từ vựng riêng, TTS 🔊, checkbox thuộc
- **Ngữ pháp**: Đúng bài, 3 ví dụ Hàn-Việt, giải thích dễ hiểu
- **Câu giao tiếp**: Coming Soon, chia theo từng bài, Sơ cấp/Trung cấp/Cao cấp
- **Video sưu tầm**: YouTube nhỏ, admin duyệt

### 2. Tích hợp Đăng nhập (Auth):
- **Học viên**: Google, Facebook, Kakao, Apple OAuth (mock, production dùng Firebase)
- **Admin**: Route `/admin30012001.html`, Secret Key: `30012001` hoặc `MINJUN2026`

File: `auth/auth.js` - Class AuthManager

### 3. Giá & Thanh toán:
- 1 khóa Sơ cấp/Trung cấp/Cao cấp: **499k**
- TOPIK 1-4: **499k**
- TOPIK 5-6: **599k**
- Thanh toán qua Zalo: **086 889 8558** - https://zalo.me/0868898558
- Học viên bấm "Đã nhắn Zalo" -> Admin duyệt trong `/admin30012001.html` -> Cấp quyền

### 4. 2 File riêng biệt:
- `index.html`: File học viên (không có admin code)
- `admin30012001.html`: File admin riêng để:
  - Thêm video vào từng phần (Từ vựng/Ngữ pháp/Giao tiếp/Video)
  - Quản lý khóa học, bài học, từ vựng, ngữ pháp
  - Duyệt video, đơn hàng Zalo, cấp quyền mua file, quản lý users

### 5. Deploy GitHub Pages:
1. Tạo repo mới: `han-ngu-min-jun`
2. Upload toàn bộ file trong folder này
3. Settings -> Pages -> Deploy from branch: main, root
4. Truy cập: `https://username.github.io/han-ngu-min-jun/`
5. Admin: `https://username.github.io/han-ngu-min-jun/admin30012001.html`

## 📁 Cấu trúc file:
```
han-ngu-min-jun-github/
├── index.html (học viên)
├── admin30012001.html (admin riêng)
├── data/
│   ├── FINAL_90_BAI_FULL.json (90 bài chuẩn)
│   ├── BAI_HOC_CHUAN_90.json
│   └── ...
├── auth/
│   ├── auth.js (AuthManager)
│   └── README.md
└── README.md
```

## 🔑 Secret Key Admin:
`30012001` hoặc `MINJUN2026`

## 📞 Liên hệ:
Zalo: 086 889 8558
