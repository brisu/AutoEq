# Koss Tony Bennett

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.7; 26 5.6; 28 5.1; 30 4.6; 32 4.2; 35 3.6; 37 3.3; 40 2.8; 42 2.5; 45 2.1; 49 1.7; 52 1.4; 56 1.0; 59 0.7; 64 0.3; 68 0.1; 73 -0.0; 78 0.5; 83 1.5; 89 1.8; 95 0.9; 102 -0.8; 109 -1.7; 117 -2.1; 125 -2.5; 134 -3.1; 143 -3.6; 153 -3.9; 164 -3.6; 175 -3.8; 188 -4.3; 201 -4.5; 215 -4.5; 230 -4.2; 246 -4.1; 263 -3.9; 282 -3.3; 301 -2.9; 323 -2.3; 345 -1.9; 369 -1.8; 395 -2.0; 423 -2.5; 452 -3.2; 484 -3.7; 518 -3.8; 554 -3.4; 593 -3.0; 635 -2.5; 679 -2.2; 726 -1.7; 777 -0.8; 832 -0.1; 890 0.8; 952 1.0; 1019 0.1; 1090 0.6; 1167 1.4; 1248 2.1; 1336 2.4; 1429 2.5; 1529 2.5; 1636 2.5; 1751 2.4; 1873 2.7; 2004 2.7; 2145 2.5; 2295 2.1; 2455 2.2; 2627 2.0; 2811 2.2; 3008 1.7; 3219 0.9; 3444 3.0; 3685 4.9; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.1; 9502 -1.8; 10167 -0.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1000000000000005dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Koss Tony Bennett ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.1dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 18 Hz   | 0.57 | 6.5 dB  |
| Peaking | 194 Hz  | 1.08 | -4.7 dB |
| Peaking | 550 Hz  | 2    | -3.5 dB |
| Peaking | 1585 Hz | 1.18 | 2.6 dB  |
| Peaking | 4885 Hz | 1.69 | 6.8 dB  |
| Peaking | 89 Hz   | 8.55 | 2.4 dB  |
| Peaking | 3875 Hz | 5.59 | 3.7 dB  |
| Peaking | 4011 Hz | 1.89 | -1.9 dB |
| Peaking | 6300 Hz | 5.61 | 2.8 dB  |
| Peaking | 8978 Hz | 2.77 | -2.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Koss%20Tony%20Bennett/Koss%20Tony%20Bennett.png)