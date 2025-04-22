# TYPE-2_to_EUC_connector

This project is designed to help EUC riders charge their EUCS on public stations with Type-2 sockets.

With this connector, the public charghing stations may be used to charge up to 9-12 EUCs from one Type-2 slot at the same time.
![image](https://github.com/user-attachments/assets/29569a1c-80a8-4b43-9e5a-b522e3135be4)

In my location, Type-2 stations support 7kWt or 22 kWt, depending on if 1 or 3 phases are available.

Each phase supports up to 4 EUCs with 1,75 kWt each (1,75*4=7). The quantity is limited by the number of connection slots you will make. The charging station do not control the quantity, but the total power for each phase. So, there is no difference if you charge 6 EUCs by 3,5 kWt each, or 12, by 1,75 kWt each.

For multiple slots, it is important that each socket between EUC and the charging Type-2 connector is designed to withstand the total current you going to path it by it. 

![image](https://github.com/user-attachments/assets/a3609b37-7de3-4c97-8f92-d3f9c73f5162)

For the moment, when this description is made, there were tested a few times with 5 EUCs max with no heating of the connectors, registered. This description will be updated after 9 and 12 EUCs have been tested.

![image](https://github.com/user-attachments/assets/9d256e85-899c-489f-bc3d-43122fa341ab)

## List of components

1. Type-2 connector
   - Specs
     - Type-2 (for my location as the most widespread)
     - Male (for my location as the most widespread)
     - 3 phases
     - 32A (the contact pins will be for 6 mm2, if you by 16A the pins will be for 2.5 mm2)
   - Example
     - [URL](https://a.aliexpress.com/_ExlY7cO)
     - ![image](https://github.com/user-attachments/assets/3b6ad6c7-9cfe-4858-a460-cb37da181c0e)
     - ![image](https://github.com/user-attachments/assets/9fff3809-4be0-449d-bb1c-9b77d4ef7690)

2. The main wires
   - Specs
     - AWG10
     - length 0.3 m
     - silicon cover
     - optional:
       - soldered to XT60 female
   - Example
     - [URL](https://a.aliexpress.com/_EItfFi2)
     - ![image](https://github.com/user-attachments/assets/e383f741-4dc6-4243-bb04-241e92cca410)
       
3. Resistor of max load
   - Specs
     - 220 Ohm
   - Example
     - [URL1](https://www.amazon.com/Projects-Resistors-Watt-Choose-Quantity/dp/B00CVZ3YOQ?th=1)
     - [URL2](https://imrad.com.ua/ua/pr01-220r-5)
5. Resistor "Stage B"
   - Specs
     - 2.74 kOhm
   - Example
     - ![image](https://github.com/user-attachments/assets/3ca18027-13b3-4718-9764-45f835617715)
     - [URL1](https://www.amazon.com/2-74K-Metal-Resistor-Piece-271-2-74K-RC/dp/B07GPFHFCN)
     - [URL2](https://vseplus.com/ua/product/radiodetali-mikroshemy/294-rezistory-potenciometry-kvarcevye-rezonatory/f-p140_24355-p81_25143)
6. Resistor "Stage C"
   - Specs
     - 1.3 kOhm
   - Example
     - ![image](https://github.com/user-attachments/assets/60c84c1c-0356-4318-8976-3c7359662ff7)
     - [URL1](https://www.amazon.com/uxcell-Tolerance-Resistance-Electronic-Experiments/dp/B07PPVDHN8)
     - [URL2](https://epts.com.ua/ua/p1110345629-rezistor-mlt-0125.html)
8. Switch
   - Specs
     - A simple switch with 2 contacts
   - Example
     - ![image](https://github.com/user-attachments/assets/69253b10-ff74-4c31-a425-450f670260c1)
     - ![image](https://github.com/user-attachments/assets/73387a6d-8ced-4b73-894b-309f200f44a1)
     - [URL1](https://www.amazon.com/DaierTek-250VAC-Rocker-KCD1-101-Plastic/dp/B07S2QJKTX)
10. Diode
    - Specs
      - Model: 1N4007 | 1N4148
    - Example
      - ![image](https://github.com/user-attachments/assets/78bd2980-33e5-48c7-b84b-67c248f8dc26)
      - [URL1](https://www.amazon.com/100-Pieces-1N4148-Switching-High-Speed/dp/B079KJ91JZ/ref=sr_1_1)
      - [URL2](https://imrad.com.ua/ua/1n4148-1-1-437993)
11. XT60 connectors
   - Specs
      - Female
   - Example
      - ![image](https://github.com/user-attachments/assets/0c6b3df7-ed5a-4bcd-9ad6-d8393e5fdb4d)
12. 1:3 XT60
   - Specs
      - 1 Male to 3 Female
   - Example
      - ![image](https://github.com/user-attachments/assets/c66f23b4-7275-4b7f-bad3-10ee4fa50bba)
      - [URL](https://a.aliexpress.com/_EjiTLKS)
 

## Chart of connection
   - ![image](https://github.com/user-attachments/assets/6dbae1c8-2e5a-40bf-b24a-8ce56490a1d5)
   - The diode to be connected by anode to CP contact, and by cathode to the resistors

## How to check?
   - The test, before diode is connected:
      - ![image](https://github.com/user-attachments/assets/7e974030-86a3-4a2d-80c0-7972e7164970)      
   - The test, with diode (full set up):
      - (under construction)



## Additional actions
   - Action:
     - To cut out the last piece of the black plastic body
   - Restriction:
     - a few millimetres away from the contacts
   - Reason:
     - to use both types of type-2 stations: as a socket and as a plug.
   - ![image](https://github.com/user-attachments/assets/e840a113-fe82-49e7-a8f1-07dca36e552f)
   - ![image](https://github.com/user-attachments/assets/896e5efd-7746-4b21-be3b-fe181e343290)
   - ![image](https://github.com/user-attachments/assets/890303e6-bd36-4768-8e4b-2298ccd9d388)
   - ![image](https://github.com/user-attachments/assets/f05557ef-4dc9-4ad3-9814-5269cbb278d3)







