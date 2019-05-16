# Efeito-Parallax-Scrolling
Efeito Parallax simples ao descer a tela

Efeito parallax usando um plugin jQuery Parallax.js, com CSS e HTML. 

![](efeito-scrolling-parallax.gif)


1. É necessário ter feito o download do parallax.js, pois é necessário ter o parallax.min.js para o efeito parallax ser feito.
esse arquivo deve está na raiz do projeto. 

2. Instalação e linkagem HTML e CSS. 
  2.1 HTML: Dentro do seu arquivo index.html
  
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
    <script src="/path/to/parallax.js"></script>
  
  2.2 CSS: Dentro do seu arquivo style.css
    .parallax-window {
      min-height: 400px;
      background: transparent;
    }
  
 3. Div's especificas para que o parallax funcione
 
   <div class="parallax-window" data-parallax="scroll" data-image-src="/path/to/image.jpg"></div>

 seu arquivo deve conter essas Divs, você pode colocar tags dentro dessas divs.
 
 
 OBS: Pode ser que ainda assim o efeito parallax não funcione, caso não funcione olhar a documentação do plugin aqui (http://pixelcog.github.io/parallax.js/)
