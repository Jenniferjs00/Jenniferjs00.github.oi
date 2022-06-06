<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="./assets/css/style.css">
    <link rel="shortcut icon" href="./assets/images/favicon.png" />
    <script src="https://kit.fontawesome.com/ef2c46f17f.js" crossorigin="anonymous"></script>
    <title>Jennifer Brito</title>

    <script type="text/javascript">
        window.onload = function() {
            document.querySelector(".menu_mobile").addEventListener("click", function(){
                if(document.querySelector(".menu nav ul").style.display == "flex") {
                    document.querySelector(".menu nav ul").style.display = "none";
                } else {
                    document.querySelector(".menu nav ul").style.display = "flex";
                }
            });
        };
    </script>
</head>
<body>
    <header id="header">
        <div class="container">
            <div class="logo"><img src="./assets/images/favicon (1).png" alt=""></div>
            <div class="menu">
                <nav>
                    <div class="menu_mobile">
                        <div class="mm_line"></div>
                        <div class="mm_line"></div>
                        <div class="mm_line"></div>
                    </div>
                    <ul>
                        <li><a href="#header">Home</a></li>
                        <li><a href="#sobre-mim">Sobre</a></li>
                        <li><a href="#conhecimentos">Conhecimentos</a></li>
                        <li><a href="#projetos">Projetos</a></li>
                        <li><a href="https://wa.me/55919980618904" class="menu-buttom">Contato</a></li>
                        <li><a href="https://github.com/Jenniferjs00/" target="_blank"><i class="fa fa-github"aria-hidden="true"></i></a></li>
                        <li><a href="https://www.linkedin.com/in/jennifer-brito-18224409/" target="_blank"><i class="fa fa-linkedin-square"aria-hidden="true"></i></a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <main>
        <section id="banner">
            <div class="container">
                <div class="banner">
                    <div class="banner-esquerda">
                        <p>Olá Mundo! <span>&#128075</span> Meu nome é Jennifer</p>
                        <h1>Jennifer Brito</h1>
                        <h2>Desenvolvedora Web</h2>
                        <p>Programadora Front-end com foco em sites E-commerce e Institucional.</p>
                        <a href="#sobre-mim" class="buttom">Saiba mais</a>
                    </div>
                    <div class="banner-direita">
                        <img src="./assets/images/banner_semfundo.png" alt="">
                    </div>
                </div>
            </div>
            <div class="icone-rolagem">
               <img src="./assets/images/mouse.png" alt="">
            </div>
        </section>

        <section id="sobre-mim">
            <div class="container">
                <div class="sobre-mim">
                    <div class="sobre-mim-esquerda">
                        <img src="assets/images/ilustracao-avatar.png">
                    </div>
                    <div class="sobre-mim-direita">
                        <div class="titulo">
                            <p>Quem sou eu</p>
                            <h1>Sobre mim</h1>
                        </div>
                        <p>Apaixonada por tecnologia, formada em Análise e Desenvolvimento de Sistemas fui apresentada ao desenvolvimento web e desde então, sigo estudando e me aperfeiçoando desenvolvendo projetos, a fim de dominar o Desenvolvimento Web. Sempre buscando criar soluções combinando design e interatividade para uma melhor experiência do usuário. </br>
                        </br>Sou fascinada por resolução de problemas, principalmente utilizando a tecnologia.</p>
                        <a href="https://drive.google.com/file/d/1pJHSsISj_vuP73bJKY7rhNgb-KVtPmkA/view?usp=sharing" target="_blank" class="buttom">Download CV</a></li>
                    </div>
                </div>
            </div>
        </section>

        <section id="conhecimentos">
            <div class="container">
                <div class="conhecimentos">
                    <div class="titulo">
                        <p>O que estou estudando</p>
                        <h1>Conhecimentos</h1>
                    </div>
                    <div class="conhecimentos-cards">
                        <div class="card">
                            <div class="card-area">
                                <img src="assets/images/html_icon.png">
                            <h2>HTML</h2>
                            <p>HTMl é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores.</p>
                            </div>            
                        </div>
                        <div class="card">
                            <div class="card-area">
                                <img src="assets/images/css_icon.png">
                            <h2>CSS</h2>
                            <p>O CSS é uma linguagem de folhas de estilos que é utilizada para definir como os documentos escritos na linguagem de marcação HTML.</p>
                            </div>   
                        </div>
                        <div class="card">
                            <div class="card-area">
                                <img src="assets/images/js_icon.png">
                            <h2>Javascript</h2>
                            <p>JavaScript é uma linguagem de programação interpretada estruturada, de script em alto nível com tipagem dinâmica fraca e multiparadigma.</p>
                            </div>   
                        </div>
                        <div class="card">
                            <div class="card-area">
                                <img src="assets/images/php_icon.png">
                            <h2>Php</h2>
                            <p>PHP é uma linguagem interpretada livre, usada originalmente apenas para o desenvolvimento de aplicações presentes e atuantes no lado do servidor, capazes de gerar conteúdo dinâmico na World Wide Web</p>
                            </div>   
                        </div>

                        <div class="card desativado"> 
                        </div>

                        <div class="card desativado">
                            
                            </div>   
                        </div>
                    </div>
                </div>
            </div>
        </section>  


        <section id="projetos">
            <div class="container">
                <div class="projetos">
                    <div class="titulo">
                        <p>Meus projetos</p>
                        <h1>Projetos</h1>
                    </div>
                    <div class="projetos-cards">
                        <div class="projetos-card">
                            <img src="./assets/images/cicle.png" alt="">
                            <div class="projeto-card-desc">
                                <div class="projeto-card-desc-esquerda">
                                    <h2>Cicle</h2>
                                    <div class="projeto-card-desc-categorias">
                                        <div class="projeto-card-desc-categoria flutter">Flutter</div>
                                    </div>
                                </div>
                                <div class="projeto-card-desc-direita">
                                    <p> Cicle é uma startup que permite vender materiais reciclados com facilidade, descartando aquilo que não se é usado por um preço justo.</p>
                                    <div class="projeto-card-desc-direita-icons">
                                        <a href="https://github.com/DavidAugustoo/Cicle" target="_blank"><i class="fab fa-github"></i></a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                        <div class="projetos-card">
                            <img src="./assets/images/petfood.png" alt="">
                            <div class="projeto-card-desc">
                                <div class="projeto-card-desc-esquerda">
                                    <h2>PetFood</h2>
                                    <div class="projeto-card-desc-categorias">
                                        <div class="projeto-card-desc-categoria html">HTML</div>
                                        <div class="projeto-card-desc-categoria css">CSS</div>
                                        <div class="projeto-card-desc-categoria javascript">JavaScript</div>
                                    </div>  
                                </div>
                                <div class="projeto-card-desc-direita">
                                    <p> PetFood é um e-commerce totalmente voltado para o ramo de animais de estimação                                    </p>
                                    <div class="projeto-card-desc-direita-icons">
                                        <a href="https://github.com/DavidAugustoo/PetFood" target="_blank"><i class="fab fa-github"></i></a>
                                        <a href="https://petfoood.netlify.app/" target="_blank"><i class="fas fa-link"></i></a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                        <div class="projetos-card">
                            <img src="./assets/images/freeplay.png" alt="">
                            <div class="projeto-card-desc">
                                <div class="projeto-card-desc-esquerda">
                                    <h2>Freeplay</h2>
                                    <div class="projeto-card-desc-categorias">
                                        <div class="projeto-card-desc-categoria html">HTML</div>
                                        <div class="projeto-card-desc-categoria css">CSS</div>
                                        <div class="projeto-card-desc-categoria javascript">JavaScript</div>
                                    </div>  
                                </div>
                                <div class="projeto-card-desc-direita">
                                    <p> FreePlay é um ótimo site para encontrar jogos novos, divertidos e gratuitos para jogar com seus amigos.</p>
                                    <div class="projeto-card-desc-direita-icons">
                                        <a href="https://github.com/DavidAugustoo/FreePlay" target="_blank"><i class="fab fa-github"></i></a>
                                        <a href="https://freeplayy.netlify.app/" target="_blank"><i class="fas fa-link"></i></a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                        <div class="projetos-card">
                            <img src="./assets/images/medicenter.png" alt="">
                            <div class="projeto-card-desc">
                                <div class="projeto-card-desc-esquerda">
                                    <h2>MediCenter</h2>
                                    <div class="projeto-card-desc-categorias">
                                        <div class="projeto-card-desc-categoria html">HTML</div>
                                        <div class="projeto-card-desc-categoria css">CSS</div>
                                    </div>
                                </div>
                                <div class="projeto-card-desc-direita">
                                    <p>Landing page dedicado a instituições médicas e de saúde, clínicas e hospitais, médicos e todos os outros envolvidos em serviços de saúde.</p>
                                    <div class="projeto-card-desc-direita-icons">
                                        <a href="https://github.com/DavidAugustoo/MediCenter" target="_blank"><i class="fab fa-github"></i></a>
                                        <a href="https://davidaugustoo.github.io/MediCenter/" target="_blank"><i class="fas fa-link"></i></a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                        <div class="projetos-card">
                            <img src="./assets/images/awax.png" alt="">
                            <div class="projeto-card-desc">
                                <div class="projeto-card-desc-esquerda">
                                    <h2>Awax</h2>
                                    <div class="projeto-card-desc-categorias">
                                        <div class="projeto-card-desc-categoria html">HTML</div>
                                        <div class="projeto-card-desc-categoria css">CSS</div>
                                    </div>
                                </div>
                                <div class="projeto-card-desc-direita">
                                    <p>Landing page voltada para agências de comunicação visual, marketing e fotografia.</p>
                                    <div class="projeto-card-desc-direita-icons">
                                        <a href="https://github.com/DavidAugustoo/Awax" target="_blank"><i class="fab fa-github"></i></a>
                                        <a href="https://davidaugustoo.github.io/Awax/" target="_blank"><i class="fas fa-link"></i></a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>
</body>
</html>

