<!DOCTYPE html>
<html lang="pt-BR">
    <head>
        
        <meta charset="UTF-8" />
        <meta name="description" content="Texto descritivo da página web" />
        <meta name="author" content="Gama Academy" />
        <meta name="viewport" content="width=devide-width, initial-scale=1.0" />
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;400;700&display=swap" rel="stylesheet">
        <link rel="stylesheet" href="styles.css">
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.3/css/all.css" integrity="sha384-SZXxX4whJ79/gErwcOYf+zWLeJdY/qpuqC4cAa9rOGUstPomtqpuNWT9wdPEn2fk" crossorigin="anonymous">
        <title>Wine Shop</title>

    </head>
    
    <body>
        <header>
            <div>
                <img src="https://chapiuski.com.br/wp-content/uploads/2017/04/Tipos-de-uvas-para-vinhos.jpg" alt="logo"> 
            </div>

            <ul>
                <li>Institucional</li>
                <li>
                    <a target="_blank" href="http://wa.me/16999999999" >Fale conosco</a>
                    </li>
                <li>Faça parte do nosso time</li>
            </ul>
            </header>
           
            <main>
                <section class="container">
                    <div class="name">
            <h1>Wine Shop</h1>
            <h4>Os melhores preços estão aqui.</h4>
            </div>

            <div onclick="displayAbout()" id="grape">
                <i id="animation" class="fas fa-wine-glass-alt"></i>
            </div>

            <div style="display: none;" id="about">
                <p>Wine Shop é uma loja exclusivamente on-line</p>
            </div>
            <div class="form">
                <form action="">
                    <input type="text" placeholder="seu melhor e-mail :)">
                    <button>enviar!</button>
                </form>
            </div>
           
            <script>
                function displayAbout() {
                    var grape = document.getElementById("animation");
                    grape.classList.toggle("rotate");
                    var display = document.getElementById("about");
                    display.classList.toggle("rotate");
                }
            </script>
             </section>
            </main>


            <div class="flex">
            <div>
                <img src="https://www.wine.com.br/cdn-cgi/image/f=auto,h=515,q=99/assets-images/produtos/26401-01.png" alt="Vik A 2018">
                <p>Vik A 2018, Chile Tinto Seco 750ml</p>
            </div>

            <div>
                <img src="https://www.wine.com.br/cdn-cgi/image/f=auto,h=515,q=99/assets-images/produtos/26161-01.png" alt="Mosen Pierre Red Blend">
                <p>Mosen Pierre Red Blend, Espanha Tinto Seco 750 ml</p>
            </div>
            <div>
                <img src="https://www.wine.com.br/cdn-cgi/image/f=auto,h=515,q=99/assets-images/produtos/20883-01.png" alt"Rocinha">
                <p>Rocinha, Portugal
                    Tinto
                    Meio Seco
                    750 ml</p>
            </div>
            <div>
                <img src="https://www.wine.com.br/cdn-cgi/image/f=auto,h=515,q=99/assets-images/produtos/24863-01.png" alt="Toro loco">
                <p>Toro Loco D.O.P. Utiel-Requena 
                    Tinto Superior 2019 375 ml</p>
            </div>
            <div>
                <img src="https://www.wine.com.br/cdn-cgi/image/f=auto,h=515,q=99/assets-images/produtos/25757-01.png" alt="Almaviva">
                <p>Almaviva 2018 1,5L, Chile
                    Tinto
                    Seco
                    1 L
                    </p>
            </div>
            <div>
                <img src="https://www.wine.com.br/cdn-cgi/image/f=auto,h=515,q=99/assets-images/produtos/20624-01.png" alt="Leyenda del Toqui 2013">
                <p>Leyenda del Toqui 2013, Chile
                    Tinto
                    Seco
                    750 ml
                    </p>
            </div>
            </div>
            
        
        
    </body>
</html>