# SOLAR CHARGER FOR MOBILE PHONES
## Overview
This project is a Solar Charger designed to convert solar energy into electrical power for charging portable electronic devices, specifically mobile phones. It utilizes a solar panel array to step down and regulate the voltage to a stable 5V USB output.

## Bill of Materials (BOM)
Please refer to the separate BOM file provided in this repository for the complete list of required components.

## Circuit Assembly & Safety
* Wire the two 6V solar cells in series to provide a 12V input to the LM2596 buck converter.
* **CRITICAL STEP:** Before connecting any device, use a multimeter to adjust the LM2596 potentiometer to output exactly 5.0V.
* Wire the 1 mF filter capacitor in parallel across the output terminals to smooth voltage ripples.
* Connect the female USB-A connector to the regulated output.

## Reference Diagrams
Block diagrams and schematics can be found in the `SOLAR-CHARGER-FOR-MOBILE-PHONES /Media/` directory.
