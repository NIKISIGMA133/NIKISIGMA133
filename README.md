 <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nugget Tahu Sehat</title>
    <style>
        /* CSS Dasar */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            background: linear-gradient(135deg, #ffcc80, #ff8c00);
        }

        header {
            background-color: #35424a;
            color: #ffffff;
            text-align: center;
            padding: 20px;
            width: 100%;
        }

        .container {
            width: 90%;
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            background-image: url('link-ke-gambar-tahu.jpg'); /* Ganti dengan URL gambar tahu */
            background-size: cover;
            background-position: center;
        }

        h1, h2 {
            color: #ff8c00;
        }

        p, ul, ol {
            max-width: 600px;
            margin: auto;
            text-align: justify;
            background: rgba(255, 255, 255, 0.8); /* Menambahkan sedikit transparansi */
            padding: 10px;
            border-radius: 8px;
        }

        section {
            padding: 1em;
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.5s ease, transform 0.5s ease;
        }

        section.show {
            opacity: 1;
            transform: translateY(0);
        }

        .menu-item {
            display: flex;
            justify-content: space-between;
            padding: 10px;
            border-bottom: 1px solid #ddd;
            font-size: 18px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 8px;
        }

        .menu-item:last-child {
            border-bottom: none;
        }

        .menu-section {
            background-color: #f7c35f;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
            background: rgba(255, 255, 255, 0.8);
        }

        .menu-price {
            color: #666;
        }

        .button-order {
            display: block;
            background-color: #35424a;
            color: #fff;
            text-align: center;
            padding: 12px;
            border-radius: 8px;
            text-decoration: none;
            font-size: 18px;
            margin-top: 20px;
        }

        .button-order:hover {
            background-color: #2c3a3d;
        }

        form {
            max-width: 600px;
            margin: auto;
            padding: 1em;
            background: rgba(255, 255, 255, 0.9);
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        label {
            display: block;
            margin-bottom: 0.5em;
        }

        input[type="text"],
        input[type="email"] {
            width: 100%;
            padding: 0.5em;
            margin-bottom: 1em;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        input[type="submit"],
        input[type="reset"] {
            background-color: #ff8c00;
            color: white;
            border: none;
            padding: 0.5em 1em;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
        }

        input[type="submit"]:hover,
        input[type="reset"]:hover {
            background-color: #e07a00;
        }

        footer {
            background-color: #35424a;
            color: #ffffff;
            text-align: center;
            padding: 1em;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Nugget Tahu Sehat</h1>
</header>

<div class="container">
    <section id="manfaat">
        <h2>Manfaat dan Kepraktisan</h2>
        <ul>
            <li><strong>Sehat dan Bergizi:</strong> Nugget tahu mengandung protein tinggi dari tahu yang baik untuk tubuh dan ideal sebagai camilan sehat.</li>
            <li><strong>Mudah dan Praktis:</strong> Bisa langsung digoreng tanpa persiapan rumit, menjadikannya pilihan tepat untuk keluarga yang sibuk.</li>
            <li><strong>Rasa yang Gurih:</strong> Dibuat dengan bahan berkualitas untuk menghasilkan rasa gurih dan tekstur renyah.</li>
            <li><strong>Harga Terjangkau:</strong> Tersedia dalam pilihan kemasan yang ekonomis, cocok untuk anak-anak hingga orang dewasa.</li>
            <li><strong>Beragam Variasi:</strong> Tersedia dengan pilihan saus, menambah kenikmatan dalam setiap gigitan.</li>
        </ul>
    </section>

    <section id="cara">
        <h2>Cara Membuat Nugget Tahu</h2>
        <ol>
            <li>Hancurkan tahu hingga lembut.</li>
            <li>Campur dengan bahan lainnya hingga merata.</li>
            <li>Bentuk adonan menjadi nugget dan lapisi dengan tepung roti.</li>
            <li>Goreng hingga berwarna kecoklatan.</li>
        </ol>
    </section>

    <section id="menu">
        <div class="menu-section">
            <h2>Menu Pilihan</h2>
            <div class="menu-item">
                <span>🍢 Nugget Tahu (Isi 3) - Mika</span>
                <span class="menu-price">Rp5.000</span>
            </div>
            <div class="menu-item">
                <span>🍢 Nugget Tahu + Saus</span>
                <span class="menu-price">Rp7.000</span>
            </div>
        </div>
    </section>

    <section id="pesan">
        <h2>Pesan Sekarang!</h2>
        <p>Isi formulir di bawah ini untuk memesan nugget tahu:</p>
        
        <form action="mailto:nikisorong640@gmail.com" method="get" enctype="text/plain">
            <label for="name">Nama:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <input type="submit" value="Pesan Nugget Tahu">
            <input type="reset" value="Reset">
        </form>
    </section>
</div>

<footer>
    <p>&copy; 2024 Nugget Tahu Sehat. Semua Hak Dilindungi.</p>
    <p>Instagram: <a href="https://instagram.com/niki_nenobais" target="_blank">@niki_nenobais</a> | Kelas: <a href="https://instagram.com/classique.x2" target="_blank">@classique.x2</a></p>
</footer>

<script>
    // Animasi Scroll Muncul dan Hilang
    const sections = document.querySelectorAll("section");

    function handleScrollAnimation() {
        sections.forEach((section) => {
            const sectionTop = section.getBoundingClientRect().top;
            const sectionBottom = section.getBoundingClientRect().bottom;
            const windowHeight = window.innerHeight;

            // Muncul saat bagian bawah elemen masuk layar, hilang saat keluar layar
            if (sectionTop < windowHeight && sectionBottom > 0) {
                section.classList.add("show");
            } else {
                section.classList.remove("show");
            }
        });
    }

    window.addEventListener("scroll", handleScrollAnimation);
    window.addEventListener("load", handleScrollAnimation);
</script>

</body>
</html>
