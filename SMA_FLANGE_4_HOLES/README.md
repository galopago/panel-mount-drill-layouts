# SMA PANEL ANTENNA CONNECTOR DRILLING TEMPLATE

Different "drilling helpers" for mounting a [SMA PANEL ANTENNA CONNECTOR](assets/pdf/Catalog_SMA.pdf). This templates can be produced in different media: paper or pcb. 

![SMAPANEL](assets/img/smapanel.jpg)

## How to use this repository

The PCB was developed in KiCad V5.1,

## Directory structure

* The root folder contains template KiCad files: project, schematic and PCB 
* /gerber folder contains ready to manufacture files.
* /assets folder contains support files for reade.md

## SMA panel connector

![SMACONNECTOR](assets/img/smaconnector.jpg)

## Paper drilling templae

![PAPERTEMPLATE](assets/img/paper.jpg)

## PCB drilling template


![PCBTEMPLATE](assets/img/pcb.jpg)

## MEDIA FILES

| HINT                        | LINK                                     
|-----------------------------|------------------------------------------
| PCB Source (KiCad V5.1)     | root folder
| PCB Gerber (single board)   | [GERBER_SINGLE](gerber/single)  
| PCB Gerber (panelized board)| [GERBER_PANEL](gerber/panel)  
| Paper (PDF)                 | [PAPER_PDF](assets/pdf/drill-layout.pdf)
| Paper (SVG)                 | [PAPER_SVG](assets/img/drill-layout.svf)

All of the pins of the module are routed to pcb pads, also, space for 2 AA size battery holder. There are also some traces for breadboarding

![FRONT](assets/img/front.jpg)

Module soldered on the back

![MODULE](assets/img/module.jpg)

Female headers used for debugging or adding a "hat" card with additional electronics.

![MODULE](assets/img/space.jpg)

Panelized PCB version 

![PANEL](assets/img/panel.jpg)


