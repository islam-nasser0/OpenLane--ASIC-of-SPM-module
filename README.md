# OpenLane--ASIC-of-SPM-module
## simple ASIC description will suite the new users of the tool i work on small predesigned module (SPM) you will find it in the tool files

## introduction about the tool
![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/beb9a886-cccd-40ea-9c37-5f499a9e9eb8)

### - google make fund to people make chips with thier tool and make them fabrication ans this is thier schedule 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/6a1cfc99-e6ef-4f71-a8e6-84309a656942)

### - it has automated RTL to GDSII flow (no-human) , you can run all flow from one file 


Including tools :
 OpenROAD, Yosys, Magic, Netgen, CVC, SPEF-Extractor, KLayout
 
 ![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/f63d1497-5655-40db-b745-b7f05812387f)

### -you can run all the flow from this non interactive mode , only you will rum the flow.tcl script  
the flow.tcl script will call the another scripts (S2S) and the scripts call the commands (S2command) then commands call the configrations these are the three steps of automation in the tool 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/3937305b-dd60-4d22-b689-d33481c71594)

### -PDKS is Sky130A from SW 130nm and have 5 metal layers 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/9a026481-38ab-495a-83c7-d4ae990bf592)

### -in the tool you will find predesigned modules , i choose simple one and desided to implement it inshallah 
SPM (smart power module)

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/d6d5f70a-4138-43bc-901a-7bd439bbcc40)

### -i run synthesis script and the tool of synthesis called yosys 

![image](https://github.com/islam-nasser0/OpenLane--ASIC-of-SPM-module/assets/111699435/e30aa4a4-a9af-410b-adfe-566e969260c2)

### -i run floorplane script and the tool of PnR called openroad

Initial floorplane(core area , die area )

Io placement (macro 23 cell)

Tap & Decap insertion 

Power planning 





