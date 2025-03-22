# cabot-mcu-index

This page provides a summary table of the firmware for the cabot microcontroller, including the model, bus, type of microcontroller, functionality, and a link to the repository.

<table>
<tr>
  <th>CABOT_MODEL</th>
  <th>Bus</th>
  <th>Micro Controller</th>
  <th>Component</th>
  <th>Code</th>
</tr>
<!-- cabot3-kx -->
<tr>
  <td rowspan="4">
    cabot3-k1<br>
    cabot3-k2<br>
    cabot3-k3<br>
    cabot3-k4<br>
  </td>
  <td rowspan="4">
    CAN
  </td>
  <td>
    ESP32<br>
  </td>
  <td>
    IMU<br>
    Altitude<br>
    WiFi<br>
  </td>
  <td>
    <a href="https://github.com/CMU-cabot/cabot-mcu-kx/tree/main/ais_esp32_sensor_board">cabot-mcu-kx/ais_esp32_sensor_board</a><br>
  </td>
</tr>
<tr>
  <td rowspan="3">
    STM32<br>
  </td>
  <td>
    Temperature<br>
  </td>
  <td>
    <a href="https://github.com/CMU-cabot/cabot-mcu-kx/tree/main/ais_stm32_thermo_board">cabot-mcu-kx/ais_stm32_thermo_board</a><br>
  </td>
</tr>
<tr>
  <td>
    Capacitive Touch<br>
    ToF<br>
    Buttons<br>
    Directional Indicator<br>
  </td>
  <td>
    <a href="https://github.com/CMU-cabot/cabot-mcu-kx/tree/main/ais_stm32_handle_board">cabot-mcu-kx/ais_stm32_handle_board</a><br>
  </td>
</tr>
<tr>
  <td>
    Power<br>
    Fan<br>
  </td>
  <td>
    <a href="https://github.com/CMU-cabot/cabot-mcu-kx/tree/main/ais_stm32_power_board">cabot-mcu-kx/ais_stm32_power_board</a><br>
  </td>
</tr>
<!-- ace -->
<tr>
  <td rowspan="2">
    cabot2-ace<br>
    cabot3-ace2<br>
  </td>
  <td rowspan="2">
    Serial
  </td>
  <td>
    ESP32
  </td>
  <td>
    IMU<br>
    Altitude<br>
    WiFi<br>
    Serial to STM32<br>
  </td>
  <td>
    <a href="https://github.com/CMU-cabot/cabot-arduino-ace">cabot-arduino-ace</a><br>
  </td>
</tr>
<tr>
  <td>
    STM32
  </td>
  <td>
    Capacitive Touch<br>
    Buttons<br>
  </td>
  <td>
    <a href="https://github.com/CMU-cabot/cabot-handle-ace">cabot-handle-ace (TBD)</a><br>
  </td>
</tr>
<!-- prototype 2 -->
<tr>
  <td rowspan="2">
    cabot3-i1<br>
    cabot3-m1<br>
    cabot3-m2<br>
  </td>
  <td rowspan="2">
    Serial
  </td>
  <td>
    ESP32
  </td>
  <td>
    IMU<br>
    Altitude<br>
    WiFi<br>
    Serial to Arduino Nano<br>
  </td>
  <td>
    <a href="https://github.com/CMU-cabot/cabot-arduino-di">cabot-arduino-di</a><br>
  </td>
</tr>
<tr>
  <td>
    Arduino Nano
  </td>
  <td>
    Capacitive Touch<br>
    Buttons<br>
    Directional Indicator<br>
  </td>
  <td>
    <a href="https://github.com/CMU-cabot/cabot-handle">cabot-handle</a><br>
  </td>
</tr>
<!-- prototype 1 -->
<tr>
  <td rowspan="2">
    cabot2-gt1<br>
    cabot2-gtm<br>
    cabot2-gtm-outdoor<br>
    cabot2-gtmx22<br>
    cabot3-gtmx23<br>
    cabot3-s1<br>
  </td>
  <td rowspan="2">
    Serial
  </td>
  <td>
    Arduino Mega
  </td>
  <td>
    IMU<br>
    Altitude<br>
    Capacitive Touch<br>
    Buttons<br>
  </td>
  <td>
    <a href="https://github.com/CMU-cabot/cabot-arduino">cabot-arduino</a>
  </td>
</tr>
<tr>
  <td>
    ESP32
  </td>
  <td>
    WiFi (Optional)
  </td>
  <td>
    <a href="https://github.com/CMU-cabot/cabot-wifi-scan">cabot-wifi-scan</a>
  </td>
</tr>
</table>

