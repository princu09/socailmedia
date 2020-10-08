## Social Media Button CSS Layout

##### 📫 Connect with me here:<br />
 <br />
 <p>
  <a target="_blank" href="https://www.instagram.com/princu.09">
    <img src="https://img.shields.io/badge/princu.09-386938188?style=flat&logo=instagram&color=black">
  </a> &nbsp; 
  <a target="_blank" href="https://twitter.com/princu09">
    <img src="https://img.shields.io/badge/@princu09-30302f?style=flat&logo=twitter&color=black">
  </a>&nbsp; 
  <a target="_blank" href="https://github.com/princu09">
    <img src="https://img.shields.io/badge/@princu09-30302f?style=flat&logo=github&color=black">
  </a>&nbsp;
    <a target="_blank" href="https://www.t.me/proghub09">
    <img src="https://img.shields.io/badge/ProgHub09-386938188?style=flat&logo=telegram&color=black">
  </a>
</p>

|  ![Video Here](Social_Media.gif)  |   ![Video Here](Social_Media_Mobile.gif) |
| ------------- | ------------- |

HTML File :

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Social Media</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css" />
    <link rel="shortcut icon" href="https://princu09.github.io/nfwebbuilder/img/logo.png" type="image/x-icon">
</head>

<body>
    <h1>Follow Us on Social Media</h1>

    <div class="social-media">
        <a href=""><i class="fab fa-facebook"></i></a>
        <a href=""><i class="fab fa-twitter"></i></a>
        <a href=""><i class="fab fa-whatsapp"></i></a>
        <a href=""><i class="fab fa-instagram"></i></a>
        <a href=""><i class="fab fa-youtube"></i></a>
    </div>
</body>

</html>
```
CSS File :

```
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
* {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
}

body {
    background: #e3edf7;
}

h1 {
    font-weight: 700;
    font-size: 30px;
    letter-spacing: 4px;
    padding: 200px 0 100px;
    color: darkorange;
    text-align: center;
}

.social-media {
    display: flex;
    justify-content: center;
}

a {
    display: flex;
    background: #e3edf7;
    min-height: 80px;
    min-width: 80px;
    margin: 0 15px;
    border-radius: 8px;
    align-items: center;
    justify-content: center;
    text-decoration: none;
    box-shadow: 6px 6px 10px -1px rgba(0, 0, 0, 0.15), -6px -6px 10px -1px rgba(255, 255, 255, 0.7);
    border: 1px solid rgba(0, 0, 0, 0);
    transition: transform 0.5s;
}

a i {
    font-size: 45px;
    color: #777;
    transition: transform 0.5s;
}

a:hover {
    box-shadow: inset 4px 4px 6px -1px rgba(0, 0, 0, 0.15), inset -4px -4px 6px -1px rgba(255, 255, 255, 0.7), -0.5px -0.5px 0px rgba(255, 255, 255, 1), 0.5px 0.5px 0px rgba(0, 0, 0, 0.15), 0px 12px 10px -10px rgba(0, 0, 0, 0.05);
    border: 1px solid rgba(0, 0, 0, 0.01);
    transform: translateY(2px);
}

a:hover i {
    transform: scale(0.90);
}

a:hover .fa-facebook {
    color: #3b5998;
}

a:hover .fa-whatsapp {
    color: #4fce5d;
}

a:hover .fa-twitter {
    color: #00acee;
}

a:hover .fa-instagram {
    color: #f14843;
}

a:hover .fa-youtube {
    color: #f00;
}

@media (max-width: 550px) {
    h1 {
        font-weight: 800;
        font-size: 25px;
        letter-spacing: 2px;
        padding: 50px 50px;
        color: #555;
        text-align: center;
    }
    .social-media {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    a {
        margin: 30px 0;
        background: #e3edf7;
        max-height: 80px;
        max-width: 80px;
    }
    a .fa-facebook {
        color: #3b5998;
    }
    a .fa-whatsapp {
        color: #4fce5d;
    }
    a .fa-twitter {
        color: #00acee;
    }
    a .fa-instagram {
        color: #f14843;
    }
    a .fa-youtube {
        color: #f00;
    }
    body {
        max-width: 100%;
        max-height: 100%;
    }
}
```
