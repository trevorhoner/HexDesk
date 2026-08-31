# HexDesk

![HexDesk computer desk](images/hexdesk-computer-desk.png)

## Table of Contents

- 📖 [About](#about)
- ⚙️ [Parts](#parts)
  -  [Mounting Bracket](#mounting-bracket)
  -  [Brackets](#brackets)
  -  [Connectors](#connectors)
  -  [Accessories](#accessories)
- 🛠️ [How to Use](#how-to-use)
- 🌎 [Contributing](#contributing)
- ⚖️ [License](#license)

## About
HexDesk v1.0 currently has 33 STLs ready to print. HexDesk utilizes a standardized 25mm, hole-pin mating pattern with matching brackets, shelf-plates, connectors, and accessories to build nearly infinite combinations.

The purpose of HexDesk is to provide a fun, versatile, affordable, and easily-accessible way for people to customize their desk.

🔶 [Printables](https://www.printables.com/model/1823229-hexdesk-modular-desk-organizer-system-open-source)

## Parts

### Mounting Bracket
![Mounting Bracket](images/mounting-bracket.png "0.5m Mounting Bracket")

![Mounting_Bracket_w/Clamp](images/mounting-clamp.png "Mounting Bracket w/ Clamp")

The mounting bracket is a 25mm spaced, hexagonal-hole patterned bracket and is the heart of the HexDesk system. The mounting bracket mates to the desk utilizing 4 rubber-compression clamps and allows users to freely build via combinations of L/S/I brackets, hex-pins, connectors, and accessories.

The mounting bracket currently consists of 3 length variations i.e.:
  - 200mm, 3D-Printable
  - 0.5m
  - 1m

With the exception of the 200mm 3D-Printable variation, the mounting bracket is designed for sheet metal and cannot be 3D printed. The 0.5m and 1m variations are best suited for sheet metal considering the strength needed for the length of the part. The sheet metal variations use a press-fit M6 threaded-insert while the 200mm variation uses a tapered, M6 heat-set insert to secure the rubber-compression clamps. 

All clamp hardware below is sourced from McMaster-Carr/Amazon and can ship to most parts of the world:

| Part | Description | Source |
|------|-------------|--------|
| Heat-set nut (200 mm print) | M6 × 1 tapered insert for plastic | [McMaster# 97163A156](https://www.mcmaster.com/97163A156/) |
| Press-fit nut (sheet metal) | M6 × 1 flush press-fit | [McMaster# 94674A219](https://www.mcmaster.com/94674A219/) |
| Socket screw | M6 × 1 flat head, 70 mm | [McMaster# 92125A258](https://www.mcmaster.com/92125A258/) |
| Rubber bumper | 20 × 15 mm M6 female mounts | [Amazon](https://www.amazon.com/uxcell-Female-Vibration-Isolator-Replaces/dp/B0DD4DMK56) |
  

### Brackets
All brackets utilize a tongue-groove and hole-pin mating layout. Combined, the tongue/groove and hole-pin interfaces create six-axis locking. This allows simple modification and removability of parts. Each bracket is invertible, meaning that the tongue/groove and bracket bends can be aligned either way for more customization.

All variations of brackets are under 200mm to ensure fit for 3D Printing.

#### L-bracket
![L-bracket](images/L-bracket.png)

90-degree angle bracket

#### S-bracket
![S-bracket](images/s-bracket.png)

two 90-degree bends

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

Allows the monitor bracket accessory to be quickly replaced in conjunction with a standard L/S/I bracket

### Accessories

#### Cupholder
![cupholder](images/cupholder.png)

A cupholder designed using an L-bracket. The cupholder base is designed for containers with a diameter of 130mm (~5 in)

#### Shelves
![shelves](images/shelf-layout.png)

Shelf plates that can be used to make shelves and cabinetry.
There are currently 4 variations of shelf panels i.e.:

  - brick-board
  - 1-inch pegboard spacing
  - hexhole (10mm diameter, 25mm spacing)
  - flat

The shelves consist of end and middle pieces. Combined, users can make consistent planes out of shelves and brackets. Each shelf-plate mounts to a bracket via tongue-groove.

![shelf-layout](images/shelf-panels.png)

#### Monitor Bracket

![Monitor-Bracket](images/monitor-bracket.png "Monitor Bracket")

A quick attach monitor bracket with 75mm, 100mm VESA pattern holes

![Monitor-Arm](images/monitor-arm.png "Monitor Arm")

Monitor arm assembly showing the monitor with bracket connections

#### Custom Parts

Need a part that is not in the pack?
[Custom part design on Fiverr](https://www.fiverr.com/s/Em0YBZ9)

## How to Use

1. Print the following parts and perform a no-go test. If they do not fit properly, then you'll have to skip this section and edit the original SolidWorks files. See [Contributing](#contributing) 
   
  - [L-bracket](STLs/L-bracket/2x5%20(L%20-%200.35mm,%202H).STL)
  - [double connector](STLs/connectors/double.STL)
  - [hex-pin](STLs/hex-pin/hex-pin-15mm.STL)

2. Download the [latest release](https://github.com/trevorhoner/HexDesk/releases/latest)
   
3. Purchase or source the specified hardware for the mounting bracket that you choose, whether 3D printed or sheet-metal.

4. Print parts from the STLs folder and build.

5. Any modifications to the parts e.g. tolerances, will have to be done in SolidWorks. See contributing for more detail.

## Contributing
HexDesk is an open-source modular desk organization system designed using SolidWorks Maker. All source parts are currently native SolidWorks files, so anybody who is willing to contribute to the project will need a license of SolidWorks. Fortunately, [SolidWorks Maker](https://www.solidworks.com/solution/solidworks-makers) remains about $48/yr U.S.D for an annual license. 

1. Clone the repo

2. Print the [test-jig.STL](STLs/test-jig.STL) and [test-key.STL](STLs/test-key.STL) file

   ![test-jig](images/test-jig.png "Test Jig")

   ![test-key](images/test-key.png "Test Key")

3. Insert the test-key for every connection i.e. tongue, groove, hole, and pin and choose the best tolerance for your printer.

4. Open [global-variables.txt](global-variables.txt), and search "tol_nom" (nominal tolerance). Replace the nominal tolerance with your chosen tolerance from the test-jig.

5. Any part that you open should automatically update with the new tolerance. You can now print the selected part with your specified tolerance. Rebuild the part before deciding to print.

6. All other global variables can be changed but at your own risk.

## License
  - Repo license: CC BY-NC-SA 4.0
  - Personal prints: intended
  - Selling prints or shipping a product: ask
