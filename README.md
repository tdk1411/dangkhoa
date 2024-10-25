
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hộp quà bất ngờ</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
        }
        #gift {
            width: 200px;
            height: 200px;
            cursor: pointer;
        }
        #message {
            font-size: 24px;
            color: red;
            display: none;
        }
    </style>
</head>
<body>
    <h1>Hộp quà bí mật</h1>
    <img id="gift" src="https://png.pngtree.com/png-clipart/20220125/original/pngtree-gift-box-gift-box-png-image_7213113.png" alt="Hộp quà" />
    <div id="message">bắn em vay 500</div>

    <script>
        document.getElementById('gift').addEventListener('click', function() {
            this.style.display = 'none';
            document.getElementById('message').style.display = 'block';
        });
    </script>
</body>
</html>
