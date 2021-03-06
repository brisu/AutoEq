# Sennheiser HD 800 S sn01067

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.9dB
GraphicEQ: 10 -84; 20 4.8; 22 4.3; 23 4.0; 25 3.6; 26 3.5; 28 3.2; 30 2.9; 32 2.7; 35 2.4; 37 2.2; 40 2.0; 42 1.8; 45 1.6; 49 1.5; 52 1.4; 56 1.3; 59 1.1; 64 1.1; 68 1.1; 73 0.8; 78 0.3; 83 0.1; 89 -0.1; 95 -0.6; 102 -1.1; 109 -1.3; 117 -1.6; 125 -1.9; 134 -2.0; 143 -2.2; 153 -2.3; 164 -2.3; 175 -2.4; 188 -2.5; 201 -2.6; 215 -2.6; 230 -2.6; 246 -2.7; 263 -2.7; 282 -2.5; 301 -2.5; 323 -2.4; 345 -2.3; 369 -2.2; 395 -2.1; 423 -1.9; 452 -1.8; 484 -1.7; 518 -1.7; 554 -1.4; 593 -1.1; 635 -1.1; 679 -1.0; 726 -0.9; 777 -0.5; 832 -0.4; 890 -0.2; 952 -0.1; 1019 0.1; 1090 0.4; 1167 0.4; 1248 0.9; 1336 1.1; 1429 1.3; 1529 1.7; 1636 1.5; 1751 1.4; 1873 1.3; 2004 1.6; 2145 1.6; 2295 1.6; 2455 2.1; 2627 2.6; 2811 2.0; 3008 1.9; 3219 2.2; 3444 2.0; 3685 0.4; 3943 -0.3; 4219 -0.4; 4514 -0.0; 4830 0.4; 5168 -0.0; 5530 -1.3; 5917 -1.8; 6331 -3.7; 6775 -3.7; 7249 -2.3; 7756 -1.1; 8299 -0.8; 8880 -0.9; 9502 -0.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 -0.3; 14260 -1.3; 15258 -0.7; 16326 -0.0; 17469 0.0; 18692 0.0; 20000 -0.3
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-4.8546460294946785dB` and instead set Global volume in the UI for both channels to **-48**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 800 S sn01067 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-3.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -4.0dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 10 Hz    | 0.2  | 4.3 dB  |
| Peaking | 221 Hz   | 0.47 | -2.9 dB |
| Peaking | 1537 Hz  | 1.54 | 1.5 dB  |
| Peaking | 2781 Hz  | 2.16 | 2.3 dB  |
| Peaking | 6586 Hz  | 3.99 | -4.2 dB |
| Peaking | 40 Hz    | 1.59 | -0.5 dB |
| Peaking | 69 Hz    | 3.57 | 0.6 dB  |
| Peaking | 8763 Hz  | 5.19 | -0.2 dB |
| Peaking | 14466 Hz | 5.87 | -1.4 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20HD%20800%20S%20sn01067/Sennheiser%20HD%20800%20S%20sn01067.png)