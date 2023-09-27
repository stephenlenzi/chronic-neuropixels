# Apollo Implant Parts List and Instructions
## NOTE
The commercially available NP2.0 probes have a slightly different form-factor from the previous release. We are in the process of making the minor changes to the implant to fit these probes, which will be completed (and posted here) before these probes ship. There are two versions of the commercially available NP2.0 probes: those with a "metal cap" (also called a dovetail) and those without. The Apollo Implant will work with both versions, but to minimise the size and weight of chronic implants, we recommend getting the probes without the metal cap.
## Parts List
In this repository are all the parts required to build the chronic implant (not including glue, dental cement, etc.).
Files are adjustable using annotated parameter tables. Please watch “SupplementaryVideo_1.mp4” (found here) if you are unfamiliar with this process. You will also need Autodesk Inventor which is free for educational use. This allows you to, for example, change the angle of the docking module, spacing between probes, or thickness of the walls. However, be aware that parameters like “length of exposed probes” are estimates based on our own use and not exact. The default values are those we use in the lab for a typical insertion, although we change them as needed.

Files are also inter-linked, such that changes you make to the parameters of Payload_NP1 will cause changes in Docking_NP1, and DockingHolder_NP1. Usually, these are changes you want because it means all the parts will fit together. However, you should be aware that these are happening, and can be overridden if needed.

Files specific to versions 1 and 2 of Neuropixels are in NP1 and NP2 folders. Other parts are in the base folder and can be used (in some cases with a parameter change) for either version. NOTE: The "PayloadHolder" was updated on 27/09/2023 to add a minor adjustment for NP1 sizing.

&nbsp;
### “Payload_NP1” or “Payload_NP2”
This is the module that holds the probe(s). You will need one of these for each probe (or pair of probes) you use, and it is re-used across implantations. Print in Natural Rigid Resin 4000, including 4x M1 threaded inserts.

<p align="center">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/6d932aba-95ff-400f-87c5-b286c515460e">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/342aa9b6-97c1-4da7-822e-ae678719fe4f">
</p>

&nbsp;
### “PayloadHolder”
This is a holder that can be attached to the Payload Module for construction, painting, implants, storage, carrying around etc. There are two versions which can be produced from the save file by adjusting the binary “REDUCEDHOLDERVERSION” parameter. 
* If REDUCEDHOLDERVERSION is "0", you will see the version used for payload construction (below, left). You only need one of these. Print in PA12, including 2x M3 insert.
* If REDUCEDHOLDERVERSION is "1", you will see the reduced version used general manipulation, storage, insertion etc. You need as many of these as would be useful. Print in PA12, including 2x M3 insert.
NOTE: to change the part for NP1 and NP2 versions, simply change the “SlotLength” (14/9 mm for NP1/NP2) and "InterArmExtend" (0.4/0 mm for NP1/NP2) parameters as instructed in the comments . We have provided .stp files for all versions.

<p align="center">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/665314e6-c5af-4019-92a6-9f7827f77623">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/c11606f2-2a0e-4d34-819c-7b9b809868e1">
</p>

&nbsp;
### “PayloadCap_NP1” or “PayloadCap_NP2”
This is the lid for Payload Module, to be attached with glue after the probe is cemented in position. You will need one per probe. Print in PA12.

<p align="center">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/ff92b541-b34a-47be-a0cf-19f633d9ab2a">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/0e75abd9-8448-4eb8-9d17-81f2b80c7986">
</p>

&nbsp;
### “Docking_NP1” or “Docking _NP2”
This is the module that is cemented to the skull after being screwed to the Payload Module. A new Docking Module is required for each insertion. Print in Natural Rigid Resin 4000.

<p align="center">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/11d06e51-a7d2-4d17-af85-f0f744a4ca93">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/8f824646-ecec-4fe6-868f-6988759c262c">
</p>

&nbsp;
### “DockingHolder_NP1” or “DockingHolder_NP2”
This holds the Docking Module in place when using the constructor to combine the two modules. You only need one of these. Print in Natural Rigid Resin 4000, including 4x M3 insert.
    
<p align="center">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/5b422126-788e-4381-9a86-dd3819ef6751">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/a73924c3-5e27-4622-b062-03dc5bbc17fb">
</p>

&nbsp;
### “ConstructorHead”
This forms one end of the constructor setup (used to “safely” combine the docking and payload modules). You will only need one of these. Print in Natural Rigid Resin 4000. 
<p align="center">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/d9750dce-31a2-4ef1-ad70-424c6572bcde">
</p>

&nbsp;
### “ProbeSharpener” 
This is a simple part that we use to hold the probe itself in order to sharpen them prior to construction. Note that it uses a screw to hold the probe: do not tighten it too much, or the probe base will break.

&nbsp;
### Additional screws and bolts:
NOTE: Links are for reference but could be sourced elsewhere. The brass inserts can be easily inserted using a soldering iron and mild pressure. We typically do this in-house, but your 3D-printing company may also do this for you upon request.
* [M1 Brass knurled inserts](https://www.ebay.co.uk/itm/124331900287): To be heat-inserted into the Payload.
* [M3 Brass knurled inserts](https://uk.rs-online.com/web/p/threaded-inserts/2040620): To be heat-inserted into the PayloadHolder and DockingHolder.
* [M1 Screws](https://www.accu.co.uk/cheese-head-screws/6426-SFE-M1-3-A2): To lock modules together (4 per module).
* [M3 5mm screws](https://www.accu.co.uk/flanged-button-screws/8592-SSBF-M3-5-A2): For connecting Payload Module holder to Thor Labs posts (3 total)
* [M3 10mm screws](https://www.accu.co.uk/flanged-button-screws/8595-SSBF-M3-10-A2): For connecting Constructor Head to Thor Labs posts (3 total) and also for securing the Docking Module in its holder (2-4 depending on your preference)
* [M3 20mm screws](https://www.accu.co.uk/flanged-button-screws/8600-SSBF-M3-20-A2): For connecting Constructor Head to Thor Labs posts (3 total)
* [Thor labs posts](https://www.thorlabs.com/thorproduct.cfm?partnumber=MS3R/M): At least 3 for the constructor, potentially more to hold the probes etc.

&nbsp;
&nbsp;
## Assembly 
This section describes how to put all the parts together. We recommend practicing on dummy probes (or even on probes that are already broken!) to get used to it, since specific steps can be finicky.  
### MATERIAL: 
* Blu Tack 
* Epoxy glue (e.g., Araldite ARA-400007) 
* Super glue 
* Silver wire and soldering  

&nbsp;
### 1. CHECKING THE PARTS: 
  1. Before fixing the probe, perform full assembly procedure without the probe to ensure the parts fit together.

&nbsp;
### 2. FIXING A PROBE TO THE PAYLOAD MODULE 
  1. Using Blu Tack, position payload module and coat it with a thin layer of epoxy (so that the probe will stick to it).
  2. Carefully bring the probe (usually holding the flex with two fingers and pushing the probe down with the index finger) onto the payload module. Make sure you push it to the end of the payload module. Check for probe alignment, and readjust the angle manually. Add more epoxy to fix the probe to the module – you can cover the base and parts of the electronics, but it’s usually good to avoid covering the GND and REF electrodes since they can be used to check for good soldering (or to solder GND and REF here directly). While applying epoxy, you can keep the probe in position using the tip of forceps.
  3. Short the GND and the REF by soldering a silver wire in between (this can also be done beforehand). This step and the overall grounding are currently being discussed and improved (see troubleshooting).
  4. Fold the flex and insert it in the slot on the inside of the lid. Then push the lid down and glue it by putting super glue on both sides of contact with the payload module. If you’ve soldered a silver wire for your ground, make sure it sticks out. You can then fold the flex and slide the connectors end in the slot on the outside of the lid.
  5. You can now use the payload holder to sharpen your probe.

<p align="center">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/6eaa825d-e772-422b-aa68-67fa0e6fabe2">
<p align="center">
Stage 2.3 (left) and 2.4 (right) 
</p>  
 
&nbsp;
### 3. FIXING A SECOND PROBE TO THE PAYLOAD MODULE 
These steps are only if you want a second probe. If you don’t, you can close the empty side with a lid and make sure you close all gaps with epoxy or kwikcast. If you do, please follow these steps: 
  1. You must first sharpen the second probe. To do so, you can use the temporary probe holder (we have been using “ProbeSharpener.stl” to hold the probe during this process, but this hasn’t been heavily optimized).
  2. Then, you can assemble the second probe by repeating the same steps as before, while being extra careful not to touch the probe that is already attached to the docking module. 
 
&nbsp;
### 4. ASSEMBLING THE PAYLOAD AND THE DOCKING MODULES 
  1. Position the docking module in the docking module holder.
  2. Position the payload module (with the probes) in the payload module holder. This step is easier if the payload module holder is at that stage independent of the docking module holder. The probe is secured in the holder, and then the holder is screwed in. Check the alignment of the probe.
  3. Slide the docking module holder until the docking module is fully covering the payload module and that the holes are aligned to the threads. While sliding, check for the good alignment of the probe. Screw in (we found using forceps to hold the screws was easier). 
4.	Unscrew the docking module from the docking module holder. You can now slide it away from the probe.  
5.	Unscrew the now fully assembled implant from the payload module holder.  
 
<p align="center">
<img src = "https://github.com/Coen-Lab/chronic-neuropixels/assets/1191043/119cb38c-35c5-43d6-83c8-ae715129d858">
<p align="center">
Stage 4.2 (left) and 4.5 (right)  
</p>  


&nbsp;
&nbsp;
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
