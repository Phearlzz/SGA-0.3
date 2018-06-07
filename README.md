# SGA-0.3<!DOCTYPE html>
<head>
<title>My Blog Page</title>
<link href="/normalize.css" rel="stylesheet">
<style>
header{
  text-align: center;
  background: url("https://imgur.com/M1ekcBL.jpg");
  background-size: cover;
  background-position: center;
  color: #fff;
  }
  h1{
    font-size: 40px;
    margin: 0px 0px 0.5px 0px;
    }
    h2{
      margin: 0px 0px 0px 0px;
      font-size: 20px;
      }
  li{
    display: inline;
    padding: 0px 10px 0px 10px;
    }
  ul{
    padding: 10px;
    background: rgba(255,255,150,0.5);
    }
    img{
      margin: 70px 0px 10px 0px;
      border: 10px black solid;
      border-radius: 20px
      }
      a{
        color: black;
        }
        a:hover{
          color: #505050;
          }
        article{
          color: black;
          max-width: 500px;
          margin: 0 auto;
          }
          button{
            background: #50050;
            padding: 10px 5px 10px 5px;
            }
            button:hover{
              color: blue;
              cursor: pointer;
              background: rgba(100,100,100,0.5);
              }
          @media (max-width: 500px) {
            
            h1{
              font-size: 20px;
              padding: 5px;
              }
              li{
                display: block;
                padding: 5px;
                }
            }
       
</style>
</head>
<body>
<header>
<img src="https://imgur.com/yO0v72D.jpg" height="350" width="230">
<h1>Phearlzz Diary </h1>
<h2>Beauty/Brains/Lifestyle</h2>


<ul>
<li><a href="#">About me</a></li>
<li><a href="#">Contact</a></li>
<li><a href="#">Beauty</a></li>
<li><a href="#">Brains</a></li>
<li><a href="#">Lifestyle</a></li>
</ul>
</header>

<article>
<h3>Beauty</h3>
<p> Welcome to the beauty section. In this section, we are gonna be talking all on fashion and how to make yourself look good for any occasion.</p>
<button>Like</button>  <button>Go to Beauty</button>
</article>

<article>
<h3>Brains</h3>
<p>Welcome to the brains section. In this section, we are gonna be talking all about academics and how to make yourself stand out and stay on top of your class.</p>
<button>Like</button>   <button>Go to Brains</button>
</article>

<article>
<h3>Lifestyle</h3>
<p>Welcome to my Lifestyle section. In this section, we are gonna be talking all about God and how to make Him the center of your life and wellbeing.</p>
<button>Like</button>  <button>Go to Lifestyle</button>
</article>

<script>
alert("Thank you for choosing my blog. Have fun!");
    $("button").on("click", function() {
      alert("Thank you!");
    });
  </script>
  
</body>
