<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Elzeiny</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css">
    <link rel="stylesheet" href="css/Elzeiny_main_page.css">
 </head>
  <body id="body">
    <div class="navigation">
        <ul>
          <li id="BookNow"><a class="navWord" href="#">Book Now</a></li>
          <li id="imoID"><a href="#"><img src="Pic/e/logoElzeiny.jpg" alt="logo"></a></li>
          <li class="mnavLi" id="AboutID"><a class="AboutBio" href="#">About</a>
            <div class="BIODiv" id="BLOID">
              <h1>Ahmed Elzeiny</h1>
              In today’s world, there is a gigantic competition in practically every sector of services. And photography is no exception. Why should the client choose you? There has to be something about you and your page that simply won’t let the customer click on another photographer’s website (and there are so many of those on the Internet, you know that).
            </div>
          </li>
          <li class="mnavLi" id="ConId"><a href="#">Contact</a>
            <ul class="snavul">
              <li class="snavLi" id="PhoneId"><a target="_blank" href="https://web.whatsapp.com/">By Phone</a></li>
              <li class="snavLi"><a target="_blank" href="elzeinyahmed5@gmail.com">By E-mail</a></li>
              <li class="snavLi" id="socialId"><a href="#">Social Media</a>
                  <ul class="ssnavul">
                    <li class="snavLi" id="faceId"><a target="_blank" href="https://www.facebook.com/AhmedElzeiny.APh/?ref=page_internal">Facebook</a></li>
                    <li class="snavLi"><a target="_blank" href="https://www.instagram.com/ahmed.elzeiny_photography/">Instegram</a></li>
                    <li class="snavLi"><a target="_blank" href="https://twitter.com/ph_a_elzeiny">Twitter</a></li>
                  </ul>
              </li>
            </ul>
          </li>
        </ul>
    </div>
    <div class="BookingForm" id="BookingFormID">
      <form action="" method="post">
        <div class="BookingFormDiv">
          <h1 id="HeaderForm">
            <span id="CloseForm" class="CloseForm">
              <i class="fa-solid fa-rectangle-xmark"></i>
            </span>
            Book Your Session</h1>
          <div class="DataContainer1">
            <div class="FNDiv">
              <label class="FNLLabel" for="FNL">First Name</label>
              <input id="FNL" class="FDateSection" type="text" name="FName" placeholder="First Name" title="Your First Name">
            </div>
            <div class="LNDiv">
              <label class="LNLLabel" for="LNL">Last Name</label>
              <input id="LNL" class="FDateSection" type="text" name="LName" placeholder="Last Name" title="Your Last Name">
            </div>
            <div class="PHDiv">
              <label class="PHLLabel" for="PHL">Phone Number</label>
              <input id="PHL" class="FDateSection" type="Phone" name="Phone" placeholder="Phone Number" title="Your Phone Number">
            </div>
          </div>
          <div class="DataContainer2">
            <p>Gender</p>
            <div class="MaleG">
              <input id="ML" type="radio" name="MaleI" value="Male">
              <label for="ML">Male</label>
            </div>
            <div class="FemaleG">
              <input id="ML" type="radio" name="MaleI" value="Male">
              <label for="ML">Female</label>
            </div>
          </div>
          <div class="DataContainer3">
            <p>Demand Type</p>
            <div class="SingleD">
              <input id="SL" type="radio" name="SingleI" value="Single">
              <label for="SL">Single</label>
            </div>
            <div class="CoupleD">
              <input id="CL" type="radio" name="SingleI" value="Single">
              <label for="CL">Couple</label>
            </div>
          </div>
          <div class="DataContainer4">
            <p>Type Contract</p>
            <select class="BookSection" name="BookSection">
              <option value="Option 1">Wedding</option>
              <option value="Option 2">Session</option>
              <option value="Option 3">Wedding Session</option>
              <option value="Option 4">Album</option>
              <option value="Option 5">Single Photo</option>
            </select>
            <p>location</p>
              <input class="BookSection" type="text" name="Location" placeholder="Location" title="Your City">
            <p>location</p>
              <input class="BookSection" type="text" name="Location Name" placeholder="Location Name" title="Location">
            <p>Date</p>
              <input id="DateBtn" class="BookSection" type="date" name="Date" placeholder="Date" title="Date Of Contract">
          </div>
          <div class="DataContainer5">
            <input class="SubmitButton" type="submit" name="Confirm" value="Confirm">
          </div>
        </div>
      </form>
    </div>
    <div class="showPotoC" id="showPotoCID">
      <div class="showPoto" id="ShowImg1">
        <span class="rightAngel" id="RightAngelBTN">
          <i class="fa-solid fa-angle-right"></i>
        </span>
        <img id="PhotoTemp"  src="" alt="Photo">
        <span class="leftAngel" id="LeftAngelBTN">
          <i class="fa-solid fa-angle-left"></i>
        </span>
        <span class="backIcon" id="backIcon1">
          <i class="fa-solid fa-xmark" id="backIconI"></i>
        </span>
      </div>
    </div>
    <div class="wideImg" id="WideImgId">
      <video src="Pic/e/ABOUT-VIDEO-DS720.mov" autoplay loop preload="auto" playsinline webkit-playsinline x5-playsinline poster="Pic/e/Poster.png" width="100%">
        <source src="Pic/e/ABOUT-VIDEO-DS720.mov" type="video/">
        <source src="Pic/e/wideVideo.mp4" type="video/">
      </video>
    </div>

    <div class="PortofolioFlexBoxs" id="MainFlexBox">
        <div class="parent">
          <div class="div1l" id="img1c">
             <img src="Pic/e/11.jpg" alt="1" id="img1">
            <span class="zoomIcon" id="zoomIcon1">
              <i class="fas fa-search-plus"></i>
            </span>
           </div>
          <div class="div2" id="img2c">
            <img src="Pic/e/7.jpg" alt="2" id="img2">
            <span class="zoomIcon" id="zoomIcon2">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div3" id="img3c">
            <img src="Pic/e/6.jpg" alt="3" id="img3">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
           </div>
          <div class="div4l" id="img4c">
            <img src="Pic/e/4.jpg" alt="4" id="img4">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div5l" id="img5c">
            <img src="Pic/e/14.jpg" alt="5" id="img5">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div8l" id="img8c">
            <img src="Pic/e/11.jpg" alt="8" id="img8">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div9" id="img9c">
            <img src="Pic/e/17.jpg" alt="9" id="img9">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div10" id="img10c">
            <img src="Pic/e/fox.jpg" alt="10" id="img10">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div12l" id="img12c">
            <img src="Pic/e/5.jpg" alt="12" id="img12">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div13" id="img13c">
            <img src="Pic/e/18.jpg" alt="13" id="img13">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div16" id="img16c">
            <img src="Pic/e/18.jpg" alt="16" id="img16">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div17" id="img17c">
            <img src="Pic/e/4.jpg" alt="17" id="img17">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div18" id="img18c">
            <img src="Pic/e/16.jpg" alt="18" id="img18">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div19" id="img19c">
            <img src="Pic/e/19.jpg" alt="19" id="img19">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div20" id="img20c">
            <img src="Pic/e/3.jpg" alt="20" id="img20">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div21" id="img21c">
            <img src="Pic/e/8.jpg" alt="21" id="img21">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
          <div class="div24" id="img24c">
            <img src="Pic/e/11.jpg" alt="24" id="img24">
            <span class="zoomIcon">
            <i class="fas fa-search-plus"></i>
          </span>
          </div>
        </div>
    </div>
    <div class="moreAlbum" id="AlbumFlexBox">
      <p class="albumP" id="album">More Album</p>
      <div class="contaniner">
        <div class="parent2">
        <div class="diva1" id="imga1c">
          <img src="Pic/09 (2).jpg" alt="1" id="imga1">
        </div>
        <div class="diva2" id="imga2c">
          <img src="Pic/0118.jpg" alt="2" id="imga2">
        </div>
        <div class="diva3" id="imga3c">
          <img src="Pic/DSC_0696.jpg" alt="3" id="imga3">
        </div>
      </div>
      </div>

  </div>
  <div class="footer" id="FooterId">
    <a href="#">Created By Mohamed hassan</a>
    <footer>
      <li><a target="_blank" href="https://wa.me/+201117551643">
          <span class="whatsappIcon">
            <i class="fa-brands fa-whatsapp-square"></i>
          </span>
      </a></li>
    </footer>
  </div>

  <script src="Js/Elzeiny.js" charset="utf-8"></script>

  </body>
</html>
