# LEEBYTE™
<img width="1688" height="2588" alt="Copy of fallout_zine_template pdf-2" src="https://github.com/user-attachments/assets/985ffba0-0eb9-49ae-b0b4-a6fce2dc5185" />


[ONSHAPE CAD](https://cad.onshape.com/documents/775b1919785149165ef0f27a/w/a0b05a09ec9f946b8b8a4a30/e/c002d06697f726d420ef8c8a?renderMode=0&uiState=6a315a62f65bd0542a2cae44)
-

# What is it?
LEEBYTE is a mischevious tamagotchi pet bunny you can play with, take care of, bully, or put in your pocket and forget about for the next twenty years! It features a 2-axis joystick, three Jureumi themed buttons, and a temperature sensor that will cause LEEBYTE to have different reactions based on your enviornment :)!

# Why did I make it?
I made this project as a start point to my hardware journey! While starting with an odd, rabbit head PCB may not have been the best idea, it challenged me a lot. 

My main motivation after seeing the guide for it on Fallout website was the existing Leebit Tamagotchi [(See here!)](https://kplaceshop.com/products/stray-kids-skzoo-tamagotchi-case-set?variant=51409921999166). It's way out of my budget though, so I thought this would be the perfect chance for me to design one myself, and customize it to my own liking! Additionally, I've been wanting to get into pixel art for a while, and this project let me experiment with drawing so many different expressions and actions.

# How does it work?
LEEBYTE is unlike the usual 3-button tamagotchi pet; he can move! Using the joystick, you can take LEEBYTE on adventures and perhaps, you'll even find some cool treasures along the way... 

Like most tamagotchi, LEEBYTE also comes with 3 Jureumi themed buttons that can be pressed to feed him, play with him, or put him to sleep. Pressing two buttons at once can have some effect too :). When playing with LEEBYTE, he enjoys hula hooping, jump roping, or (if he's in the mood) you can even play a short game of some good ol' Tic-Tac-Toe. 

He's also able to detect the temperature of your enviornment. Make sure you keep him warm during the freezing winters and next to a blasting AC during the blazing summers! Otherwise, LEEBYTE might leave you...

# Designing the PCB
PCB designed on KiCad!
-
<img width="929" height="579" alt="Screenshot 2026-06-15 at 11 00 14 PM" src="https://github.com/user-attachments/assets/22d3f011-677a-4503-b00d-544582e21f7b" />
<img width="564" height="592" alt="Screenshot 2026-06-15 at 11 01 25 PM" src="https://github.com/user-attachments/assets/470217ae-35f3-457c-b520-f36e1fb2d385" />
<img width="562" height="596" alt="Screenshot 2026-06-15 at 11 01 33 PM" src="https://github.com/user-attachments/assets/33dee868-597d-4470-8a43-6c81031af0dd" />
<img width="539" height="602" alt="Screenshot 2026-06-14 at 1 18 59 AM" src="https://github.com/user-attachments/assets/d2908d15-2d91-4a8b-b7da-95c01c5fc073" />

Case designed and assembled on OnShape!
-
<img width="598" height="549" alt="Screenshot 2026-06-12 at 10 08 50 PM" src="https://github.com/user-attachments/assets/173c528e-c853-4b22-b6ae-635f68a4c077" />
<img width="593" height="695" alt="Screenshot 2026-06-13 at 9 16 08 PM" src="https://github.com/user-attachments/assets/70cb6942-b8a4-4d76-bf2e-bf2a1fe6684a" />
<img width="760" height="690" alt="Screenshot 2026-06-13 at 9 18 49 PM" src="https://github.com/user-attachments/assets/6995118d-7bc2-4b39-84a8-f4eff1f63e3e" />
<img width="535" height="482" alt="Screenshot 2026-06-13 at 9 18 21 PM" src="https://github.com/user-attachments/assets/502d1ac1-4356-4adc-aa19-d786f19dcc80" />

Rendered on Fusion360!
-
<img width="648" height="548" alt="Screenshot 2026-06-14 at 8 44 53 PM" src="https://github.com/user-attachments/assets/5b00ce67-0c30-4432-af8d-e49daf8c099a" />
<img width="581" height="510" alt="leebyte_render" src="https://github.com/user-attachments/assets/369f8783-041a-4c99-9e1e-8ba40732102f" />

# Bill of Materials
| Name | Qty | Unit | Price (USD) | Total (USD) | MOQ | MOQ Price (USD) | Source |
| :--- | :---: | :---: | ---: | ---: | ---: | ---: | :--- |
| Seeed Studio XIAO ESP32 C3 | 1 | pcs | 11.14 | 11.14 | 1 | 11.14 | [Link](https://www.aliexpress.us/item/3256808047100037.html) |
| PSP 2-Axis Analog Thumb Joystick | 1 | pcs | 3.50 | 3.50 | 1 | 3.50 | [Link](https://www.adafruit.com/product/444) |
| 0.96 inch OLED Display 128x64 | 1 | pcs | 1.91 | 1.91 | 1 | 1.91 | [Link](https://www.aliexpress.us/item/2251832337475453.html) |
| Right Angle Slide Switch | 1 | pcs | 1.00 | 1.00 | 1 | 1.00 | [Link](https://www.alibaba.com/product-detail/Brand-New-Original-MST-12D18G4-SPDT_1601682630920.html) |
| 4.7k Resistor | 1 | pcs | 0.01 | 0.01 | 100 | 1.47 | [Link](https://www.aliexpress.us/item/2251832130817202.html) |
| Temperature Sensor (DS18B20) | 1 | pcs | 0.48 | 0.48 | 5 | 2.42 | [Link](https://www.aliexpress.us/item/3256808767131467.html) |
| Piezo Buzzer | 1 | pcs | 0.50 | 0.50 | 10 | 5.02 | [Link](https://www.aliexpress.us/item/3256810135642750.html) |
| Tactile Switch | 3 | pcs | 0.23 | 0.68 | 10 | 2.25 | [Link](https://www.aliexpress.us/item/3256807067168626.html) |
| M1.6 5mm Screws | 7 | pcs | 0.03 | 0.21 | 50 | 1.56 | [Link](https://www.aliexpress.us/item/2251832785290389.html) |
| M3 8mm Screws | 3 | pcs | 0.04 | 0.13 | 50 | 2.09 | [Link](https://www.aliexpress.us/item/2251832785290389.html) |
| M2 5mm Standoff | 2 | pcs | 0.15 | 0.30 | 20 | 2.94 | [Link](https://www.aliexpress.us/item/3256804631738035.html) |
| M2 Hex Nut | 2 | pcs | 0.07 | 0.14 | 50 | 3.38 | [Link](https://www.aliexpress.us/item/3256806284464354.html) |
| Battery | 1 | pcs | 5.16 | 5.16 | 1 | 5.16 | [Link](https://www.aliexpress.us/item/3256808658204287.html) |
| PCB | 1 | pcs | 0.40 | 0.40 | 5 | 2.00 | [Link](https://jlcpcb.com) |
| PLA 3D Printed Case | 1 | pcs | - | - | - | - | - |
| **Total** | **27** | **-** | **-** | **25.56** | **-** | **45.84** | **-** |

# Build & Assembly
Required Tools
-
1. Solder
2. Soldering iron
3. Tweezers
4. Screwdriver for M3/M2/M1.6 screws
5. Computer w. a USB port
6. 3D printer

Assembly
-
1. Solder all parts onto the PCB.
2. Secure the button caps onto the tact switches.
3. Secure the joystick with 2 M2 5mm screws, M2 standoffs, and M2 hex nuts.
4. Place the battery in the open part below the bottom case.
5. Place PCB into the bottom case and wire to battery.
6. Secure the PCB with 3 M3 screws.
7. Place the top case over the bottom and secure with the M1.6 screws.
8. Use Arduino IDE for the firmware.
9. Connect the ESP32 to your computer via USB-C to upload code.
10. Upload firmware.
11. Test the OLED display and test the joystick inputs.
