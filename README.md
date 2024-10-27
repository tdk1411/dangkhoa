<!DOCTYPE html>
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
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/van_hoc_v2.jpg?raw=true" alt="Văn Học Việt Nam">
            <a href="https://nhasachmienphi.com/category/van-hoc-viet-nam">
              <button>Văn Học Việt Nam</button>
            </a>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/khoa_hoc_v2.jpg?raw=true" alt="Khoa Học - Kỹ Thuật">
            <a href="https://nhasachmienphi.com/category/khoa-hoc-ky-thuat">
              <button>Khoa Học - Kỹ Thuật</button>
            </a>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/lich_su_v2.jpg?raw=true" alt="Lịch Sử - Chính Trị">
            <a href="https://nhasachmienphi.com/category/lich-su-chinh-tri">
              <button>Lịch Sử - Chính Trị</button>
            </a>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/kinh_doanh_v2.jpg?raw=true" alt="Kinh Tế - Quản Lý">
            <a href="https://nhasachmienphi.com/category/kinh-te-quan-ly">
              <button>Kinh Tế - Quản Lý</button>
            </a>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/thieu_nhi_v2.jpg?raw=true" alt="Cổ Tích - Thần Thoại">
            <a href="https://nhasachmienphi.com/category/co-tich-than-thoai">
              <button>Cổ Tích - Thần Thoại</button>
            </a>
        </div>
    </div>
</body>
</html>
