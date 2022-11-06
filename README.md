# CPLD-Bug

This mini project was inspired by a post that I read by Bill Herd over on Hackaday [Link](https://hackaday.com/2016/02/04/a-better-way-to-plug-a-cpld-into-a-breadboard/)

It is essentially a DIP-40 spaced CPLD board featuring an Altera EPM7064SLC44-10 CPLD (Part of the MAX 7000 family) which consists of 1250 usable gates and 64 macro cells and works on 5v.

This board breaks out 28 I/O pins and features a 25MHz oscilator, power led, 0805 passive components and a JTAG connector for programming.

Programming is done with the standard Altera USB Blaster

## Parts:
Oscillator can be found [Here](https://lcsc.com/product-detail/Oscillators_Shenzhen-SCTF-Elec-S7D25-000000A20F30T_C387028.html) from LCSC.com

USB Blaster can be bought cheaply from Ebay or Aliexpress, just search for "Altera USB Blaster) - [Example](https://www.aliexpress.com/item/1005002252748935.html?spm=a2g0o.productlist.0.0.119c3a7cvtNqnZ&algo_pvid=d0c171bd-3eed-42db-bdbb-d8fbd28dad4a&algo_exp_id=d0c171bd-3eed-42db-bdbb-d8fbd28dad4a-14&pdp_ext_f=%7B%22sku_id%22%3A%2212000019659224352%22%7D&pdp_npi=2%40dis%21GBP%213.44%212.03%21%21%211.92%21%21%402100bdd516677786996293070ec750%2112000019659224352%21sea&curPageLogUid=pfJKLvQGYS9V)

The rest of the parts are pretty standard and can be purchased from LCSC, Digikey, Ebay etc.

## PCB:
Gerbers for the PCB are included, these were created using Easy EDA.  I purchased my boards from JLCPCB.com due to the low cost & shipping

![PCB](/Images/PCB.png)

## Schematic 
![Schematic](/Images/Schematic.png)

## Finished Board

![Schematic](/Images/Top.jpg)

![Schematic](/Images/Side.jpg)
