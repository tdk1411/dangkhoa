<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thể loại sách</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            padding: 0;
        }

        h1 {
            text-align: center;
            margin-top: 20px;
        }

        .categories {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
            flex-wrap: wrap; /* Đảm bảo ảnh tự động xuống dòng khi không đủ không gian */
            max-width: 100%;
            padding: 0 20px;
        }

        .category {
            width: 200px;
            text-align: center;
        }

        .category img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 8px;
            transition: transform 0.3s ease; /* Tạo hiệu ứng khi hover */
        }

        .category img:hover {
            transform: scale(1.05); /* Phóng to nhẹ khi di chuột vào */
        }

        .category h3 {
            margin-top: 10px;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <h1>Thể loại sách</h1>
    <div class="categories">
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-120-mon-sup-bo-duong-cho-tre-em-va-nguoi-benh.jpg?raw=true" alt="Ẩm thực - Nấu ăn">
            <a href="https://nhasachmienphi.com/category/am-thuc-nau-an">
              <button>Ẩm thực - Nấu ăn</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-tu-hoc-tieng-anh-hieu-qua.jpg?raw=true" alt="Học Ngoại Ngữ">
            <a href="https://nhasachmienphi.com/category/hoc-ngoai-ngu">
              <button>Học Ngoại Ngữ</button>
            </a>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/khoa_hoc_v2.jpg?raw=true" alt="Khoa Học - Kỹ Thuật">
            <a href="https://nhasachmienphi.com/category/khoa-hoc-ky-thuat">
              <button>Khoa Học - Kỹ Thuật</button>
            </a>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/kinh_doanh_v2.jpg?raw=true" alt="Kinh Tế - Quản Lý">
            <a href="https://nhasachmienphi.com/category/kinh-te-quan-ly">
              <button>Kinh Tế - Quản Lý</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/wp-content/uploads/Huong-dan-bao-ton-da-dang-sinh-hoc-Viet-nam.jpg?raw=true" alt="Nông - Lâm - Ngư">
            <a href="https://nhasachmienphi.com/category/nong-lam-ngu">
              <button>Nông - Lâm - Ngư</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/wp-content/uploads/khoa-hoc-livestream.png?raw=true" alt="Sách nói miễn phí">
            <a href="https://nhasachmienphi.com/category/sach-noi-mien-phi">
              <button>Sách nói miễn phí</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/wp-content/uploads/FB_IMG_1656397154891.jpg?raw=true" alt="Thơ Hay">
            <a href="https://nhasachmienphi.com/category/tho-hay">
              <button>Thơ Hay</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-thien-tang.jpg?raw=true" alt="Tiểu Thuyết Trung Quốc">
            <a href="https://nhasachmienphi.com/category/tieu-thuyet-trung-quoc">
              <button>Tiểu Thuyết Trung Quốc</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-tho-ngu-ngon-la-fontaine.jpg?raw=true" alt="Truyện Cười - Tiếu Lâm">
            <a href="https://nhasachmienphi.com/category/truyen-cuoi-tieu-lam">
              <button>Truyện Cười - Tiếu Lâm</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-co-dau-di-hoc.jpg?raw=true" alt="Truyện Teen - Tuổi Học Trò">
            <a href="https://nhasachmienphi.com/category/truyen-teen-tuoi-hoc-tro">
              <button>Truyện Teen - Tuổi Học Trò</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-duc-phat-va-phat-phap.jpg?raw=true" alt="Văn Hoá - Tôn Giáo">
            <a href="https://nhasachmienphi.com/category/van-hoa-ton-giao">
              <button>Văn Hoá - Tôn Giáo</button>
            </a>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/thieu_nhi_v2.jpg?raw=true" alt="Cổ Tích - Thần Thoại">
            <a href="https://nhasachmienphi.com/category/co-tich-than-thoai">
              <button>Cổ Tích - Thần Thoại</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/wp-content/uploads/sach-noi-cuoc-doi-va-su-nghiep-tong-thong-my-Abraham-Lincoln.jpg?raw=true" alt="Hồi Ký - Tuỳ Bút">
            <a href="https://nhasachmienphi.com/category/hoi-ky-tuy-but">
              <button>Hồi Ký - Tuỳ Bút</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-pham-nhan-tu-tien-chi-tien-gioi-thien-pham-nhan-tu-tien-2.jpg?raw=true" alt="Kiếm Hiệp - Tiên Hiệp">
            <a href="https://nhasachmienphi.com/category/kiem-hiep-tien-hiep">
              <button>Kiếm Hiệp - Tiên Hiệp</button>
            </a>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/lich_su_v2.jpg?raw=true" alt="Lịch Sử - Chính Trị">
            <a href="https://nhasachmienphi.com/category/lich-su-chinh-tri">
              <button>Lịch Sử - Chính Trị</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-tarzan-1-con-cua-rung-xanh.jpg?raw=true" alt="Phiêu Lưu - Mạo Hiểm">
            <a href="https://nhasachmienphi.com/category/phieu-luu-mao-hiem">
              <button>Phiêu Lưu - Mạo Hiểm</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-de-co-tri-nho-tot.jpg?raw=true" alt="Tâm Lý - Kỹ Năng Sống">
            <a href="https://nhasachmienphi.com/category/tam-ly-ky-nang-song">
              <button>Tâm Lý - Kỹ Năng Sống</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-giao-trinh-luat-hanh-chinh-viet-nam.jpg?raw=true" alt="Thư Viện Pháp Luật">
            <a href="https://nhasachmienphi.com/category/thu-vien-phap-luat">
              <button>Thư Viện Pháp Luật</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-cuoc-cach-mang-nguoc-trong-khoa-hoc.jpg?raw=true" alt="Triết Học">
            <a href="https://nhasachmienphi.com/category/triet-hoc">
              <button>Triết Học</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-nhat-ky-phong-tro-ma.jpg?raw=true" alt="Truyện Ma - Truyện Kinh Dị">
            <a href="https://nhasachmienphi.com/category/truyen-ma-truyen-kinh-di">
              <button>Truyện Ma - Truyện Kinh Dị</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-truyen-tranh-doremon-plus.jpg?raw=true" alt="Truyện Tranh">
            <a href="https://nhasachmienphi.com/category/truyen-tranh">
              <button>Truyện Tranh</button>
            </a>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/van_hoc_v2.jpg?raw=true" alt="Văn Học Việt Nam">
            <a href="https://nhasachmienphi.com/category/van-hoc-viet-nam">
              <button>Văn Học Việt Nam</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-cong-nghe-blockchain.jpg?raw=true" alt="Công Nghệ Thông Tin">
            <a href="https://nhasachmienphi.com/category/cong-nghe-thong-tin">
              <button>Công Nghệ Thông Tin</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-vo-han-khung-bo.jpg?raw=true" alt="Huyền bí - Giả Tưởng">
            <a href="https://nhasachmienphi.com/category/huyen-bi-gia-tuong">
              <button>Huyền Bí - Giả Tưởng</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-cac-kieu-kien-truc-tren-the-gioi.jpg?raw=true" alt="Kiến Trúc - Xây Dựng">
            <a href="https://nhasachmienphi.com/category/kien-truc-xay-dung">
              <button>Kiến Trúc - Xây Dựng</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-nghe-thuat-lay-long-khach-hang.jpg?raw=true" alt="Marketing - Bán Hàng">
            <a href="https://nhasachmienphi.com/category/marketing-ban-hang">
              <button>Marketing - Bán Hàng</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/wp-content/uploads/B%E1%BB%99-S%C3%A1ch-Gi%C3%A1o-Khoa-l%E1%BB%9Bp-12.jpg?raw=true" alt="Sách Giáo Khoa">
            <a href="https://nhasachmienphi.com/category/sach-giao-khoa">
              <button>Sách Giáo Khoa</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-ky-thuat-danh-bong-ban.jpg?raw=true" alt="Thể Thao - Nghệ Thuật">
            <a href="https://nhasachmienphi.com/category/the-thao-nghe-thuat">
              <button>Thể Thao - Nghệ Thuật</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-moi-tinh-dau.jpg?raw=true" alt="Tiểu Thuyết Phương Tây">
            <a href="https://nhasachmienphi.com/category/tieu-thuyet-phuong-tay">
              <button>Tiểu Thuyết Phương Tây</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-an-mang-dem-cuoi-nam.jpg?raw=true" alt="Trinh Thám - Hình Sự">
            <a href="https://nhasachmienphi.com/category/trinh-tham-hinh-su">
              <button>Trinh Thám - Hình Sự</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-lam-vo-bac-si.jpg?raw=true" alt="Truyện Ngắn - Ngôn Tình">
            <a href="https://nhasachmienphi.com/category/truyen-ngan-ngon-tinh">
              <button>Truyện Ngắn - Ngôn Tình</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/images/thumbnail/nhasachmienphi-tu-vi-dau-so-toan-thu-2.jpg?raw=true" alt="Tử Vi - Phong Thuỷ">
            <a href="https://nhasachmienphi.com/category/tu-vi-phong-thuy">
              <button>Tử Vi - Phong Thuỷ</button>
            </a>
        </div>
        <div class="category">
            <img src="https://nhasachmienphi.com/wp-content/uploads/Ch%C4%83m-s%C3%B3c-r%C4%83ng-mi%E1%BB%87ng-to%C3%A0n-di%E1%BB%87n.jpg?raw=true" alt="Y Học - Sức Khoẻ">
            <a href="https://nhasachmienphi.com/category/y-hoc-suc-khoe">
              <button>Y Học - Sức Khoẻ</button>
            </a>
        </div>
    </div>
</body>
</html>
