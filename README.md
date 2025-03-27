<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мое расписание на неделю</title>
    <style>
        body {
            background-image: url('background.jpg');
            background-size: cover;
            background-attachment: fixed;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #fff;
            margin: 0;
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            background-color: rgba(0, 0, 0, 0.7);
            max-width: 800px;
            margin: 30px auto;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.6);
        }
        
        h1 {
            text-align: center;
            color: #4CAF50;
            margin-bottom: 30px;
            text-shadow: 2px 2px 4px #000;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        
        th {
            background-color: #4CAF50;
            color: white;
            padding: 12px;
            text-align: center;
        }
        
        td {
            padding: 10px;
            text-align: center;
            border-bottom: 1px solid #ddd;
            background-color: rgba(255, 255, 255, 0.1);
        }
        
        tr:hover td {
            background-color: rgba(255, 255, 255, 0.2);
        }
        
        .weekend {
            color: #ff9800;
            font-weight: bold;
        }
        
        .decor-img {
            display: block;
            margin: 30px auto;
            max-width: 80%;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.8);
            border: 2px solid #4CAF50;
        }
        
        footer {
            text-align: center;
            margin-top: 30px;
            color: #aaa;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Мое учебное расписание</h1>
        
        <table>
            <tr>
                <th>День недели</th>
                <th>Предмет</th>
                <th>Время</th>
            </tr>
            <tr>
                <td>Понедельник</td>
                <td>Математика</td>
                <td>9:00 - 10:30</td>
            </tr>
            <tr>
                <td>Вторник</td>
                <td>Физика</td>
                <td>10:45 - 12:15</td>
            </tr>
            <tr>
                <td>Среда</td>
                <td>История</td>
                <td>13:00 - 14:30</td>
            </tr>
            <tr>
                <td>Четверг</td>
                <td>Химия</td>
                <td>9:00 - 10:30</td>
            </tr>
            <tr>
                <td>Пятница</td>
                <td>Информатика</td>
                <td>10:45 - 12:15</td>
            </tr>
            <tr>
                <td>Суббота</td>
                <td>Литература</td>
                <td>13:00 - 14:30</td>
            </tr>
            <tr class="weekend">
                <td>Воскресенье</td>
                <td colspan="2">Выходной</td>
            </tr>
        </table>
        
        <img src="decor.jpg" alt="Учебные материалы" class="decor-img">
        
        <footer>
            Расписание на осенний семестр 2023 | Последнее обновление: сентябрь 2023
        </footer>
    </div>
</body>
</html>
