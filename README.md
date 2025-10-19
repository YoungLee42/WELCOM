Chúc Mừng Ngày Phụ Nữ Việt Nam🌹💖  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>HAPPY WOMEN'S DAY🌹💖</title>
<link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">
<style>  
  body {  
    margin: 0;  
    padding: 0;  
    overflow: hidden;  
    background: url("class.jpg") no-repeat center center fixed;  
    background-size: cover;  
    font-family: 'Poppins', sans-serif;  
    color: #e91e63;  
    text-align: center;  
  }  

  h1 {
    font-family: 'Dancing Script', cursive;
    font-weight: 700;
    font-size: 2.5em;
    color: #e91e63;
    text-shadow: 
      0 0 10px #fff, 
      0 0 20px #ff80bf, 
      2px 2px 8px rgba(0, 0, 0, 0.3);
    animation: fadeZoom 3s ease-in-out;
  }  

  h2 {  
    font-size: 1.1em;  
    font-weight: normal;  
    color: #d81b60;  
    text-shadow:  
      0 0 10px #ffffff,  
      0 0 20px #ffb6c1,  
      2px 2px 6px rgba(0, 0, 0, 0.2);  
    animation: fadeIn 4s ease-in-out;  
  }  

  footer {  
    position: fixed;  
    bottom: 15px;  
    width: 100%;  
    font-size: 1em;  
    color: #c2185b;  
    text-shadow:  
      0 0 8px #ffffff,  
      0 0 15px #ff80ab;  
    animation: fadeIn 5s ease-in-out;  
  }  

  @keyframes fadeZoom {  
    from {opacity: 0; transform: scale(0.8);}  
    to {opacity: 1; transform: scale(1);}  
  }  

  @keyframes fadeIn {  
    from {opacity: 0;}  
    to {opacity: 1;}  
  }  

  .heart {  
    position: fixed;  
    bottom: 0;  
    width: 20px;  
    height: 20px;  
    background: #ff99cc;  
    transform: rotate(45deg);  
    animation: floatUp 6s ease-in infinite;  
  }  

  .heart::before, .heart::after {  
    content: "";  
    position: absolute;  
    width: 20px;  
    height: 20px;  
    background: inherit;  
    border-radius: 50%;  
  }  

  .heart::before { top: -10px; left: 0; }  
  .heart::after { left: 10px; top: 0; }  

  @keyframes floatUp {  
    0% {transform: translateY(0) rotate(45deg); opacity: 1;}  
    100% {transform: translateY(-800px) rotate(45deg); opacity: 0;}  
  }  

  #music-btn {  
    position: fixed;  
    bottom: 20px;  
    right: 20px;  
    background-color: #ff69b4;  
    color: white;  
    border: none;  
    border-radius: 50%;  
    width: 60px;  
    height: 60px;  
    font-size: 26px;  
    box-shadow: 0 0 15px rgba(255, 105, 180, 0.6);  
    cursor: pointer;  
    transition: transform 0.2s, background-color 0.3s;  
    z-index: 9999;  
  }  

  #music-btn:hover {  
    transform: scale(1.1);  
    background-color: #ff85c1;  
  }  
</style>  
</head>  
<body>  
  <h1>💐 Happy Women’s Day From 11A2 With Love! 💖</h1>  
  <h2>Nhân ngày 20/10, tập thể 11A2 xin gửi lời chúc tốt đẹp nhất đến những cô gái tuyệt vời của lớp!  
  Chúc các bạn luôn tự tin, thành công, và tỏa sáng trên con đường mình chọn.!🌟💖</h2>  
  <footer>FROM 11A2 WITH LOVE 💗</footer>  

  <audio id="bg-music" loop>  
    <source src="Beautiful_in_White.mp3" type="audio/mpeg">  
  </audio>  

  <button id="music-btn" onclick="toggleMusic()">🎵</button>  

  <script>  
    const music = document.getElementById("bg-music");  
    const btn = document.getElementById("music-btn");  
    let isPlaying = false;  

    function toggleMusic() {  
      if (isPlaying) {  
        music.pause();  
        btn.textContent = "🎵";  
      } else {  
        music.play();  
        btn.textContent = "⏸️";  
      }  
      isPlaying = !isPlaying;  
    }  

    function createHeart() {  
      const heart = document.createElement("div");  
      heart.className = "heart";  
      heart.style.left = Math.random() * 100 + "vw";  
      const colors = ["#ff99cc", "#ffb6c1", "#ff80bf", "#ff69b4"];  
      heart.style.background = colors[Math.floor(Math.random() * colors.length)];  
      heart.style.animationDuration = (3 + Math.random() * 4) + "s";  
      document.body.appendChild(heart);  
      setTimeout(() => heart.remove(), 6000);  
    }  
    setInterval(createHeart, 300);  
  </script>  
</body>  
</html>
