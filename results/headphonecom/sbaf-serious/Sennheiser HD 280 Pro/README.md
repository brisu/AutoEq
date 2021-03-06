# Sennheiser HD 280 Pro

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 0.5; 22 0.2; 23 0.0; 25 -0.2; 26 -0.3; 28 -0.5; 30 -0.6; 32 -0.7; 35 -0.8; 37 -0.8; 40 -0.7; 42 -0.7; 45 -0.5; 49 -0.2; 52 0.1; 56 0.9; 59 1.6; 64 3.0; 68 5.0; 73 6.0; 78 6.0; 83 4.5; 89 1.9; 95 0.9; 102 3.6; 109 5.9; 117 5.9; 125 4.6; 134 3.7; 143 3.5; 153 3.9; 164 4.8; 175 2.5; 188 1.7; 201 0.9; 215 0.4; 230 0.1; 246 -0.2; 263 -0.4; 282 -0.4; 301 -0.3; 323 -0.4; 345 -0.3; 369 -0.2; 395 -0.3; 423 -0.2; 452 0.0; 484 0.1; 518 0.2; 554 -0.1; 593 -0.3; 635 -0.2; 679 -0.1; 726 -0.1; 777 -0.0; 832 0.1; 890 0.1; 952 0.1; 1019 -0.1; 1090 -0.2; 1167 -0.2; 1248 -0.1; 1336 0.0; 1429 0.4; 1529 0.7; 1636 0.2; 1751 -0.7; 1873 -0.9; 2004 -1.1; 2145 -1.2; 2295 -1.8; 2455 -1.8; 2627 -0.8; 2811 1.2; 3008 3.3; 3219 3.3; 3444 2.0; 3685 1.2; 3943 1.0; 4219 1.8; 4514 1.3; 4830 2.0; 5168 3.2; 5530 3.3; 5917 2.5; 6331 1.1; 6775 0.9; 7249 -0.1; 7756 -1.3; 8299 -3.0; 8880 -4.8; 9502 -5.7; 10167 -5.1; 10879 -3.0; 11640 -0.3; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1000000000000005dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 280 Pro ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 73 Hz   | 5.01 | 5.8 dB  |
| Peaking | 126 Hz  | 2    | 5.1 dB  |
| Peaking | 3143 Hz | 7.98 | 3.8 dB  |
| Peaking | 5461 Hz | 2.88 | 3.7 dB  |
| Peaking | 9484 Hz | 3.22 | -6.4 dB |
| Peaking | 40 Hz   | 2.09 | -1.2 dB |
| Peaking | 164 Hz  | 9.93 | 2.7 dB  |
| Peaking | 264 Hz  | 1.24 | -0.8 dB |
| Peaking | 2328 Hz | 4.18 | -2.4 dB |
| Peaking | 7284 Hz | 0.14 | 0.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sennheiser%20HD%20280%20Pro/Sennheiser%20HD%20280%20Pro.png)