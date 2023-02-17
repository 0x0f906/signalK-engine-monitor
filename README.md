<h1>signalk-engine-monitor</h1>
<p>SignalK engine monitor utilizing a SH-ESP32 with the code being mostly based off examples provided by <a href="https://github.com/hatlabs">@hatlabs</a>.</p>

This project connects to a SignalK server via WiFi and does not send NEMA-2000 data over a NEMA backbone. 

<p><strong>Working:</strong> 
<ul>
  <li>03 Temperature sensors
    <ul>
      <li>oil</li>
      <li>coolant</li>
      <li>exhaust</li>
    </ul>
  </li>
  <li>RPM off "W" post on alternator</li>
</ul></p>
<p><strong>In progress:</strong> Oil pressure</p>
<p>Uses the following components:</p>
<ul>
   <li>SH-ESP32 Board</li>
   <li>SH-ESP32 Engine Top Hat</li>
   <li>I2C OLED Display - SSD1306</li>
   <li>1-Wire temperature sensor</li>
  </li>
</ul>
<p><a href="https://docs.hatlabs.fi/sh-esp32/">https://docs.hatlabs.fi/sh-esp32/</a></p>
<p><a href="https://github.com/hatlabs">https://github.com/hatlabs</a></p>
