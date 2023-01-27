<!--Degradê.html-->

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <link rel="stylesheet" href="style.css"/>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Testando o degradê  </title>
</head>
<body>

    <div class="boxgradiente">
        <h1> Nathalia de Macedo Martins</h1> 
    </div>
    
</body>
</html>

<!--style.css-->

*{
    margin:0 auto;/*Ao passar o margin assim,
    estamos definindo que as margens superior e inferior são igual a zero,
    e os da esquerda, e as da esquerda e direta são automáticas*/
    padding:0;/*Definindo que não tem distancia entre um elemento e outro*/
    box-sizing: border-box;/*faz com que o navegador não calcule a dimensão
    de um elemento somando bordas e margens com altura e largura*/
    font-family: Arial;
}
.boxgradiente{
    width: 100%;
    padding:500px 0;
    display:flex;/* quando colocamos flex como propriedade de um elemento, esse elemento se 
    torna um flex container, e a partir dai podemos manipular com propriedades
    novas*/
    align-items: center;/*alinhando todos os itens no centro;*/
    justify-content: center;/* alinha os elementos ao longo do eixo principal;*/
    background-image: linear-gradient(to left,blue,orangered,yellow);/* determinamos que o background vai ser com gradiente 
    linear, comecando da esquerda, com as cores azuis,laranja avermelhado e amarelo*/
    background-size: 500% 100%;/* determinamos a porcentagem do x e y, o tamanho do background*/
    animation: degrade 5s infinite alternate;/*Chamando a animação degrade criada mais abaixo, definindo o tempo, 
    determinando que ela será infinita, e que vai alternar entre um lado e outro*/ 
}


/*keyframes são regras definidas, ao criar a estilização de um elemento,
para lidarmos com mudanças de poropriedades no css durante o processo de animação, 
chamamos com o @ e definimos um nome para nossa animação, e então passamos as condições para quando ela vai acontecer;*/
@keyframes degrade {
    0%{
        background-position-x: 0%;

    }
    100%{
        background-position-x:100%
    }

}
