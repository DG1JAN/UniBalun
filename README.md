# UniBalun
a PCB for a lightweight qrp Balun (1:1, 1:4 or UnUn 1:49)

![alt text](https://github.com/DG1JAN/UniBalun/blob/main/examples.jpg)

Depending on the winding of the toroid, you can use the PCB to create a 1:1 or 1:4 Balun or a 1:49 UnUn.

1:1 Balun: solder a wire jumper between Pad 1 and 3. No capacitor.

1:4 Balun: solder a wire jumper between Pad 1 and 2 and another jumper between Pad 3 and 4. No capacitor.

1:49 Unun: solder a wire-jumper between Pad 1 and 4 on the backside of the PCB (gives better isolation). Solder the capaciator to C1

![alt text](https://github.com/DG1JAN/UniBalun/blob/main/variants.png)

I recommend using Amidon FT82-43 Cores for 1:49 UnUns. For 1:1 and 1:4 Balun also "Würth 74270118" (or similar sized NiZn) toroids will work.

Measurements have shown, that the best winding radio for 1:49 UnUns on the small FT82-43 core is 3-to-21. 

After a request from an OM, I also did a version using a BNC connector. (Amphenol B6252H7, Telegärtner J01001A0038 or similar)

For German/EU-Based Hams, I can recommend https://aisler.net/ for PCB manufacturing. You can upload the Kicad file and order the PCBs.
Please select the Surface Finish: "ENIG"  for best results (Perfect Gold / Nickel surface finish with excellent planarity).
