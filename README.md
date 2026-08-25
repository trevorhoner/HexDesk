# HexDesk

![HexDesk computer desk](images/HexDesk%20-%20computer%20desk%20(3).png)

## Tables of Contents


- 📖 [About](#About)
- 🌄 [Purpose](#Purpose)
- ⚙️ [Parts](#Parts)
  -  [Mounting Bracket](#mounting-bracket)
  -  [Brackets](#Brackets)
  -  [Connectors](#Connectors)
  -  [Accessories](#Accessories)
- 🛠️ [How to Use](#how-to-use)
- 🎯 [Objectives](#Objectives)
- ⚖️ [License](#License)

## About
HexDesk is an open-source modular desk organization system designed using Solidworks Maker. All source parts are currently native Solidworks files, so anybody who is willing to contribute to the project will need a license of Solidworks. Fortunately, [Solidworks Maker](https://www.solidworks.com/solution/solidworks-makers) remains about $48/yr U.S.D for an annual license.

HexDesk utilizes a hole-pin mating pattern with a standardized hole spacing of 25mm. Users can build nearly infinite desk setups e.g. shelves, monitor arms, cupholders, cord organizers, and much more. The idea was to create a system that would be easy to use, somewhat stylish, and versatile.
It's basically LEGO for desks.

## Purpose
The purpose of HexDesk is to provide a fun, versatile, affordable, and easily-accessible way for people to customize their desk.
HexDesk is to remain open-source to encourage users to contribute their creative talent and make HexDesk fun and exciting for everybody to use.

## Parts

### Mounting Bracket
![Mounting Bracket](images/Mounting-bracket.png "0.5m Mounting Bracket")

![Mounting_Bracket_w/Clamp](images/mounting-clamp.png "Mounting Bracket w/ Clamp")

The mounting bracket is a 25mm spaced, hexagonal-hole patterned bracket and is the heart of the HexDesk system. The mounting bracket mates to the desk utilizing 4 rubber-compression clamps and allows users to freely build via combinations of L/S/I brackets, hex-pins, connectors, and accessories.

The mounting bracket currently consists of 3 length variations i.e.:
  - 200mm, 3D-Printable
  - 0.5m
  - 1m

With the exception of the 200mm 3D-Printable variation, the mounting bracket is designed for sheet metal. The 0.5m and 1m long variations are best suited for sheet metal considering the strength needed for the length of the part. The sheet metal variations use a press-fit M6 threaded-insert while the 200mm variation uses a tapered, M6 heat-set insert to secure the rubber-compression clamps. 

All hardware below is sourced from McMaster-Carr/Amazon and can ship internationally:

  - [200mm 3D Printable Hardware (subtotal: $18.74)](https://www.mcmaster.com/order/rcvRtedOrd.aspx?ordid=5708077851437&lnktyp=txt)
  - [0.5m, 1m Sheet-metal Hardware (subtotal: $18.46)](https://www.mcmaster.com/order/rcvRtedOrd.aspx?ordid=8152341834576&lnktyp=txt)
  - [Female Rubber Bumpers - M6 4pcs 20mmx15mm uxcell ($8.59)](https://www.amazon.com/uxcell-Female-Vibration-Isolator-Replaces/dp/B0DD4DMK56/ref=sr_1_6?sr=8-6)

### Brackets
All brackets utilize a tongue-groove and hole-pin mating layout. Combined, the tongue/groove and hole-pin interfaces create six-axis locking. This allows simple modification and removability of parts. Each bracket is invertible, meaning that the tongue/groove and bracket bends can be aligned either way for more customization.

All variations of brackets are under 200mm to ensure fit for 3D Printing.

#### L-bracket
![L-bracket](images/L-bracket.png)

90-degree angle bracket

#### S-bracket
![S-bracket](images/s-bracket.png)

Two 90-degree angle bracket

#### I-bracket
![I-bracket](images/I-bracket.png)

180-degree, straight bracket

### Connectors

#### Single Chamfered Connector

![single-chamfered-connector](images/chamfered-single-connector.png "Single Chamfered Connector")

Mates two brackets along the same plane

#### Double Connector

![Double Connector](images/double-connector.png "Double Connector")

Mates two brackets in parallel

#### Monitor Connector

![Monitor-Connector-1](images/monitor-connector-1.png "Monitor Connector -1")

![Monitor-Connector-2](images/monitor-connector-2.png "Monitor Connector -2")

Allows the monitor bracket accessory to be quickly replaced in conjuction with a standard L/S/I bracket

### Accessories

#### Cupholder
![cupholder](images/cupholder.png)

A cupholder designed using an L-bracket. The cupholder base is designed for containers with a diameter of 130mm (~5 in)

#### Shelves
![shelves](images/shelf-layout.png)

Shelf plates that can be used to make shelves and cabinetry.
There are currently 4 variations of shelf panels i.e.:

  - LEGO
  - peghole (U.S. standard 1" spacing)
  - hexhole (10mm diameter, 25mm spacing)
  - flat

The shelves consist of end and middle pieces. Combined, users can make consistent planes out of shelves and brackets. Each shelf-plate mounts to a bracket via tongue-groove.

![shelf-layout](images/shelf-panels.png)

#### Monitor Bracket

![Monitor-Bracket](images/monitor-bracket.png "Monitor Bracket")

A quick attach monitor bracket with 75mm, 100mm VESA pattern holes

![Monitor-Arm](images/monitor-arm.png "Monitor Arm")

Monitor arm assembly showing the monitor with bracket connections



## How to Use
1. Make sure you have a working license for Solidworks

2. Download this repo

3. Print the [test-jig.sldprt](test-jig.SLDPRT) and [test-key.SLDPRT](test-key.SLDPRT) file

   ![test-jig](images/test-jig.png "Test Jig")

   ![test-key](images/test-key.png "Test Key")

4. Insert the test-key for every connection i.e. tongue, groove, hole, and pin and choose the best tolerance for your printer.

5. Open [global-variables.txt](global-variables.txt), and search "tol_nom" (nominal tolerance). Replace the nominal tolerance with your chosen tolerance from the test-jig.

6. Any part that you open should automatically update with the new tolerance. You can now print the selected part with your specified tolerance. Rebuild the part before deciding to print.

7. All other global variables can be changed but at your own risk. That's what open source is for after all.

## Objectives
Ideally, HexDesk remains as an open-source project where everybody from around the world can contribute their ideas. The more the project grows and expands, the more possibilities also occur.

## License
HexDesk is under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
Users are allowed to freely distribute, modify, and contribute the source content for personal use.
Commercial use is strictly prohibited unless granted authorized permission by me under a commercial license.

If you would like me to build you custom, tailored accessories for your HexDesk project, 
please click on my [Fiverr](https://www.fiverr.com/s/Em0YBZ9) page. 
Just know that any custom work will still be under the Creative Commons license.

