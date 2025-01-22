<html>
 <head>
   <title>Sensor Data</title>
   <style>
     /* Banner style */
     .navbar {
       overflow: hidden;
       background-color: #333;
     }
     
     .navbar a {
       float: left;
       display: block;
       color: white;
       text-align: center;
       padding: 14px 20px;
       text-decoration: none;
     }
     
     .navbar a:hover {
       background-color: #ddd;
       color: black;
     }
   </style>
 </head>
 <body style="background-color: #F5F5DC;">
   <!-- Navigation Banner -->
   <div class="navbar">
     <a href="/home">Home</a>
     <a href="/about">About</a>
     <a href="/contact">Contact Us</a>
   </div>
   
   <h1>Real-Time Sensor Data</h1>
   <p><strong>Download sensor data as a CSV file:</strong></p>
   <a href="/download" download="sensor_data.csv">
     <button type="button">Download CSV</button>
   </a>
   <p>The CSV contains:</p>
   <ul>
     <li>Air Temperature (C)</li>
     <li>Air Humidity (% RH)</li>
     <li>Soil Moisture (%)</li>
   </ul>
 </body>
</html>
