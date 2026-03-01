# 🎛️ Adrian's Volume Splitter V1.0

A passive 2-channel mono audio splitter that takes a single audio input and splits it into two independent outputs, each with its own volume potentiometer for individual level control.

To use it, plug your audio source into the **Input jack (J3)**, then connect your two audio devices to **Output 1 (J1)** and **Output 2 (J2)**. Use the two potentiometers (**RV1**, **RV2**) to balance the volume on each output independently. Works best when the connected devices have any form of preamplification.

I made this because I needed to share a single audio source between two devices simultaneously without buying an expensive active splitter. I built a prototype, it worked great for my use case, and then I designed a proper PCB for it.

>  This splitter does **not** separate L/R stereo channels — it mixes both into a single mono signal on each output.

---

## Previews

### 3D Model
![PCB 3D Render](GP/PCB3D.png)

### PCB Layout
![PCB Editor](GP/PCBEDITOR.png)

### Schematic
![Schematic](GP/SCHEMATIC.png)

---

## BOM

| # | Component | Value / Description | Qty | 
|---|-----------|---------------------|-----|
| J1, J2 | TRS Jack | 3.5mm or 6.35mm Through-Hole Stereo Jack (Output) | 2 
| J3 | TRS Jack | 3.5mm or 6.35mm Through-Hole Stereo Jack (Input) | 1 
| RV1, RV2 | Potentiometer | R_Potentiometer, panel mount (e.g. 10kΩ) | 2 
| H1–H4 | Mounting Hole | M3 screw hole, no copper | 4 
| — | PCB | Adrian's Volume Splitter V1.0, Rev 1 | 1
---

