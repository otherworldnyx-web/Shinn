<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat ulaangg tahunn sayaanggkuu!</title>
    <style>
        /* Gaya khusus untuk layar HP */
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #1a1a1a; /* Tema gelap ala aplikasi modern */
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            color: white;
            overflow: hidden;
        }
        .container {
            text-align: center;
            width: 85%;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 25px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid #ff4d6d;
            margin-bottom: 15px;
            object-fit: cover;
        }
        h1 { font-size: 1.5rem; margin-bottom: 10px; color: #ff4d6d; }
        p { font-size: 1rem; line-height: 1.5; opacity: 0.9; }
        .btn {
            background: #ff4d6d;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 50px;
            font-weight: bold;
            margin-top: 20px;
            box-shadow: 0 4px 15px rgba(255, 77, 109, 0.4);
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="foto.jpg" class="profile-pic" alt="Ulang Tahun">
        <h1>Happy Birthday! 🎉</h1>
        <p>buatt pacarrkuu sayaaangg
        <p>semogaa di usia kamuu yang baru inii, semua impianmu satu per satu jadi nyata yaa sayaangh. tetepp semangatt sayaangg,,kamuu hebatt buatt bisa sampee sekarangg!</p>
        <button class="btn" onclick="tambahKertas()">Buka Kejutan 🎁</button>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.5.1/dist/confetti.browser.min.js"></script>
    <script>
        function tambahKertas() {
            confetti({
                particleCount: 150,
                spread: 70,
                origin: { y: 0.6 }
            });
            alert("Ciee yang ulang tahun! 🎂✨");
        }
    </script>
</body>
</html>
