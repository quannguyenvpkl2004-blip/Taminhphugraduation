# 🎓 Thiệp Mời Lễ Tốt Nghiệp | Tạ Minh Phú

Chào mừng đến với mã nguồn thiệp mời điện tử (E-Invitation) dành cho Lễ Tốt nghiệp của **Tạ Minh Phú - Cử nhân Chính sách công**. 

Trang web được thiết kế theo phong cách thiệp sự kiện cao cấp, tối ưu hóa hiển thị chuẩn xác trên cả điện thoại di động và máy tính, với tông màu Đỏ Đun (Burgundy) & Vàng Gold sang trọng. Lời tâm sự trong thiệp được tinh chỉnh mang đậm dấu ấn tư duy phản biện và phân tích xã hội của một sinh viên ngành Chính sách công.

## ✨ Tính năng nổi bật
- **Giao diện chuẩn Mobile-first:** Tự động căn giữa và bóp khung trên máy tính để không bị vỡ giao diện.
- **Hiệu ứng Mở thiệp:** Màn hình chờ với hiệu ứng nhịp thở, sticker (🎓, ✨, 📜, 🎉, 🌟) bay bồng bềnh 3D siêu mượt và ảnh chân dung tách nền.
- **Album 3D Coverflow:** Lướt ảnh mượt mà dạng xếp lớp bằng thư viện SwiperJS.
- **Hệ thống m thanh:** Nút đĩa nhạc tự động quay và phát nhạc nền khi khách mở thiệp.
- **Sổ Lưu Bút Điện Tử:** Cho phép khách mời để lại lời chúc, dữ liệu được lưu trực tiếp bằng `LocalStorage`.
- **Phông chữ việt hóa 100%:** Sử dụng bộ đôi *Playfair Display* và *Lora* sắc nét.

## 📁 Cấu trúc thư mục (Cần tuân thủ)

Để trang web hoạt động hoàn hảo, hãy đảm bảo các file tài nguyên được đặt đúng vị trí sau:

```text
📦 Taminhphugraduation
 ┣ 📂 assets
 ┃ ┣ 📂 images 
 ┃ ┃ ┣ 📜 1.jpg (Sử dụng làm ảnh bìa chính)
 ┃ ┃ ┣ 📜 2.jpg
 ┃ ┃ ┣ 📜 3.jpg
 ┃ ┃ ┣ 📜 4.jpg
 ┃ ┃ ┣ 📜 5.jpg
 ┃ ┃ ┣ 📜 6.jpg
 ┃ ┃ ┣ 📜 7.jpg
 ┃ ┃ ┗ 📜 avatar-tach-nen.png (Ảnh chân dung không nền ở trang chờ)
 ┃ ┣ 📂 logo   (Chứa ảnh logo trường)
 ┃ ┗ 📂 music  (Chứa file nhạc: nhac-nen.mp3.mp3)
 ┣ 📜 index.html (File chứa toàn bộ mã nguồn HTML, CSS, JS)
 ┗ 📜 README.md
