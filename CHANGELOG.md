# DownDraft Changelog

### 2026-02-02

- Modified all the Concept 1 and Concept 2 parts. Both have improved HE fan wiring. Both have improved X rail mount screw access. Both have improved lower face part mounts. Concept 2 has improved duct design

- CAD updated

### 2026-02-02

- Modified the Concept 2 parts. Improved wiring routes

- Modified lower mount screw position

- Improved part cooling ducts to diminish the low pressure spots around the hotend

- CAD updated

### 2026-02-14

- All new parts replace old ones

- Concept 2 removed as cooling compromises too great

- 4010 Concept temporarily removed until it's brought up to date

### 2026-02-15

- Added Crossbow Cutter mount

- Modified the Alternative Extruder Mount to fit the current aesthetics

- Widened the 5015 tab grooves in the Front Mounts and Fan Mounts

### 2026-02-19

- Added Crossbow mount

- Added a little more room for the 5015 fans

- Added spacing to the hotend/extruder mount to make it fit more easily over the fan mounts

- Added left and right PCB PUG mounts

- Added strain relief to the PCB PUG mounts

- Added PCB strain relief mount (no PUG)

- Added zip tie holes to the rear of the fan mounts

- Added hardware to CAD (screws, nuts, heat inserts)

- Added spacers for the PCB mounts

- Added enlarged exhaust space at the rear of the hotend/extruder mount

### 2026-02-22

- Updated HE Fan Spacer design and better screw clearance(needs testing)

- Updated Fan Mounts with improved part cooling ducts, improved fan wire ducts, improved duct printability

- Updated Crossbow cutter mount height

- Modified hotend mounts for better clearance and HE exhaust

### 2026-02-25

- Added new 4010 dual Fan mounts and Front mounts

- All Common Parts are shared with the 5015 version apart from the Fan Spacer

- All the same extruders and hotends are supported

### 2026-02-27

- Updated the 5015 Fan Mount ducts to fix a thin wall between the duct and the lower screw channel (STLs only)

### 2026-03-02

- Modified the HE fan retainers on the Fan Mounts for the 4010 so that they don't interfere with airflow

- Modified ziptie locations to accommodate Chariot cable routing

- Modified rear of the Fan Mounts to add space for belt loops when using Chariot

- Added chamfers to the rear sides of the Hotend Mounts to make wiring more easy

- Added nozzle LED mounts

- Added logo LED mounts (diffuser uses the Stealthburner version)

### 2026-03-04

- Modified all Hotend Mounts to fix geometry measurements

- Modified all Front, Left and Right Mounts to fix a geometry measurements

- Tidied up CAD

### 2026-03-09

- Aligned upper mounting holes with Chariot

- Added CPAP version as a POC - likely to change

- Remodelled the 3 and 2 hole chain mounts

### 2026-03-10

- Rebuilt the 4010 ducts

- This updates all of the 4010 specific parts and brings their performance in line with the DB v8

### 2026-03-15

- Added an additional screw guide to the 5015 right fan mount to prevent the screw dropping down when fitting the toolhead

- Modified all of the hotend mounts to shorten gap to the left and right fan mounts to help prevent plastic stress when tightening the top two mounting screws

- Modified 2 and 3 hole cable chain mounts to allow more clearance from the chain

### 2026-03-17

- Modified the 5015 fan duct inlets to better match the fan outlet location

- Modified the left and right 5015 fan mounts for a tighter fit to prevent rattling

- New CPAP toolheads

### 2026-03-18

- Modified the CPAP Pipe Connector to stop such that it points to the rear of the toolhead

- Added a simple BUILD document

### 2026-03-19

- Added Bowden mounts that use either ECAS or Collet fittings

### 2026-03-21

- Improved Left and Right Fan Mount printability of overhangs and first layer for both the 4010 and 5015 options

### 2026-03-23

- Checked against both the latest Legacy and Switchwire and all looks good
- Added a little more plastic to the 4010 ducts to improve printability
- Modified the square nut holes on all of the Hotend mounts, where the mount secures to the Front mount, to avoid the thin wall at the base
- Added print specs and warning to the BUILD document

### 2026-03-29

- Beefed up the PCB mounts to help limit flexing

- Modified all Hotend Mounts to switch the PCB / Cable Chain mounts to M3 square nuts instead of heat inserts

- Fixed the HE fan locator bumps on the 4010 Low and High Front mounts to be the correct diameter

- Adjusted top 2 mounting positions so that the screws do not bottom out and pull the CW2 heat inserts out

- Updated BOM

- Moved the Front part mounting screws to the side and top of the toolhead instead of the face. 
  **NOTE: The top 2 screws must be BHCS**

- Modified the 2 and 3 hole Chain mounts and added 36mm PCB mount points

### 2026-03-29

- Fixed the Alternative Extruder Spacer and the Crossbow Cutter Mount to not interfere with the PCB/Chain tabs
- Added a Hardware Compatibility Test document which lists tested hardware: hotend/hotend mount is supported, Extruders, Hotend Fans and Part cooling fans

### 2026-04-01

- Added a BARF LED carrier
- Added a bespoke Roto Vitamins front cover
- Modified all of the Hotend Mounts to account for supported extruders widths

### 2026-04-05

- Modified the 5015 Front mounts to add retaining nubs for the logo and nozzles LEDs holders

- Added a printable Fan leaf spring part for the 5015 option

- Modified the right 5015 Fan mount to use a printed leaf spring

- Modified all the 5015 Front mounts to use a printed leaf spring

- Added Nozzle LED strip mount for 144 led's per metre lights

### 2026-04-06

- Modified all Hotend mounts to add 3mm to the inner length of the mount screw holes

- Modified all Hotend mounts to give a little room to align the Hotend and Front mounts

- Modified all Hotend mounts to increase the inner height if the Hotend to Front mounting screws

- Added two zip tie holes on all Hotend mounts

- Added a fan leaf spring part for use with most 5015 fans

- Added a fan "spring" for Vindr 5015 fans for us instead of the leaf spring. Only use these if you need to, don't use them if it feels like the Fan assembly will deform the Front part

- Modified the 5015 Fan leaf spring mount to have a slightly tighter fit

- Reduced the size of the Logo and Nozzle LED retaining nub

- Updated the BUILD  and Hardware Compatibility documents

### 2026-04-08

- Updated the BUILD document

- Added multiple Cable Chain mounts for for single board PCB's to fit Orbiter v2 spacing extruders for both 2 and 3 hole chain mounts. These attach on one side of the Hotend/Extruder mount and on one point on the extruder:
  
  - Wristwatch BMG
  
  - Wristwatch G2
  
  - Orbiter v2.x
  
  - Roto Vitamins (requires the front cover in this repo)

### 2026-04-09

- Removed strain relief from PUG mounts

- Added 4 more Umbilical mounts with an additional mount point on the 4 extruders mentioned in 2026-04-08

- Added cable tie points to all PCB mounts

### 2026-04-11

- Added Roto Vitamins swappable Front Panels
- Modified all the 5015 Front, Left Fan and Right Fan mounts. Rejigged the 5015 geometry so that the Front mounts are 0.2mm thicker (no need to reprint, but if you print a new Front mount, the Left and Right Fan mounts also need reprinting)
- Added extruder specific PUG mounts for Umbilical single board toolhead PCB's

### 2026-04-12

- Added new Roto Vitamins Front Panels

- Fixed geometry issues with the 5015 Front parts

### 2026-04-15

- Added tapered holes for the thread forming HE fan screws
- Modified the Nozzle LED strip mount to support 2 Neopixels which is held in place with 2 thread forming M3x8mm screws in the Front part of all fan options
- Modified the 4010 and 5015 Front and Hotend/Extruder parts with new aesthetics at the corners
- Modified all of the Hotend/Extruder mounts to push the 2 Front part mounting screws further back to give more plastic for the joints
- Added a single LED nozzle mount

### 2026-04-18

- Updated the Roto Vitamins front panel to tie in with the revised design of the hotend/extruder mount

- Added a tab to the 5015 right Fan mount to provide lateral support

- Modified the Logo and Nozzle LED carriers for both Neopixels and BARF to help prevent the LED's from easily pulling out

### 2026-04-19

- Modified the 4010 Fan mount rears to reduce the risk of wires getting trapped between the mount face to the rail carriage mount
- Fixed some geometry issues with the 5015 Fan mounts
- Added another cable tie slot to the 4010 Fan mounts to match the 5015's
- Added a tabs to the bottom of the 5015 Fan mounts to provide more lateral support
- Improved bridging on the back of the 4010 Fan mounts

### 2026-04-20

- Added G2SA extruder mounts for Umbilical, PUG and Chain mounts

### 2026-04-24

- Modified the 4010 and 5015 toolheads to use tabs on the Fan mounts to hold the Nozzle LED mount in place

- Added more accent chamfers to the 5015 Front mounts

- Modified the CPAP Pipe Connector to more easily allow pipe removal

### 2026-04-26

- Modified the 5015 Front and Fan mounts to slim the toolhead down by 2mm to help with X carriage limits
- Modified 5015 Fan mounts to use M3x25mm top mounting screws
- Modified the 5015 Fronts to fix a dimension issue with the new Fan mounts

### 2026-04-29

- Modified CPAP and 4010 Fan mount versions to use M3x25mm top mounting screws

- Modified 5015 Fan and Front mounts to use an new fan spring system. This removes the thin face on the left of the Front mount, so that left and right are now equal

- Updated the BUILD and TESTING documents for the closed Beta test

### 2026-05-03

- Modified the CPAP version to fit the 5015 aesthetic

### 2026-05-05

- Modified WWG2 extruder PUG PCB Mount to use inbuilt heat insert to the rear of the extruder

- Modified CPAP (Banshee) toolheads

### 2026-05-06

- Added an Umbilical PUG PCB mount variant for the WWG2 with Dual Filament Sensors
- Fixed PCB mount hole depth for Umbilical PUG PCB mount variant for the WWG2 with Dual Filament Sensors and add some space for the main cable
- Modified the non-PUG mount variant for the WWG2 to use the lower inbuilt extruder mount to the rear
- Modified 4010 Fan and Front mounts to add more plastic to the PCF ducts
- Added locating nubs to the 4010 and 5015 Front mounts for the Nozzle LED mount
- Modified all of the Hotend mounts to help with bridging the Orbiter v2 spacing square nut hole
- Modified most PCB mounts to have the correct depth heat insert holes

### 2026-05-07

- Modified the Crossbow filament cutter mount to remove interference
- Added full counterbore bridging to all of the Hotend mount extruder square nut holes

### 2026-05-08

- Added the XOL CNC Adapter from DWTas, to fit the toolheads to
- Modified the HE Fan Spacer for better printability
- Modified the DB adapter plate rear screw part for fitment
- Modified the Hardware Compatibility List to show that the TZ-V6 v2 Hotend mount is for a V6 nozzle
- Fixed geometry issue with the Umbilical PUG PCB mount variant for the WWG2 with Dual Filament Sensors

### 2026-05-11

- Chube Air support removed
- Modified all relevant PCB/Chain mounts to use heat inserts rather than square nuts for the mount to the extruder motor

### 2026-05-12

- Added some sample Front mount aesthetic cutters

- Modified all relevant PCB/Chain mounts to use heat inserts to have both PCB mount holes from the same side

### 2026-05-13

- Decreased the Arc at the bottom of the 4010 Front mounts to improve printability

- Decreased the Arc at the bottom of the 5015 Front mounts to cover the Nozzle Mount

- Modified 4010 and 5015 Left and Right Fan Mounts and Front Mounts to move the Nozzle LED's 4mm forwards to cater for large hotend heater blocks

- Modified CPAP Front Mounts to move the Nozzle LED's 4mm forwards to cater for large heater blocks

### 2026-05-16

- Modified all Hotend mounts to provide more space for cables and slightly more surface contact between the part and the hotend. Cable tie points to the rear have been redesigned to help provide more space
- Updated Hotend mounts to remove thin walls
- Updated 4010 Front High mount to widen single wall

### 2026-05-17

- Updated Alternative_Extruder_Spacer to allow 4 screw attachment to Hotend mounts when using an LGX Lite mount pattern extruder

- Updated All Hotend mounts to cater for the 4 screw attachment change

- Updated Bowden mounts to cater for the 4 screw attachment change

- Updated Crossbow_Cutter Mount to cater for the 4 screw attachment change

### 2026-05-22

- Withdrawn the DB pattern mount adapter
- Updated 4010 Left and Right Fan mounts tidying up parts of the design
- All PCB mounts updated with additional zip tie points

### 2026-05-24

- Modified 4010 Fan mount aesthetics

- Minor changes to 4010 Front mounts

- Resized the PCB Spacers to make them a slightly tighter fit

- Modified the PCB Mounts to better print the motor connector pin gap

### 2026-06-01

- Modified the 4010 Fan mounts to better fit the HoneyBadger fans

- Updated the Roto Vitamins cover to make it more symmetrical

- Modified multiple PCB mounts to support the following SB PCB's:
  
  - Generic Hartk 2pc Stealthburner PCB
  
  - LDO Nitehawk-SB*
  
  - EBB SB*
  
  Unsupported:
  
  - EBB SB* USB
  
  - FYSETC SB*
  
  Note: Not all PCB mounts or all variations of the PCB boards are supported. These are provided as a legacy option as the 36mm boards are the ones supported

- Added 10mm spacers for the EBB SB PCB mounts

- Added Dragon Ace MZE hotend mount

### 2026-06-05

- Modified the SB PCB mounts

- Modified the non-PUG PCB mounts

- Added a Generic ADXL mount

- Added an E3D PZ PCB mount

- Increased the height of the Crossbow mount

### 2026-06-18

- Modified WWG2_Umbilical_PCB36_Pug_Mount and WWG2_Umbilical_PCB36_Mount to accommodate NHSB v2

- Modified the Nozzle 1x and 2x LED mounts to better fit the Neopixel LEDs

### 2026-06-19

- Updated all 5015 Front mounts to be consistent in design and to add extra cabling space
- Modified Crossbow Cutter mount to fix some geometry issues

### 2026-06-24

- Added LED Jigs for single and double nozzle and single logo Neopixel LED wiring. A strip Neopixel Jig is also included, but it's a little fiddly as the wires solder onto the face, which has to be done prior to mounting into the Jig which can then be used for the Logo LED
  Note: The Jigs are for Neopixel LED's, not others such as BARF LED's
  Note: This is a fixed length between the Nozzle and Logo LED's. Different Front mounts have different distances. The Jig distance is the longest of these
- Modification to the 5015 Left Fan Mount to allow for taller fans at the rear of the mount

### 2026-06-27

- Updated the geometry of the Logo Neopixel and BARF LED Carriers

- Modified all the Nozzle LED mounts

- Modified all 4010 and 5015 Front mounts to cater for the LED changes that give an extra 1mm space above for wires and solder joints
  Note: You will need to print new Nozzle LED mounts to fit the new 4010 and 5015 Front mounts

### 2026-06-28

- Added README.md files to the STL directory and sub-directories that describe the contents of each directory to help users choose parts for their version of the toolhead

### 2026-07-08

- Added ReVolcano hotend mount

- Exported all STL's in High resolution

### 2026-07-12

- Minor cosmetic changes to the 4010 Front mounts to match the 5015 Front mounts

### 2026-07-14

- Added a keying nub to the PUG clamp and associated Umbilical mounts to make orientation clear

- Modified all of the non-chain PCB mounts to improve printability and cosmetic issues

- Fixed a missing heatset insert hole in the Generic Umbilical_PCB36_Pug_Mount_Left mount

### 2026-07-18

- Added abbreviated hotend names to the Hotend mount STL's and cross-referenced them in the Hardware Compatibility document

### 2026-07-24

- Due to popular demand, the pattern indented Front mount parts have made a return. They are in the /Extras/ folder as 3mf files. This allows you to either print in 2 colours, or hide the cutter parts and print an indented part instead

### 2026-08-11

- Added missing chamfer to one of the 4010 Front mounts

- Improved screw engagement for the lower 8mm screw on all of the PCB/Chain mounts

- Modified the Umbilical PCB mounts to move the left rear zip tie to avoid interference with the heat insert mount next to it

- Modified some of the Umbilical PCB mounts to add zip tie locations missing due to differing geometry compared to the majority of the other mounts

### 2026-08-14

- Modified the generic and BTT daughterboard mounts to allow more room for a cutter bar

- Fixed dimensions of the PCB mount spacers

### 2026-08-19

- Added Left and Right Generic "Integrated" 36mm PCB PUG mounts

### 2026-09-26

- Tidied up geometry for all Front and Fan mount parts

- Removed the test documents

- Added the Downdraft Assembly Manual

### 2026-10-10

- Added Rapido X hotend mount
- Tidied up CAD for all hotend mounts

### 2026-10-11

- Modified the 5015 spacer for the 2510 fan to use an M3x20mm screw

- Updated BOM and manual for the screw length change

### 2026-10-21

- Added notch to prevent 5015 front fan springs from inserting to far on the 5015 Front mounts
