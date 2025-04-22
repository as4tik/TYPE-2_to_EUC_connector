# TYPE-2_to_EUC_connector

This project is designed to help EUC riders charge their EUCS on public stations with Type-2 sockets.

With this connector, the public charghing stations may be used to charge up to 9-12 EUCs from one Type-2 slot at the same time.
![Image](https://github.com/user-attachments/assets/f7710aa4-30f3-48e4-b877-5d4120573671)

In my location, Type-2 stations support 7kWt or 22 kWt, depending on if 1 or 3 phases are available.

Each phase supports up to 4 EUCs with 1,75 kWt each (1,75*4=7). The quantity is limited by the number of connection slots you will make. The charging station do not control the quantity, but the total power for each phase. So, there is no difference if you charge 6 EUCs by 3,5 kWt each, or 12, by 1,75 kWt each.

For multiple slots, it is important that each socket between EUC and the charging Type-2 connector is designed to withstand the total current you going to path it by it. 

![EUC_on_charge2](https://github.com/user-attachments/assets/794547de-bf91-42e3-bb84-aa9d504cd787)

For the moment, when this description is made, there were tested a few times with 5 EUCs max with no heating of the connectors, registered. This description will be updated after 9 and 12 EUCs have been tested.

![5EUCs_on_charge](https://github.com/user-attachments/assets/749e6c8d-c3f2-4a5a-9758-fee6f05d7618)

## List of components

1. Type-2 connector
  * Specs
    * Type-2 (for my location as the most widespread)
    * Male (for my location as the most widespread)
    * 3 phases
    * 32A (the contact pins will be for 6 mm2, if you by 16A the pins will be for 2.5 mm2)
  * Example
    * [URL]([url](https://a.aliexpress.com/_ExlY7cO))
    * ![Type-2_connector](https://github.com/user-attachments/assets/7b3df7fd-a1c3-47d6-91e5-fcc83e519a40)

2. The main wires
   * Specs
     * AWG10
     * length 0.3 m
     * silicon cover
     * optional:
       * soldered to XT60 female
   * Example
     * [URL]([url](https://a.aliexpress.com/_EItfFi2))
     * ![Wires](https://github.com/user-attachments/assets/97747fc6-5264-4b88-9079-c2d6c5e9157d)

