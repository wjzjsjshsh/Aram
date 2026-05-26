<!DOCTYPE html>
<html lang="ku">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile | AK-47 Edition</title>
    <style>
        /* ڕێکخستنا گشتی یا لاپەڕی */
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            /* وێنێ پشتپەردێ: چەکێ AK-47 ب شێوازەکێ تەکتیتکی و جوان */
            background: url('https://images.unsplash.com/photo-1695642820359-2ca73ccdf98d?q=80&w=1200&auto=format&fit=crop') no-repeat center center fixed;
            background-size: cover;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        }

        /* کارتێ سەرەکی یا شووشەیی دۆدری (Dark Glassmorphism) */
        .main-card {
            background: rgba(0, 0, 0, 0.45); /* من کارتەکا تۆختر دانا دا کۆد دگەل وێنەی بگۆنجیت */
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 35px 25px;
            border-radius: 30px;
            text-align: center;
            box-shadow: 0 20px 50px rgba(0, 0, 0, 0.6);
            max-width: 400px;
            width: 85%;
            animation: fadeIn 1.2s ease-in-out;
        }

        /* ناڤنیشانێ سەرەکی */
        .card-title {
            color: #ffffff;
            font-size: 1.8rem;
            margin-bottom: 25px;
            font-weight: bold;
            text-shadow: 0 2px 10px rgba(0,0,0,0.8);
            letter-spacing: 1px;
        }

        /* ستایلێ گشتی یێ دوگمەیان */
        .social-btn {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 14px 20px;
            margin: 15px 0;
            border-radius: 50px;
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0,0,0,0.4);
        }

        .social-btn:hover {
            transform: translateY(-4px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.6);
        }

        /* 1. تیکتۆک */
        .tiktok {
            background-color: #000000;
            color: #ffffff;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        .tiktok:hover { border-color: #ff0050; }

        /* 2. سناپچات */
        .snapchat {
            background-color: #FFFC00;
            color: #000000;
        }
        .snapchat:hover { background-color: #fff300; }

        /* 3. رۆبلۆکس */
        .roblox {
            background-color: #ffffff;
            color: #111111;
            border: 1px solid #111111;
        }
        .roblox:hover {
            background-color: #e51921;
            color: #ffffff;
            border-color: #e51921;
        }

        /* ئیمۆجی و ڕێکخستنا ناڤی */
        .icon { font-size: 1.4rem; }
        .user-text { flex-grow: 1; text-align: center; }

        /* ئەنیمەیشنا دیاربوونێ */
        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.95); }
            to { opacity: 1; transform: scale(1); }
        }
    </style>
</head>
<body>

    <div class="main-card">
        <div class="card-title">MY ACCOUNTS ⚔️</div>

        <a href="https://www.tiktok.com/@a_r_a139" target="_blank" class="social-btn tiktok">
            <span class="icon">🎵</span>
            <span class="user-text">@a_r_a139</span>
            <span class="icon">➔</span>
        </a>

        <a href="https://www.snapchat.com/add/axa294928" target="_blank" class="social-btn snapchat">
            <span class="icon">👻</span>
            <span class="user-text">axa294928</span>
            <span class="icon">➔</span>
        </a>

        <a href="#" onclick="alert('Roblox Username: Bawar_17'); return false;" class="social-btn roblox">
            <span class="icon">🎮</span>
            <span class="user-text">Bawar_17</span>
            <span class="icon">➔</span>
        </a>
    </div>

</body>
</html>
