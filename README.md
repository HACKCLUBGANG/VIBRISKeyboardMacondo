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
<img width="745" height="401" alt="image" src="https://github.com/user-attachments/assets/a4a1d375-b695-49d8-b60a-2d05fb35b990" />
<img width="949" height="196" alt="image" src="https://github.com/user-attachments/assets/f355acf8-e408-4bd4-ad35-992f955fdfdb" />
<img width="397" height="238" alt="image" src="https://github.com/user-attachments/assets/025bf3b6-2e2d-455f-bd99-1c4f461e4afc" />

TOP PLATE
<img width="893" height="382" alt="image" src="https://github.com/user-attachments/assets/bfece9c4-67b7-4901-8bd8-25fd28f5a4eb" />

BOTTOM PLATE
<img width="971" height="412" alt="image" src="https://github.com/user-attachments/assets/dbc25e57-0106-4f36-a3ac-60fd8502bdf2" />


## SCHEMATICS
You can find the schematics that i made in kicad in the schematics folder
You have to connect is like the pictures given below
<img width="1265" height="508" alt="image" src="https://github.com/user-attachments/assets/c692b87b-6e10-492d-b80c-dca89481c19d" />
<img width="474" height="454" alt="image" src="https://github.com/user-attachments/assets/8cfcb84c-299c-4389-a3f5-d4ac81f0f400" />


## ASSEMBLY.

After buying all of the parts you have to follow this tutorial to assemble it.

First you have to print the bottom and top plate given in the CAD Folder after printing take the top plate and the cherry mx switches.

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

# BOM

| Component | Required Qty | Purchase Qty | Cost (INR) | Cost (USD) | Link |
|---|---:|---:|---:|---:|---|
| RP2040-Zero MCU | 1 | 1 | ₹235.00 | $2.47 | [Robu](https://robu.in/) |
| Gateron G Pro 3.0 Red Switch | 61 | 7 Packs | ₹1,393.00 | $14.66 | Meckeys |
| Contour Side Printed Keycap Set | 1 | 1 | ₹799.00 | $8.41 | Meckeys |
| Genuine Cherry MX Plate Mount Stabilizers | 5 Sets | 5 Sets | ₹500.00 | $5.28 | StacksKB |
| 1N4148 Diodes | 70 | 70 | ₹86.80 | $0.91 | Robu |
| 28 AWG Enamelled Copper Wire | 1 | 1 | ₹299.00 | $3.15 | — |
| Heat Shrink Tube | 1 | 1 | ₹225.00 | $2.36 | Amazon |
| 5mm White/Blue LEDs | 70 | 70 | ₹98.00 | $1.03 | [Robocraze](https://robocraze.com/products/5mm-white-blue-led-pack-of-10?variant=40192389120153) |
| 220 Ω 0.25W Metal Film Resistor | 70 | 70 | ₹42.70 | $0.45 | [Robu](https://robu.in/product/220-ohm-0-25w-metal-film-resistor/) |
| AO3400-HXY N-Channel MOSFET | 1 | 3 | ₹12.27 | $0.13 | [Robu](https://robu.in/product/ao3400-hxy-mosfet-30v-5-8a-30m%CF%89-10v-5-8a-1-4w-700mv-1-n-channel-sot-23-mosfets-rohs/) |
| 100 Ω 1/4W 0603 Resistor | 1 | 18 | ₹10.08 | $0.11 | [Robu](https://robu.in/product/100-ohm-chip-resistor-1-4w-0603-surface-mount/) |
| 100 kΩ 1/4W 1206 Resistor | 1 | 14 | ₹10.22 | $0.11 | [Robu](https://robu.in/product/100k-ohm-1-4w-1206-surface-mount-chip-resistor/) |
| M2 × 8 mm SS304 Hex Button-Head Screws | 16 | 16 | ₹76.80 | $0.80 | OnlyScrews |
| M2 × 6 mm Brass Threaded Inserts | 16 | 16 | ₹38.40 | $0.40 | OnlyScrews |
| 3D Printed Parts | — | — | ₹0 | $0 | DIY |
| Shipping & Taxes | — | — | ₹250.00 | $2.62 | — |
| **TOTAL** | | | **₹4,076.27** | **~$42.64** | |

## Cart Pic

# Amazon
<img width="1000" height="498" alt="{318C8C84-536D-47A5-962B-B79CDD735C04}" src="https://github.com/user-attachments/assets/175557c7-3240-4925-a1f5-3093e9ace8b0" />

# Robu
<img width="1087" height="657" alt="image" src="https://github.com/user-attachments/assets/0fd974db-2871-42f7-8fec-35be0d1a0e06" />

# STACKSKB
<img width="1319" height="612" alt="image" src="https://github.com/user-attachments/assets/80463bcc-1102-456c-a2de-89daf728b8ba" />





