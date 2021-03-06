# Denon AH-C360

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -1.2dB
GraphicEQ: 10 -84; 20 -7.6; 22 -7.7; 23 -7.8; 25 -7.9; 26 -7.9; 28 -8.0; 30 -8.1; 32 -8.2; 35 -8.4; 37 -8.4; 40 -8.5; 42 -8.5; 45 -8.6; 49 -8.7; 52 -8.9; 56 -9.0; 59 -9.1; 64 -9.2; 68 -9.4; 73 -9.5; 78 -9.7; 83 -9.9; 89 -10.1; 95 -10.3; 102 -10.3; 109 -10.3; 117 -10.3; 125 -10.3; 134 -10.3; 143 -10.3; 153 -10.2; 164 -10.1; 175 -9.9; 188 -9.7; 201 -9.5; 215 -9.2; 230 -8.8; 246 -8.5; 263 -8.2; 282 -7.8; 301 -7.3; 323 -6.9; 345 -6.4; 369 -6.0; 395 -5.5; 423 -4.9; 452 -4.3; 484 -4.0; 518 -3.5; 554 -2.8; 593 -2.2; 635 -1.7; 679 -1.4; 726 -0.9; 777 -0.4; 832 -0.2; 890 -0.0; 952 0.0; 1019 0.0; 1090 0.1; 1167 0.0; 1248 0.0; 1336 -0.3; 1429 -0.8; 1529 -1.3; 1636 -1.4; 1751 -0.6; 1873 0.8; 2004 1.0; 2145 0.6; 2295 0.4; 2455 0.7; 2627 0.5; 2811 0.2; 3008 0.2; 3219 -0.0; 3444 -0.6; 3685 -1.6; 3943 -2.8; 4219 -4.9; 4514 -6.5; 4830 -7.6; 5168 -8.0; 5530 -8.0; 5917 -7.1; 6331 -5.2; 6775 -3.7; 7249 -3.2; 7756 -3.9; 8299 -4.6; 8880 -4.0; 9502 -1.6; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-1.1644550617593619dB` and instead set Global volume in the UI for both channels to **-11**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Denon AH-C360 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-0.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -0.1dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 35 Hz    | 0.24 | -7.8 dB |
| Peaking | 150 Hz   | 0.7  | -5.8 dB |
| Peaking | 313 Hz   | 1.23 | -3.3 dB |
| Peaking | 5418 Hz  | 2.02 | -8.6 dB |
| Peaking | 24000 Hz | 2.32 | -2.4 dB |
| Peaking | 895 Hz   | 3.48 | 1.0 dB  |
| Peaking | 2886 Hz  | 1.55 | 1.6 dB  |
| Peaking | 4478 Hz  | 5.15 | -2.2 dB |
| Peaking | 8497 Hz  | 3.66 | -5.6 dB |
| Peaking | 8753 Hz  | 1.32 | 2.4 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Denon%20AH-C360/Denon%20AH-C360.png)