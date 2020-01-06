我利用bootstape的模板
https://getbootstrap.com/docs/4.4/components/carousel/
上為幻燈片學處習處
https://getbootstrap.com/docs/4.4/components/navbar/
上為導覽欄學習處
https://getbootstrap.com/docs/4.4/layout/grid/
上為下方文字編輯模板以及封面編輯學習處
<nav class="nav navbar-inverse">
        <div class="container-fluid">
            <div class="navbar-header">
                <a class="navbar-brand" href="index.html" >HOME</a>
            </div>
            <div class="navbar-header">
                <a class="navbar-brand" href="登山.html">登山</a>
            </div>            
            <div class="navbar-header">
                <a class="navbar-brand" href="露營.html">露營</a>
            </div>            
            <div class="navbar-header">
                <a class="navbar-brand" href="野炊.html">野炊</a>
            </div>
            <div class="navbar-header">
                <a class="navbar-brand" href="相關影片.html">相關影片</a>
            </div>            
        </div>
    </  導航> 
運用bootstrap上的導覽欄相關教學，並加入超連結HREF連結至其他分頁
    <div class="container">
               <h2></h2>
        <div id="myCarousel" class="carousel slide" data-ride="carousel">
            <!-- 點點 -->
            <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="1" class="active"></li>
                <li data-target="#myCarousel" data-slide-to="2"></li>
                <li data-target="#myCarousel" data-slide-to="3"></li>
                <li data-target="#myCarousel" data-slide-to="4"></li>
                <li data-target="#myCarousel" data-slide-to="5"></li>
                <li data-target="#myCarousel" data-slide-to="6"></li>

            </ol>
            <script src="https://code.jquery.com/jquery.js"></script>
            <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.3.7/js/bootstrap.min.js"></script>
            
               <div class="jumbotron text-center">
                <h1>Natural Felling</h1>
                <p>Relax your body and walk into nature</p>
            </div>
            <div class="carousel-inner">
                <div class="item active">
                    <img src="幻燈片/1.jpg" style="width:100%">
                </div>
                <div class="item">
                    <img src="幻燈片/2.jpg" style="width:100%">
                </div>
                <div class="item">
                    <img src="幻燈片/3.jpg" style="width:100%">
                </div>
                <div class="item">
                    <img src="幻燈片/4.jpg" style="width:100%">
                </div>
                <div class="item">
                    <img src="幻燈片/5.jpg" style="width:100%">
                </div>
                <div class="item">
                    <img src="幻燈片/6.jpg" style="width:100%">
                </div>
            </div>
            <a href="#myCarousel" class="left carousel-control" data-slide="prev">
                <span class="glyphicon glyphicon-chevron-left"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a href="#myCarousel" class="right carousel-control" data-slide="next">
                <span class="glyphicon glyphicon-chevron-right"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
            </div>
   
