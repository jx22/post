<head>
	<title>Post</title>
        <link rel="stylesheet" type="text/css"
          href="https://fonts.googleapis.com/css?family=Lato:900">
        <meta charset='utf-8' />
        <meta name='viewport' content='initial-scale=1,maximum-scale=1,user-scalable=no' />

  
  <script src="https://www.gstatic.com/firebasejs/3.7.5/firebase.js"></script>
        <script>
          // Initialize Firebase
          var config = {
            apiKey: "AIzaSyDnBjPeImep36ck5POjfbOtVZedgbuYQ14",
            authDomain: "post-84657.firebaseapp.com",
            databaseURL: "https://post-84657.firebaseio.com",
            projectId: "post-84657",
            storageBucket: "post-84657.appspot.com",
            messagingSenderId: "65912592248"
          };
          firebase.initializeApp(config);
          // Get a reference to the database service
          var database = firebase.database();

        </script>

  <script src="https://www.gstatic.com/firebasejs/3.7.4/firebase-app.js"></script>
  <script src="https://www.gstatic.com/firebasejs/3.7.4/firebase-auth.js"></script>
  <script src="https://www.gstatic.com/firebasejs/3.7.4/firebase-database.js"></script>
  <script src="https://www.gstatic.com/firebasejs/3.7.4/firebase-messaging.js"></script>

  <!-- Leave out Storage -->
  <!-- <script src="https://www.gstatic.com/firebasejs/3.7.4/firebase-storage.js"></script> -->

  <script>
    var config = {
     // ...
    };
    firebase.initializeApp(config);
  </script>


 <!-- Firebase -->
  <script src="https://www.gstatic.com/firebasejs/3.3.0/firebase.js"></script>

  <!-- CodeMirror -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/codemirror/5.17.0/codemirror.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/codemirror/5.17.0/codemirror.css"/>



  <script src='https://api.tiles.mapbox.com/mapbox-gl-js/v0.32.1/mapbox-gl.js'></script>
        <link href='https://api.tiles.mapbox.com/mapbox-gl-js/v0.32.1/mapbox-gl.css' rel='stylesheet' />
    <style>
     body { margin:90; padding:40; }
        #map { position:absolute; top:20; bottom:50; width:100%; }
      h1 {
        font-family: 'Lato', sans-serif;
        font-size: 48px;
        color: blue;
      }
     body {
        font-family: 'Lato', sans-serif;
        font-size: 24px;
        background: #373738;
      }
    </style>
</head>

<body onload="init()">
  <div id="firepad"></div>
  <script>
    function init() {
      // Initialize the Firebase SDK.
      firebase.initializeApp({
        apiKey: 'AIzaSyDnBjPeImep36ck5POjfbOtVZedgbuYQ14',
        databaseURL: 'https://post-84657.firebaseio.com'
      });

      // Get Firebase Database reference.
      var firepadRef = firebase.database().ref();

      // Create CodeMirror (with lineWrapping on).
      var codeMirror = CodeMirror(document.getElementById('firepad'), { lineWrapping: true });

      // Create Firepad (with rich text toolbar and shortcuts enabled).
      var firepad = Firepad.fromCodeMirror(firepadRef, codeMirror,
          { richTextShortcuts: true, richTextToolbar: true, defaultText: 'Hello, World!' });
    }
  </script>

<p></p>
<h1>POST</h1>

<div id='map' style='width: 400px; height: 300px;'></div>
<script>
mapboxgl.accessToken = 'pk.eyJ1Ijoianh4IiwiYSI6IjUxNWVmNGYzZGRmOTU1ZjEwY2JkMzVlNTg1MGI5OWY5In0.JoebSQedSPap-0FYAQ00wg';
var map = new mapboxgl.Map({
    container: 'map', // container id
    style: 'mapbox://styles/jxx/ciz26caqr00182rq7roymuruh', //stylesheet location
    center: [126.947,37.544], // starting position
    zoom: 9.9 // starting zoom
});
</script>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p>So stay tuned!</p>
</body>