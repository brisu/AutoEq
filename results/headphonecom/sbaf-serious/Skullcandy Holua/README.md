# Skullcandy Holua

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -9.9; 22 -9.8; 23 -9.8; 25 -9.8; 26 -9.7; 28 -9.7; 30 -9.7; 32 -9.6; 35 -9.6; 37 -9.5; 40 -9.5; 42 -9.4; 45 -9.4; 49 -9.3; 52 -9.3; 56 -9.3; 59 -9.3; 64 -9.3; 68 -9.2; 73 -9.2; 78 -9.2; 83 -9.1; 89 -9.1; 95 -8.9; 102 -8.8; 109 -8.6; 117 -8.4; 125 -8.3; 134 -8.1; 143 -7.9; 153 -7.7; 164 -7.4; 175 -7.1; 188 -6.8; 201 -6.5; 215 -6.1; 230 -5.7; 246 -5.3; 263 -4.9; 282 -4.5; 301 -4.0; 323 -3.5; 345 -3.0; 369 -2.5; 395 -2.1; 423 -1.8; 452 -1.6; 484 -1.2; 518 -0.8; 554 -0.4; 593 -0.0; 635 0.3; 679 0.6; 726 0.8; 777 0.8; 832 0.8; 890 0.6; 952 0.3; 1019 -0.1; 1090 -0.3; 1167 -0.6; 1248 -0.9; 1336 -1.5; 1429 -2.4; 1529 -3.7; 1636 -4.9; 1751 -5.9; 1873 -6.7; 2004 -7.6; 2145 -8.6; 2295 -9.6; 2455 -8.6; 2627 -5.0; 2811 -1.7; 3008 1.3; 3219 3.9; 3444 5.7; 3685 6.0; 3943 5.3; 4219 3.3; 4514 1.1; 4830 -0.6; 5168 -1.7; 5530 -0.4; 5917 2.9; 6331 5.3; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999918362887dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Skullcandy Holua ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.5dB.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 30 Hz   | 0.23 | -9.6 dB  |
| Peaking | 160 Hz  | 0.81 | -3.9 dB  |
| Peaking | 2287 Hz | 2.08 | -13.1 dB |
| Peaking | 3242 Hz | 1.43 | 6.0 dB   |
| Peaking | 3594 Hz | 4.48 | 4.1 dB   |
| Peaking | 296 Hz  | 2.72 | -0.8 dB  |
| Peaking | 788 Hz  | 1.37 | 1.8 dB   |
| Peaking | 1666 Hz | 5.13 | -1.9 dB  |
| Peaking | 5177 Hz | 5.48 | -3.8 dB  |
| Peaking | 6361 Hz | 5.98 | 5.6 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Skullcandy%20Holua/Skullcandy%20Holua.png)