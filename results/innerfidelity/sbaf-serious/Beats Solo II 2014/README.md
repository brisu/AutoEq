# Beats Solo II 2014

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -2.7dB
GraphicEQ: 10 -84; 20 -4.8; 22 -5.0; 23 -5.1; 25 -5.2; 26 -5.3; 28 -5.4; 30 -5.4; 32 -5.5; 35 -5.6; 37 -5.7; 40 -5.7; 42 -5.7; 45 -5.8; 49 -5.8; 52 -5.9; 56 -6.0; 59 -6.1; 64 -6.2; 68 -6.3; 73 -6.5; 78 -6.7; 83 -6.9; 89 -7.1; 95 -7.3; 102 -7.4; 109 -7.5; 117 -7.6; 125 -7.7; 134 -7.8; 143 -8.0; 153 -8.2; 164 -8.2; 175 -7.9; 188 -8.0; 201 -8.0; 215 -8.0; 230 -7.8; 246 -7.7; 263 -7.4; 282 -7.0; 301 -6.4; 323 -5.8; 345 -5.4; 369 -5.3; 395 -4.9; 423 -4.4; 452 -4.0; 484 -3.9; 518 -3.7; 554 -3.3; 593 -2.9; 635 -1.9; 679 -1.0; 726 -0.8; 777 -0.6; 832 -0.8; 890 -1.0; 952 -0.4; 1019 -0.1; 1090 -0.7; 1167 -0.9; 1248 -1.0; 1336 -1.1; 1429 -1.2; 1529 -1.2; 1636 -1.2; 1751 -0.9; 1873 -0.4; 2004 0.1; 2145 0.4; 2295 0.7; 2455 1.3; 2627 1.7; 2811 1.7; 3008 1.4; 3219 0.8; 3444 0.2; 3685 0.3; 3943 0.8; 4219 0.8; 4514 -0.7; 4830 -1.9; 5168 0.4; 5530 2.1; 5917 2.6; 6331 1.9; 6775 0.9; 7249 0.9; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.5
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-2.678542145085054dB` and instead set Global volume in the UI for both channels to **-26**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beats Solo II 2014 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-2.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -2.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 28 Hz   | 0.38 | -4.7 dB |
| Peaking | 110 Hz  | 0.67 | -3.5 dB |
| Peaking | 240 Hz  | 0.65 | -5.8 dB |
| Peaking | 2722 Hz | 4.01 | 2.0 dB  |
| Peaking | 6035 Hz | 5.93 | 2.8 dB  |
| Peaking | 557 Hz  | 2.45 | -2.2 dB |
| Peaking | 656 Hz  | 1.45 | 1.9 dB  |
| Peaking | 1573 Hz | 2.06 | -1.3 dB |
| Peaking | 2133 Hz | 3.17 | 0.6 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Beats%20Solo%20II%202014/Beats%20Solo%20II%202014.png)