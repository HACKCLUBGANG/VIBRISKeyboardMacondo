# VIBRISKeyboardMacondo 

Hi! This is VIBRIS Keyboard I made for YSWS Macondo In Hackclub.
So the VIBRIS Keyboard is a 60% keyboard that is compact and FULLY HANDWIRED!
I made this project to learn more about cad and soldering!
I will also be gifting this keyboard to my sister!
<img width="1080" height="1350" alt="Pink and Purple Modern New Product Instagram Post" src="https://github.com/user-attachments/assets/4b4d0cdf-f99e-4022-9878-560e6c11aa71" />
So Basically This keyboard is ran by qmk firmware and It uses a rp2040 Microchip the devboard is named RP2040-ZERO a compact development board with alot of GPIO pins to connect the keyboard columns and rows to.

## CAD
Source Link Onshape - https://cad.onshape.com/documents/ce0877fe3fbc02251fe6ba09/w/a497414719130e804db706af/e/002c5fa22ab6ceef532ed83b?renderMode=0&leftPanel=false&uiState=6a1fc2ac9539fb6e97131235
FULLY ASSEMBLED KEYBOARD
<img width="745" height="401" alt="image" src="https://github.com/user-attachments/assets/a4a1d375-b695-49d8-b60a-2d05fb35b990" /> | <img width="949" height="196" alt="image" src="https://github.com/user-attachments/assets/f355acf8-e408-4bd4-ad35-992f955fdfdb" />

<img width="397" height="238" alt="image" src="https://github.com/user-attachments/assets/025bf3b6-2e2d-455f-bd99-1c4f461e4afc" />

TOP PLATE
<img width="893" height="382" alt="image" src="https://github.com/user-attachments/assets/bfece9c4-67b7-4901-8bd8-25fd28f5a4eb" />

BOTTOM PLATE
<img width="971" height="412" alt="image" src="https://github.com/user-attachments/assets/dbc25e57-0106-4f36-a3ac-60fd8502bdf2" />


## SCHEMATICS
You can find the schematics that i made in kicad in the schematics folder
You have to connect is like the pictures given below
<img width="832" height="576" alt="{E519D9AD-38AF-4175-8E73-E21F404571FA}" src="https://github.com/user-attachments/assets/9c35e5a3-6420-4999-a6e4-1bc269d2e733" />
<img width="1274" height="567" alt="{00A3D660-7E08-496A-902B-38DFA6FA57E7}" src="https://github.com/user-attachments/assets/48efdd68-4191-4a9c-9466-7bcaf3b5ab59" />



## ASSEMBLY.

After buying all of the parts you have to follow this tutorial to assemble it.

First you have to print the bottom and top plate given in the CAD Folder after printing take the top plate and the cherry mx switches.

Add the white led to each switch like this
<img width="305" height="313" alt="image" src="https://github.com/user-attachments/assets/6fa88bc8-7897-414e-ba8f-aed26cf6e2a6" />
<img width="316" height="440" alt="image" src="https://github.com/user-attachments/assets/aa88fec6-16a5-481e-80a7-218ec94e00c8" />

And you have to insert each one like this.

<img width="1117" height="405" alt="image" src="https://github.com/user-attachments/assets/bd828761-a51b-4cc5-834f-863062fea708" />

You have to put each key in their slot 

then you have to connect each key like this 

<img width="976" height="361" alt="image" src="https://github.com/user-attachments/assets/be9fec4e-6a39-40ec-867f-25171155071f" />

you have to use diodes too to prevent issues.

Then you have to connect all of these wires 

After that you will have to solder those wires to the rp2040 zero 

You can check how the wires will be connected to rp2040-zero in the schematics section in this readme.

After that you have to upload the firmware given in the firmware folder

To upload the firmware you have to put the rp2040 zero into boot mode so that u can upload the firmware

To put it into boot mode you have to Hold the BOOT button on the rp2040 zero board

Then you have to open file manager in your pc/laptop (AFTER CONNECTING THE BOARD TO PC/LAPTOP AND IT HAS TO BE IN BOOT MODE)

Then drag the firmware file into the new disk that appeared

Then you can go to any keyboard testing website and test your keyboard.

Then after testing you can use your soldering iron to heat the inserts into the holes that were printed in the bottom plate heres a pic 
<img width="890" height="338" alt="image" src="https://github.com/user-attachments/assets/d2addea3-8629-4421-9df3-400bcf148ebe" />
Stick you rp2040 zero using double sided tape under the board and stick to the top left side of the bottom board (KEEP THE WIRES LONG)
Then You Have to allign the top plate and use the m2x8mm screws to lock the top n bottom plates in place.
And Add the keycaps as you want and you're ready to GO!

Congratulations You have Just Built A 60% Hand Wired Keyboard

## Firmware

# 61-Key Handwired Keyboard BOM

| Component | Required Qty | Purchase Qty | Cost (INR) | Cost (USD) | Links |
|---|---:|---:|---:|---:|---:|
| RP2040-Zero | 1 | 1 | ₹235.00 | $2.47 | https://robu.in/product/rp2040-zero-for-raspberry-pi-microcontroller-with-soldering/ |
| Gateron Milky PRO Yellow 5-pin Switches | 61 | 70 | ₹1,323.35 | $13.91 | https://meckeys.com/shop/accessories/keyboard-accessories/key-switches/gateron-mechanical-pro-switch-5pin/ |
| Chainsaw Reze Keycap Set | 1 | 1 | ₹1,720.00 | $18.08 | https://meckeys.com/shop/accessories/keyboard-accessories/keycaps/valorant-full-keycap-set/ |
| 1N4148TA Diodes | 61 | 70 | ₹99.40 | $1.04 | https://robu.in/product/1n4148-t50a-onsemi-100v-1v10ma-4ns-200ma-do-35-switching-diodes-rohs/ |
| TLC5948APWPR 16-Channel LED Driver | 4 | 4 | ₹1,144.00 | $12.02 | https://robu.in/product/tlc5948apwpr-texas-instruments-10v-16-60ma-3v5-5v-tssop-24-ep-led-drivers-rohs/ |
| 18 kΩ MF25 Resistor | 4 | 6 | ₹10.08 | $0.11 | https://robu.in/product/mf25-18k-multicomp-pro-through-hole-resistor-18-kohm-mf25-series-250-mw-%c2%b1-1-axial-leaded-250-v/ |
| 100 nF 50V Ceramic Capacitor | 4 | 9 | ₹10.98 | $0.12 | https://robu.in/product/100nf-50v-disc-capacitor/ |
| 3 mm Bright White LEDs | 61 | 100 | ₹209.00 | $2.20 | https://www.amazon.in/Electronic-Spices-Basic-White-Round |
| Cherry MX 2U Plate-Mount Stabilizers | 5 | 5 | ₹500.00 | $5.26 | https://stackskb.com/store/genuine-cherry-mx-plate-mount-stabilizers-2u/ |
| 24 AWG Solid-Core PVC Wire | ~7 m | 7 m | ₹70.00 | $0.74 | https://robu.in/product/24-awg-solid-core-insulated-wire-pvc/ |
| Krytox GPL 205g0 | — | 1 g | ₹120.00 | $1.26 | https://stackskb.com/store/molykote-em50l-lubricant-5g/ |
| M2 × 8 mm SS304 Screws | 16 | 16 | ₹57.60 | $0.61 | OnlyScrews |
| M2 × 6 mm Brass Threaded Inserts | 16 | 16 | ₹38.40 | $0.40 | OnlyScrews | 
| 3D-Printed Case + Plate | — | 1 | - | homemade | hpmemade |
| **Total** | | | **₹5,576.81** | **~$58.63** |

