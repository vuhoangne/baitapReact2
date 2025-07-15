# TRY GLASSES APP ONLINE

Ứng dụng thử kính mắt trực tuyến đơn giản, cho phép người dùng thử các loại kính khác nhau trên các khuôn mặt khác nhau.

![Try Glasses App Preview](https://via.placeholder.com/800x400?text=Try+Glasses+App+Online)

## Tính năng

- Chọn giữa 3 khuôn mặt khác nhau với tông màu da khác nhau
- Thử 6 kiểu kính mắt khác nhau:
  - Classic
  - Modern
  - Vintage
  - Sport
  - Cat Eye
  - Aviator
- Xem trước kính trên khuôn mặt đã chọn
- Giao diện thân thiện với người dùng, đáp ứng trên nhiều thiết bị
- Hiệu ứng chuyển động mượt mà khi tương tác

## Công nghệ sử dụng

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (Vanilla JS)
- SVG cho hình ảnh kính và khuôn mặt

## Cách sử dụng

1. Chọn một khuôn mặt bằng cách nhấp vào một trong ba tùy chọn khuôn mặt
2. Duyệt qua các kiểu kính khác nhau và nhấp vào kính bạn muốn thử
3. Kính sẽ xuất hiện trên khuôn mặt đã chọn
4. Sử dụng nút "Xóa kính" để loại bỏ kính đã chọn
5. Nhấp vào nút "Mua ngay" khi bạn đã tìm thấy kính ưng ý

## Cài đặt

Không cần cài đặt đặc biệt. Chỉ cần tải xuống mã nguồn và mở file `index.html` trong trình duyệt web.

```bash
git clone https://github.com/your-username/try-glasses-app.git
cd try-glasses-app
# Mở file index.html trong trình duyệt
```

## Cấu trúc dự án

```
try-glasses-app/
├── index.html      # File HTML chính chứa cấu trúc trang web
├── README.md       # Tài liệu dự án
```

## Tùy chỉnh

Bạn có thể dễ dàng thêm các kiểu kính mới bằng cách thêm vào đối tượng `glassesData` trong file JavaScript:

```javascript
const glassesData = {
    // Thêm kiểu kính mới ở đây
    'new-style': {
        svg: `<svg>...</svg>`,
        name: 'Tên kiểu kính mới'
    }
};
```

## Đóng góp

Đóng góp luôn được chào đón! Nếu bạn muốn đóng góp, vui lòng:

1. Fork dự án
2. Tạo nhánh tính năng (`git checkout -b feature/amazing-feature`)
3. Commit thay đổi của bạn (`git commit -m 'Add some amazing feature'`)
4. Push lên nhánh (`git push origin feature/amazing-feature`)
5. Mở Pull Request

## Giấy phép

Dự án này được cấp phép theo giấy phép MIT - xem file [LICENSE](LICENSE) để biết thêm chi tiết.

## Liên hệ

Hayden - [vuhoangdz2003@gmail.com](mailto:vuhoangdz2003@gmail.com)

