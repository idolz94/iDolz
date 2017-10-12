<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ramdom Quote</title>
</head>
<body>
  <div class="container">
    <div class = "jumbotron">
      <div class='text-center row titleBox'>
        <div class="col-xs-12 bookDiv"><h1 class="book-icon"><i class ="fa fa-book book"></i></h1></div>
        <div class="col-xs-12"><h1 class="title">Radom Quotes</h1></div>
        <hr class="hr1">
        <div class="row qouteBox">
          <div class="col-xs-12">
            <div class="bookBg">
              <div class="well text-center target1" id="target1">
                <blockquote class="blockquote"><h2><q class="quote"></q></h2><h3><footer class="author"></footer></h3></blockquote>

              </div>
            </div> <!-- Block Bg -->
            <hr class="hr2">
            <div class="well row targer2" id="target2">
              <div class="col-xs-4"><a target="_blank"><button type="button" class="btn btn-info btn-lg tweetButton" id="tweet" ontouchstart=""><i class="fa fa-twitter"></i> Share Quotes</button></a></div>
              <div class="col-xs-4 text-center"><button type="button" class="btn btn-default btn-lg btn-block qButton" id="qButton" ontouchstart="">Click New Quote <i class="fa fa-exclamation"></i></button></div>
              <div class="col-xs-2 text-right"><button type="button" class="btn btn-waring btn-sm leftButton" id="back" ontouchstart=""><i class="fa fa-hand-o-left"> Back</i></button></div>
              <div class="col-xs-2 text-left"><button type="button" class="btn btn-success btn-sm rightbutton" id="forward" ontouchstart="">Forward<i class="fa fa-hand-o-right"></i></button></div>
            </div>
            
          </div>
          
        </div>
        <footer class="text-center footer">by <a href="https://www.facebook.com/idolz94">Idolz</a></footer>
       </div> 
    </div> <!--jumbotron-->
  
  </div><!-- container-->
    </body>
    <style>
    body {
  /*(background-image:    url(https://www.clipartsgram.com/image/729211889-background-image-for-website.jpg); */
/*
background-image: url(https://s-media-cache-ak0.pinimg.com/originals/79/9a/ff/799aff7475c09bccfefda6947d17bf81.jpg);
  */
  /* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#45484d+0,000000+100;Black+3D+%231 */
  
 background: rgb(69,72,77); /* Old browsers */
  background: -moz-radial-gradient(center,ellipse cover, rgba(69,72,77,1) 0% rgba(0,0,0,1) 100%); /* FF3.6-15 */
  background: -webkit-radial-gradient(center,ellipse cover, rgba(69,72,77,1) 0% rgba(0,0,0,1)100%);
  /* chorm10-25 safari5.1-6*/
  background: radial-gradient(ellipse at center, rgba(69,72,77,1) 0% rgba(0,0,0,1) 100%); /* W3C, IE10+, FF16+, Chorm26+, Opera12+, Safari7+ */
  filter:
    progid:DXImageTransform.Microsoft.gadient(startColorstr="#45484d", endColorstr="#000000",GradientType=1 ); /* IE6-9 fallback */
  
  backbround-repeat: repeat;
  width: 100%;
  height: auto;
  margin-top: 50px;
  -webkit-background-size:cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
.jumbotron{
  background-color: rgba(0, 0, 0, 0);
  margin-top: -50px;
}
.quoteBox{
  border-style: hidden;
}

.quote{
  font: 200 30px/1.3 "Oleo Script", Helvetica,san-serif;
  color: #2b2b2b;
  /*text-shadow: 4px 4px 0px rgba(0,0,0,0.1);*/
  /*color: rgba(0,0,0, 0.8);*/
 text-shadow: 0px 0px 0px #def, 0 0 0 #000, 0px 0px 0px #def;
}

.bookBg{
  background-image:
  url("http://cdn.wonderfulengineering.com/wp-content/uploads/2016/02/vintage-wallpaper-8.jpg");
  background-repeat: no-repeat;
}
.target1{
  background-color: rgba(255,255,255,0);
  /*height: 280px;*/
  height: 340px;
  margin-bottom: 0;
  border-radius: 20px;
  border-style: hidden;
  box-shadow: 0px 0px 30px 0px rgba(0, 0, 0, 0.7);
}
#target2{
  background-color: rgba(255,255,255,0) ;
  /*border-radius: 0 0 20px 20px;*/
  margin-bottom: -1px;
  border-style: hidden;
}
#qButton{
  /*border: 2px solid #000;*/
  background-color: #000;
  font: 100 25px/1.3 "Arizonia", Helvetica, san-serif;
  color: #FFF;
  box-shadow: 0px 25px 9px -20px rgba(0, 0 , 0,.90);
  white-space: normal;
  outline: none;
}
#qButton:active{
  /*border: 2px solid #000;*/
  transform: translateY(5px);
  box-shadow: 0px 10px 10px -6px rgba(0,0,0,.90);
}
#tweet{
  box-shadow: 0px 25px 9px -20px
    rgba(0,0,0,.90);
  white-space: normal;
}
#tweet:active{
  transform: translateY(4px);
  box-shadow: 0px 10px 10px -6px rgba(0,0,0,.90);
}

:not(#qButton){
  border-radius: 20px;
    outline: none;
}
#back, #forward {
  /*margin-top: 10px;*/
  white-space: normal;
  height: 50px;
  box-shadow: 0px 25px 9px -20px rgba(0,0,0,.90);
}
/* 
#back:active, #forward:active{
transform: translateY(3px);
}
*/
#back:active {
  transform: translateX(-8px);
  box-shadow: 15px 25px 9px -20px rgba(0,0,0,.90);
}
#forward:active{
  transform: translateX(8px);
  box-shadow: -20px 25px 9px -20px rgba(0,0,0,.90);
}

h1.title{
  font: 400 100px/1.3 "Arizonia", Helvetica, sans-serif;
  /*color: #2b2b2b;*/
  font-weight: bold;
  color: rgba(10,60,150,0.8);
  text-shadow: 1px 4px 6px #def, 0 0 0 #000, 1px 4px 6px #def;
}
h1.book-icon{
  font: 300 60px/1.3 "Arizonia", Helvetica, san-serif;
  /*color: #2b2b2b;*/
  color: rgba(255,255,255,0.5);
  margin-bottom: -70px;
}

.blockquote{
  border-left: 0;
}

.hr1, .hr2{
  height: 10px;
  border: 0;
  box-shadow: 0px 10px 10px -10px #8c8b8b inset;
}
.footer{
  color: #FFF;
}
.footer a{
  color: #0EF;
  text-decoration: none;
}
@media only screen and (min-width: 150px) and (max-width: 600px) {
  .body {
    width: 90%;
    font-size: 90%;
    margin: 0;
  }
  .jumbotron{
    margin-top: -120px;
  }
  h1.title{
    font-size: 200px;
  }
  .quoteBox{
    margin-top: -20px;
    margin-left: -30px;
    margin-right: -30px;
  }
  .bookDiv{
    margin-bottom: 20px;
  }
  .book{
    font-size: 50%;
  }
  .title{
    margin-bottom: -20px;
  }
  .target1{
    /*height : 80%;*/
    box-shadow: 0px 0px 15px 0px rgba(0,0,0,0.9);
  }
  .target2{
    margin-top: -30px;
    margin-bottom: -20px;
  }
  .blockquote{
    margin-top: -40px;
  }
  .quote{
    font-size: 70%;
  }
  .author{
    font-size: 70%;
  }
  .tweetButton, .qButton, .leftButton, .rightButton{
    margin-top: -10px;
    margin-left: -20px;
  }
  .leftButton, .rightButton{
    height : 60px;
  }
  .hr2{
    margin-top 7px;
  }
}
    </style>
    <script>
    //jshint esversion:6
var quoteArray = [], authorArray = [], index = 0;
$(document).ready(function() {

    $(".titleBox").addClass("animated zoomIn");
  
    changeBGColor();
    getQuote();

    $(".target1").addClass("animated zoomInDown").delay(800).queue(function(){
      $(this).removeClass("animated zoomInDown").dequeue();
    });
    checkIndex();

    function checkIndex(){
      if (quoteArray.length === 0){
        $("#back").hide();
        $("#forward").hide();
      } else {
        if (index === 0){
          $("#back").hide();
          $("#forward").show();
        } else {
          $("#back").show();
          if (index === quoteArray.length-1){
            $("#forward").hide();
          } else {
            $("#forward").show();
          }
        }
      }      
    }
  
    $("#qButton").on("click", function() {

      changeBGColor();
      
      getQuote();
      
      $(".target1").addClass("animated zoomIn").delay(800).queue(function(){
        $(this).removeClass("animated zoomIn").dequeue();
      });
      
      index++;
      checkIndex();
      $("#forward").hide();
    });
  
    $("#back").on("click", function(){
      if (index > 0){
        changeBGColor();
        console.log("in back");
        index--;
        $(".quote").html(quoteArray[index]);
        $(".author").html(authorArray[index]);       
      }
 
      //$(".target1").effect("slide", {direction: "left"}, 500);
      $(".target1").addClass("animated fadeInLeft").delay(800).queue(function(){
        $(this).removeClass("animated fadeInLeft").dequeue();
      });    
      checkIndex();
    });
  
    $("#forward").on("click", function(){
      if (index < quoteArray.length && index + 1 < quoteArray.length){
        changeBGColor();
        console.log("in forward");
        index++;
        $(".quote").html(quoteArray[index]);
        $(".author").html(authorArray[index]);       
      }     
      //$(".target1").effect("slide", {direction: "right"}, 500);
     $(".target1").addClass("animated fadeInRight").delay(800).queue(function(){
        $(this).removeClass("animated fadeInRight").dequeue();
      });        
      checkIndex();
    });
    $("#tweet").on("click", function(){
      let x = quoteArray[index].toString();
      window.open("https://twitter.com/intent/tweet?text=\"" + x.substr(0,x.length-1) + "\" - " + authorArray[index]);
      //window.open("https://twitter.com/intent/tweet?text=\"" + (x=quoteArray[index].toString()).substr(0,x.length-1) + "\" - " + authorArray[index]); // x=quoteArray[index].toString()).substr(0,x.length-1) will remove whitespace of the last index of the quote
    });
});

function getQuote(){
  /*http://crossorigin.me/*/
  $.getJSON("https://api.forismatic.com/api/1.0/?method=getQuote&format=jsonp&lang=en&jsonp=?", function(data) {
    if (data.quoteAuthor !== ""){
      $(".quote").html(data.quoteText);
      $(".author").html(data.quoteAuthor);
      quoteArray.push([data.quoteText]);
      authorArray.push([data.quoteAuthor]);
    } else{
      getQuote();
    }
    console.log(data.quoteText);
    console.log(`- ${data.quoteAuthor}`);
  });
}

var ran = function(myMin, myMax){
  return (Math.floor(Math.random() * (myMax - myMin + 1)) + myMin);
}

function changeBGColor(){
  $("#target1").css("background-color", `rgba(${ran(0,255)}, ${ran(0,255)}, ${ran(0,255)}, 0.2)`);
}

    </script>
