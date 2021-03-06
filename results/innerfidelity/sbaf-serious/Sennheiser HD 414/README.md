# Sennheiser HD 414

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 5.8; 73 5.1; 78 4.3; 83 3.7; 89 3.1; 95 2.5; 102 1.8; 109 1.5; 117 1.0; 125 0.5; 134 0.1; 143 -0.3; 153 -0.6; 164 -0.8; 175 -1.0; 188 -1.1; 201 -1.2; 215 -1.1; 230 -1.1; 246 -1.1; 263 -1.0; 282 -0.8; 301 -0.7; 323 -0.8; 345 -0.7; 369 -0.6; 395 -0.5; 423 -0.2; 452 -0.1; 484 -0.2; 518 -0.2; 554 0.1; 593 0.3; 635 0.3; 679 0.2; 726 0.2; 777 0.4; 832 0.2; 890 0.2; 952 0.1; 1019 0.0; 1090 -0.1; 1167 -0.2; 1248 -0.4; 1336 -0.9; 1429 -1.4; 1529 -2.0; 1636 -2.4; 1751 -2.5; 1873 -2.2; 2004 -1.7; 2145 -1.7; 2295 -2.5; 2455 -4.1; 2627 -5.9; 2811 -6.0; 3008 -3.9; 3219 -2.0; 3444 -0.9; 3685 -0.2; 3943 0.9; 4219 2.0; 4514 3.4; 4830 5.5; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 414 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 51 Hz   | 0.26 | 7.4 dB  |
| Peaking | 155 Hz  | 0.69 | -5.6 dB |
| Peaking | 1669 Hz | 3.68 | -2.3 dB |
| Peaking | 2746 Hz | 3.54 | -6.7 dB |
| Peaking | 5463 Hz | 2.37 | 7.1 dB  |
| Peaking | 60 Hz   | 0.94 | -0.9 dB |
| Peaking | 65 Hz   | 2.95 | 1.6 dB  |
| Peaking | 774 Hz  | 2.73 | 0.5 dB  |
| Peaking | 6564 Hz | 6.82 | 2.5 dB  |
| Peaking | 7648 Hz | 2.15 | -1.5 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20HD%20414/Sennheiser%20HD%20414.png)