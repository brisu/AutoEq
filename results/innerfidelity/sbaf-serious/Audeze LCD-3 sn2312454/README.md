# Audeze LCD-3 sn2312454

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.9dB
GraphicEQ: 10 -84; 20 2.9; 22 3.0; 23 3.0; 25 3.1; 26 3.1; 28 3.1; 30 3.0; 32 2.9; 35 2.7; 37 2.6; 40 2.6; 42 2.7; 45 2.8; 49 2.5; 52 1.7; 56 1.0; 59 0.9; 64 1.0; 68 0.9; 73 0.8; 78 0.7; 83 0.5; 89 0.3; 95 0.0; 102 -0.2; 109 -0.3; 117 -0.5; 125 -0.7; 134 -0.9; 143 -1.0; 153 -1.1; 164 -1.2; 175 -1.3; 188 -1.5; 201 -1.6; 215 -1.6; 230 -1.6; 246 -1.7; 263 -1.7; 282 -1.7; 301 -1.9; 323 -2.0; 345 -1.9; 369 -1.9; 395 -1.8; 423 -1.7; 452 -1.6; 484 -1.5; 518 -1.5; 554 -1.5; 593 -1.5; 635 -1.7; 679 -1.8; 726 -1.8; 777 -1.4; 832 -1.3; 890 -0.8; 952 -0.2; 1019 0.1; 1090 0.3; 1167 0.4; 1248 0.7; 1336 0.4; 1429 0.3; 1529 -0.0; 1636 0.1; 1751 0.6; 1873 1.0; 2004 1.2; 2145 0.9; 2295 1.0; 2455 1.1; 2627 1.0; 2811 0.7; 3008 1.0; 3219 1.3; 3444 2.1; 3685 2.5; 3943 2.5; 4219 2.5; 4514 4.6; 4830 5.5; 5168 5.5; 5530 4.1; 5917 5.1; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 -0.3; 16326 -2.5; 17469 -5.6; 18692 -6.6; 20000 -3.3
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.895640314481384dB` and instead set Global volume in the UI for both channels to **-58**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audeze LCD-3 sn2312454 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -5.6dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 28 Hz    | 0.66 | 3.3 dB  |
| Peaking | 266 Hz   | 0.64 | -2.0 dB |
| Peaking | 693 Hz   | 3.56 | -1.3 dB |
| Peaking | 5251 Hz  | 1.62 | 5.6 dB  |
| Peaking | 18517 Hz | 1.79 | -7.3 dB |
| Peaking | 1980 Hz  | 1.9  | 0.7 dB  |
| Peaking | 5572 Hz  | 8.18 | -2.0 dB |
| Peaking | 6381 Hz  | 3.74 | 3.5 dB  |
| Peaking | 7548 Hz  | 2.34 | -2.4 dB |
| Peaking | 14701 Hz | 3.83 | 1.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Audeze%20LCD-3%20sn2312454/Audeze%20LCD-3%20sn2312454.png)