@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap');
        
* {
 margin: 0;
 padding: 0;
 box-sizing: border-box;
}

header {
 background-color: #040714;
 height: 10vh;
 display: flex;
 align-items: center;
 padding: 0 20px;
}

.top-header {
 display: flex;
 justify-content: center;
 align-items: center;
 position: sticky;
 top: 0;
 width: 100%;
}

.logo {
 font-family: 'Poppins', sans-serif;
 font-size: 50px;
 color: white;
 text-transform: uppercase;
 font-weight: bold;
 position: relative;
}

.logo span {
 color: #1f80e0;
}

.arc {
 position: absolute;
 top: -40px;
 left: -10px;
 width: 180px;
 height: 80px;
 border: 4px solid #1f80e0;
 border-color: transparent transparent #1f80e0 transparent;
 border-radius: 50%;
 transform: rotate(-10deg);
}

.plus {
 position: absolute;
 right: -30px;
 top: 5px;
 font-size: 40px;
 color: #1f80e0;
}

.bottom-header {
 display: flex;
 justify-content: left;
 align-items: center;
 background-color: #004D99;
 padding: 10px 20px;
}

ul {
 list-style: none;
 display: flex;
 gap: 15px;
}

li {
 display: inline-block;
 padding: 8px 12px;
 color: white;
 font-size: 14px;
 cursor: pointer;
 border-radius: 5px;
 transition: 0.3s ease-in-out;
}

li:hover {
 color: #ffa500;
 background: rgba(255, 255, 255, 0.2);
}

.anime {
 width: 100%;
 height: 700px;
 margin-top: 20px;
 background: url('./images/animation.gif') no-repeat center center;
 background-size: cover;
 position: relative;
}

.gif-text {
 position: absolute;
 top: 50%;
 left: 50%;
 transform: translate(-50%, -50%);
 color: white;
 font-size: 20px;
 font-weight: bold;
 background: rgba(0, 0, 0, 0.5);
 padding: 10px;
 border-radius: 5px;
 text-align: center;
}

.main-hero-section {
 background-color: #7d7dd3;
 display: flex;
 justify-content: center;
 padding: 20px 0;
}

.hero-sec {
 display: flex;
 justify-content: center;
 align-items: center;
 width: 100%;
}

.hero-section {
 width: 80%;
 max-width: 400px;
 border-radius: 15px;
 display: flex;
 justify-content: center;
 align-items: center;
}

img {
 width: 100%;
 max-width: 400px;
 height: auto;
 text-align: center;
}
