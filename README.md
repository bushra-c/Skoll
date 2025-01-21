<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link href="css/styles.css" rel="stylesheet">
    <title>Skoll</title>
  </head>
 
String webpage = R"rawliteral(
<!DOCTYPE html>
<html>
 <head>
   <title>Sensor Data</title>
 </head>
 <body style="background-color: #EEEEEE;">
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
)rawliteral";


