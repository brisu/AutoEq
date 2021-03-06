# Sennheiser Momentum

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 3.6; 22 3.4; 23 3.3; 25 3.2; 26 3.1; 28 2.9; 30 2.8; 32 2.7; 35 2.6; 37 2.5; 40 2.3; 42 2.2; 45 2.1; 49 2.0; 52 1.8; 56 1.7; 59 1.5; 64 1.4; 68 1.2; 73 0.9; 78 0.7; 83 0.5; 89 0.2; 95 -0.1; 102 -0.3; 109 -0.3; 117 -0.3; 125 -0.3; 134 -0.2; 143 -0.4; 153 -0.9; 164 -1.2; 175 -0.7; 188 -1.0; 201 -1.3; 215 -1.3; 230 -1.2; 246 -1.1; 263 -0.9; 282 -0.6; 301 -0.3; 323 -0.0; 345 0.4; 369 0.8; 395 1.1; 423 1.5; 452 1.5; 484 1.4; 518 1.4; 554 1.6; 593 1.5; 635 1.3; 679 0.9; 726 0.7; 777 0.7; 832 0.4; 890 0.1; 952 -0.0; 1019 0.0; 1090 0.1; 1167 0.1; 1248 -0.0; 1336 -0.5; 1429 -1.1; 1529 -1.4; 1636 -1.4; 1751 -1.2; 1873 -0.6; 2004 0.0; 2145 1.0; 2295 2.1; 2455 3.7; 2627 4.7; 2811 5.6; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999999678133dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser Momentum ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 22 Hz   | 1.27 | 3.4 dB  |
| Peaking | 48 Hz   | 2.07 | 1.5 dB  |
| Peaking | 526 Hz  | 2.52 | 1.7 dB  |
| Peaking | 1704 Hz | 2.06 | -3.6 dB |
| Peaking | 3811 Hz | 0.88 | 7.1 dB  |
| Peaking | 205 Hz  | 1.87 | -1.5 dB |
| Peaking | 2820 Hz | 4.92 | 1.3 dB  |
| Peaking | 3849 Hz | 2.78 | -1.0 dB |
| Peaking | 6301 Hz | 2.45 | 5.3 dB  |
| Peaking | 7334 Hz | 1.5  | -4.0 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20Momentum/Sennheiser%20Momentum.png)