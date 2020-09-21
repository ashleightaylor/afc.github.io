<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link href="./resources/style.css" type="text/css" rel="stylesheet">
    <title>University of Cambridge Archaeological Field Club</title>
  </head>
  <body>
    <script> /*makes header resize as you scroll*/
    window.onscroll = function() {scrollFunction()};

    function scrollFunction() {
      if (document.body.scrollTop > 50 || document.documentElement.scrollTop > 50) {
        document.getElementById("header").style.fontSize = "25px";
        document.getElementById("header").style.padding = "10px";
        document.body.classList.add("minilogo")
      } else {
        document.getElementById("header").style.fontSize = "50px";
        document.getElementById("header").style.padding = "20px 10px";
        document.body.classList.remove("minilogo");
      }
    }
    </script>

    <header id="header">University of Cambridge AFC</header>

    <div id="logo">
        <a href="index.html"><img src="Resources/imageedit_2_4435323263.png" width="100px"/></a>
    </div>

      <div class="content">
        <div class="membership container">
        <p>Life membership costs £10 but, for the first three weeks of Michelmas Term, you can get your membership for only £5!
          Unfortunately, we don't yet have a paypal link or other system set up, so to join please email Amy Bigwood,
          President of the AFC at <strong>ab2556@cam.ac.uk</strong></p>
        </div>
      </div>

      <footer class="footer container">
        <div class="left">
          <p>Copyright &copy; 2020 Ash Taylor
          </p></div>
          <img src="Resources/imageedit_2_4435323263.png" width="70px"/>
        <div class="contact container right">
          <p>Contact Us:</p><br>
          <a href="https://www.facebook.com/pg/UofCAFC/posts/"><img src="Resources/output-onlinepngtools.png"/></a><br>
          <p>demg2@cam.ac.uk</p><br>
        </div>
      </footer>

  </body>
</html>
