<!DOCTYPE html>  
<html lang=**"**ar**"** dir=**"**rtl**"**>  
<head>  
    <meta charset=**"**UTF-8**"**>  
    <meta name=**"**viewport**"** content=**"**width=device-width, initial-scale=1.0**"**>  
    <title>Aroob Downloader - **تحميل** **فيديوهات** **تيك** **توك**</title>  
    <style>  
        body {  
            background-color: #0c0c0c;  
            color: #d4af37;  
            font-family: **'**Segoe UI**'**, Tahoma, Geneva, Verdana, sans-serif;  
            text-align: center;  
            margin: 0;  
            padding: 20px;  
        }  
        .header {  
            padding: 50px 20px;  
        }  
        h1 {  
            font-size: 2.5rem;  
            text-transform: uppercase;  
            letter-spacing: 2px;  
            margin-bottom: 10px;  
        }  
        .container {  
            max-width: 600px;  
            margin: 0 auto;  
            background: #1a1a1a;  
            padding: 40px;  
            border-radius: 20px;  
            border: 1px solid #d4af37;  
            box-shadow: 0 10px 30px rgba**(**212, 175, 55, 0.1**)**;  
        }  
        input[type=**"**text**"**] {  
            width: 100%;  
            padding: 15px;  
            margin-bottom: 20px;  
            border-radius: 10px;  
            border: 1px solid #d4af37;  
            background: #000;  
            color: #fff;  
            box-sizing: border-box;  
        }  
        button {  
            background: linear-gradient**(**45deg, #d4af37, #f9e29c**)**;  
            color: #000;  
            padding: 15px 40px;  
            border: none;  
            border-radius: 10px;  
            font-weight: bold;  
            cursor: pointer;  
            width: 100%;  
            font-size: 1.1rem;  
        }  
        .footer {  
            margin-top: 50px;  
            font-size: 0.8rem;  
            opacity: 0.7;  
        }  
    </style>  
</head>  
<body>  
    <div class=**"**header**"**>  
        <h1>Aroob KH</h1>  
        <p>**الأداة** **الأفخم** **لتحميل** **الفيديوهات** **بدون** **علامة** **مائية**</p>  
    </div>  
  
    <div class=**"**container**"**>  
        <input type=**"**text**"** id=**"**url**"** placeholder=**"ضع** **رابط** **الفيديو** **هنا**...**"**>  
        <button onclick=**"**startDownload**()"**>**بدء** **التحميل**</button>  
        <p id=**"**status**"** style=**"**margin-top: 20px;**"**></p>  
    </div>  
  
    <div class=**"**footer**"**>  
        © 2026 Aroob KH - **جميع** **الحقوق** **محفوظة**  
    </div>  
  
    <script>  
        function startDownload**()** {  
            document.getElementById**('**status**')**.innerText = **"جاري** **الاتصال** **بالمحرك**... **(الخطوة** **القادمة** **ربط** **الـ** API**)"**;  
        }  
    </script>  
</body>  
</html>  
