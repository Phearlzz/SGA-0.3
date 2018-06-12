<!DOCTYPE html>
<head>
<script src="/assets/jquery.js"></script>
<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet">
<style>
body {
  font-family: helvetica, sans-serif;
  margin: 0 auto;
  max-width: 600px;
  background: rgba(0,15,15,1);
}
div {
  height: 450px;
  background-size: cover;
  position: relative;
  margin: 40px 0 0 0;
  border-radius: 12px;
}
h1 {
  font-family: 'Lobster', cursive;
  text-align: center;
  font-size: 60px;
  color: #aabbaa;
  margin: 60px 0 0 0;
}
h2 {
  font-family: 'Lobster', cursive;
  text-align: center;
  color: #baddbb;
  margin: 0px 0 70px 0;
}
p {
  color: rgba(255,255,255,1);
  background: black;
  background: linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  background: -webkit-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  background: -moz-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
  padding: 10px;
  line-height: 28px;
  text-align: justify;
  position: absolute;
  bottom: 0;
  margin: 0;
  height: 30px;
  transition: height .5s;
  -webkit-transition: height .5s;
  -moz-transition: height .5s;
}

small {
  opacity: 0;
}

.show-description p {
  height: 150px;
}

.show-description small {
  opacity: 1;
}

.first{
  background-image: url("https://imgur.com/2AooyRE.jpg");
}
.second{
  background-image: url("https://imgur.com/PXe0mjh.jpg");
}
.third{
  background-image: url("https://imgur.com/rhpL0TA.jpg");
}
.price {
  float: right;
}
@media (max-width: 500px) {
  h1 {
    font-size: 50px;
    margin-top: 20px;
    line-height: 40px;
  }
  h2 {
    font-size: 20px;
    margin: 20px 0 30px 0;
  }
  div {
    margin: 20px 12px 0 12px;
    height: 200px;
    
  }
  p {
    font-size: 15px;
    line-height: 24px;
  }
  small {
    font-size: 16px;
  }
}

</style>

</head>

<body>
<h1>Phearlzz Foot wears</h1>
<h2>Walk! Strut! Slay!</h2>
<div class="first show description">
  <p>Active Harmony shoe  <span class="price">#10,000</span><br />
  <small>Female pink active harmony shoe available from size 37-41. Look good exercising and also hanging out with friends or going on a date. </small></p>
</div>

<div class="second show description">
  <p>Stilettos <span class="price">#10,000</span><br />
  <small>Stilettos Womens Shoes 12CM High Heels  Purple Shoes Pumps Women Heels Sexy Pointed Toe.</small></p>
</div>
  
<div class="third show description">
  <p>Sneakers <span class="price">#15,000</span><br />
  <small>New Balance will show off its running shoe with the 3D-printed midsole. Sizes available: 37,38,39,40,41.   </small></p>
</div>

<script>
alert("Thank you for choosing Phearlzz footwears!")
  $('div').on('click', function() {
      $(this).toggleClass('show-description');
  });
</script>

</body>
