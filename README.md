<h1>Aces</h1>

<h2>What is it?</h2>

<ol>
  <li>Get your most liked Facebook posts all in a responsive, Pinterest style grid layout :)</li>
  <li>Filter your posts</li>
</ol>

<h2>Desktop</h2>
![alt tag](https://github.com/Nikhil22/aces/blob/master/public/img/reel.png)

<h2>Mobile</h2>
![alt tag](https://github.com/Nikhil22/aces/blob/master/public/img/reelmobile.png)

<h2>How to use</h2>

<ol>
  <li>Clone this repo</li> <br>
  <li>cd into aces. 'cd aces'</li> <br>
  <li>'npm install'</li> <br>

  <li>Important! Make sure you have a Facebook App ID. <br> If you don't, visit https://developers.facebook.com.</li> <br>

  <li>
  Once you have your App ID, head over to public/js/fb-magic.js <br>

  Modify the following piece of code: <br> <br>

  <strong>FB.init({<br>
    appId      : 'Your APP ID here',<br>
    cookie     : true,  // enable cookies to allow the server to access<br>
                        // the session<br>
    xfbml      : true,  // parse social plugins on this page<br>
    version    : 'v2.2' // use version 2.2
  });</strong> <br> <br>
  </li>

   <li>
    Have 2 Terminal tabs open <br>
    In the first tab, run 'npm start' <br>
    In the second tab, run 'nodemon server.js'
   </li> <br>

   <li>Head over to 'http://localhost:8000/fb_login'</li> <br>
   <li>Click 'Login'</li> <br>
   <li>Grab a drink, sit back, and watch as your most liked Facebook posts fill your screen</li>
 </ol>

<h2>Technologies used</h2>

<ol>
  <li>NodeJS</li>
  <li>ReactJS</li>
  <li>ExpressJS</li>
  <li>Facebook Graph API</li>
  <li>Twitter Bootstrap</li>
  <li>SemanticUI</li>
</ol>
