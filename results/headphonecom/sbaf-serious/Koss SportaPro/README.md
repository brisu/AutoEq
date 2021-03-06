# Koss SportaPro

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.5; 37 4.9; 40 3.9; 42 3.3; 45 2.5; 49 1.4; 52 0.7; 56 -0.1; 59 -0.6; 64 -1.1; 68 -1.6; 73 -2.3; 78 -2.7; 83 -2.9; 89 -3.2; 95 -3.6; 102 -3.8; 109 -3.9; 117 -4.0; 125 -4.2; 134 -4.2; 143 -4.2; 153 -3.8; 164 -3.4; 175 -3.3; 188 -3.2; 201 -3.3; 215 -3.3; 230 -3.1; 246 -2.9; 263 -2.7; 282 -2.5; 301 -2.3; 323 -2.0; 345 -1.7; 369 -1.4; 395 -1.2; 423 -1.0; 452 -0.9; 484 -0.7; 518 -0.4; 554 -0.3; 593 -0.1; 635 0.0; 679 0.2; 726 0.3; 777 0.3; 832 0.3; 890 0.2; 952 0.1; 1019 -0.1; 1090 -0.1; 1167 -0.2; 1248 -0.5; 1336 -0.9; 1429 -1.6; 1529 -2.3; 1636 -2.8; 1751 -3.2; 1873 -3.7; 2004 -4.3; 2145 -4.7; 2295 -4.7; 2455 -4.0; 2627 -2.8; 2811 -1.8; 3008 -1.0; 3219 -1.0; 3444 -1.7; 3685 -3.7; 3943 -4.6; 4219 -1.9; 4514 -1.9; 4830 -4.6; 5168 -1.6; 5530 -0.4; 5917 2.8; 6331 5.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.8; 8880 -7.3; 9502 -8.6; 10167 -3.6; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -1.8
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1000000000000005dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Koss SportaPro ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.6dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 28 Hz   |  0.79 | 7.4 dB  |
| Peaking | 113 Hz  |  0.56 | -4.9 dB |
| Peaking | 2857 Hz |  0.7  | -3.4 dB |
| Peaking | 6433 Hz |  5.1  | 7.4 dB  |
| Peaking | 9274 Hz |  6.47 | -9.7 dB |
| Peaking | 1070 Hz |  1.03 | 2.1 dB  |
| Peaking | 2858 Hz |  0.77 | -4.8 dB |
| Peaking | 3011 Hz |  2.98 | 6.0 dB  |
| Peaking | 4853 Hz | 13.37 | -2.9 dB |
| Peaking | 4925 Hz |  0.61 | 1.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Koss%20SportaPro/Koss%20SportaPro.png)