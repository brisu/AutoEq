# Sennheiser HD 419

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -6.1; 22 -6.4; 23 -6.5; 25 -6.8; 26 -6.8; 28 -7.0; 30 -7.1; 32 -7.3; 35 -7.4; 37 -7.5; 40 -7.6; 42 -7.7; 45 -7.8; 49 -7.8; 52 -7.9; 56 -8.0; 59 -8.0; 64 -7.9; 68 -8.0; 73 -8.1; 78 -7.7; 83 -6.8; 89 -4.7; 95 -5.3; 102 -8.2; 109 -9.3; 117 -9.7; 125 -9.7; 134 -9.6; 143 -10.0; 153 -10.0; 164 -9.5; 175 -10.1; 188 -10.3; 201 -10.1; 215 -10.1; 230 -9.9; 246 -9.2; 263 -8.4; 282 -7.5; 301 -6.7; 323 -5.9; 345 -5.3; 369 -4.0; 395 -2.8; 423 -2.4; 452 -2.1; 484 -2.1; 518 -2.5; 554 -3.0; 593 -2.8; 635 -2.0; 679 -1.3; 726 -1.1; 777 -1.2; 832 -1.0; 890 -0.1; 952 -0.3; 1019 0.0; 1090 -0.5; 1167 -0.8; 1248 -0.4; 1336 -1.0; 1429 -1.6; 1529 -1.9; 1636 -1.9; 1751 -2.1; 1873 -2.3; 2004 -1.6; 2145 -0.3; 2295 1.1; 2455 1.6; 2627 1.2; 2811 2.1; 3008 2.1; 3219 2.1; 3444 2.1; 3685 1.9; 3943 3.6; 4219 6.0; 4514 6.0; 4830 6.0; 5168 4.9; 5530 5.1; 5917 5.6; 6331 4.9; 6775 3.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099993182728349dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 419 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.5dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 27 Hz   | 0.76 | -6.3 dB |
| Peaking | 57 Hz   | 1.84 | -3.1 dB |
| Peaking | 164 Hz  | 0.68 | -9.3 dB |
| Peaking | 244 Hz  | 2.5  | -2.3 dB |
| Peaking | 4938 Hz | 1.77 | 6.4 dB  |
| Peaking | 93 Hz   | 6.86 | 5.3 dB  |
| Peaking | 95 Hz   | 2.46 | -2.2 dB |
| Peaking | 1867 Hz | 2.38 | -3.7 dB |
| Peaking | 2323 Hz | 2.03 | 2.3 dB  |
| Peaking | 8476 Hz | 4.33 | -1.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sennheiser%20HD%20419/Sennheiser%20HD%20419.png)