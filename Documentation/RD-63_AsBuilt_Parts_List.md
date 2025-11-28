# RD-63 "Vespa" As-Built Parts List

**Last Updated**: 2024-11-28
**Document Version**: 1.0
**Status**: Parts Ordered - Awaiting Delivery

---

## Current Configuration Status

| System | Component | Status | Notes |
|--------|-----------|--------|-------|
| Frame | SpeedyBee Bee35 | Ordered | 3.5" cinewhoop with prop guards |
| FC/ESC | HDZero Halo Stack | Ordered | Primary - H743, 70A, integrated ELRS |
| FC/ESC (Alt) | SpeedyBee F405 Mini Stack | Ordered | Backup option - F405, 35A |
| Motors | EMAX ECO II 2004 3000KV (x4) | Ordered | - |
| Props | Gemfan Hurricane 3525 | Ordered | Tri-blade |
| Video TX | HDZero Race V3 | Ordered | - |
| Camera | HDZero Nano 90 V2 | Ordered | - |
| Receiver | Integrated (Halo Stack) | Ordered | ELRS 2.4GHz Gemini RX |
| GPS | None | N/A | Not planned for initial build |
| Batteries | Tattu 4S (x8 total) | Ordered | 850mAh HV + 650mAh standard |

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
| **Status** | Ordered |

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
| **Status** | Ordered |

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
| **Status** | Ordered |

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
| **Status** | Ordered (backup) |

#### ESC

| Attribute | Value |
|-----------|-------|
| **Model** | SpeedyBee 35A 4in1 BLHeli_S |
| **Input Voltage** | 3S - 6S |
| **Current Rating** | 35A continuous |
| **Firmware** | BLHeli_S |
| **Status** | Ordered (backup) |

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
| **Status** | Ordered |

### Propellers

| Attribute | Value |
|-----------|-------|
| **Model** | Gemfan Hurricane 3525 |
| **Size** | 3.5" diameter |
| **Pitch** | 2.5" |
| **Blades** | 3 (tri-blade) |
| **Material** | Polycarbonate (PC) |
| **Weight** | 1.7g each |
| **Shaft** | 1.5mm (M5 adapter included) |
| **Status** | Ordered |

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
| **Status** | Ordered |

### Camera

| Attribute | Value |
|-----------|-------|
| **Model** | HDZero Nano 90 V2 |
| **Frame Rates** | 90fps (540p), 60fps (540p/720p) |
| **Latency** | 3ms pixel / 14ms glass-to-glass |
| **Lens** | RC18D |
| **Status** | Ordered |

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
| **Status** | Ordered |

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
| **Status** | Ordered |

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

---

## Known Issues

*No issues documented yet.*

---

## Pending Upgrades

*No pending upgrades - initial build in progress.*
