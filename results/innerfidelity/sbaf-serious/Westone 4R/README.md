# Westone 4R

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 3.3; 22 2.7; 23 2.5; 25 2.0; 26 1.8; 28 1.4; 30 1.0; 32 0.7; 35 0.3; 37 -0.0; 40 -0.4; 42 -0.6; 45 -0.9; 49 -1.2; 52 -1.5; 56 -1.8; 59 -2.1; 64 -2.5; 68 -2.8; 73 -3.1; 78 -3.4; 83 -3.8; 89 -4.2; 95 -4.5; 102 -4.8; 109 -4.9; 117 -5.2; 125 -5.5; 134 -5.7; 143 -5.9; 153 -5.9; 164 -6.1; 175 -6.2; 188 -6.2; 201 -6.2; 215 -6.2; 230 -6.1; 246 -6.1; 263 -6.0; 282 -5.8; 301 -5.7; 323 -5.5; 345 -5.2; 369 -5.0; 395 -4.7; 423 -4.3; 452 -4.0; 484 -3.8; 518 -3.4; 554 -2.9; 593 -2.2; 635 -1.7; 679 -1.4; 726 -0.9; 777 -0.4; 832 -0.1; 890 0.0; 952 0.1; 1019 -0.0; 1090 -0.3; 1167 -0.4; 1248 -0.6; 1336 -0.9; 1429 -1.0; 1529 -1.1; 1636 -0.9; 1751 -0.5; 1873 0.2; 2004 0.9; 2145 1.6; 2295 2.3; 2455 3.2; 2627 3.9; 2811 4.5; 3008 5.7; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.9; 8880 -4.0; 9502 -6.8; 10167 -7.6; 10879 -5.0; 11640 -0.7; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999997757682dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Westone 4R ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 18 Hz   | 1.04 | 3.5 dB   |
| Peaking | 113 Hz  | 0.66 | -3.4 dB  |
| Peaking | 271 Hz  | 0.61 | -4.9 dB  |
| Peaking | 4606 Hz | 0.85 | 7.2 dB   |
| Peaking | 9799 Hz | 3.16 | -10.1 dB |
| Peaking | 866 Hz  | 2.74 | 1.3 dB   |
| Peaking | 1597 Hz | 2.15 | -2.0 dB  |
| Peaking | 3095 Hz | 2.06 | 2.5 dB   |
| Peaking | 4270 Hz | 1.02 | -1.5 dB  |
| Peaking | 6126 Hz | 5.32 | 2.1 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Westone%204R/Westone%204R.png)