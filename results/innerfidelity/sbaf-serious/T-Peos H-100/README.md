# T-Peos H-100

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.0dB
GraphicEQ: 10 -84; 20 -6.8; 22 -6.5; 23 -6.3; 25 -6.0; 26 -5.9; 28 -5.6; 30 -5.4; 32 -5.1; 35 -4.8; 37 -4.5; 40 -4.2; 42 -4.0; 45 -3.7; 49 -3.4; 52 -3.2; 56 -2.9; 59 -2.8; 64 -2.6; 68 -2.5; 73 -2.3; 78 -2.3; 83 -2.2; 89 -2.1; 95 -2.0; 102 -1.9; 109 -1.7; 117 -1.5; 125 -1.4; 134 -1.3; 143 -1.2; 153 -1.1; 164 -0.9; 175 -0.7; 188 -0.5; 201 -0.4; 215 -0.2; 230 0.0; 246 0.2; 263 0.3; 282 0.6; 301 0.7; 323 0.9; 345 1.1; 369 1.2; 395 1.4; 423 1.6; 452 1.7; 484 1.7; 518 1.8; 554 1.9; 593 2.0; 635 2.0; 679 2.0; 726 1.8; 777 1.8; 832 1.4; 890 1.0; 952 0.5; 1019 -0.1; 1090 -0.8; 1167 -1.3; 1248 -2.0; 1336 -2.9; 1429 -3.9; 1529 -4.7; 1636 -5.7; 1751 -6.7; 1873 -7.6; 2004 -8.4; 2145 -9.0; 2295 -9.0; 2455 -8.0; 2627 -7.1; 2811 -6.4; 3008 -5.7; 3219 -5.7; 3444 -3.1; 3685 0.8; 3943 3.4; 4219 3.5; 4514 2.5; 4830 2.5; 5168 3.9; 5530 5.2; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.4; 8880 -3.7; 9502 -7.3; 10167 -9.5; 10879 -8.9; 11640 -6.0; 12455 -3.1; 13327 -1.1; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.994929231343958dB` and instead set Global volume in the UI for both channels to **-59**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `T-Peos H-100 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.2dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 12 Hz    | 0.25 | -7.1 dB  |
| Peaking | 2286 Hz  | 1.52 | -9.8 dB  |
| Peaking | 4030 Hz  | 6.69 | 5.1 dB   |
| Peaking | 5983 Hz  | 2.21 | 7.6 dB   |
| Peaking | 10353 Hz | 2.87 | -10.9 dB |
| Peaking | 660 Hz   | 0.88 | 2.7 dB   |
| Peaking | 1683 Hz  | 1.51 | -2.7 dB  |
| Peaking | 2376 Hz  | 1.23 | 1.7 dB   |
| Peaking | 3193 Hz  | 6.82 | -3.1 dB  |
| Peaking | 14396 Hz | 4.59 | 1.2 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/T-Peos%20H-100/T-Peos%20H-100.png)