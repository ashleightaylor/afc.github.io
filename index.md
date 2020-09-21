<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <link href="./style.css" type="text/css" rel="stylesheet">
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
      <div class="opener container">
        <img src="Resources/museumofana.jpg" width="50%"/>
        <div class="about container">
        <p>The AFC (Archaeological Field Club) is a Cambridge Society that runs talks, events, and activities linked
          to archaeology, biological anthropology, and heritage. We host talks with archaeologists (alumni and beyond),
          as well as socials, subject-specfic information talks, and the annual AFC Feast.<br><br>The AFC aims to welcome students
           who have an interest in the past and archaeology, regardless of subject or level of knowledge. Come along
         to an event (virtual or otherwise) and see what the AFC and archaeology have to offer!</p>
        </div>
      </div>

      <div class="divider container">
      </div>

      <div class="termcard">
      </div>

      <div class="divider container">
      </div>

      <div class="memberhow container">
        <a href="membership.html">become a member</a>
      </div>

      <div class="divider container">
      </div>

      <div class="committee container">
        <h2>Current Committee</h2>
        <div id="committee-members">
          <div class="member">
            <img src="Resources/amy.JPG" alt="Photo of committee member">
            <h4>Amy Bigwood</h4>
            <p><em>President</em></p>
          </div>
          <div class="member">
            <img src="Resources/ish.JPG" alt="Photo of committee member">
            <h4>Ishbel Russell</h4>
            <p><em>Co-Vice President</em></p>
          </div>
          <div class="member">
            <img src="Resources/robert.JPG" alt="Photo of committee member">
            <h4>Robert Sizer</h4>
            <p><em>Co-Vice President</em></p>
          </div>
          <div class="member">
            <img src="Resources/daz.JPG" alt="Photo of committee member">
            <h4>Daisy Green</h4>
            <p><em>Secretary</em></p>
          </div>
          <div class="member">
            <img src="Resources/marc.JPG" alt="Photo of committee member">
            <h4>Marc Mills</h4>
            <p><em>Treasurer</em></p>
          </div>
          <div class="member">
            <img src="Resources/anna.JPG" alt="Photo of committee member">
            <h4>Anna Freed</h4>
            <p><em>Social Secretary</em></p>
          </div>
          <div class="member">
            <img src="Resources/ash.JPG" alt="Photo of committee member">
            <h4>Ash Taylor</h4>
            <p><em>Stash Officer/Website Manager</em></p>
          </div>
          <div class="member">
            <img src="Resources/morgan.JPG" alt="Photo of committee member">
            <h4>Morgan Sapsford</h4>
            <p><em>Fundraising Officer</em></p>
          </div>
        </div>
      </div>

      <div class="divider container">
      </div>

        <div class="stashheader container">
          <h2>Stash</h2>
        </div>
        <div class="stashexplain container">
          <p>In order to keep prices as low as possible, please note that orders are made once per term, in week three, so you
            won't get your order as soon as you make it. Currently we do not have an official bank account, so please send your
            order request to akt42@cam.ac.uk, and payment will be organised at a later date.</p>
        </div>
        <div class="stashavailable container">
          <p>Currently there is no stash available.</p>
        </div>
        <div style="clear:both;"></div>
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
