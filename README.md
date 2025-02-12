# NORA MINI 🚀

 ## 📢 _**COLD STORGE CONTROLLER**_

This work focuses on the design of a control board and peripheral components tailored to 
meet the demands of industrial _**cold storage facilities**_. The primary goal of the design process 
is to develop a functional and reliable system suitable for active use in such environments. As 
part of this effort, the hardware design of the control board has been finalized, and its 
software integration has been successfully completed.

![image](https://github.com/user-attachments/assets/5c32fabf-740f-4aa5-99a2-0ea9da2395a6)


![alt text](https://github.com/alihancakir/COLD-STORGE-CONTROLLER/blob/main/PCB.jpg?raw=true)

##  🔶 FEATURES


| VOLTAGE SUPPLY |
| ------------- |
|  24V-5V , 5V-3.3V  (DC-DC) |


| PERIPERHAL UNITS |
| ------------- |
| 1-PWM INPUT (ISOLATED) | 
| 1-NTC10K INPUT (ISOLATED) | 
| 1-RTC INPUT  (EXTERNAL) | 
| 1-HUMIDITY SENSOR INPUT (ISOLATED) |
| 1-CURRENT READER (ISOLATED)| 
| 1-24V RELAY (ISOLATED) | 

| UI |
| ------------- |
|  I2C OLED SSD1106 |

| MICROCONTROLLER|
| ------------- |
|  ESP32U -WROOM |

| PROGRAMMER|
| ------------- |
|  CH340G |


##  🔶 SOFTWARE

![image](https://github.com/user-attachments/assets/a9008b2e-1204-4461-92ed-9eabfd5b06cd)

I developed this project using ESPRESSIF-IDF. Throughout the coding process, I actively utilized **_sdkconfig_** to ensure optimal configuration. Implementing FreeRTOS was a valuable experience, as it helped manage multiple tasks efficiently and reduce processing load. -There isn't u8g2 lib in software file. 

For now, the code structure will remain as it is. In future projects, I plan to focus more on data control and management.

You can find a more detailed Turkish report of this project:  https://github.com/alihancakir/COLD-STORGE-CONTROLLER/blob/main/NORA_MINI_REPORT.pdf 


