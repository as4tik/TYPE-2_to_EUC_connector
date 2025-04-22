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
  * Specs
    * Type-2 (for my location as the most widespread)
    * Male (for my location as the most widespread)
    * 3 phases
    * 32A (the contact pins will be for 6 mm2, if you by 16A the pins will be for 2.5 mm2)
  * Example
    * [URL](https://a.aliexpress.com/_ExlY7cO)
    * ![image](https://github.com/user-attachments/assets/3b6ad6c7-9cfe-4858-a460-cb37da181c0e)
    * ![image](https://github.com/user-attachments/assets/9fff3809-4be0-449d-bb1c-9b77d4ef7690)


2. The main wires
   * Specs
     * AWG10
     * length 0.3 m
     * silicon cover
     * optional:
       * soldered to XT60 female
   * Example
     * [URL](https://a.aliexpress.com/_EItfFi2)
     * ![image](https://github.com/user-attachments/assets/e383f741-4dc6-4243-bb04-241e92cca410)
       
3. Resistor of max load
   * Specs
     * 220 Ohm
   * Example
     * [URL1](https://www.amazon.com/Projects-Resistors-Watt-Choose-Quantity/dp/B00CVZ3YOQ?th=1)
     * [URL2](https://imrad.com.ua/ua/pr01-220r-5)
5. Resistor "Stage B"
   * Specs
     * 2.74 kOhm
   * Example
     * N/A
6. Resistor "Stage C"
   * Specs
     * 1.3 kOhm
   * Example
     * N/A
8. Stage selector
   * Specs
   * Example
10. Diode
   * Specs
     * Model: 1N4007 | 1N4148
   * Example
     * ![image](https://github.com/user-attachments/assets/78bd2980-33e5-48c7-b84b-67c248f8dc26)
     * [URL1](https://www.amazon.com/100-Pieces-1N4148-Switching-High-Speed/dp/B079KJ91JZ/ref=sr_1_1)
     * [URL2](https://imrad.com.ua/ua/1n4148-1-1-437993)

12. 

## Chart of connection


