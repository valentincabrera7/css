# css
@import url('https://fonts.googleapis.com/css2?family=Agbalumo&family=Creepster&family=Black+Ops+One&family=Mooli&family=Oswald:wght@500&family=Roboto:ital,wght@0,300;0,400;0,700;0,900;1,300&family=Tilt+Neon&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Agbalumo&family=Creepster&family=Lacquer&family=Mooli&family=Oswald:wght@500&family=Roboto:ital,wght@0,300;0,400;0,700;0,900;1,300&family=Tilt+Neon&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

h1 {
    font-family: lacquer, sans-serif; 
    font-size: 70px;
    font-weight: bold;
    color: #9e0303;
    margin-top: 30px;  
    cursor: pointer;
}

h2 {
    font-family: 'Black Ops One', sans-serif; 
}

header {
    background-image: url("../img/fondo\ 7\ violeta.png");
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    box-sizing: border-box;
    height: 27vh;
    margin-bottom: 0; 
}

.nav {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 0;
    background: linear-gradient(to right, #000, #313131);
    height: 8vh;
}

.nav-list {
    list-style-type: none;
    display: flex;
    gap: 1rem;
}

.nav-list {
    list-style-type: none;
    display: flex;
    gap: 1rem;
    padding: 12px;
}

.nav-list li a {
    text-decoration: none;
    font-family: 'Black Ops One', sans-serif; 
    color: #fff; 
    transition: transform 0.4s, color 0.4s, font-size 0.4s; 
}

.nav-list li a:hover {
    scale: (1.1);
    font-size: 16.3px;
    color: #9e0303; 
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 50px;
}

article {
    text-align: center;
    margin: 50px;
    position: relative;;
}

.h2-tittle {
    font-size: 40px;
    margin-bottom: 10px;
    position: absolute;
    left: 50%;
    top: 50%;
    z-index: 1;
    transform: translate(-50%, -50%);
}

.h2-tittle a {
    color: #9e0303;
    text-decoration: none;
    display: inline-block;
    transition: transform 0.4s;
}

.h2-tittle a:hover {
    transform: scale(1.1);
}

.img2 {
    height: 250px;
}

footer {
    margin-top: 80px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #000;
    height: 45vh;
}

.logo-wp {
    position: sticky;
    top: 600px;
    left: 1293px;
}

.logo-wp img {
    height: 50px;
    width: 50px;
}

.rashguard h1 {
    font-family:'Black Ops One', sans-serif;
}


.rashguard-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px; 
    justify-content: center;
    align-items: center;
}


.rashguard-container article {
    margin-bottom: 5px;
}


.rashguard-container img {
    height: 270px;
    transition: transform border 0.4s, padding 0.4s;
    cursor: pointer;
}
    

.rashguard-container img:hover {
    transform: scale(1.1);
    border: 1px solid #000;
    padding: 10px;
}

.rashguard-container p {
    font-size: 18px;
    margin: 20px 20px 10px;
    font-family: 'Black Ops One', sans-serif;
}

.rashguard-container select {
    margin-top: 8px;
    padding: 4px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    border: 1px solid;
    border-radius: 3px;
}

.rashguard-container input {
    margin: 10px;
    padding: 5px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-color: #9e0303;
    color: #fff;
    border: 1px solid #9e0303;
    border-radius: 3px;
    cursor: pointer;
}

.short-container p {
    font-size: 18px;
    margin: 20px 20px 10px;
    font-family: 'Black Ops One', sans-serif;
}

.short-container select {
    margin-top: 8px;
    padding: 4px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    border: 1px solid;
    border-radius: 3px;
}

.short-container input {
    margin: 10px;
    padding: 5px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-color: #9e0303;
    color: #fff;
    border: 1px solid #9e0303;
    border-radius: 3px;
    cursor: pointer;
}

h3, p { 
    font-family:'Black Ops One', sans-serif;
    padding: 7px;
    color: #000;
}

#h3 {
    color: #9e0303;
}

.footer-contacto {
    display: flex;
    flex-direction: column;
}

.footer-contacto a {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 15px;
    padding: 10px;
    color: #fff;
}

.footer-contacto a.instagram-link {
    color: #ffffff; 
}

.footer-contacto a.instagram-link i {
    color: #ffffff; 
}
