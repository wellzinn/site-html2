index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Allura&family=Katibeh&family=Niramit:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,200;1,300;1,400;1,500;1,600;1,700&family=Orienta&family=Passion+One:wght@400;700;900&display=swap" rel="stylesheet">
</head>
<body>
    <header class="cabecalho">
        <img class="cabecalho-imagem" src="logo da loja.png" alt="logo da Car Power">
        <ul class="cabecalho-lista">
            <li class="cabecalho-lista-item">Car</li>
            <li class="cabecalho-lista-item">Power</li>
        </ul>
    </header>
    <section class="escola">
        <div class="escola-div-conteudo">
            <h2 class="escola-titulo">O que a Car Power pode lhe ofereçer?</h2>
            <section class="textos-sobre-a-loja">
            <p class="escola-texto-um">Em busca de preço bom, conforto e segurança para</p>
            <p class="escola-texto-dois">você e sua família? A Car Power tem o carro perfeito</p>
            <p class="escola-texto-três">para você! Venha tomar um café com a gente e</p>
            <p class="escola-texto-quatro">conhecer nossos modelos. Carros novos e seminovos</p>
            <p class="escola-tesxto-cinco">com bom preço, você só encontra na Car Power!</p>
            </div>
            <img class="escola-imagem" src="foto loja.png" alt="foto representativa da loja">
    </section>
    <section class="estudante">
        <h2 class="estudante-titulo">Confira alguns de nossos produtos!</h2>
        <div class="estudantes-todos">
            <span></span>
        <div class="estudante-div">
            <img class="estudante-imagem" src="carro um.png" alt="carro 1">
        </div>
        <div class="estudante-div">
            <img class="estudante-imagem" src="carro dois.png" alt="carro 2">
        </div>
        <div class="estudante-div">
            <img class="estudante-imagem" src="carro três.png" alt="carro 3">
        </div> 
        <span></span>
        <span></span>
        <div class="estudante-div">
            <img class="estudante-imagem" src="carro quatro.png" alt="carro 4">
        </div> 
        <div class="estudante-div">
            <img class="estudante-imagem" src="carro cinco.png" alt="carro 5">
        </div> 
        <div class="estudante-div">
            <img class="estudante-imagem" src="carro seis.png" alt="carro 6">
        </div> 

     </div>
    </section>
    <footer class="rodape">
        <div class="elementos-do-rodape">
            <img class="imagem-rodape" src="telefone.png" alt="logo telefone">
        <h2 class="textinho">Entre em contato conosco:</h2>
        <h2 class="textinho-dois">(46) 99977-9874</h2>
        <img class="imagem-rodape-dois" src="watts.png" alt="logo watts">
    </div>
    </footer>
</body>
</html>

style.css

*{
    margin: 0;
    padding: 0;
}

.cabecalho {
    background-color: #1C3058;
    color: black;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 30px 0;
    font-family: 'Allura', cursive;
}

.cabecalho-imagem{
    width: 26%;
}

.cabecalho-lista-item{
    display: inline-block;
    margin: 0 26px;
    .mea-culpa-regular {
        font-family: "Allura", cursive;
        font-weight: 400;
        font-style: normal;
      }
    padding: 24px 0;
    font-size: 140px;
}

.escola-imagem{
    width: 30%;
}

.escola{
    background-image: linear-gradient(#0E42AC,#4074DB);
    color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 24px 0;
    font-size: 26px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
}

.escola-div-conteudo{
    width: 60%;
}
.escola-titulo{
    padding: 24px 0;
    font-size: 40px;
    font-family: 'Orienta', sans-serif;
}

.textos-sobre-a-loja{
    font-family: 'Katibeh', serif;
    padding: 24px 0;
    font-size: 30px;
}
.cabecalho-lista-item{
    font-family: 'Allura', cursive;
}

.estudante-titulo{
    font-family: 'Passion One', sans-serif;
    padding: 20px 0;
    font-size: 42px;
    justify-content: center;
    align-items: center;
    display: flex;
}

.estudante-imagem{
    width: 125px;
}

.estudante-div{
   text-align: center;
}

.estudantes-todos{
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
}
.estudante{
    background-image: linear-gradient(#4074DB,#0E42AC);
}

.rodape{
    background-color: #1C3058;
}

.rodape-imagem{
    padding: 6px;
}

.elementos-do-rodape{
    text-align: center;
    justify-content: center;
    display: flex;
    align-items: center;
}
