<html>
    <head>
        <style>
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

a {
    text-decoration: none;
}

.box {
font-size: 20px;
color: white;
height: 250px;
width: 350px;
border-radius: 10px;
background: #191919;
flex-direction: column;
display: flex;
align-items: center;
justify-content: center;
}

.button-container {
display: flex;
justify-content: space-around;
height: 50px;
width: 150px;
}

button{
    height: 30px;
    width: 50px;
    background: white;
    border-radius: 5px;
    color:blueviolet;
    font-weight: 600;
}
        </style>
    </head>
    <body>
        <div class="box">
            <p>Quer namorar comigo?</p>
            <div class="buttons-container">
                <button>
<a href="https://www.tiktok.com/@bs.maju/video/7324517451356556550?is_from_webapp=1&sender_device=pc&web_id=7365580537950832134">Sim</a>
</button>
<button id="no">Não</button>
</div>
</div>
    </body>
    <script>
        let button = document.getElementById('no');
        let height = window.innerHeight - 50;

         button.addEventListener('mouseover', function() {
            button.style.position = "absolute";
            button.style.top = Math.random() *height + "px";
            button.style.left = Math.random() *width + "px";
        

         })
    </script>
</html>
