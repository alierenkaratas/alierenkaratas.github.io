<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ali Eren Karataş - Portföy</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8;
        }
        header {
            background: #3b5998;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 20px;
            margin: 10px auto;
            background: #fff;
            max-width: 800px;
            border-radius: 5px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #3b5998;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .proje {
            margin-bottom: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ali Eren Karataş</h1>
        <nav>
            <ul>
                <li><a href="#hakkimda">Hakkımda</a></li>
                <li><a href="#yetenekler">Yetenekler</a></li>
                <li><a href="#deneyimlerim">Deneyimlerim</a></li>
                <li><a href="#projelerim">Projelerim</a></li>
                <li><a href="#egitim">Eğitim</a></li>
                <li><a href="#iletisim">İletişim</a></li>
            </ul>
        </nav>
    </header>

    <section id="hakkimda">
        <h2>Hakkımda</h2>
        <p>Merhaba! Ben Ali Eren Karataş, yazılım geliştirme alanında tutkulu bir bireyim. Bilgisayar mühendisliği eğitimim sayesinde, kullanıcı odaklı çözümler üretmeyi hedefliyorum. HTML, CSS ve JavaScript dillerinde uzmanlaşarak, dinamik web uygulamaları geliştirme konusunda kendimi sürekli olarak geliştiriyorum.</p>
        <p>Teknolojiye olan ilgim, sorun çözme becerim ve yaratıcılığım sayesinde projelerde yenilikçi ve etkili sonuçlar elde ediyorum. Boş zamanlarımda yeni teknolojiler ve yazılım dilleri hakkında bilgi edinmek, ayrıca doğa yürüyüşleri yapmayı seviyorum.</p>
    </section>

    <section id="yetenekler">
        <h2>Yetenekler</h2>
        <ul>
            <li>HTML5, CSS3, JavaScript</li>
            <li>Veritabanı yönetimi (MySQL, MongoDB)</li>
        </ul>
    </section>

    <section id="deneyimlerim">
        <h2>Deneyimlerim</h2>
        <ul>
            <li>
                <strong>XYZ Şirketi</strong> - Yazılım Geliştirici (2022 - Günümüz)
                <p>Dinamik web uygulamaları geliştirerek kullanıcı deneyimini artırmaya yönelik çalışmalara katkıda bulunuyorum.</p>
            </li>
            <li>
                <strong>ABC Yazılım</strong> - Stajyer Yazılım Geliştirici (2021 - 2022)
                <p>Farklı projelerde yer alarak yazılım geliştirme süreçlerini deneyimledim.</p>
            </li>
        </ul>
    </section>

    <section id="projelerim">
        <h2>Projelerim</h2>
        <div class="proje">
            <h3>Görev Yönetimi Uygulaması</h3>
            <p>Kullanıcıların görevlerini yönetebileceği bir web uygulaması geliştirdim.</p>
            <a href="#" target="_blank">Projeyi Görüntüle</a>
        </div>
        <div class="proje">
            <h3>Kişisel Blog</h3>
            <p>Yazılarımı paylaşmak için geliştirdiğim basit bir blog uygulaması.</p>
            <a href="#" target="_blank">Projeyi Görüntüle</a>
        </div>
    </section>

    <section id="egitim">
        <h2>Eğitim</h2>
        <ul>
            <li>
                <strong>ABC Üniversitesi</strong> - Bilgisayar Mühendisliği (2019 - 2023)
                <p>Yazılım mühendisliği üzerine yoğunlaştım ve çeşitli projelerde yer aldım.</p>
            </li>
        </ul>
    </section>

    <section id="iletisim">
        <h2>İletişim Bilgileri</h2>
        <form>
            <label for="isim">İsim:</label>
            <input type="text" id="isim" name="isim" required>
            
            <label for="email">E-posta:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="mesaj">Mesaj:</label>
            <textarea id="mesaj" name="mesaj" required></textarea>
            
            <button type="submit">Gönder</button>
        </form>
    </section>

    <footer>
        <p>2024 Ali Eren Karataş</p>
    </footer>
</body>
</html>
