<!DOCTYPE html>
<html lang="PT-BR">
<head>
    <link rel="stylesheet" href="style.css"></link><!--importando a pasta de estilização-->
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Além do código</title>
</head>
<body>
    <div class="content">

        <div class="slides"><!--Criando uma classe slides para estilizar depois-->
            <input   type="radio" name="slide" id="slide1" checked><!-- Vamos deixar a primeira imagem pre selecionada por padrão-->
            <input  type="radio" name="slide" id="slide2"><!--E determinar uma id diferente para cada imagem-->
            <input   type="radio" name="slide" id="slide3">
            <input type="radio" name="slide" id="slide4">
            <input   type="radio" name="slide" id="slide5">

            
            <div class="slide s1">
                <img src="./images/1.jpg" alt="Paisagem medieval com montanhas">
            </div>

            <div class="slide">
                <img src="./images/2.jpg" alt="paisagem com arvore roxa">
            </div>

            <div class="slide">
                <img src="./images/3.jpg" alt=" inicio de tela de um jogo">
            </div>

            <div class="slide">
                <img src="./images/4.jpg" alt="caminho elfico">
            </div>

            <div class="slide">
                <img src="./images/5.jpg" alt="raposa solitária">
            </div>
        </div>

        <div class="navigation"><!--Cada label vai levar a um id diferente, que está ligado a uma imagem diferente-->
            <label class="bar" for="slide1"></label>
            <label class="bar" for="slide2"></label>
            <label class="bar" for="slide3"></label>
            <label  class="bar" for="slide4"></label>
            <label class="bar" for="slide5"></label>
        </div>
    </div>
    
</body>
</html>

/* Fazendo a estilização de todo o body */
/* Determinando margem 0 para que a imagem fique colada com o canto,e tire os espaços entre elas (padding) */
/* Criando um gradiente com duas cores */

body{
    margin:0;
    padding: 0;
    height: 100vh;
    background: linear-gradient(72deg,#3DEBB0 1%, #8956F3 99%);
    width: 100vw;
}


.content{
    height: 520px;
    width: 935px;
    border-radius: 20px;
    overflow:hidden;
    position:absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
}

.navigation{
    position: absolute;
    bottom: 20px;
    left:50%;
    transform: translate(-50%);
    display: flex;
}

.bar{
    width:70px;
    height: 17px;
    border:2px solid #fff;
    margin:6px;
    border-radius: 5px;
    cursor:pointer;
    transition: .3s;

}

.bar:hover{
    background-color: #fff;
}

input{
    display: none;
}

.slides{
    display:flex;
    width:500%;
    height: 100%;
}

.slide{
    width: 20%;
    transition: .6s;
}

.slide img{
    width:100%;
    height: 100%;
}

#slide1:checked ~ .s1{
    margin-left: 0;

}

#slide2:checked ~.s1{
    margin-left: -20%;
}

#slide3:checked ~ .s1{
    margin-left: -40%;
}

#slide4:checked ~.s1{
    margin-left: -60%;
}

#slide5:checked ~.s1{
    margin-left: -80%;
}



link das imagens:
https://www.mediafire.com/view/2t29fgu8hynzzxc/1.jpg/file
https://www.mediafire.com/view/j55lsotkq02mgkm/2.jpg/file
https://www.mediafire.com/view/vkipuw56s653wvx/3.jpg/file
https://www.mediafire.com/view/it1f4kdo37y0frj/4.jpg/file
https://www.mediafire.com/view/ezz06cx0nz7gzgz/5.jpg/file

