# Sleek SA6 Neutral

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 3.1; 22 2.9; 23 2.8; 25 2.6; 26 2.6; 28 2.4; 30 2.2; 32 2.1; 35 1.9; 37 1.8; 40 1.6; 42 1.5; 45 1.4; 49 1.1; 52 0.9; 56 0.6; 59 0.5; 64 0.3; 68 0.0; 73 -0.4; 78 -0.6; 83 -0.8; 89 -1.1; 95 -1.3; 102 -1.5; 109 -1.6; 117 -1.8; 125 -2.0; 134 -2.2; 143 -2.4; 153 -2.6; 164 -2.7; 175 -2.8; 188 -2.9; 201 -2.9; 215 -2.8; 230 -2.8; 246 -2.8; 263 -2.7; 282 -2.6; 301 -2.4; 323 -2.2; 345 -2.0; 369 -2.0; 395 -2.1; 423 -2.0; 452 -1.8; 484 -1.6; 518 -1.3; 554 -1.1; 593 -0.8; 635 -0.5; 679 -0.3; 726 -0.1; 777 0.2; 832 0.3; 890 0.4; 952 0.2; 1019 -0.0; 1090 -0.3; 1167 -0.4; 1248 -0.7; 1336 -1.0; 1429 -1.3; 1529 -1.6; 1636 -1.7; 1751 -1.9; 1873 -1.9; 2004 -1.6; 2145 -1.2; 2295 -0.5; 2455 0.8; 2627 2.4; 2811 4.5; 3008 5.9; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999999259689dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sleek SA6 Neutral ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 19 Hz   | 0.46 | 3.0 dB  |
| Peaking | 199 Hz  | 0.57 | -3.1 dB |
| Peaking | 1952 Hz | 1.78 | -4.6 dB |
| Peaking | 3860 Hz | 0.93 | 7.5 dB  |
| Peaking | 843 Hz  | 3.64 | 0.9 dB  |
| Peaking | 3004 Hz | 6.21 | 2.2 dB  |
| Peaking | 6104 Hz | 0.7  | -2.6 dB |
| Peaking | 6188 Hz | 2.02 | 5.6 dB  |
| Peaking | 7609 Hz | 3.01 | -2.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sleek%20SA6%20Neutral/Sleek%20SA6%20Neutral.png)