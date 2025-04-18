<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Đi ăn với anh nha?</title>
  <style>
    body {
      background-color: pink;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      text-align: center;
      padding-top: 100px;
      overflow: hidden;
      position: relative;
    }

    h1 {
      font-size: 2.5em;
      color: white;
      margin-bottom: 50px;
    }

    .btn {
      padding: 15px 30px;
      font-size: 1.2em;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: 0.3s;
    }

    #yesBtn {
      background-color: #fff;
      color: #ff69b4;
      margin-right: 20px;
    }

    #noBtn {
      background-color: #ff69b4;
      color: #fff;
      position: absolute;
    }

    #message {
      margin-top: 50px;
      font-size: 1.5em;
      color: white;
      display: none;
      animation: fadeIn 1s ease-in-out forwards;
    }

    #curiousBtn {
      position: fixed;
      bottom: 20px;
      left: 20px;
      background-color: white;
      color: #ff1493;
    }

    #catSection {
      display: none;
      margin-top: 40px;
      animation: fadeIn 1s ease-in-out forwards;
    }

    #catSection img {
      width: 250px;
      border-radius: 20px;
      margin-top: 20px;
    }

    #catSection p {
      font-size: 1.3em;
      color: #fff;
      margin-top: 10px;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <h1>Đi ăn với anh ngày 14 tháng 5 nhaaaa? 🍜💖</h1>
  <button class="btn" id="yesBtn">Có 🥰</button>
  <button class="btn" id="noBtn">Không 😒</button>

  <div id="message">Hẹn em ở Charleston 1000 Lancaster St, Baltimore 7PM 🍽️</div>

  <button class="btn" id="curiousBtn">Em có curious về món quà sinh nhật năm nay không?</button>

  <div id="catSection">
    <img src="chup.jpg" alt="Con Chụp giận dữ">
    <p>Con Chụp tức giận vì sự curious của em 😾</p>
  </div>

  <script>
    const noBtn = document.getElementById('noBtn');
    const message = document.getElementById('message');
    const catSection = document.getElementById('catSection');

    noBtn.addEventListener('mouseover', () => {
      const x = Math.random() * (window.innerWidth - noBtn.offsetWidth);
      const y = Math.random() * (window.innerHeight - noBtn.offsetHeight);
      noBtn.style.left = `${x}px`;
      noBtn.style.top = `${y}px`;
    });

    document.getElementById('yesBtn').addEventListener('click', () => {
      message.style.display = 'block';
    });

    document.getElementById('curiousBtn').addEventListener('click', () => {
      catSection.style.display = 'block';
    });
  </script>

</body>
</html>
