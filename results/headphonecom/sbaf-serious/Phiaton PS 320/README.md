# Phiaton PS 320

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 3.3; 22 3.1; 23 3.0; 25 3.0; 26 3.1; 28 3.2; 30 3.3; 32 3.3; 35 3.0; 37 2.8; 40 2.7; 42 2.7; 45 2.6; 49 2.4; 52 2.3; 56 2.5; 59 3.0; 64 3.7; 68 3.4; 73 2.0; 78 1.2; 83 0.7; 89 0.2; 95 -0.2; 102 -0.6; 109 -0.7; 117 -0.5; 125 -0.4; 134 -0.3; 143 0.3; 153 1.0; 164 -0.0; 175 -1.5; 188 -2.4; 201 -2.9; 215 -3.1; 230 -3.2; 246 -3.8; 263 -4.3; 282 -4.3; 301 -4.0; 323 -3.7; 345 -3.3; 369 -2.2; 395 -1.3; 423 -0.6; 452 -0.4; 484 0.2; 518 1.1; 554 1.9; 593 2.3; 635 2.7; 679 2.8; 726 2.5; 777 2.3; 832 2.0; 890 1.5; 952 0.8; 1019 -0.3; 1090 -1.2; 1167 -1.6; 1248 -1.9; 1336 -2.3; 1429 -3.0; 1529 -3.4; 1636 -3.7; 1751 -4.2; 1873 -3.9; 2004 -4.0; 2145 -4.9; 2295 -4.2; 2455 -3.0; 2627 -1.7; 2811 -0.2; 3008 0.9; 3219 1.6; 3444 1.9; 3685 2.3; 3943 2.9; 4219 4.1; 4514 5.5; 4830 6.0; 5168 6.0; 5530 6.0; 5917 4.0; 6331 0.0; 6775 -1.0; 7249 -0.4; 7756 -0.6; 8299 -2.1; 8880 -2.8; 9502 -0.8; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -0.5; 15258 -3.8; 16326 -4.9; 17469 -4.6; 18692 -5.0; 20000 -7.1
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099856830925146dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Phiaton PS 320 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 28 Hz    | 0.91 | 3.5 dB  |
| Peaking | 65 Hz    | 4.61 | 3.1 dB  |
| Peaking | 266 Hz   | 2.22 | -4.8 dB |
| Peaking | 1943 Hz  | 2.06 | -5.2 dB |
| Peaking | 4802 Hz  | 2.71 | 7.0 dB  |
| Peaking | 351 Hz   | 3.57 | -1.6 dB |
| Peaking | 704 Hz   | 1.52 | 3.5 dB  |
| Peaking | 1244 Hz  | 2.01 | -1.8 dB |
| Peaking | 3253 Hz  | 5.29 | 1.6 dB  |
| Peaking | 19728 Hz | 0.64 | -6.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Phiaton%20PS%20320/Phiaton%20PS%20320.png)