# RD-63 "Vespa" As-Built Parts List

**Last Updated**: 2025-12-15
**Document Version**: 1.0
**Status**: Parts Ordered - Awaiting Delivery

---

## Current Configuration Status

| System | Component | Status | Notes |
|--------|-----------|--------|-------|
| Frame | SpeedyBee Bee35 | Received | AliExpress CNG00780675384114 |
| FC/ESC | HDZero Halo Stack | Received | Primary - H743, 70A, integrated ELRS |
| FC/ESC (Alt) | SpeedyBee F405 Mini Stack | In Stock | Backup option - F405, 35A |
| Motors | EMAX ECO II 2004 3000KV (x4) | Received | AliExpress JY25CAA0D001136806 |
| Props | Gemfan Hurricane 3525-3 | Received | 10 sets (2CW+2CCW each) |
| Video TX | HDZero Race V3 | In Transit | HDZero #30050 (FedEx 886713836293) |
| Camera | HDZero Nano 90 V2 | In Transit | HDZero #30050 (FedEx 886713836293) |
| Receiver | Integrated (Halo Stack) | Received | ELRS 2.4GHz Gemini RX |
| GPS | None | N/A | Not planned for initial build |
| Batteries | Tattu 4S (x8 total) | In Stock | 850mAh HV + 650mAh standard |

---

## Airframe

### Frame

| Attribute | Value |
|-----------|-------|
| **Model** | SpeedyBee Bee35 |
| **Type** | 3.5" Cinewhoop (ducted) |
| **Wheelbase** | 153mm |
| **Material** | Carbon fiber + injection-molded prop guards |
| **Weight** | 138g |
| **Stack Mount** | 20x20mm (also supports 25.5x25.5, 30.5x30.5) |
| **Camera Mount** | 19mm / 20mm |
| **Price** | $40 |
| **Order Date** | Nov 27, 2025 |
| **Order ID** | AliExpress #8207230388097853 |
| **Tracking** | CNG00780675384114 |
| **Status** | Received |

---

## Flight Controller & ESC

### Primary: HDZero Halo Stack

#### Flight Controller

| Attribute | Value |
|-----------|-------|
| **Model** | HDZero Halo Flight Controller |
| **Processor** | STM32H743 (480MHz) |
| **Gyro** | MPU6000 or ICM42688 (TBD on delivery) |
| **BEC** | 5V/4A, 9V/3A, 4.5V/0.5A |
| **Blackbox** | 16MB Flash |
| **UARTs** | TX2/RX2, TX7/RX7, TX8/RX8, VTX MSP on TX5/RX5 |
| **Firmware Target** | Betaflight: HDZERO_HALO |
| **Mounting** | 20x20mm M4 |
| **Weight** | 5.6g |
| **Status** | Received |

#### Integrated Receiver

| Attribute | Value |
|-----------|-------|
| **Type** | ELRS 2.4GHz Gemini RX |
| **Chipset** | ESP32 + 2x SX1280 |
| **UART** | TX1/RX1 |
| **Max Power** | 10mW |
| **Antenna** | 2x u.FL |
| **Status** | Integrated with FC |

#### ESC

| Attribute | Value |
|-----------|-------|
| **Model** | HDZero Halo 4in1 70A ESC |
| **Processor** | AT32F421 (120MHz) |
| **Firmware** | BLHeli32 or AM32 (TBD on delivery) |
| **Input Voltage** | 3S - 8S (9V - 40V) |
| **Current Rating** | 70A continuous / 100A burst (per motor) |
| **Protocol** | DShot 150/300/600/1200, MultiShot, OneShot |
| **Current Sensor** | Scale = 400, Offset = 0 |
| **Mounting** | 20x20mm |
| **Weight** | 13.4g |
| **Status** | Received |

---

### Alternative: SpeedyBee F405 Mini Stack

*Backup option if Halo Stack has issues*

#### Flight Controller

| Attribute | Value |
|-----------|-------|
| **Model** | SpeedyBee F405 Mini |
| **Processor** | STM32F405 |
| **Gyro** | ICM42688P |
| **BEC** | 5V/2A, 9V/3A |
| **Blackbox** | 8MB Flash |
| **Features** | Built-in Bluetooth, barometer |
| **Mounting** | 20x20mm |
| **Status** | In Stock |

#### ESC

| Attribute | Value |
|-----------|-------|
| **Model** | SpeedyBee 35A BL_S Mini V2 20x20 4in1 |
| **Input Voltage** | 3S - 6S |
| **Current Rating** | 35A continuous |
| **Firmware** | BLHeli_S |
| **Status** | In Stock |

---

## Propulsion

### Motors (x4)

| Attribute | Value |
|-----------|-------|
| **Model** | EMAX ECO II 2004 |
| **KV** | 3000KV |
| **Stator Size** | 20x4mm |
| **Motor Dimensions** | 24.7 x 19.2mm |
| **Shaft Diameter** | 1.5mm |
| **Mounting Pattern** | 12x12mm |
| **Weight** | 18g (with wires) |
| **Max Thrust** | 1130g (on 6S) |
| **Recommended Props** | 3" - 5" |
| **Status** | Received |

### Propellers

| Attribute | Value |
|-----------|-------|
| **Model** | Gemfan Hurricane 3525-3 |
| **Size** | 3.5" diameter |
| **Pitch** | 2.5" |
| **Blades** | 3 (tri-blade) |
| **Material** | Glass Fiber Nylon |
| **Weight** | 1.7g each |
| **Shaft** | 1.5mm (M5 adapter included) |
| **Quantity** | 10 sets (2CW+2CCW each) |
| **Status** | Received |

---

## Video System

### VTX

| Attribute | Value |
|-----------|-------|
| **Model** | HDZero Race V3 |
| **Protocol** | HDZero Digital |
| **Power Output** | 25mW / 200mW (switchable) |
| **Resolutions** | 540p90, 720p60, 1080p30 |
| **Latency** | ~14ms (540p90 mode) |
| **Input Voltage** | 4V - 12V |
| **Dimensions** | 28x32x5mm |
| **Weight** | 5.5g |
| **Antenna Connector** | u.FL |
| **Status** | In Transit (FedEx 886713836293) |

### Camera

| Attribute | Value |
|-----------|-------|
| **Model** | HDZero Nano 90 V2 |
| **Frame Rates** | 90fps (540p), 60fps (540p/720p) |
| **Latency** | 3ms pixel / 14ms glass-to-glass |
| **Lens** | RC18D |
| **Status** | In Transit (FedEx 886713836293) |

### Antenna

| Attribute | Value |
|-----------|-------|
| **Model** | TBD - from existing u.FL stock |
| **Connector** | u.FL |
| **Status** | Available - testing required |

---

## Radio System

### Receiver

| Attribute | Value |
|-----------|-------|
| **Model** | Integrated ELRS Gemini RX (Halo Stack) |
| **Protocol** | ExpressLRS 2.4GHz |
| **Features** | Dual antenna diversity (Gemini) |
| **Status** | Integrated with FC |

---

## Navigation

### GPS

| Attribute | Value |
|-----------|-------|
| **Model** | None |
| **Status** | Not planned for initial build |

---

## Power System

### Batteries

#### Set 1: Tattu 850mAh 4S HV

| Attribute | Value |
|-----------|-------|
| **Model** | Tattu 850mAh 4S 95C HV |
| **Capacity** | 850mAh |
| **Cell Count** | 4S |
| **Voltage** | 15.2V (HV - 4.35V/cell) |
| **C Rating** | 95C |
| **Connector** | XT30 |
| **Quantity** | 4 |
| **Status** | In Stock |

#### Set 2: Tattu 650mAh 4S

| Attribute | Value |
|-----------|-------|
| **Model** | Tattu 650mAh 4S 95C |
| **Capacity** | 650mAh |
| **Cell Count** | 4S |
| **Voltage** | 14.8V (standard - 4.2V/cell) |
| **C Rating** | 95C |
| **Connector** | XT30 |
| **Quantity** | 4 |
| **Status** | In Stock |

---

## Weight Summary

| Component | Weight (g) |
|-----------|------------|
| Frame | 138 |
| FC (Halo) | 5.6 |
| ESC (Halo) | 13.4 |
| Motors (x4) | 72 (18g each) |
| VTX (Race V3) | 5.5 |
| Camera (Nano 90 V2) | ~3 (est.) |
| Antenna | ~2 (est.) |
| Wiring/Hardware | ~10 (est.) |
| **Dry Weight** | **~250g (est.)** |
| Battery (850mAh) | ~95g (est.) |
| Battery (650mAh) | ~75g (est.) |
| **AUW (850mAh)** | **~345g (est.)** |
| **AUW (650mAh)** | **~325g (est.)** |

*Note: Weights are estimates until actual build. Will be updated with measured values.*

---

## Build History

| Date | Change | Reference |
|------|--------|-----------|
| 2024-11-28 | Parts ordered, documentation initialized | - |
| 2025-12-02 | Props received: 10 sets Gemfan Hurricane 3525-3 | - |
| 2025-12-02 | HDZero Halo Stack in transit | FedEx 886320063930 |
| 2025-12-02 | SpeedyBee F405 Mini Stack confirmed in stock | - |
| 2025-12-02 | Tattu 4S batteries (x8) confirmed in stock | - |
| 2025-12-02 | EMAX ECO II 2004 3000KV motors in transit | AliExpress JY25CAA0D001136806 |
| 2025-11-27 | SpeedyBee Bee35 frame ordered ($40) | AliExpress #8207230388097853 |
| 2025-12-02 | SpeedyBee Bee35 frame in transit (ETA Dec 18) | CNG00780675384114 |
| 2025-12-05 | HDZero VTX + Camera shipped | FedEx 886713836293 |
| 2025-12-08 | HDZero Halo Stack received | - |
| 2025-12-15 | EMAX ECO II 2004 3000KV motors received (x4) | - |
| 2025-12-15 | SpeedyBee Bee35 frame received | - |

---

## Known Issues

*No issues documented yet.*

---

## Pending Upgrades

*No pending upgrades - initial build in progress.*
