<html>
<head>
  <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0, user-scalable=no\">
  <title>ESP8266 Weather Report</title>
  <style>
    html {
       font-family: Helvetica; display: inline-block; margin: 0px auto;
        text-align: center;
      }
    body{
      margin-top: 50px;
    }
    h1 {
      color: #444444;margin: 50px auto 30px;
    }
    p{
      font-size: 24px;color: #444444;margin-bottom: 10px;
      }
    #button1 {
    background-color: #f44336;
    color: white;
    padding: 25px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    }
    #button2 {
    background-color: #f44336;
    color: white;
    padding: 25px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    }
  </style>
  </head>
  <body>
    <div id=\"webpage\">
      <h1>ESP8266 NodeMCU Weather Report</h1>
      <p>
        Temperature: (int)Temperaturestat°C
      </p>
      <p>
        Humidity: (int)Humiditystat%
      </p>
    <div id="button1">
        <a href="/on">ON</a>
    </div>
    <div id="button2">
        <a href="/off">OFF</a>
    </div>
    </div>
  </body>
</html>
