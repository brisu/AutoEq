# Noontec Zoro

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -1.1; 22 -1.4; 23 -1.5; 25 -1.7; 26 -1.8; 28 -2.0; 30 -2.2; 32 -2.4; 35 -2.5; 37 -2.6; 40 -2.8; 42 -2.9; 45 -3.0; 49 -3.1; 52 -3.1; 56 -3.2; 59 -3.4; 64 -3.7; 68 -3.8; 73 -3.9; 78 -4.1; 83 -4.2; 89 -4.2; 95 -4.5; 102 -4.7; 109 -4.6; 117 -4.7; 125 -4.7; 134 -4.8; 143 -5.0; 153 -5.3; 164 -5.2; 175 -5.2; 188 -5.3; 201 -5.3; 215 -5.2; 230 -5.1; 246 -4.9; 263 -4.7; 282 -4.3; 301 -4.0; 323 -4.0; 345 -4.0; 369 -3.8; 395 -3.6; 423 -3.4; 452 -3.4; 484 -3.3; 518 -3.2; 554 -3.0; 593 -2.6; 635 -2.2; 679 -1.8; 726 -1.4; 777 -0.9; 832 -0.5; 890 -0.2; 952 -0.0; 1019 -0.1; 1090 -0.1; 1167 -0.2; 1248 -0.2; 1336 -0.6; 1429 -1.3; 1529 -1.6; 1636 -1.7; 1751 -1.1; 1873 -0.2; 2004 1.1; 2145 2.5; 2295 4.2; 2455 5.7; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.2; 6331 4.4; 6775 3.5; 7249 1.3; 7756 -1.3; 8299 -4.0; 8880 -5.0; 9502 -4.2; 10167 -1.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999999994905dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Noontec Zoro ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 66 Hz    | 0.29 | -2.0 dB |
| Peaking | 256 Hz   | 0.32 | -4.0 dB |
| Peaking | 1671 Hz  | 2.03 | -6.1 dB |
| Peaking | 3436 Hz  | 0.41 | 7.6 dB  |
| Peaking | 8822 Hz  | 2.75 | -9.0 dB |
| Peaking | 553 Hz   | 6.09 | -0.5 dB |
| Peaking | 2528 Hz  | 6.09 | 1.5 dB  |
| Peaking | 4054 Hz  | 1    | -0.9 dB |
| Peaking | 5704 Hz  | 2.6  | 1.5 dB  |
| Peaking | 14567 Hz | 1.61 | -0.7 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Noontec%20Zoro/Noontec%20Zoro.png)