# OpenLane--ASIC-of-SPM-module
## simple ASIC description will suite the new users of the tool i work on small predesigned module (SPM) you will find it in the tool files

## introduction about the tool

### - Google make fund to people make chips with thier tool and make them fabrication ans this is thier schedule 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/beb9a886-cccd-40ea-9c37-5f499a9e9eb8)

### - it has automated RTL to GDSII flow (no-human) , you can run all flow from one file 

Including tools :
 OpenROAD, Yosys, Magic, Netgen, CVC, SPEF-Extractor, KLayout
![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/6a1cfc99-e6ef-4f71-a8e6-84309a656942)



### -you can run all the flow from this non interactive mode , only you will rum the flow.tcl script  
the flow.tcl script will call the another scripts (S2S) and the scripts call the commands (S2command) then commands call the configrations these are the three steps of automation in the tool 
 
 ![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/f63d1497-5655-40db-b745-b7f05812387f)

### -PDKS is Sky130A from SW 130nm and have 5 metal layers 


![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/3937305b-dd60-4d22-b689-d33481c71594)

### -in the tool you will find predesigned modules , i choose simple one and desided to implement it inshallah 
SPM (smart power module)
![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/9a026481-38ab-495a-83c7-d4ae990bf592)


### -i run synthesis script and the tool of synthesis called yosys 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/d6d5f70a-4138-43bc-901a-7bd439bbcc40)

### -i run floorplane script and the tool of PnR called openroad

Initial floorplane(core area , die area )

Io placement (macro 23 cell)

Tap & Decap insertion 

Power planning 
![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/e30aa4a4-a9af-410b-adfe-566e969260c2)


### view from the GUI to the floorplaning 


![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/960e3e75-9b02-46d5-8d77-f60450240425)

### tap insertion to prevent latchup poroplem 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/c8bf9003-f344-4dee-8bb3-d1605c4c2859)

### poewr grid 


![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/978de398-b088-49fd-b320-e11c8a2772c2)

### initial placement cells not correct orianted or fit in it's place in power grid 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/04cc61ca-e9af-48fe-8d0a-a23bd2a9631f)

### detailed placement and final placement 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/abceab18-7009-4441-a4c5-ee031666926b)

### placement dinesty to avoid problems in routing 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/f27ddebf-68e8-4b9c-884b-6a5877047ca5)

### view in logical connections after placement 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/41db66e0-bcb3-4dec-9fac-7111a8eb7f88)

### future work inshallah 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/b850767b-bf2f-4429-8b56-48ac869e04d9)








