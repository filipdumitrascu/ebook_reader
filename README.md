# Ebook Reader (OpenBook Project)

## Contributor: Dumitrașcu Filip-Teodor 333CA

## 1. Block diagram

![alt text](<Images/schema bloc.png>)

## 2. Bill Of Materials (BOM)

| Nume | Component | Link to purchase | Datasheet |
|------|------------|-------------------|-----------|
| PFMF.050.1 | VARISTORCN1812 | [Component Search Engine](https://componentsearchengine.com/part-view/VE1812K401R050/KEMET) | [Datasheet](https://content.kemet.com/datasheets/KEM_V0003_VE.pdf) |
| Rezistente | RR0402 | [Component Search Engine](https://componentsearchengine.com/part-view/R0402%201%25%20100%20K%20(RC0402FR-07100KL)/YAGEO) | [Datasheet](https://content.kemet.com/datasheets/KEM_V0003_VE.pdf)
| J2 | SAMACSYS_PARTS_USB4110-GF-A | [Component Search Engine](https://componentsearchengine.com/part-view/USB4110-GF-A/GCT%20(GLOBAL%20CONNECTOR%20TECHNOLOGY)) | [Datasheet](https://gct.co/files/drawings/usb4110.pdf) |
| D1 | USBLC6-2SC6Y | [Snapeda](https://www.snapeda.com/parts/USBLC6-2SC6Y/STMicroelectronics/view-part/?ref=eda) | [Datasheet](https://www.snapeda.com/parts/USBLC6-2SC6Y/STMicroelectronics/datasheet/) |
| Condensatoare | CC0402 | [Component Search Engine](https://componentsearchengine.com/part-view/CC0402MRX5R5BB106/YAGEO) | [Datasheet](https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf)|
| Q1 | WROVER_SPARKFUN-DISCRETESEMI_MOSFET_PCH-DMG2305UX-7 | [Component Search Engine](https://componentsearchengine.com/part-view/DMG2305UX-7/Diodes%20Incorporated) | [Datasheet](https://www.diodes.com//assets/Datasheets/DMG2305UX.pdf) |
| D2 | WROVER_AVX---SD0805S020S1R0_AVX_SD0805S020S1R0_0_0AVX_SD0805S020S1R0_0_0 | [Mouser](https://eu.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0?qs=jCA%252BPfw4LHbpkAoSnwrdjw%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/40/schottky-3165252.pdf) |
| C3 | RCL_CPOL-EUCT3528 | [Snapeda](https://eu.mouser.com/ProductDetail/KYOCERA-AVX/F910J107MBAAJ6?qs=PqoDHHvF649LraCA%2FjeGXg%3D%3D) | [Datasheet](https://s3.amazonaws.com/snapeda/datasheet/TAJB475K025RNJ_AVX.pdf) |
| J4 | 112A-TAAR-R03_ATTEND | [Snapeda](https://www.snapeda.com/parts/112A-TAAR-R03/Attend/view-part/) | [Datasheet](https://www.snapeda.com/parts/112A-TAAR-R03/Attend/datasheet/) |
| U2 | C6-WROOM-1-N8 | [Snapeda](https://www.snapeda.com/parts/ESP32-C6-WROOM-1-N8/Espressif+Systems/view-part/?ref=eda) | [Datasheet](https://www.snapeda.com/parts/ESP32-C6-WROOM-1-N8/Espressif%20Systems/datasheet/) |
| MCP73831 | WROVER_SPARKFUN-IC-POWER_MCP73831 | [Mouser](https://eu.mouser.com/ProductDetail/Microchip-Technology/MCP73831T-2ACI-OT?qs=yUQqVecv4qvbBQBGbHx0Mw%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/268/MCP73831_Family_Data_Sheet_DS20001984H-3441711.pdf) |
| CHG_LED | ADAFRUIT_LEDCHIP-LED0603 | [Snapeda](https://www.snapeda.com/parts/KP-1608SURCK/Kingbright/view-part/?ref=search&t=LED%200603) | [Datasheet](https://www.snapeda.com/parts/KP-1608SURCK/Kingbright/datasheet/) |
| L1 | 744043680IND_4828-WE-TPC_WRE | [Mouser](https://eu.mouser.com/ProductDetail/Wurth-Elektronik/744043680?qs=PGXP4M47uW6VkZq%252BkzjrHA%3D%3D) | [Datasheet](https://www.we-online.com/components/products/datasheet/744043680.pdf) |
| D3 | MBR0530 | [Snapeda](https://www.snapeda.com/parts/MBR0530/Onsemi/view-part/?ref=eda) | [Datasheet](https://www.snapeda.com/parts/MBR0530/ON%20Semiconductor/datasheet/) |
| Q3 | SI1308EDL-T1-GE3 | [Snapeda](https://www.snapeda.com/parts/SI1308EDL-T1-GE3/Vishay+Siliconix/view-part/?ref=eda) | [Datasheet](https://www.snapeda.com/parts/SI1308EDL-T1-GE3/Vishay+Siliconix/view-part/?ref=eda) |
| SJ1 | SJ | [GrabCad](https://grabcad.com/library/solder-jumpers-1) | [Datasheet](https://www.we-online.com/components/products/datasheet/609002115121.pdf) |
| J1 | FH34SRJ-24S-0.5SH_99_ | [Component Search Engine](https://componentsearchengine.com/part-view/FH34SRJ-24S-0.5SH(99)/Hirose) | [Datasheet](https://www.hirose.com/en/product/document?clcode=CL0580-1255-6-99&productname=FH34SRJ-24S-0.5SH(99)&series=FH34SRJ&documenttype=2DDrawing&lang=en&documentid=0000990903) |
| Sensor2  | WROVER_BME680_BME680 | [Snapeda](https://www.snapeda.com/parts/BME680/Bosch/view-part/?welcome=home) | [Datasheet](https://www.snapeda.com/parts/BME680/Bosch%20Sensortec/datasheet/) |
| Buttons | BUTTON_CUSYOMV1 | [Snapeda](https://www.snapeda.com/parts/EVQP7L01P/Panasonic/view-part/?ref=dk&t=evqp7l01p&con_ref=None) | [Datasheet](https://s3.amazonaws.com/snapeda/datasheet/EVQP7L01P_Panasonic.pdf) |
| U4 | MAX17048G+T10 | [Snapeda](https://www.snapeda.com/parts/MAX17048G+T10/Analog+Devices/view-part/?ref=eda) | [Datasheet](https://www.snapeda.com/parts/MAX17048G+T10/Analog%20Devices/datasheet/) |
| U3 | DS3231SN# | [Snapeda](https://www.snapeda.com/parts/RV-3029-C3-TB-QA-OPT.B/Micro%20Crystal/view-part/?ref=micro%20crystal_rel&p=DS3231SN#&t=None) | [Datasheet](https://www.snapeda.com/parts/DS3231SN%23/Analog%20Devices/datasheet/) |
| C10_SUPERCAP | CPH3225A | [Snapeda](https://www.snapeda.com/parts/CPH3225A/Seiko+Instruments/view-part/?ref=eda) | [Datasheet](https://www.snapeda.com/parts/CPH3225A/Seiko%20Instruments/datasheet/) |
| J3 | QWIIC_CONNECTORJS-1MM | [Snapeda](https://www.snapeda.com/parts/PRT-14417/SparkFun%20Electronics/view-part/?ref=search&t=QWIIC_CONNECTORJS-1MM) | [Datasheet](https://www.snapeda.com/parts/PRT-14417/SparkFun%20Electronics/view-part/?ref=search&t=QWIIC_CONNECTORJS-1MM) |
| D6,8,9,10,11,12 | PGB1010603MR | [Snapeda](https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=eda) | [Datasheet](https://www.snapeda.com/parts/PGB1010603MR/Littelfuse%20Inc./datasheet/) |
| U1 | W25Q512JVEIQ | [Snapeda](https://www.snapeda.com/parts/W25Q512JVEIQ/Winbond+Electronics/view-part/?ref=eda) | [Datasheet](https://www.snapeda.com/parts/W25Q512JVEIQ/Winbond%20Electronics/datasheet/) |

## 3. Hardware functionality description

### Components and interfaces
- **ESP32-C6-WROOM-1-N8** is the main microcontroller, responsible for managing the entire system, communicating with sensors and external modules, as well as power management.
  - Architecture: 32-bit RISC-V
  - Operating frequency: 160 MHz
  - Wireless connectivity: Wi-Fi 6 (2.4 GHz), Bluetooth 5.0

- The 3.7V, 1800mAh **Li-Po battery** provides portable power to the system.
- The MCP73831T-based charging circuit manages safe battery charging.
- The LDO regulator stabilizes the supply voltage at 3.3V for all components.

- The 7.5-inch E-Ink display allows information to be displayed with minimal power consumption.
  - Resolution: 800x480 pixels
  - Communication interface: SPI

- **SD Card Module** allows data storage on a MicroSD card (FAT32).
  - Communication interface: SPI

- **External NOR Flash memory** provides 64MB for additional storage.
  - Communication interface: SPI

- **BME688 ambient sensor** measures temperature, humidity, pressure, and gas levels.
  - Communication interface: I2C

- **The DS3231SN RTC module** keeps track of time and date even when the system is turned off.
  - Communication interface: I2C

### Connections and specifications
- **The USB-C connector** allows for system power and data transfer.
  - Integrated ESD protection and Schottky diode for reverse polarity protection.

- **Touch buttons** used for user interaction.

- **Communication interfaces** used:
- GPIO: for buttons and general I/O operations.
  - SPI: for SD Card, NOR Flash memory, and E-Ink display.
  - I2C: for BME688 sensor and RTC module.
  - UART: for debugging and serial communication.
  - Wi-Fi & Bluetooth: provided by ESP32-C6 for wireless connectivity.

## 4. Power Consumption Estimate

| Component                   | Current (mA) | Voltage (V) | Power (mW) |
|-----------------------------|--------------|-------------|------------|
| ESP32-C6 (Wi-Fi active)     | 200          | 3.3         | 660        |
| E-Paper Display (Refresh)   | 40           | 3.3         | 132        |
| BME688 Sensor (Measurement) | 3.1          | 3.3         | 10.23      |
| RTC Module (Active)         | 0.15         | 3.3         | 0.495      |
| SD Card (Active)            | 50           | 3.3         | 165        |
| External NOR Flash Memory   | 25           | 3.3         | 82.5       |


### Estimated Total Consumption
- Total Current: ~318.5 mA  
- Supply Voltage: 3.3 V  
- Total Power: 1050.72 mW

## 5. Pins used on ESP32-C6

| ESP32-C6 Pin | Functionality | Connected Component |
|--------------|----------------|----------------------|
| 3            | EPD_BUSY        | Status signal for EPD (E-paper display) |
| 4            | SS_SD           | Chip Select for SD card |
| 5            | EPD_DC          | Data/Command pin for EPD |
| 6            | SCK             | Common SPI clock line for EPD, SD Card, and external memory |
| 7            | MOSI            | Common SPI MOSI (Master Out Slave In) line for EPD, SD Card, and external memory |
| 2            | MISO            | Common SPI MISO (Master In Slave Out) line for SD Card and external memory |
| 10           | CS_EPD          | Chip Select for EPD |
| 11           | CS_FLASH        | Chip Select for external NOR Flash memory |
| 23           | EPD_RST         | Reset for EPD |
| 21           | SDA             | Common I2C data line for BME688, DS3231 and battery monitoring |
| 22           | SCL             | Common I2C clock line for BME688, DS3231, and battery monitoring |
| 18           | RTC_RST         | Reset for RTC module (DS3231) |
| 1            | 32KHZ           | 32 kHz oscillator for RTC |
| 0            | INT_RTC         | Interrupt signal from RTC |
| 9            | BOOT            | Boot/flash button (user input) |
| 15           | CHANGE          | Button for changing status/functions (user input) |
| EN           | RESET           | General reset button for the system |
| -            | USB-C           | Power supply and programming via USB-C (with ESD protection and Schottky diode) |


## 6. Design aspects and issues encountered
- **Schematic**: Components were positioned according to the system architect's specifications. (I also added frames with names). I accepted 15 warnings when checking the erc
- **PCB 2D**: I split it to get the desired shape in the specifications and placed the components on the edges with the measurements received to ensure that the 3D version fits into the case and the connectors are aligned. I also positioned the central components as in the picture in the specifications. I first autorouted the power nets with a width of 0.3 mm without passing through the bottom plane and then the normal nets of 0.15 with passage through the bottom plane. I placed via stitching near the esp module and the ground planes on both the top and bottom. Indeed, there are a lot of vias placed. Perhaps a better strategy would have been to route the normal nets first so as not to take up space and to place as few vias as possible. Another option would have been to route everything manually. (A bit hardcore for my first project in Fusion 360 with this device, a fairly complex ebook reader). I modified the footprint for parts that had 0.3 mm nets, which were wider than the part pin could support. In the DRC check, I have two approved errors about holes in the footprint of a component. (system architect's mistake)
- **3D PCB**: I downloaded the STEP file and uploaded it for each component so that it would have a 3D representation. The test pads are custom made. I placed the PCB in the case I received from the system architect. I would like to point out that the 15.30mm dimension from the top left corner (with the origin in the bottom left corner) places the SD card below the hole in the case. I chose to move the hole in the case to solve the problem (rather than changing routes, repositioning the SD card, and other 3D pushes).
- **Battery, display**: I made a custom battery and screen (I learned Fusion rather than taking the step file from the internet), noting that the connection wires are missing (a bit much for a first Fusion project). Their dimensions and components are taken from the relevant datasheets.
- **Bom, PcP** I generated the bom, pick and place, and gerbers for the pcb from manufacturing.
