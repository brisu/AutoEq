# Brainwavz R3

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 4.2; 22 4.0; 23 3.9; 25 3.7; 26 3.6; 28 3.4; 30 3.3; 32 3.1; 35 2.9; 37 2.8; 40 2.6; 42 2.5; 45 2.3; 49 2.0; 52 1.8; 56 1.5; 59 1.3; 64 1.0; 68 0.8; 73 0.4; 78 0.1; 83 -0.2; 89 -0.6; 95 -0.9; 102 -1.3; 109 -1.4; 117 -1.7; 125 -2.0; 134 -2.2; 143 -2.4; 153 -2.6; 164 -2.7; 175 -2.8; 188 -2.9; 201 -3.0; 215 -2.9; 230 -2.9; 246 -3.0; 263 -2.9; 282 -2.8; 301 -2.7; 323 -2.6; 345 -2.5; 369 -2.3; 395 -2.1; 423 -1.9; 452 -1.6; 484 -1.5; 518 -1.3; 554 -1.0; 593 -0.6; 635 -0.4; 679 -0.3; 726 -0.1; 777 0.2; 832 0.2; 890 0.2; 952 0.1; 1019 0.0; 1090 -0.0; 1167 0.0; 1248 0.5; 1336 -0.3; 1429 -0.8; 1529 -1.0; 1636 -1.3; 1751 -2.0; 1873 -1.9; 2004 -2.0; 2145 -1.6; 2295 -0.3; 2455 2.1; 2627 4.7; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 4.3; 4830 5.4; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999999918781dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Brainwavz R3 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 18 Hz    | 0.34 | 4.1 dB  |
| Peaking | 201 Hz   | 0.59 | -3.4 dB |
| Peaking | 2050 Hz  | 2.05 | -6.4 dB |
| Peaking | 3021 Hz  | 1.16 | 7.9 dB  |
| Peaking | 5716 Hz  | 3.19 | 4.7 dB  |
| Peaking | 805 Hz   | 3.07 | 0.7 dB  |
| Peaking | 1483 Hz  | 6.63 | -0.5 dB |
| Peaking | 6554 Hz  | 8.15 | 1.9 dB  |
| Peaking | 7714 Hz  | 3.63 | -1.4 dB |
| Peaking | 10018 Hz | 1.75 | -0.5 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Brainwavz%20R3/Brainwavz%20R3.png)