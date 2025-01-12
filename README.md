<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bảo Vệ Môi Trường</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 20px 10px;
            text-align: center;
        }
        nav {
            background: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background: #ddd;
            color: black;
        }
        section {
            padding: 20px;
        }
        .banner img {
            max-width: 100%;
            height: auto;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .content div {
            flex: 1 1 300px;
            border: 1px solid #ccc;
            padding: 15px;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
            border-radius: 5px;
        }
        footer {
            background: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .video-container {
            text-align: center;
            margin: 20px 0;
        }
        .video-container iframe {
            width: 100%;
            max-width: 560px;
            height: 315px;
            border: none;
        }
        .additional-content img {
            float: left;
            margin-right: 15px;
            max-width: 40%;
            height: auto;
            border-radius: 10px;
        }
        .clear {
            clear: both;
        }
        #capture {
            margin: 20px auto;
            display: block;
            padding: 10px 20px;
            background: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }
        #capture:hover {
            background: #45a049;
        }
    </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/0.4.1/html2canvas.min.js"></script>
</head>
<body>
    <header>
        <h1>Chung Tay Bảo Vệ Môi Trường</h1>
        <p>Hành động hôm nay để cứu lấy ngày mai</p>
    </header>

    <nav>
        <a href="#home">Trang Chủ</a>
        <a href="#about">Về Chúng Tôi</a>
        <a href="#activities">Hoạt Động</a>
        <a href="#contact">Liên Hệ</a>
    </nav>

    <section id="home" class="banner">
        <img src="images/environment-banner.jpg" alt="Hình ảnh bảo vệ môi trường">
        <p>Trái đất là ngôi nhà chung của chúng ta. Hãy bảo vệ nó!</p>
    </section>

    <section class="video-container">
        <h2>Video Truyền Cảm Hứng</h2>
        <iframe 
            src="https://www.youtube.com/embed/qetZJiQa-z8" 
            title="Xem Xong Bạn Sẽ Khác | Bảo Vệ Môi Trường - Chống Rác Thải Nhựa" 
            frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
        </iframe>
    </section>

    <section id="about">
        <h2>Về Chúng Tôi</h2>
        <p>Chúng tôi là một tổ chức phi lợi nhuận với sứ mệnh nâng cao nhận thức và thúc đẩy các hoạt động bảo vệ môi trường. 
           Đội ngũ của chúng tôi bao gồm các tình nguyện viên và chuyên gia cam kết mang đến sự thay đổi tích cực cho cộng đồng.</p>
        <div class="additional-content">
            <img src="images/team-working.jpg" alt="Hình ảnh đội ngũ làm việc">
            <p>Chúng tôi tổ chức các buổi họp mặt định kỳ để thảo luận các giải pháp bền vững. Với sự hỗ trợ của cộng đồng, chúng tôi đã thực hiện nhiều chiến dịch lớn, từ trồng rừng đến tuyên truyền giáo dục tại các trường học và khu dân cư.</p>
            <div class="clear"></div>
        </div>
    </section>

    <section id="activities">
        <h2>Các Hoạt Động</h2>
        <div class="content">
            <div>
                <h3>Trồng Cây Xanh</h3>
                <img src="images/planting-trees.jpg" alt="Hình ảnh trồng cây xanh">
                <p>Tham gia các chương trình trồng cây xanh để phủ xanh các khu vực bị khai thác quá mức.</p>
            </div>
            <div>
                <h3>Thu Gom Rác Thải</h3>
                <img src="images/cleaning-up.jpg" alt="Hình ảnh thu gom rác thải">
                <p>Hỗ trợ các chiến dịch làm sạch bãi biển, công viên và khu vực công cộng.</p>
            </div>
            <div>
                <h3>Tuyên Truyền Giáo Dục</h3>
                <img src="images/education-campaign.jpg" alt="Hình ảnh tuyên truyền giáo dục">
                <p>Đào tạo và nâng cao nhận thức cộng đồng về bảo vệ môi trường.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Liên Hệ</h2>
        <p>Nếu bạn muốn tham gia cùng chúng tôi hoặc có bất kỳ câu hỏi nào, vui lòng liên hệ:</p>
        <ul>
            <li>Email: info@moitruong.com</li>
            <li>Điện thoại: 0123 456 789</li>
            <li>Địa chỉ: 123 Đường Xanh, Thành phố Xanh</li>
        </ul>
        <div class="additional-content">
            <img src="images/contact-team.jpg" alt="Hình ảnh liên hệ">
            <p>Đội ngũ hỗ trợ của chúng tôi luôn sẵn sàng giải đáp thắc mắc và cung cấp thông tin về các hoạt động của tổ chức. Hãy liên hệ ngay hôm nay để cùng chung tay bảo vệ môi trường.</p>
            <div class="clear"></div>
        </div>
    </section>

    <button id="capture">Chụp Ảnh Trang Web</button>

    <footer>
        <p>&copy; 2025 Bảo Vệ Môi Trường. Tất cả các quyền được bảo lưu.</p>
    </footer>

    <script>
        document.getElementById('capture').addEventListener('click', function () {
            html2canvas(document.body).then(function (canvas) {
                var link = document.createElement('a');
                link.href = canvas.toDataURL();
                link.download = 'bao-ve-moi-truong.png';
                link.click();
            });
        });
    </script>
</body>
</html>

