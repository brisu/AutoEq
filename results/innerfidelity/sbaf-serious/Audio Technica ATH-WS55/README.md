# Audio Technica ATH-WS55

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 4.6; 22 3.8; 23 3.4; 25 2.7; 26 2.5; 28 1.9; 30 1.5; 32 1.1; 35 0.6; 37 0.3; 40 0.1; 42 -0.1; 45 -0.4; 49 -0.8; 52 -1.1; 56 -1.3; 59 -1.5; 64 -1.7; 68 -1.8; 73 -1.8; 78 -2.0; 83 -2.1; 89 -2.1; 95 -2.1; 102 -2.4; 109 -2.7; 117 -2.9; 125 -3.3; 134 -3.4; 143 -3.4; 153 -3.5; 164 -3.3; 175 -3.3; 188 -3.3; 201 -3.1; 215 -2.6; 230 -1.8; 246 -1.0; 263 -0.6; 282 -0.2; 301 0.0; 323 0.5; 345 0.5; 369 0.7; 395 1.0; 423 1.6; 452 2.1; 484 2.2; 518 2.3; 554 2.2; 593 2.2; 635 1.9; 679 1.5; 726 1.2; 777 1.1; 832 0.7; 890 0.3; 952 0.1; 1019 -0.0; 1090 0.5; 1167 1.6; 1248 0.6; 1336 0.0; 1429 -0.2; 1529 -0.1; 1636 0.7; 1751 1.2; 1873 2.2; 2004 3.5; 2145 4.9; 2295 5.9; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.7; 6331 4.5; 6775 2.2; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999999999442dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audio Technica ATH-WS55 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.1dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 18 Hz   | 1.08 | 5.0 dB  |
| Peaking | 74 Hz   | 0.68 | -1.8 dB |
| Peaking | 163 Hz  | 1.37 | -3.1 dB |
| Peaking | 492 Hz  | 1.83 | 2.6 dB  |
| Peaking | 3658 Hz | 0.91 | 7.0 dB  |
| Peaking | 1540 Hz | 2.81 | -2.1 dB |
| Peaking | 2316 Hz | 3.32 | 2.6 dB  |
| Peaking | 3659 Hz | 2.8  | -1.2 dB |
| Peaking | 5887 Hz | 2.4  | 4.4 dB  |
| Peaking | 7190 Hz | 1.27 | -3.0 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Audio%20Technica%20ATH-WS55/Audio%20Technica%20ATH-WS55.png)