<head>
	<title>Submissions</title>
        <link rel="stylesheet" type="text/css"
          href="https://fonts.googleapis.com/css?family=Lato:900">
        <meta charset='utf-8' />
        <meta name='viewport' content='initial-scale=1,maximum-scale=1,user-scalable=no' />
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

<p></p>
<h1>Submissions</h1>
<br>

<p>Please enter your preferred flight for your trip, along with your contact information. A representative will reach you to confirm your reservations.</p>

<br>

<div class="mainDiv" align="center">
    <textarea id="mainText" rows="5" cols="100" placeholder="Enter text here" autofocus></textarea>
    <input id="submitBtn" onclick="submitClick()" type="submit" value="Submit">
</div>


<script src="https://www.gstatic.com/firebasejs/3.8.0/firebase.js"></script>
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
</script>

<script src="index.js"></script>

<p></p>

<!-- via https://www.youtube.com/watch?v=F6UWb9FNnj4 -->