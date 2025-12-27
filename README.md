# Micholin
# This was supposed to be my first self made website. Ran out of ideas
# I don't know about the CSS design and the colour harmony
[Micholin.html](https://github.com/user-attachments/files/24353476/Micholin.html)
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <link rel="stylesheet" href="Stylesfold/Text.css">
    <link rel="stylesheet" href="Stylesfold/headtext.css">
    <link rel="stylesheet" href="Stylesfold/gentext.css">
    <link rel="stylesheet" href="Stylesfold/Sidebar.css">

    <title>
      Micholin
    </title>
  </head>
  <body>
    <div class="header">
      <p style="
      font-family: cursive;
      font-size: 50px;
      color: white;
      ">Micholin</p>
    </div>
      <header>
        <nav>
          <ul>
            <div class="gendiv">
              <div class="leftdiv">
                <div class="homediv">
                  <p style="
                    font-family: cursive;
                    font-size: 20px;
                    ">
                    <a href="Homepage.html" target="Home">Home</a>
                  </p> 
                </div>
                <div class="aboutdiv">
                  <p style="
                    font-family: cursive;
                    font-size: 20px;
                    ">
                    <a href="Code one.html" target="sign-in">About</a>
                  </p>
                </div>
              </div>
              <div>
                <input class="search" type="text" placeholder="Search">
              </div>
              <div class="rightdiv">
                <div class="logdiv">
                  <p style="
                    font-family: cursive;
                    font-size: 20px;
                    ">
                    <a href="Complex.html" target="log-in">Log in</a>
                  </p> 
                </div>
                <div class="signdiv">
                  <p style="
                    font-family: cursive;
                    font-size: 20px;
                    " id="sign-in">
                    <a href="youtube.html" target="sign-in">Sign in</a>
                  </p> 
                </div>
              </div>
            </div>
          </ul> 
        </nav>
      </header>
      <div class="side-bar">
        Side bar
      </div>
    <!--Body HTML-->


    <div class="videogrid">
      <div class="videopreview">
        <div class="channelpics">
          <img class="vidpics" src="Thumbnails/Airplane2.jpg">
          <div class="video-time">
            14:09
          </div>
        </div>
        <div class="videoinfo">
          <div class="profilepics">
            <img class="selfie" src="Thumbnails/Oceans.jpg">
          </div>
          <div class="videostats">
            <p class="title">The beauty of outer space</p>
            <p class="author">Update&#46;com </p>
            <p class="stats">450K views &#183; 1 month ago</p>
          </div>
        </div>
      </div>


      <div class="videopreview">
        <div class="channelpics">
          <img class="vidpics" src="Thumbnails/Advice2.png">
          <div class="video-time">
            2:02:58
          </div>
        </div>
        <div class="videoinfo">
          <div class="profilepics">
            <img class="selfie" src="Thumbnails/Oceans.jpg">
          </div>
          <div class="videostats">
            <p class="title">The beauty of outer space</p>
            <p class="author">Update&#46;com </p>
            <p class="stats">450K views &#183; 1 month ago</p>
          </div>
        </div>
      </div>

      <div class="videopreview">
        <div class="channelpics">
          <img class="vidpics" src="Thumbnails/Space.jpg">
          <div class="video-time">
            02:58
          </div>
        </div>
        <div class="videoinfo">
          <div class="profilepics">
            <img class="selfie" src="Thumbnails/Techmakers.jpg">
          </div>
          <div class="videostats">
            <p class="title">The beauty of outer space</p>
            <p class="author">Update&#46;com </p>
            <p class="stats">450K views &#183; 1 month ago</p>
          </div>
        </div>
      </div>


      <div class="videopreview">
        <div class="channelpics">
          <img class="vidpics" src="Thumbnails/Mountains.jpg">
          <div class="video-time">
            12:50
          </div>
        </div>
        <div class="videoinfo">
          <div class="profilepics">
            <img class="selfie" src="Thumbnails/Oceans.jpg">
          </div>
          <div class="videostats">
            <p class="title">The beauty of outer space</p>
            <p class="author">Update&#46;com </p>
            <p class="stats">450K views &#183; 1 month ago</p>
          </div>
        </div>
      </div>

      <div class="videopreview">
        <div class="channelpics">
          <img class="vidpics" src="Thumbnails/Airplane1.jpg">
          <div class="video-time">
            13:09
          </div>
        </div>
        <div class="videoinfo">
          <div class="profilepics">
            <img class="selfie" src="Thumbnails/Oceans.jpg">
          </div>
          <div class="videostats">
            <p class="title">The beauty of outer space</p>
            <p class="author">Update&#46;com </p>
            <p class="stats">450K views &#183; 1 month ago</p>
          </div>
        </div>
      </div>

      <div class="videopreview">
        <div class="channelpics">
          <img class="vidpics" src="Thumbnails/Lone wolf1.png">
          <div class="video-time">
            5:00
          </div>
        </div>
        <div class="videoinfo">
          <div class="profilepics">
            <img class="selfie" src="Thumbnails/Oceans.jpg">
          </div>
          <div class="videostats">
            <p class="title">The beauty of outer space</p>
            <p class="author">Update&#46;com </p>
            <p class="stats">450K views &#183; 1 month ago</p>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>

[Homepage-body.css](https://github.com/user-attachments/files/24353477/Homepage-body.css).intro{
  display: flex;
  flex-direction: row;
  justify-content: center;
  z-index: 200;
  background-color: black;
  position: relative;
  top: 200px;
}

>[Homepage-head.css](https://github.com/user-attachments/files/24353478/Homepage-head.css).welcome-head{
  background-color: rgb(91, 6, 6);
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}
.weltext{
  font-family: cursive;
  font-size: 80px;
  font-weight: 700;
  color: white;
}

.homediv{
  display: inline-block;
  margin-right: 20px;
}
.aboutdiv{
  display: inline-block;
}
.logdiv{
  display: inline-block;
  margin-right: 20px;
}
.signdiv{
  display: inline-block;
}

.leftdiv{
  display: inline-block;
  align-content: center;
}
.rightdiv{
  display: inline-block;
  align-content: center;
}

.gendiv{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding-top: 15px;
  background-color:rgb(7, 7, 96);
  border-bottom-width: 1px;
  border-bottom-style: solid; 
  border-bottom-color: black;
  position: fixed;
  top: 100px;
  left: 0;
  right: 0;
}

.welcome-head{
  
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgb(112, 1, 1);
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  height: 100px;
  z-index: 100;
}

.search{
  width: 700px;
  border: 2px solid rgb(167, 165, 165);
  border-radius: 30px;
  padding-top: 15px;
  padding-bottom: 12px;
  padding-left: 8px;
  padding-left: 8px;
  font-size: 18px;
  font-family: cursive;
  display: flex;
  flex-direction: row;
  justify-content: center;
}
nav a{
  display: block;
  padding: 20px 15px;
  text-decoration: none;
  color: rgb(230, 229, 255);
  font-family: cursive;
  transition: background-color 0.15s, opacity 0.15s;
}
nav a:hover{
  background-color: rgb(3, 3, 61);
}
nav a:active{
  opacity: 0.7;
}
header{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  position: fixed;
  top: 80px;
  z-index: 100;
}

.intro-text{
  color: white;
  font-size: 35px;
}



# If anyone could teach me how to commit files to github, I'd be glad
