<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>ONYX ИНФОРМАЦИЯ</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    h1, h2 {
      color: #333;
    }
    ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    li {
      margin-bottom: 10px;
    }
    a {
      text-decoration: none;
      color: #337ab7;
    }
    a:hover {
      color: #23527c;
    }
   .prev,.next {
      font-size: 18px;
      font-weight: bold;
    }
   .alert {
      background-color: #f0f0f0;
      padding: 10px;
      border: 1px solid #ccc;
    }
  </style>
</head>
<body>
  <h1>Введение</h1>
  <p>Опух - Новый проект который является 00:00 III 3 25 project.gitbook.io + 43 : ONYX ИНФОРМАЦИЯ</p>
  <h2>Критерии</h2>
  <ul>
    <li>Критерий 1: Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
    <li>Критерий 2: Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</li>
    <li>Критерий 3: Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</li>
  </ul>
  <h2>ПРАВИЛА</h2>
  <ul>
    <li><a href="#">Правила Classic SCP: CS сервера</a></li>
    <li><a href="#">Правила Discord Сообщества</a></li>
  </ul>
  <h2>МОДЕРАЦИЯ</h2>
  <ul>
    <li><a href="#">Иерархия</a></li>
    <li><a href="#">Кодекс модерации</a></li>
  </ul>
  <p>Powered by GitBook</p>
  <a href="#" class="prev">&laquo;</a>
  <a href="#" class="next">(N) &raquo;</a>
  
  <!-- Alert message -->
  <div class="alert">
    <p>Внимание! Это новый проект, и мы работаем над его развитием.</p>
  </div>
  
  <!-- Footer section -->
  <footer>
    <p>&copy; 2023 ONYX ИНФОРМАЦИЯ. All rights reserved.</p>
  </footer>
  
  <!-- JavaScript code -->
  <script>
    // Add event listener to prev and next buttons
    document.addEventListener("DOMContentLoaded", function() {
      var prevButton = document.querySelector(".prev");
      var nextButton = document.querySelector(".next");
      
      prevButton.addEventListener("click", function() {
        alert("Previous page");
      });
      
      nextButton.addEventListener("click", function() {
        alert("Next page");
      });
    });
  </script>
</body>
</html>
