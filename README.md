<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Danilo Peixoto - Front-end Developer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 800px;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin: auto;
        }
        .profile {
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
            text-align: left;
        }
        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            border: 3px solid #0077B5;
        }
        .profile h2 {
            flex: 1;
            font-size: 24px;
        }
        .icons img {
            margin: 5px;
        }
        .social-buttons img {
            margin: 10px;
        }
        .snake-animation {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile">
            <h2>Hey there! My name is Danilo Peixoto and I'm a Front-end developer, from Goiás, Brazil</h2>
            <img src="https://media.licdn.com/dms/image/v2/D4D03AQHy7GEZaEKRtA/profile-displayphoto-shrink_800_800/B4DZVhgYqBGcAg-/0/1741097635600?e=1749081600&v=beta&t=TCEs-Si3XRw8vHDU65wUfMC_x8AuxvmAsUIl0tlip7Q" alt="Profile Photo">
        </div>

        <div class="icons">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="JavaScript">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="HTML5">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="CSS3">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="Python">
        </div>

        <div class="social-buttons">
            <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="Instagram">
            <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="Discord">
            <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="Gmail">
            <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="LinkedIn">
        </div>

        <div class="snake-animation">
            <img src="https://raw.githubusercontent.com/maurodesouza/maurodesouza/output/snake.svg" alt="Snake animation">
        </div>
    </div>
</body>
