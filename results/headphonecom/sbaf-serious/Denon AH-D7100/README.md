# Denon AH-D7100

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -6.8; 22 -6.8; 23 -6.8; 25 -6.8; 26 -6.8; 28 -6.7; 30 -6.6; 32 -6.5; 35 -6.4; 37 -6.3; 40 -6.1; 42 -6.0; 45 -5.8; 49 -5.6; 52 -5.4; 56 -4.8; 59 -4.3; 64 -4.0; 68 -4.2; 73 -4.7; 78 -5.1; 83 -5.5; 89 -6.4; 95 -7.1; 102 -7.4; 109 -7.4; 117 -7.4; 125 -7.3; 134 -7.2; 143 -6.9; 153 -6.6; 164 -5.1; 175 -5.1; 188 -4.5; 201 -3.3; 215 -1.8; 230 0.2; 246 2.4; 263 4.5; 282 5.9; 301 6.0; 323 6.0; 345 6.0; 369 6.0; 395 6.0; 423 5.7; 452 5.3; 484 4.6; 518 4.0; 554 3.4; 593 2.8; 635 2.0; 679 1.6; 726 1.3; 777 1.1; 832 0.9; 890 0.6; 952 0.2; 1019 0.0; 1090 -0.3; 1167 -0.4; 1248 -0.8; 1336 -1.3; 1429 -2.0; 1529 -2.8; 1636 -3.4; 1751 -3.4; 1873 -3.2; 2004 -2.7; 2145 -1.9; 2295 -0.6; 2455 1.1; 2627 2.4; 2811 2.7; 3008 2.7; 3219 3.3; 3444 5.1; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 5.9; 5917 4.2; 6331 3.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.7; 8880 -4.7; 9502 -4.1; 10167 -0.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.5; 17469 -6.1; 18692 -6.1; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Denon AH-D7100 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.3dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 26 Hz    | 0.74 | -6.6 dB |
| Peaking | 141 Hz   | 0.75 | -8.7 dB |
| Peaking | 323 Hz   | 1.2  | 10.1 dB |
| Peaking | 4513 Hz  | 1.88 | 7.2 dB  |
| Peaking | 18125 Hz | 3.13 | -8.1 dB |
| Peaking | 508 Hz   | 3.28 | 1.3 dB  |
| Peaking | 1840 Hz  | 1.69 | -5.0 dB |
| Peaking | 2759 Hz  | 1.86 | 2.7 dB  |
| Peaking | 6564 Hz  | 4.56 | 2.0 dB  |
| Peaking | 9112 Hz  | 6.42 | -6.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Denon%20AH-D7100/Denon%20AH-D7100.png)