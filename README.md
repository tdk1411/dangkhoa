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
        }

        h1 {
            text-align: center;
        }

        .categories {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            max-width: 1200px;
            margin-top: 20px;
        }

        .category {
            display: inline-block;
            width: 200px;
            text-align: center;
            margin: 20px;
        }
        .category img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 8px;
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
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/van-1.jpg" alt="Văn học">
            <h3>Văn học</h3>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/khoa_hoc.jpg" alt="Khoa học">
            <h3>Khoa học</h3>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/lich_su.jpg" alt="Lịch sử">
            <h3>Lịch sử</h3>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/kinh_doanh.jpg" alt="Kinh doanh">
            <h3>Kinh doanh</h3>
        </div>
        <div class="category">
            <img src="https://github.com/tdk1411/TkWeb_Group10/blob/main/sachonlfinal/IMG/thieu_nhi.jpg" alt="Thiếu nhi">
            <h3>Thiếu nhi</h3>
        </div>
    </div>
</body>
</html>
