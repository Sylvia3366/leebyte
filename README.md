# LEEBYTE™
<img width="1688" height="2588" alt="Copy of fallout_zine_template pdf-2" src="https://github.com/user-attachments/assets/985ffba0-0eb9-49ae-b0b4-a6fce2dc5185" />

# What is it?
LEEBYTE is a mischevious tamagotchi pet bunny you can play with, take care of, bully, or put in your pocket and forget about for the next twenty years! It features a 2-axis joystick, three Jureumi themed buttons, and a temperature sensor that will cause LEEBYTE to have different reactions based on your enviornment :)!

# Why did I make it?
I made this project as a start point to my hardware journey! While starting with an odd, rabbit head PCB may not have been the best idea, it challenged me a lot. 

My main motivation after seeing the guide for it on Fallout website was the existing Leebit Tamagotchi (https://kplaceshop.com/products/stray-kids-skzoo-tamagotchi-case-set?variant=51409921999166). It's way out of my budget though, so I thought this would be the perfect chance for me to design one myself, and customize it to my own liking! Additionally, I've been wanting to get into pixel art for a while, and this project let me experiment with drawing so many different expressions and actions.

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
| Name | Qty | Unit | Price (USD) | Total (USD) | Source |
| :--- | :---: | :---: | ---: | ---: | :--- |
| Seeed Studio XIAO ESP32 C3 | 1 | pcs | 8.04 | 8.04 | [Link](https://www.aliexpress.us/item/3256808605622611.html?spm=a2g0o.productlist.main.1.4ef97845qBd5SM&algo_pvid=b096e515-c4b6-4b71-9feb-49b6fa017657&algo_exp_id=b096e515-c4b6-4b71-9feb-49b6fa017657-0&pdp_ext_f=%7B%22order%22%3A%221115%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%217.84%210.99%21%21%217.84%210.99%21%40210328d417815761467148649ed980%2112000052930246748%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Abbfc19f3%3Bm03_new_user%3A-29895%3BpisId%3A5000000207269582&curPageLogUid=sgutw4krVkZt&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008791937363%7C_p_origin_prod%3A) |
| PSP 2-Axis Analog Thumb Joystick | 1 | pcs | 3.50 | 3.50 | [Link](https://www.adafruit.com/product/444?srsltid=AfmBOor8oeFeQEUyqc9zcjpnPBiO4mtjF3cJeVjxOdrs84u4-aMwuCpL) |
| 0.96 inch OLED Display 128x64 | 1 | pcs | 1.87 | 1.87 | [Link](https://www.aliexpress.us/item/2251832337475453.html?src=google&snps=y&src=google&albch=shopping&acnt=708-803-3821&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en2251832337475453&ds_e_product_merchant_id=109329005&ds_e_product_country=US&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=20542171667&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=18545443176&gbraid=0AAAAAD6I-hEGa4vCjbQEz_fnmZhTeNZeX&gclid=CjwKCAjwxb7RBhA5EiwAQ-AAdPo_B4hbtld6DJmm81xFozCqz3pqHQ8PoMJU68SPwU8ek89lr45glRoCSvoQAvD_BwE&gatewayAdapt=glo2usa) |
| Right Angle Slide Switch | 1 | pcs | 1.00 | 1.00 | [Link](https://www.alibaba.com/product-detail/Brand-New-Original-MST-12D18G4-SPDT_1601682630920.html) |
| 4.7k Resistor | 1 | pcs | 0.01 | 0.01 | [Link](https://www.aliexpress.us/item/2251832130817202.html?src=google&src=google&albch=shopping&acnt=708-803-3821&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en2251832130817202&ds_e_product_merchant_id=106279061&ds_e_product_country=US&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=19558607238&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=19566915268&gbraid=0AAAAAD6I-hF4w9uSb_bQ9009LPUlirFTl&gclid=Cj0KCQjw2_TQBhCnARIsAF3-Xhxmx7giF2xi9KZ1WlRf7dR1hDq0ibaBQ5tFXM3J4R8SRctX4AARk-UaAjeEEALw_wcB&gatewayAdapt=glo2usa) |
| Temperature Sensor (DS18B20) | 1 | pcs | 0.95 | 0.95 | [Link](https://aliexpress.us) |
| Piezo Buzzer | 1 | pcs | 0.50 | 0.50 | [Link](https://www.aliexpress.us/item/3256810135642750.html) |
| Tactile Switch | 3 | pcs | 2.26 | 6.78 | [Link](https://www.aliexpress.us/item/3256807067168626.html?spm=a2g0o.productlist.main.1.7f9258c1KLjAOZ&algo_pvid=490cc209-ccc0-4654-88ac-e48f4b2323b9&algo_exp_id=490cc209-ccc0-4654-88ac-e48f4b2323b9-0&pdp_ext_f=%7B%22order%22%3A%2210%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%212.03%211.99%21%21%2113.63%2113.33%21%4021032f3717815770777272760ec945%2112000039957446262%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3Aac76d4c5%3Bm03_new_user%3A-29895&curPageLogUid=etrecQES0Uun&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007253483378%7C_p_origin_prod%3A&_gl=1*g854wd*_gcl_au*MTkyMDAzNTI3LjE3ODE1NzYxNDk.*_ga*MTI3MjExODYxMC4xNzgxNTc3MDgw*_ga_VED1YSGNC7*czE3ODE1NzcwODAkbzEkZzAkdDE3ODE1NzcwODAkajYwJGwwJGgw) |
| M1.6 5mm Screws | 7 | pcs | 0.03 | 0.21 | [Link](https://www.aliexpress.us/item/2251832785290389.html?src=google&snps=y&src=google&albch=shopping&acnt=708-803-3821&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en2251832785290389&ds_e_product_merchant_id=107792874&ds_e_product_country=US&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=20542171667&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=18545443176&gbraid=0AAAAAD6I-hEGa4vCjbQEz_fnmZhTeNZeX&gclid=CjwKCAjwxb7RBhA5EiwAQ-AAdHrgWosxNOZRkccANcNKR7vt21WIStiqv9YQWGaLNnBF2wXj5XR0PBoCLDAQAvD_BwE&gatewayAdapt=glo2usa) |
| M3 8mm Screws | 3 | pcs | 0.04 | 0.13 | [Link](https://www.aliexpress.us/item/2251832785290389.html?src=google&snps=y&src=google&albch=shopping&acnt=708-803-3821&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en2251832785290389&ds_e_product_merchant_id=107792874&ds_e_product_country=US&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=20542171667&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=18545443176&gbraid=0AAAAAD6I-hEGa4vCjbQEz_fnmZhTeNZeX&gclid=CjwKCAjwxb7RBhA5EiwAQ-AAdHrgWosxNOZRkccANcNKR7vt21WIStiqv9YQWGaLNnBF2wXj5XR0PBoCLDAQAvD_BwE&gatewayAdapt=glo2usa) |
| M2 5mm Standoff | 2 | pcs | 0.15 | 0.30 | [Link](https://www.aliexpress.us/item/3256804631738035.html?spm=a2g0o.productlist.main.3.27df7FLe7FLecQ&algo_pvid=a1cec274-0704-4a88-9dbf-f241cd892cef&algo_exp_id=a1cec274-0704-4a88-9dbf-f241cd892cef-2&pdp_ext_f=%7B%22order%22%3A%221094%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%212.82%210.99%21%21%2118.99%216.65%21%40210328c017815809013504491eae18%2112000030604050905%21sea%21US%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A77172365%3Bm03_new_user%3A-29895%3BpisId%3A5000000207269582&curPageLogUid=MSKdAPBWv7wd&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005004818052787%7C_p_origin_prod%3A) |
| M2 Hex Nut | 2 | pcs | 0.07 | 0.14 | [Link](https://www.aliexpress.us/item/3256806284464354.html?src=google&snps=y&src=google&albch=shopping&acnt=708-803-3821&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en3256806284464354&ds_e_product_merchant_id=5387743504&ds_e_product_country=US&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=20542171667&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=18545443176&gbraid=0AAAAAD6I-hEGa4vCjbQEz_fnmZhTeNZeX&gclid=CjwKCAjwxb7RBhA5EiwAQ-AAdD-HXltEgTpntjXNdXBa80Wk7a0wUIqDG94LwPP-CMFiyOFLLrmMeBoC3qQQAvD_BwE&gatewayAdapt=glo2usa) |
| Battery | 1 | pcs | 6.19 | 6.19 | [Link](https://www.aliexpress.us/item/3256808658204287.html?src=google&src=google&albch=shopping&acnt=708-803-3821&isdl=y&slnk=&plac=&mtctp=&albbt=Google_7_shopping&aff_platform=google&aff_short_key=UneMJZVf&gclsrc=aw.ds&albagn=888888&ds_e_adid=&ds_e_matchtype=&ds_e_device=c&ds_e_network=x&ds_e_product_group_id=&ds_e_product_id=en3256808658204287&ds_e_product_merchant_id=5400930617&ds_e_product_country=US&ds_e_product_language=en&ds_e_product_channel=online&ds_e_product_store_id=&ds_url_v=2&albcp=20269108796&albag=&isSmbAutoCall=false&needSmbHouyi=false&gad_source=1&gad_campaignid=20273564092&gbraid=0AAAAAD6I-hFVND5kqPKAMyRJSA8DM1GwA&gclid=CjwKCAjwxb7RBhA5EiwAQ-AAdCwQ6QvxVImRKQUVZZYXdy-omDGe5HRKqs4brvn1Da7SUtQTNn7_DxoCEwsQAvD_BwE&gateway) |
| PLA 3D Printed Case | 1 | pcs | - | - | 
| **Total** | **25** | **-** | **-** | **29.62** | **-** |

# Build & Assembly
Required Tools
-
> Solder
> Soldering iron
> Tweezers
> Screwdriver for M3/M2/M1.6 screws
> Computer w. a USB port
> 3D printer

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
