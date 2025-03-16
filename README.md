<!DOCTYPE html>
<html lang="vi">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Dashboard Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f8f9fa;
            padding: 20px;
        }
        h2 {
            color: #333;
        }
        .menu-btn {
            display: block;
            width: 90%;
            max-width: 300px;
            margin: 10px auto;
            padding: 15px;
            font-size: 16px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .menu-btn:hover {
            background-color: #0056b3;
        }
    </style>
    <script>
        function openLink(url) {
            window.open(url, '_blank');
        }
    </script>
</head>
<body>
    <h2>📌 Dashboard Menu</h2>
    <button class="menu-btn" onclick="openLink('https://docs.google.com/spreadsheets/')">📊 Google Sheets</button>
    <button class="menu-btn" onclick="openLink('https://forms.google.com')">📋 Google Forms</button>
    <button class="menu-btn" onclick="openLink('https://lookerstudio.google.com/')">📈 Google Looker Studio</button>
    <button class="menu-btn" onclick="openLink('https://drive.google.com/')">📂 Google Drive</button>
</body>
</html>
