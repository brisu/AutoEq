# Shure SE425

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.2dB
GraphicEQ: 10 -84; 20 6.1; 22 5.8; 23 5.6; 25 5.4; 26 5.3; 28 5.1; 30 4.9; 32 4.7; 35 4.5; 37 4.3; 40 4.1; 42 3.9; 45 3.6; 49 3.3; 52 3.1; 56 2.8; 59 2.5; 64 2.0; 68 1.7; 73 1.4; 78 1.0; 83 0.8; 89 0.4; 95 0.1; 102 -0.1; 109 -0.5; 117 -0.6; 125 -0.9; 134 -1.3; 143 -1.5; 153 -1.7; 164 -1.8; 175 -1.9; 188 -2.0; 201 -2.1; 215 -2.1; 230 -2.1; 246 -2.1; 263 -2.1; 282 -2.1; 301 -1.8; 323 -1.8; 345 -1.8; 369 -1.5; 395 -1.4; 423 -1.4; 452 -1.1; 484 -1.0; 518 -0.9; 554 -0.5; 593 -0.3; 635 -0.1; 679 0.1; 726 0.3; 777 0.4; 832 0.3; 890 0.3; 952 0.1; 1019 -0.1; 1090 -0.3; 1167 -0.4; 1248 -0.7; 1336 -0.9; 1429 -1.4; 1529 -1.7; 1636 -1.9; 1751 -2.1; 1873 -2.1; 2004 -2.2; 2145 -2.2; 2295 -2.0; 2455 -1.5; 2627 -0.7; 2811 0.3; 3008 1.5; 3219 2.8; 3444 3.9; 3685 4.4; 3943 4.3; 4219 3.8; 4514 3.8; 4830 4.6; 5168 5.9; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.2; 7756 -0.4; 8299 -0.2; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1681292785569735dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Shure SE425 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 24 Hz   | 1.47 | 5.8 dB  |
| Peaking | 44 Hz   | 2.06 | 2.9 dB  |
| Peaking | 2408 Hz | 0.95 | -3.6 dB |
| Peaking | 3567 Hz | 1.85 | 5.9 dB  |
| Peaking | 5701 Hz | 2.94 | 6.2 dB  |
| Peaking | 45 Hz   | 1.46 | -1.2 dB |
| Peaking | 64 Hz   | 1.18 | 1.8 dB  |
| Peaking | 224 Hz  | 0.57 | -2.3 dB |
| Peaking | 800 Hz  | 1.62 | 1.3 dB  |
| Peaking | 7908 Hz | 7.3  | -1.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Shure%20SE425/Shure%20SE425.png)