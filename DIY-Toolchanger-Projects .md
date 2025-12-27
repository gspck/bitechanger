# list of toolchanger projects:  
## [jubilee](https://github.com/machineagency/jubilee)  
Toolchanger compatibel with E3D Toolchanger tools  
## [tapchanger](https://github.com/viesturz/tapchanger)
attaches tools by vertical movement uses locking mechanism as  probe    
## [stealthchanger](https://github.com/DraftShift/StealthChanger) 
based on Tapchanger 
## [blackbox]( https://github.com/Black-Box-Toolchanger/BlackBox)  
Toolchanging system similar to E3d Toolchanger
## [Foxchanger](https://github.com/Noisyfox/FoxChanger)
based on Prusa Xl  
## [Daksh v2](https://github.com/ankurv2k6/daksh-toolchanger-v2) 
based on Prusa XL
## [Magchange](https://github.com/BlackShadeOSS/Voron-MagChange)  
elektromagnetic Toolchanger
## [Lineux](https://github.com/Bikin-Creative/Lineux-Toolchanger)
lock/unlock through x movement magneticly locking
## [clickchanger](https://github.com/viesturz/ClickChanger)  
based on Tapchanger and Stealthchanger  
## [misschanger](https://github.com/VIN-y/MissChanger)  
based on Tapchanger and Stealthchanger does not need a flying gantry
## [madmax](https://github.com/zruncho3d/madmax)  
lock/unlock through x movement magneticly locking  
| Toolchanger    | Compatability                                | locking mechanism  | positioning system                | (un)locking action | space per tool            | extruders                                     | hotends                       | toolheads                                                                                                    | Probe                       |
|----------------|----------------------------------------------|--------------------|-----------------------------------|--------------------|---------------------------|-----------------------------------------------|-------------------------------|--------------------------------------------------------------------------------------------------------------|-----------------------------|
| jubilee        | Not designed to fit other printers           | servo+cam          | maxwell coupling                  | servo              |  ?                        | orbiter v1.5/v2 Bondtech BMG                  | V6 Volcano dragonfly E3D Revo | E3d Toolchanger                                                                                              |                             |
| Tapchanger     | Voron V2 others might need some modification | gravity magnets    | printed linear rail with bearings | Z-movement         | 6on 350v2.4               | -                                             | -                             | Dragonburner (mini)Stealthburner                                                                             | included                    |
| Stealthchanger | Voron V2 others might need some modification | gravity magnets    | pins Bushing                      | Z-movement         | 60mm/76mm depends on tool | -                                             | -                             | Stealth Burner, Dragon Burner, Rapid Burner, Yavoth, AntHead, A4T, XOL, Jabberwocky and Archetype BlackBird  | included                    |
| blackbox       | Not designed to fit other printers           | wormdrive+cam      | maxwell coupling                  | wormdrive          | 5on 300mm                 | -                                             | e3d revo v6                   | -                                                                                                            | switch or ir- probe         |
| foxchanger     | voron V2 VT                                  | linear locking bar | ?                                 | x movement         | ?                         | -                                             | -                             | Dragonburner (mini)Stealthburner                                                                             | ?                           |
| daksh v2       | Voron VT v2 legacy,ratrig VC3                | linear locking bar | maxwell coupling                  | x movement         | ?                         |                                               |                               |                                                                                                              |                             |
| Magchange      |                                              | electromagnet      | maxwell coupling?                 | electromagnet      | ?                         | ?                                             | ?                             | ?                                                                                                            | ?                           |
| Lineux         | vzbot v2 others with modification            | magnets            | capnuts and bushings              | x movement         | ?                         | protoextruder Sherpa micro                    | revo,v6                       | -                                                                                                            | Klicky beacon               |
| Clickchanger   | Voron v2                                     | gravity magnets    | pins Bushing                      | Z-movement         | ?                         | HGX Orbiterv2 Sherpa mini and equal footprint | revo dragon(HF) rapido HF     | -                                                                                                            | cartographer beacon revo pz |
| Misschanger    | voron V2 VT                                  | gravity magnets    | pins Bushing                      | x movement         | 5 on 350 4 on 300         | -                                             | -                             | Stealth Burner                                                                                               | included                    |
| Mad Max        | Voron v2 VT PFA and others                   | magnets            | maxwell coupling                  | x movement         | ?                         | -                                             | -                             |  DragonBurner, Dragon, OmniBurner, AntHead a4t xol custom                                                    | included                    |