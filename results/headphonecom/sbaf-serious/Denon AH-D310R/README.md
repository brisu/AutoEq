# Denon AH-D310R

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 5.9; 22 5.3; 23 5.0; 25 4.5; 26 4.3; 28 3.9; 30 3.6; 32 3.3; 35 2.9; 37 2.7; 40 2.4; 42 2.2; 45 1.9; 49 1.6; 52 1.4; 56 1.1; 59 0.9; 64 0.8; 68 0.8; 73 1.0; 78 1.2; 83 0.8; 89 0.2; 95 -0.2; 102 -0.4; 109 -0.5; 117 -0.6; 125 -0.8; 134 -1.0; 143 -1.1; 153 -1.4; 164 -2.0; 175 -2.6; 188 -2.8; 201 -2.6; 215 -2.6; 230 -2.5; 246 -2.3; 263 -2.1; 282 -1.4; 301 -0.3; 323 0.1; 345 -0.1; 369 0.4; 395 1.0; 423 1.1; 452 1.6; 484 2.0; 518 2.1; 554 2.2; 593 2.8; 635 3.9; 679 4.9; 726 5.0; 777 3.4; 832 1.2; 890 0.1; 952 0.1; 1019 0.0; 1090 -0.1; 1167 -0.3; 1248 -0.6; 1336 -0.8; 1429 0.9; 1529 5.9; 1636 3.0; 1751 2.5; 1873 5.8; 2004 5.1; 2145 3.4; 2295 4.0; 2455 5.9; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.5; 4514 2.8; 4830 3.8; 5168 6.0; 5530 4.9; 5917 5.4; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.0; 9502 -2.0; 10167 -0.5; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.126096888789688dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Denon AH-D310R ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 22 Hz   |  1.13 | 5.3 dB  |
| Peaking | 678 Hz  |  3.93 | 5.1 dB  |
| Peaking | 1896 Hz |  3.56 | 3.3 dB  |
| Peaking | 3216 Hz |  1.48 | 6.3 dB  |
| Peaking | 5865 Hz |  3.4  | 4.7 dB  |
| Peaking | 206 Hz  |  1.6  | -3.1 dB |
| Peaking | 456 Hz  |  2.31 | 1.6 dB  |
| Peaking | 1352 Hz |  2.61 | -2.6 dB |
| Peaking | 1526 Hz | 11.55 | 6.0 dB  |
| Peaking | 9291 Hz |  5.37 | -2.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Denon%20AH-D310R/Denon%20AH-D310R.png)