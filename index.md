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
                        <p>Ol?? Mundo! <span>&#128075</span> Meu nome ?? Jennifer</p>
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
                        <p>Apaixonada por tecnologia, formada em An??lise e Desenvolvimento de Sistemas fui apresentada ao desenvolvimento web e desde ent??o, sigo estudando e me aperfei??oando desenvolvendo projetos, a fim de dominar o Desenvolvimento Web. Sempre buscando criar solu????es combinando design e interatividade para uma melhor experi??ncia do usu??rio. </br>
                        </br>Sou fascinada por resolu????o de problemas, principalmente utilizando a tecnologia.</p>
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
                            <p>HTMl ?? uma linguagem de marca????o utilizada na constru????o de p??ginas na Web. Documentos HTML podem ser interpretados por navegadores.</p>
                            </div>            
                        </div>
                        <div class="card">
                            <div class="card-area">
                                <img src="assets/images/css_icon.png">
                            <h2>CSS</h2>
                            <p>O CSS ?? uma linguagem de folhas de estilos que ?? utilizada para definir como os documentos escritos na linguagem de marca????o HTML.</p>
                            </div>   
                        </div>
                        <div class="card">
                            <div class="card-area">
                                <img src="assets/images/js_icon.png">
                            <h2>Javascript</h2>
                            <p>JavaScript ?? uma linguagem de programa????o interpretada estruturada, de script em alto n??vel com tipagem din??mica fraca e multiparadigma.</p>
                            </div>   
                        </div>
                        <div class="card">
                            <div class="card-area">
                                <img src="assets/images/php_icon.png">
                            <h2>Php</h2>
                            <p>PHP ?? uma linguagem interpretada livre, usada originalmente apenas para o desenvolvimento de aplica????es presentes e atuantes no lado do servidor, capazes de gerar conte??do din??mico na World Wide Web</p>
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
                                    <p> Cicle ?? uma startup que permite vender materiais reciclados com facilidade, descartando aquilo que n??o se ?? usado por um pre??o justo.</p>
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
                                    <p> PetFood ?? um e-commerce totalmente voltado para o ramo de animais de estima????o                                    </p>
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
                                    <p> FreePlay ?? um ??timo site para encontrar jogos novos, divertidos e gratuitos para jogar com seus amigos.</p>
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
                                    <p>Landing page dedicado a institui????es m??dicas e de sa??de, cl??nicas e hospitais, m??dicos e todos os outros envolvidos em servi??os de sa??de.</p>
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
                                    <p>Landing page voltada para ag??ncias de comunica????o visual, marketing e fotografia.</p>
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

