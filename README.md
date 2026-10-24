[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

# Printed Xol-Carriage v2

> [!WARNING] 
> ### Needs some good testing and feedback<br/>
> I have printed a few and tested that things fit, but this hasn't been stress tested yet.

<img src='docs/images/Xol-Carriage.5.png' width=640 />

An updated version of the original Xol-Carriage.

## Frequently Asked Questions (FAQ)

<dl>

  <dt>Is this a printed carriage?</dt>
  <dd>Yes. This expands on the updates made for the CNC Carriage v2.</dd>

  <dt>Do I need the metal pins and tubes for the belt clips?</dt>
  <dd>No. This currently supports only 6mm belts and the stock Voron Trident and 2.4 belt path. The belts are captured between this carriage and the MGN12H carriage on your X rail.</dd>

  <dt>What probes are supported?</dt>
  <dd>Xol-Carriage v2 is made to support Beacon/Cartographer probes and has modules to also support Klicky and PCB-Klicky. These Klicky modules also work with Klicky-00.</dd>

  <dt>What size rails will it work on?</dt>
  <dd>Xol-Carriage will work on front-facing MGN12H rails/carriages.</dd>

</dl>

<br/><br/>

## Print Settings
This print is not pre-scaled for any particular filament. Tune your print settings for accurate prints.

* 0.2mm layer height (including first layer)
* 0.4mm Nozzle
* 5 Top/bottom layers
* 5 Walls
* 55% infill
* Supports are included in the STL (no need for slicer supports)

*Note: Printing with walls wider than 0.4mm will affect the built-in support.*

<br/><br/>

## Bill of Materials

| Qty | Item                                                                                      | Note                                                                                                               |
| --- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| 1   | Printed part - Xol-Carriage-v2.stl                                                        | Main carriage part                                                                                                 |
| 1   | Printed part - Probe module                                                               | Select the STL to match your probe                                                                                 |
| 7   | DIN 562 thin square nut - M3                                                              | Used in most places a screw threads in                                                                             |
| 7   | M3x8 SHCS                                                                                 | * Fasten Xol-Carriage to MGN12H carriage <br>* MGN12H Carriage clamping<br>* 3rd Mounting point for toolhead board |
| 3   | M3 DIN9021 large flat washer                                                              | * MGN12H Carriage clamping. `Alternatively use M3 + M5 stacked washers`<br>* 3rd Mounting point for toolhead board |
| 2   | M3x8 Socket button head screw (BHCS)                                                      | "Hook" screws to hang A4T onto carriage                                                                            |
| 2   | Probe mounting screws<br>Beacon/Carographer: M3x12 BHCS<br>Klicky (both types): M3x8 BHCS | ⚠️ Screws that come with Beacon or Cartographer probe are likely to be too short                                  |

<br/><br/>



> [!TIP] 
> ### You can help support the development of this project.<br/>
> Donate at https://ko-fi.com/dwtas<br/>
[![ko-fi](docs/images/Ko-fi_TextLogo.png)](https://ko-fi.com/dwtas)

<br/><br/>


#### This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

### License clarification regarding non-commercial use:
The non-commercial aspect of this license is for cases where Xol-Carriage is the product, not the use of Xol-Carriage to create products.<br/>
I.e. if you wish to sell Xol-Carriage as a product, you would need to seek a commercial license before doing so.<br/>
It is NOT intended to prevent the use of Xol-Carriage with a printer that you use to provide commercial services. If you want to run Xol-Carriage in your print farm, go right ahead.
