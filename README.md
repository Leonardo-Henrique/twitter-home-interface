<!DOCTYPE html>
<html lang="pt-br">

    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Home / Twitter</title>
        <link rel="stylesheet" href="css/style.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>    
        <script src="https://rawgit.com/jackmoore/autosize/master/dist/autosize.min.js"></script>
        <script src="https://kit.fontawesome.com/9ac6cfa819.js" crossorigin="anonymous"></script>
        
    </head>
    <body>
        <!-- fixed menu -->
        <header>
            <div class="logo">
                <a href=""><img src="img/logo.png"></a>
            </div>
            <ul class="menu">
                <li><a href="" class="active">Home</a></li>
                <li><a href="">Explore</a></li>
                <li><a href="">Notifications</a></li>
                <li><a href="">Messages</a></li>
                <li><a href="">Bookmarks</a></li>
                <li><a href="">Lists</a></li>
                <li><a href="">Profile</a></li>
                <li><a href="">More</a></li>
                <button>Tweet</button>
            </ul>
            <div class="user">
                <div class="foto">
                    
                    <!-- <img src="img/foto-perfil.PNG" alt=""> -->
                </div>
                <div class="info">
                    <span><b>leo( );</b></span>
                    <span>@leonard_ow</span>
                </div>
                <div class="clear"></div>
            </div>
        </header>
        <div class="feed">
            <div class="feed-title">
                <span>Home</span>
            </div>
            <div class="box-tweet">
                <div class="user-foto">
                    <img src="img/leo.jpg">
                </div>
                <form action="">
                    <textarea placeholder="What's happening?" id="text"></textarea>
                </form>
                <span class="privacy">
                    <a href=""><i class="fas fa-globe-americas"></i> Everyone can reply</a>   
                </span>
                <div class="line"></div>
                <div class="box-footer">
                    <div class="icons">
                        <p>icones</p>
                    </div>
                    <div class="enviar">
                        <button class="btn-enviar">Tweet</button>
                    </div>
                    <div class="clear"></div>
                </div>
                <div class="clear"></div>
            </div><!-- escrever tweet -->
            <div class="divisor"></div>
            
            <div class="feed-noticias">
                <div class="box-feed">
                    
                    <div class="foto-user-box">
                        <img src="img/uol.png" alt="">
                    </div>
                    <div class="box-header">
                        
                        <span style="font-weight: 700;">UOL</span>
                        <span style="color: rgb(91, 112, 131);">@uol · 3m</span>
                        <a href="" style="font-size: 1.5em;">...</a>
                        <div class="clear"></div>
                    </div>
                    <div class="descricao">
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Recusandae.</p>
                    </div>
                    <div class="noticia">
                        <div class="noticia-img">
                            <img src="img/box.jpeg">
                        </div>
                        <div class="noticia-descricao">
                            <h1>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</h1>
                            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                            <a href="">uol.com.br</a>
                        </div>
                    </div>
                    <div class="box-footer-reactions">
                        reações
                    </div>
                </div>
                <div class="box-feed">
                    <div class="foto-user-box">
                        <img src="img/uol.png" alt="">
                    </div>
                    <div class="box-header">
                        
                        <span style="font-weight: 700;">UOL</span>
                        <span style="color: rgb(91, 112, 131);">@uol · 3m</span>
                        <a href="" style="font-size: 1.5em;">...</a>
                        <div class="clear"></div>
                    </div>
                    <div class="descricao">
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Lorem, ipsum dolor sit amet consect</p>
                    </div>
                    <div class="noticia">
                        <div class="noticia-img">
                            <img src="img/box.jpeg">
                        </div>
                        <div class="noticia-descricao">
                            <h1>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</h1>
                            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                            <a href="">uol.com.br</a>
                        </div>
                    </div>
                    <div class="box-footer-reactions">
                        reações
                    </div>
                </div>
                <div class="clear"></div>
            </div>
             <div class="clear"></div>
        </div>
        <div class="right">
            <div class="search-right">
                <form action="">
                <i class="fas fa-search" style="color: #768898;"></i><input type="text" placeholder=" Search Twitter">
                </form>
                <div class="clear"></div>
            </div>
            <div class="trends">
                <div class="trends-title">
                    <h1>What's happening</h1>
                </div>
                <div class="trends-box">
                    <div class="left-trends">
                        <div class="trends-b-title">
                            <p>Série A LIVE</p>
                        </div>
                        <div class="trends-descricao">
                            <p><b>Fiorentina vs Inter Milan</b></p>
                        </div>
                    </div>
                    <div class="trends-img">
                        <!-- <img src="img/trends.jpeg" alt=""> -->
                    </div>
                    <div class="clear"></div>
                </div>
                <div class="trends-box">
                <div class="left-trends">
                    <div class="trends-b-title">
                        <p style="color: #000;"><b>#MéquiNoBBB21</b></p>
                    </div>
                    <div class="trends-descricao">
                        <p style="color: #6d8091;">Viu BBB e bateu fome de Méqui? Então pegue seu cupom e passa no Drive</p>
                        <span style="display:inline-block; font-size: 0.85em; margin-top: 10px; color: #5b7083;"><i class="fas fa-arrow-circle-up"></i> Promoted by McDonald's Brasil</span>
                    </div>
                </div>
                <div class="clear"></div>
                </div>
                <div class="trends-box">
                <div class="left-trends">
                    <div class="trends-b-title">
                        <p id="p-f">Trending in Brazil</p>
                        <span id="r-r">...</span>
                    </div>
                    <div class="trends-descricao">
                        <p><b>Agora a Karol</b></p>
                        
                        <span style="display:inline-block; font-size: 0.85em; margin-top: 10px; color: #5b7083;"> 59.7k Tweets</span>
                    </div>
                </div>
               
                <div class="clear"></div>
                </div>
                <div class="trends-box">
                <div class="left-trends" style="float: left; width: 75%;">
                    <div class="trends-b-title">
                        <p style="color: #000;"><b>Exitoína Brasil</b> <span style="color: rgb(91, 112, 131);">· Yesterday</span></p>
                    </div>
                    <div class="trends-descricao">
                        <p style="display: inline-block;"><b>Netflix: filmes que serão lançados em 2021</b></p>
                    </div>
                </div>
                <div class="trends-img">
                    <!-- <img src="img/trends.jpeg" alt=""> -->
                </div>
                <div class="clear"></div>
                </div>
                <div class="trends-box">
                <div class="left-trends" style="float: left; width: 75%;">
                    <div class="trends-b-title">
                        <p style="color: #000;"><b>VivaBem</b> <span style="color: rgb(91, 112, 131);">· Yesterday</span></p>
                    </div>
                    <div class="trends-descricao">
                        <p style="display: inline-block;"><b>Separados por uma tela </b></p>
                    </div>
                </div>
                <div class="trends-img">
                    <!-- <img src="img/trends.jpeg" alt=""> -->
                </div>
                <div class="clear"></div>
                </div>
                <div class="trends-footer">
                    <a href="">Show more</a>
                </div>
            </div>
            <div class="trends" id="second">
                <div class="trends-title">
                    <h1>Who to follow</h1>
                </div>
                <div class="follow-box">
                    <div class="follow-foto">
                        <img src="img/leo.jpg" alt="">
                    </div>
                    <div class="follow-center">
                        <span style="clear:both;"><b>nome</b></span>
                        <span style="color: #aeb5bd;">@fuladno</span>
                        <!-- <span id="follow-you">Follows you</span> -->
                    </div>
                    <div class="btn-follow">
                        <button>Follow</button>
                    </div>
                    <div class="clear"></div>
                </div>
                <div class="follow-box">
                    <div class="follow-foto">
                        <img src="img/leo.jpg" alt="">
                    </div>
                    <div class="follow-center">
                        <span><b>nome</b></span>
                        <span style="color: #aeb5bd;">@fuladno</span>
                        <!-- <span id="follow-you">Follows you</span> -->
                    </div>
                    <div class="btn-follow">
                        <button>Follow</button>
                    </div>
                    <div class="clear"></div>
                </div>
                <div class="follow-box">
                    <div class="follow-foto">
                        <img src="img/leo.jpg" alt="">
                    </div>
                    <div class="follow-center">
                        <span><b>nome</b></span>
                        <span style="color: #aeb5bd;">@fuladno</span>
                        <!-- <span id="follow-you">Follows you</span> -->
                    </div>
                    <div class="btn-follow">
                        <button>Follow</button>
                    </div>
                    
                    <div class="clear"></div>
                    
                </div>
                <div class="trends-footer">
                    <a href="">Show more</a>
                </div>
                <div class="clear"></div>
                
            </div>
            <div class="termos">
                <a href="">Terms of Service</a>
                <a href="">Privacy Policy</a>
                <a href="">Cookie Policy</a>
                <a href="">Ads info</a>
                <a href="">More</a>
                <span>&copy 2021 Twitter, Inc.</span>
            </div>
          
            
            
        </div>
        
        <script>
            autosize(document.getElementById("text"));
            $('#text').click(function(){
                $('.privacy').show();
                $('.line').show();
                
            });
            $('#text').keyup(function() {
                $('.btn-enviar').addClass('op1');
            });
        </script>
       
    </body>
</html>
