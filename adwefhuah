
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang chủ</title>
    <link rel="stylesheet" href="/trangchu.css">
    <link rel="icon" href="/IMG/icon.png">
</head>
<body>

    <header>
        <h1>Tiêu Đề Trang Web</h1>
        <nav class="navbar">
            <ul>
                <li><a href="#">Trang Chủ</a></li> <!-- Gắn link trang chủ -->
                <li><a href="gioithieu.html">Giới Thiệu</a></li>
                <li><a href="#">Thể loại</a></li>   <!-- Gắn link thể loại -->
                <li><a href="#">Tin tức</a></li>    <!-- Gắn link tin tức -->
                <li><a href="#">Sản phẩm</a></li>  <!-- Gắn link sản phẩm -->
                <li><a href="#">Blog</a></li>   <!-- Gắn link blog -->
                
                
            </ul>
        </nav>
    </header>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .slideshow-container {
            position: relative;
            max-width: 800px;
            margin: auto;
            overflow: hidden;
            border: 2px; /* Thêm viền  */
        }

        .slide {
            display: none;
            width: 100%;
            height: 200px; /* Chiều cao cố định cho các ảnh */
            position: relative;
        }

        img {
            width: 100%;
            height: 100%;
            object-fit: cover; /* Giúp hình ảnh vừa khít mà không bị biến dạng */
            width: 1000px ;
            height: 200px;
            padding:10px ;
        }

        .active {
            display: block;
        }
    </style>
</head>
<body>

<div class="slideshow-container">
    <div class="slide active">
        <img src="/IMG/dautien.png" alt="https://haycafe.vn/wp-content/uploads/2022/03/Background-sach-background-book-800x488.jpg">
    </div>
    <div class="slide">
        <img src="/IMG/SL2.jfif" alt="Image 2">
    </div>
    <div class="slide">
        <img src="/IMG/SL1.png" alt="Image 3">
    </div>
    <div class="slide">
        <img src="/IMG/SL3.png" alt="Image 4">
    </div>
    <div class="slide">
        <img src="/IMG/SL4.png" alt="Image 5">
    </div>
</div>

<script>
    let currentSlide = 0;
    const slides = document.querySelectorAll('.slide');
    const totalSlides = slides.length;

    function showSlide(index) {
        slides.forEach((slide, i) => {
            slide.classList.toggle('active', i === index);
        });
    }

    function nextSlide() {
        currentSlide = (currentSlide + 1) % totalSlides;
        showSlide(currentSlide);
    }

    setInterval(nextSlide, 3000); // Thay đổi slide mỗi 3 giây
</script>

</body>
    <script>
        window.confirm("Nhận thông báo khi có truyện mới");
    </script>
    <footer>
        <p>Phản hồi sách có nội dung xấu, xin gửi về: NhasachMienphi.com@gmail.com</p>
        <p>Bản quyền © 2024</p>
    </footer>
    </body>
    </html>
    
