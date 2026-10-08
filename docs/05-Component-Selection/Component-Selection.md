## Servo Motors

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Adafruit|[1143](https://www.digikey.com/en/products/detail/adafruit-industries-llc/1143/5154659)|$9.95|•5V input<br> •Small package<br> •High torque output|•Most expensive option<br> •Servo pulse widths require<br>  changes from default |

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|DFRobot|[SER0046](https://www.digikey.com/en/products/detail/dfrobot/SER0046/11613083)|$6.90|•270 degree range<br> of motion<br> •Low power<br> consumption <br> •Can be manually<br> rotated 360 degrees|•Light Torque (1.5 kg*cm)<br>•Cheaper options offer<br> similar specs<br>•Large component housing|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|DFRobot|[SER0006](https://www.digikey.com/en/pChroducts/detail/dfrobot/SER0006/7597224)|$3.62|•Light weight<br> construction<br>•Cheapest option of<br>the three<br>•Lower current draw<br>|•180 degree rotation <br>•Marginally higher torque<br>than a SER0046 (1.6 kg*cm) <br> •Large component housing<br>|

### Rationale

As similar as these three different models can be, we choose option 2 (SER0046) due to its consistency in weight and torque, as well as its bigger range of motion compared to the other two.

## Drivetrain Motors

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|NMB<br>Technologies|[PAN14EE12MD](https://www.digikey.com/en/products/detail/nmb-technologies-corporation/PAN14EE12MD/6035766?s=N4IgTCBcDaIJwBYwFoAKBBAcgRgQUT2zAFkARZTUkAXQF8g)|$7.25|•Good Output torque (4.9 mNm)<br>•Small body<br>•Inexpensive|•High rpm (12,000)<br>•12VDC - will need voltage regulator|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Mabuchi Motor|[RF370CA-15370](https://www.digikey.com/en/products/detail/mabuchi-motor/RF370CA-15370/29784566)|$11.50|•Lower RPM (5,600)<br> •Inexpensive<br> •Can take lower input voltages<br> •Small body|•Lower output torque (2.48 mNm)<br>•Will still need to gear down output|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Nidec Components|[MG16B-120-AB-00](https://www.digikey.com/en/products/detail/nidec-components/MG16B-120-AB-00/6469521)|$46.51|•Very high output torque (90 mNm)<br>•Lowest rpm (100)|•Expensive<br>•Larger body<br>•12VDC - will need voltage regulator|

### Rationale

	We decided to go with the third option because it would require the least amount of hardware design to be viable. The other options would require us to design a gearbox to reduce the RPM and increase the torque of the motor. We would rather not have to do this, so picking option 3, which features this gearbox pre-installed, was the best option for us, despite its cons.

## IR Receivers

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Vishay|[TSSP6038TT](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/TSSP6038TT/3881481)|$1.27|•Low sensitivity to bright irradiance<br>•Simple pinout|•Shortest sensing distance (2m)<br>•Most current draw (5mA)<br>•Lower center frequency (38 kHz)|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Vishay|[TSOP6256TT](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/TSOP6256TT/4075859)|$1.20|•Low current draw (700uA)<br>•Cheapest unit price<br>•Long sensing distance (40m)|•Most sensitive in bright irradiance|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Vishay|[TSSP57038TT1](http://TSSP57038TT1CT-ND)|$1.54|•Low current draw (700µA)<br>•Low sensitivity to bright irradiance|•Most expensive<br>•Lower center frequency (38 kHz)<br>•Complex pinout|

### Rationale

	We have decided to go with the TSOP6256TT because it had the highest center frequency for the lowest price. The higher the center frequency of the part, the more accurate the reading will be. Although this choice had the most sensitivity to bright irradiance, it would not be such a big issue since our working area is inside an enclosed pipe.

## IR Emitters

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Vishay|[VSMY2941GX01](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/VSMY2941GX01/10235789?gclsrc=aw.ds&gad_source=1&gad_campaignid=120565755&gclid=CjwKCAjw25fWBhAVEiwAMopNjnX8LKtFDKKKCwFQz0kozuIlXsvKDchur2SyMpzhnAWhLSI9g8RV4RoCNwAQAvD_BwE)|$0.46|•Good radiant<br>•intensity (60mW/sr @ 50mA)<br>•Low current draw (50mA)•Automotive grade|•Smallest viewing angle (16°)|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Lite-On Inc.|[LTE-R38386A-ZF-U](https://www.digikey.com/en/products/detail/liteon/LTE-R38386A-ZF-U/6819917?_gl=1*1creikt*_up*MQ..&gclid=CjwKCAjw25fWBhAVEiwAMopNjnX8LKtFDKKKCwFQz0kozuIlXsvKDchur2SyMpzhnAWhLSI9g8RV4RoCNwAQAvD_BwE&gclsrc=aw.ds)|$2.08|•Largest viewing angle (150°)<br>•Highest radiant intensity (150mW/sr @ 1A)|•Highest price<br>•Most current draw (1A)|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Kingbright|[APA3010F3C-GX](https://www.digikey.com/en/products/detail/kingbright/APA3010F3C-GX/2757934?_gl=1*15vhc31*_up*MQ..*_gs*MQ..&gclid=CjwKCAjw25fWBhAVEiwAMopNjnX8LKtFDKKKCwFQz0kozuIlXsvKDchur2SyMpzhnAWhLSI9g8RV4RoCNwAQAvD_BwE&gclsrc=aw.ds)|$0.36|•Lowest price<br>•Low current draw (20mA)|•Lowest radiant intensity (1.2mW/sr @ 20mA)|

### Rationale
  
  We decided to go with the VSMY2941GX01 because it has a good radiant intensity at a low current draw. Although it was not the most powerful of the options, it fulfilled our criteria at a fairly low price.

## Cameras

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Arducam|[B0182](https://www.digikey.com/en/products/detail/arducam/B0182/29358216)|$22.78|•High resolution (3280 x 2464)<br>•Smallest pixel size (1.1µm x 1.1µm)|•Short ribbon cable<br>•No listed FPS<br>•No found datasheet|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Himax|[HM01B0-MNA-00FT870](https://www.digikey.com/en/products/detail/himax/HM01B0-MNA-00FT870/14109821)|$19.51|•Best FPS(60) <br>•Best price |•Short ribbon cable<br>•Low resolution (324 x 324)|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Leopard Imaging|[LI-IMX219-MIPI-FF-NANO-H90](https://www.digikey.com/en/products/detail/himax/HM01B0-MNA-00FT870/14109821)|$29.00|•Long ribbon cable<br>•High resolution (3280 x 2464)<br>•Good FPS (21)|•Most expensive<br>•41 in stock|

### Rationale

	We chose the LI-IMX219-MIPI-FF-NANO-H90 because it had the longest ribbon cable, good resolution, and decent frames per second. The long cable length allows us to better place the camera in our design. Preferably, we want a camera with higher FPS, but the cable length and high resolution made us stick with this choice.

## Voltage Regulators

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Microchip Technology|[MIC5156YM](https://www.digikey.com/en/products/detail/microchip-technology/MIC5156YM/1030144?s=N4IgTCBcDaIKwHYBsBaAjADjQThXFAcgCIgC6AvkA)|$3.77|•Greater operating temperature range (-40 C -> 85 C)<br>•Low current supply required (2.7 mA)|•Low quantity in stock<br>•Much lower efficiency rating for 12V->5V (41.7%)|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Analog Devices Inc.|[LT1945EMS#TRPBF](https://www.digikey.com/en/products/detail/analog-devices-inc/LT1945EMS-TRPBF/960720)|$7.59|•Dual voltage output<br>•Reasonable quantity in stock<br>|•Most expensive option by a factor of 2<br>•Smaller range for voltage input (1.2V-15V)<br>•Low current draw available|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Texas Instruments|[LMR33620CDDAR](https://www.digikey.com/en/products/detail/texas-instruments/LMR33620CDDAR/8554846)|$2.89|•Most cost effective option<br>•Greatest quantity of parts in stock<br>•Appropriate output current (2A max.)|•May generate EMF that could interfere with analog components<br>•Higher current draw may impact efficiency|

### Rationale

  The best option for this project will be the Texas Instruments LMR33620DDAR. While it may not offer dual voltage output, it does provide an effective regulator that is efficient at a reasonable price. The output current maximum of 2 amps is also another attractive feature, whereas other regulators at this price point seem to provide less than 1 A. Even while maximizing the current drawn from this component it's efficiency should still remain high enough for the time we intend on operating the whole system.

## Power Supplies

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Oznium|[12V Battery Pack - Ni-MH Rechargeable Battery](https://www.oznium.com/install-bay/12v-rechargeable-ni-mh-battery?srsltid=AU7gw4Vuk8TiJ13rLx3_3QRzyn-6K71FnczWu4d6Cqtqf6YxRx_9LviD8tE#tech)|$14.89 (+$11.69 for charger)|•Predictable voltage and current<br>•1000 charge cycle lifespan<br>•DC plug for recharging|•Cannot be mounted on the "snake"<br>•1200 mAH life<br>•Requires additional charger which raises costs|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|GlobTek Inc.|[BL5000C21704S1PFTM104IBC1NN](https://www.digikey.com/en/products/detail/globtek-inc/BL5000C21704S1PFTM104IBC1NN/22531457)|$92.15|•More robust Li-ion construction<br>•5000 mAH lifespan<br>•Rechargeable|•Too expensive to fit in budget<br>•Doesn't include charger<br>•Adds more weight to design|

|Manufacturer|Component ID|Cost / 1 Count|Pros|Cons|
|---|---|---|---|---|
|Panasonic Energy|[6LF22XWA/B](https://www.digikey.com/en/products/detail/panasonic-energy/6LF22XWA-B/5067196)|$2.98|•Most cost effective option<br>•Large quantity in stock<br>•Potential to mount on the "snake"|•Low capacity (614 mAH)<br>•Would require a boost converter<br>•Current supply would not be enough for certain components|

### Rationale

  The best option for this project will be the 12V Ni-MH Rechargeable Battery from Oznium. This battery fits snuggly into the overall budget for the project, and also provides enough capacity to run all of the components for 1-2 hours at a time. The 12V provided also work significantly better than the 9V because the drivetrain motor would require 9V to be boosted. In every metric, primarily capacity, cost and voltage supplied, this battery pack works best.

# Bill of Materials
|Subgroup|Component Category|Part Number|Unit Price|Quantity Ordered|
|---|---|---|---|---|
|Pulley Mech.|Servo Motor|SER0046|$6.90|4|
|Drivetrain|Bevel Gears|N/A|$19.99|1|
|Drivetrain|Motor|MG16B|$46.51|1|
|IR|Receiver|TSOP6256TT|$1.20|5|
|IR|Emitter|VSMY2941GX01|$0.92|5|
|Camera|Camera|LI-IMX219-MIPI-FF-NANO-H90|$29.00|2|
|Camera|Ribbon Connector|FFC3A20-15-G|$0.48|5|
|Power Supply|Voltage Regulator|LMR33620CDDAR|$2.89|5|
|Power Supply|12V Battery Pack|N/A|$14.89|1|
|Power Supply|Battery Pack Wall Charger|N/A|$11.69|1|
|Processing|Microcontroller|ESP32-C6-WROOM-1-N8|$5.55|3|

The total for parts ordered is $222.78.
