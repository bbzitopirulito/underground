# underground
<!doctype html>
<html lang="pt-BR">
    <head>
        <title>UnderGround</title>
        <link href="https://fonts.googleapis.com/css?family=Black+Ops+One|Herr+Von+Muellerhoff|Merriweather|Oswald|Passion+One"                 rel="stylesheet">
        <style>
             #janela {
                position: absolute;
                top:940px;
                height: 600px;
                width: 1903px;
                background-color:#000;
                margin-top: -835px;
                margin-left: -8px;
                text-align: center; 
            }
            /*engloba tudo*/
            #corpo {
                background-color: #fff;
                height:2000px;
            }
             #title {
                font-family: 'Black Ops One', cursive;
                font-size: 35px;
            }
            nav ul li {
                display: inline;
                letter-spacing: 0.08em;
                position: relative;
            }
            nav ul li a:hover {
                background-color: black;
                color: white;
                z-index: 100;
            }
            nav ul li ul li a {
                margin-left: -44px;
                color: green;
            }
            nav ul li a {
                padding-top: 15px;
                padding-bottom: 15px;
                padding-left: 40px;
                width: 100px;
                margin-left: -4px;            
                text-decoration: none;
                color: #000;
                font-family: "Passion One", cursive;
                display: inline-block;
            }
            #nome {
                font-family: 'Herr Von Muellerhoff', cursive;
                font-size: 25px;
                margin-left: 175px;
                margin-top: -35px;
            }
            /*cabeçalho*/
            #menu {
                font-family: "Passion One", cursive;
            }
            #cabeça {
                margin-top: 25px;
                margin-left: 100px;
            }
            /*submenu*/
            nav ul li ul {
                display: none;
                position: absolute;
            }
            nav li:hover ul {
                display: block;
            }
            footer {
                text-align: center;
            }
            nav ul li ul li a {
                background-color: black;
            }
            nav ul li ul li a:first-child{
                color: green;
            }
            #co {
                padding-right: 35px;
            }
            nav {
                margin-left: 450px;
                margin-top: -90px;
                font-size: 16px;
                z-index: 5;
                letter-spacing: 0.1em;
            }
            nav ul li ul {
                z-index: 1000;
            }
            #procura {
                float: right;
                margin-top: -47px;
                margin-right: 350px;
            }
            #idprocura a {
                float: right;
                margin-top: -45px;
                margin-right: 282px;
                font-family: "Passion One", cursive;
                letter-spacing: 0.08em;
                text-decoration: none;
                color:black;
            }
            #idprocura:hover a {
                color: green;
            }
            #lancamento {
                margin-top: 800px;
                margin-left: 100px;
                font-family: "Oswald", cursive;
                font-size: 45px;
                letter-spacing: 0.4em;
            }
            #pesquisa {
                margin-top: 10px;
                margin-right: 0px;
            }
            #topo {
                position: fixed;
                z-index: 10000;
                width: 100%;
                height: 105px;
                background-color: rgba(255,255,255,0.9);
                top: 0px;
                left: 0px;
            }
            #lancamento1 {
                margin-left: 2px;
                background-color: black;
                color: white;
                font-family: 'Oswald', cursive;
                font-size: 400%;
            }
            #lancamento2 {
                margin-left: 480px;
                background-color: black;
                margin-top: -600px;
                color: white;
                font-family: 'Oswald', cursive;
                font-size: 400%;
            }
            #lancamento3 {
                margin-left: 958px;
                margin-top: -600px;
                background-color: black;
                color: white;
                font-family: 'Oswald', cursive;
                font-size: 400%;
            }
            #lancamento4 {
                margin-left: 1435px;
                margin-top: -600px;
                background-color: black;color: white;
                font-family: 'Oswald', cursive;
                font-size: 400%;
            }
            .lancamentos {
                width: 450px;
                height: 600px;
                margin-top: 100px;
            }
            #cinto {
                font-family: 'Merriweather', cursive;
                font-size: 150%;
                margin-left: 50px;
                letter-spacing: 0.25em;
                margin-top: 1000px;
            }
            .offwhite {
                margin-bottom:-20px;
            }
            .cinquenta {
                z-index: 1000000;
                font-size: 400%;
                margin-top: -600px;
                font-family: 'Oswald', cursive;
            }
         
        </style>
        <script></script>
        <script>
        
        </script>
    </head>
    <body>
        <div id="corpo">
            <div id="topo">
                <div id="cabeça">  
                    <h1 id='title'>UnderGround</h1>
                    <p id='nome'>A trapstar's store</p>
                </div>
                    <nav>
                        <ul>
                            <li class="menu"><a href="Produtos.html">Produtos</a>
                                <ul>
                                    <li class="a"><a href="#">Camisas</a></li>
                                    <li class="a"><a href="#">Calças</a></li>
                                    <li class="a"><a href="#">Bonés</a></li>
                                    <li class="a"><a href="#">Meias</a></li>
                                    <li class="a"><a href="#">Tênis</a></li>
                                    <li class="a"><a href="#">Cintos</a></li>
                                    <li class="a"><a href="#">Relógios</a></li>
                                    <li><a class="problem" href="#">Mochilas</a></li>
                                </ul>
                            </li>
                            <li class="menu"><a href="Notícias.html">&nbsp;Notícias</a></li>
                            <li class="menu"><a href="Eventos.html">&nbsp;Eventos</a></li>
                            <li class="menu"><a href="Contato.html">&nbsp;Contato</a></li>
                            <li><a id='co' href="RedesSociais.html">Redes Sociais</a></li>
                        </ul>    
                    </nav>
                <div id='pesquisa'>
                    <label id="idprocura"><a href="#">Procurar</a></label>
                    <input type="text" name="procura" id="procura" size="30" maxlength="100" required placeholder="Pesquise aqui...">
                </div>    
            </div>
                <div id='janela'><img height="600px" width="1200px"src='xxx.jpg'></div>
                <h1 id="lancamento">LANÇAMENTOS</h1>
                <div class="lancamentos" id='lancamento1'><img height="600px" width="450px;" src="off-white.jpg"></div>
                <div class="lancamentos" id='lancamento2'><img height='600px' width="450px" src='camisasup.jpg'></div>
                <div class="lancamentos" id='lancamento3'>-50%</div>
                <div class="lancamentos" id='lancamento4'>-50%</div>
                <p class='cinquenta'>-50%</p>
                <p class='cinquenta' id="cinq2">-50%</p>
                <div id='cinto'>
                    <p class='offwhite'>CINTO OFF-WHITE</p>
                    <p class='offwhite'><strike>DE $500</strike></p>
                    <p>POR $499,99</p>
                </div>    
            </div>
        <footer>Copyright</footer>
    </body>
</html>
