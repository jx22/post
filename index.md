<head>
	<title>Post</title>
        <link rel="stylesheet" type="text/css"
          href="https://fonts.googleapis.com/css?family=Lato:900">
        <meta charset='utf-8' />
        <meta name='viewport' content='initial-scale=1,maximum-scale=1,user-scalable=no' />
        <script src='https://api.tiles.mapbox.com/mapbox-gl-js/v0.32.1/mapbox-gl.js'></script>
        <link href='https://api.tiles.mapbox.com/mapbox-gl-js/v0.32.1/mapbox-gl.css' rel='stylesheet' />
    <style>
     body { margin:0; padding:0; }
        #map { position:absolute; top:0; bottom:0; width:100%; }
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

<body>
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

<p>More to come!</p>
<p>So stay tuned!</p>
</body>