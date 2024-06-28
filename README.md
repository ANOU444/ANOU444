- 👋 Hi, I’m @ANOU444
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
ANOU444/ANOU444 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KIPPLAY - ร้านค้าเครื่องกีฬา</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        .container {
            padding: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
        }
        .product {
            border: 1px solid #ddd;
            padding: 16px;
            margin-bottom: 20px;
        }
        .product h3 {
            margin: 0;
        }
        .review {
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            padding: 10px;
            margin-bottom: 20px;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>ร้าน KIPPLAY</h1>
        <p>เครื่องกีฬาคุณภาพสำหรับทุกคน</p>
    </header>
    
    <div class="container">
        <section>
            <h2>สินค้า</h2>
            <div class="product">
                <h3>เสื้อกีฬา</h3>
                <p>เสื้อกีฬาคุณภาพสูง มีหลากหลายสีและขนาดให้เลือก</p>
            </div>
            <div class="product">
                <h3>กางเกงกีฬา</h3>
                <p>กางเกงกีฬาเบาสบาย สำหรับทุกการเคลื่อนไหว</p>
            </div>
            <div class="product">
                <h3>รองเท้า</h3>
                <p>รองเท้ากีฬาที่เหมาะสำหรับทุกประเภทกีฬา</p>
            </div>
        </section>

        <section class="gallery">
            <h2>แกลเลอรี่ภาพสินค้า</h2>
            <img src="shirt.jpg" alt="เสื้อกีฬา">
            <img src="pants.jpg" alt="กางเกงกีฬา">
            <img src="shoes.jpg" alt="รองเท้า">
        </section>

        <section>
            <h2>รีวิวจากลูกค้า</h2>
            <div class="review">
                <p>“สินค้าคุณภาพดีมาก จัดส่งรวดเร็ว” - สมชาย</p>
            </div>
            <div class="review">
                <p>“ชอบเสื้อกีฬาที่ซื้อจากที่นี่มากค่ะ ใส่สบายสุดๆ” - อรวรรณ</p>
            </div>
        </section>

        <section>
            <h2>แบบฟอร์มการสั่งซื้อ</h2>
            <form action="/submit_order" method="post">
                <label for="name">ชื่อ:</label><br>
                <input type="text" id="name" name="name" required><br>
                <label for="email">อีเมล:</label><br>
                <input type="email" id="email" name="email" required><br>
                <label for="product">สินค้า:</label><br>
                <select id="product" name="product" required>
                    <option value="shirt">เสื้อกีฬา</option>
                    <option value="pants">กางเกงกีฬา</option>
                    <option value="shoes">รองเท้า</option>
                </select><br><br>
                <input type="submit" value="สั่งซื้อ">
            </form>
            <p>สั่งซื้อทางเว็บไซต์รับส่วนลด 50%!</p>
        </section>
    </div>

    <footer>
        <p>ติดต่อเรา: info@kipplay.com | โทร: 012-345-6789</p>
    </footer>
</body>
</html>
