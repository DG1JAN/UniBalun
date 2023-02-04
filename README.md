# UniBalun
a PCB for a lightweight qrp (maximum 10W SSB & CW or 5W on FT8) 1:49 UnUn (also 1:9,1:64,... possible) or Balun (1:1, 1:4)

Update to Rev. 1.2 with some minor changes (bigger Pads for the Capaciator and updated labeling)

German speaking Hams will now find a new PDF with build instructions (Bauanleitung) in the repo: https://github.com/DG1JAN/UniBalun/blob/main/Bauanleitung_UniBalun.pdf

![alt text](https://github.com/DG1JAN/UniBalun/blob/main/Uni_Balun/UniBalun1.2_3D_Pic1.png)


![alt text](https://github.com/DG1JAN/UniBalun/blob/main/rev1_1.jpg)


Depending on the winding of the toroid, you can use the PCB to create a 1:1 or 1:4 Balun or a 1:49 UnUn.

1:1 Balun: solder a wire jumper between Pad 1 and 3. No capacitor.

1:4 Balun: solder a wire jumper between Pad 1 and 2 and another jumper between Pad 3 and 4. No capacitor.

1:49 Unun: solder a wire-jumper between Pad 1 and 4 on the backside of the PCB (gives better isolation). Solder the capaciator to C1

![alt text](https://github.com/DG1JAN/UniBalun/blob/main/variants.png)

I recommend using "Amidon FT82-43" or "Fair-Rite 5943001001" (100% identical to the Amidon) Cores or the "Würth 74270118" core. The Würth core is a bit better on higer Bands, but should not be used below ~6MHz.

Measurements have shown that the best winding radio for 1:49 UnUns on the small FT82-43 sized core is 3-to-21. 

The new revision (>1.1) has a combined footprint for BNC and SMA connectors, so only one version of the PCB is needed (thanks to DL2MAN for the idea).
For BNC connection you can use the Part: Amphenol B6252H7 / Telegärtner J01001A0038 (or similar) <br>
For SMA connection pls use a straight edge mount SMA connector (found some cheap sources at amazon, e.g. : https://www.amazon.de/10-polig-SMA-Buchse-Leiterplattenmontage-Adapter-HF-Steckverbinder-Messing/dp/B07QG2Y9L6/ref=sr_1_3?keywords=sma+buchse&qid=1662800069&sr=8-3 )

I add two new PADs in revision 1.1 to solder 4mm ("Bana Connector") sockets directly to the PCB. I used this parts: https://www.amazon.de/gp/product/B07VYSN74H/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&th=1 

For German or EU-based OM's, I can recommend https://aisler.net/ for PCB manufacturing. You can upload the Kicad file and order the PCBs.<br>
I also have good experience with http://JLCPCB.com from China. You can upload the Gerber Files (as Zip-File) directly to their homepage. delivery time to Germany is ~10 to 14 days.
Manuel (DL2MAN) did a short How-To-Order here on Youtube: https://www.youtube.com/watch?v=1b3oLp7s9gk&t=5s


Pictures from a build for a 1:49 UnUn:
![alt text](https://github.com/DG1JAN/UniBalun/blob/main/UniBalun_1_1_UnUn_example.jpg)
