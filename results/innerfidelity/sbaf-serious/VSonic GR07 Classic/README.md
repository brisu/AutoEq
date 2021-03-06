# VSonic GR07 Classic

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 2.2; 22 1.8; 23 1.6; 25 1.2; 26 1.1; 28 0.8; 30 0.5; 32 0.3; 35 0.1; 37 -0.1; 40 -0.3; 42 -0.4; 45 -0.5; 49 -0.7; 52 -0.9; 56 -1.1; 59 -1.2; 64 -1.5; 68 -1.6; 73 -1.8; 78 -2.0; 83 -2.2; 89 -2.4; 95 -2.6; 102 -2.8; 109 -2.8; 117 -2.8; 125 -2.9; 134 -3.0; 143 -3.1; 153 -3.1; 164 -3.1; 175 -3.0; 188 -3.0; 201 -3.0; 215 -2.9; 230 -2.7; 246 -2.7; 263 -2.6; 282 -2.4; 301 -2.2; 323 -2.1; 345 -1.9; 369 -1.8; 395 -1.6; 423 -1.3; 452 -1.2; 484 -1.1; 518 -0.9; 554 -0.6; 593 -0.2; 635 -0.0; 679 0.1; 726 0.2; 777 0.5; 832 0.4; 890 0.3; 952 0.2; 1019 0.0; 1090 -0.1; 1167 -0.2; 1248 -0.4; 1336 -0.7; 1429 -0.8; 1529 -1.6; 1636 -1.9; 1751 -2.1; 1873 -2.0; 2004 -1.8; 2145 -1.6; 2295 -1.1; 2455 -0.0; 2627 1.4; 2811 2.8; 3008 4.7; 3219 5.9; 3444 6.0; 3685 6.0; 3943 5.9; 4219 4.1; 4514 1.8; 4830 0.3; 5168 -0.7; 5530 -0.9; 5917 1.4; 6331 4.0; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999993210627dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `VSonic GR07 Classic ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 19 Hz    | 1.32 | 2.4 dB  |
| Peaking | 152 Hz   | 0.55 | -3.3 dB |
| Peaking | 1986 Hz  | 2.08 | -3.1 dB |
| Peaking | 3447 Hz  | 2.25 | 7.1 dB  |
| Peaking | 23485 Hz | 2.3  | 1.0 dB  |
| Peaking | 799 Hz   | 2.86 | 1.0 dB  |
| Peaking | 4061 Hz  | 8.24 | 2.0 dB  |
| Peaking | 5431 Hz  | 2.71 | -3.6 dB |
| Peaking | 6469 Hz  | 4.22 | 6.2 dB  |
| Peaking | 7568 Hz  | 2.84 | -1.1 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/VSonic%20GR07%20Classic/VSonic%20GR07%20Classic.png)