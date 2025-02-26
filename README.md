<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Sayfa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 10px;
        }
        .container {
            max-width: 100%;
            margin: auto;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        @media (max-width: 600px) {
            h1 {
                font-size: 24px;
            }
            p {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Merhaba!</h1>
        <p>Bu sayfa artık mobil uyumlu.</p>
        <img src="resim.jpg" alt="Örnek Resim">
    </div>
</body>
</html>
