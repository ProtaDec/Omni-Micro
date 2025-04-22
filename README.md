# Omni-Micro
Double grip modular extruder, based on [Sherpa Micro](https://github.com/Annex-Engineering/Sherpa_Micro-Extruder) by Annex Engineering.
## Concept Features
- Double grip extruders have existed for a while. They help conventional* hotends reach their thermal bottleneck, adding weight and build cost;
- Smooth idler extruders, on the other hand, have proved to increase extruson consistency at the loss of grip;
- I consider this extruder a spiritual successor of the [Sherpa Crew Mini](https://github.com/jrlomas/Sherpa-Crew-Mini) by KR, whom I've been in contact with for a while. I like to think I have improved on the existing formula, while they went for something entirely different, [Mirò](https://github.com/jrlomas/miro-extruder).
  
*Untested with new-generation hotends such as [Chube](https://chubehotend.com/) by Luke's Laboratory.
## Design-specific features
- No alteration of leftover original design elements, except for "fusing" two units;
- Flippable design, compatible with most sherpa micro-friendly toolheads (TBD);
- Four driving configurations & three bowden fitting options;
- Split tensioner with either two regular springs or one cut spring;
- First layer squish compensation built-in (reliability to be confirmed);
- Idler arms and tensioners are compatible with regular Sherpa Micro.
## Future Additions
- Filament sensor.
  I have an idea of how I want to go about it, but I currently don't own any multi-material DIY printers, and the motivation just isn't there.
# BOM
![alt text](Images/BOM_Render.png)
## Fasteners

| Article                    | Qty         | Notes       |
|---------------------------|-------------|-------------|
| M3x4(+)mm Ultra Low Profile | 1           | For motor   |
| M3x6mm BHCS                | 1÷2       |             |
| M3x8mm BHCS                | 2           |             |
| M3x12mm BHCS               | 0÷2       | Bowden cap  |
| M3x18mm BHCS               | 5           |             |
| M3x20(+)mm BHCS            | 1           | For motor   |
| 3x6x0.2mm Shim             | 1           | For motor   |
| 3x6x0.5mm Shim             | 3           |             |
| M3x5x4mm Heat-set Insert   | 8÷11      |             |

## Extruder Parts

| Article                          | Qty       | Notes                     |
|----------------------------------|-----------|---------------------------|
| NEMA14 36mm Stepper 10t to 6t    | 1         |                           |
| BMG Driving Gear Assembly        | 2         | OEM RIDGA V2 preferred    |
| BMG Idler Gear Assembly          | 1÷2     |                           |
| MR73 Ball bearing                | 1÷2     |                           |
| M3x20 Idler pin                  | 2÷4     | may need sanding for mr73 |
| Bondtech Spring                  | 1÷2     |                           |
| E3D 5mm Collet                   | 0÷1     |                           |
| E3D 6mm Collet                   | 0÷1     |                           |
| ECAS04 Collet                    | 0÷1     |                           |
