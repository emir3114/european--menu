<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Европейское меню</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
        }
        .menu-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px;
        }
        .menu-item {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 250px;
            margin: 10px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .menu-item:hover {
            transform: scale(1.05);
        }
        .menu-item img {
            width: 100%;
            border-top-left-radius: 8px;
            border-top-right-radius: 8px;
        }
        .menu-item h3 {
            margin: 10px 0;
            font-size: 1.2rem;
        }
        .menu-item p {
            margin: 0;
            font-size: 1rem;
            color: #555;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Европейское меню</h1>
    <p>Откройте для себя лучшие блюда европейской кухни</p>
</header>

<section class="menu-section">
    <div class="menu-item">
        <img src="https://via.placeholder.com/250x150?text=Паста+Карбонара" alt="Паста Карбонара">
        <h3>Паста Карбонара</h3>
        <p>Итальянская паста с соусом карбонара</p>
        <p><strong>Цена:</strong> 15.00€</p>
    </div>
    <div class="menu-item">
        <img src="https://via.placeholder.com/250x150?text=Рататуй" alt="Рататуй">
        <h3>Рататуй</h3>
        <p>Французское овощное рагу</p>
        <p><strong>Цена:</strong> 12.00€</p>
    </div>
    <div class="menu-item">
        <img src="https://via.placeholder.com/250x150?text=Паэлья" alt="Паэлья">
        <h3>Паэлья</h3>
        <p>Испанское блюдо с рисом и морепродуктами</p>
        <p><strong>Цена:</strong> 18.00€</p>
    </div>
</section>

<footer>
    <p>&copy; 2025 Европейское меню | Все права защищены</p>
</footer>

</body>
</html>
