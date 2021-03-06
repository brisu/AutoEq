# Master Dynamic ME05

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -1.5dB
GraphicEQ: 10 -84; 20 -5.5; 22 -5.9; 23 -6.1; 25 -6.4; 26 -6.6; 28 -6.8; 30 -7.1; 32 -7.3; 35 -7.6; 37 -7.7; 40 -7.9; 42 -8.0; 45 -8.1; 49 -8.3; 52 -8.3; 56 -8.4; 59 -8.5; 64 -8.6; 68 -8.7; 73 -8.8; 78 -8.9; 83 -8.9; 89 -9.0; 95 -9.0; 102 -9.0; 109 -8.8; 117 -8.7; 125 -8.6; 134 -8.4; 143 -8.3; 153 -8.1; 164 -7.9; 175 -7.6; 188 -7.3; 201 -7.0; 215 -6.6; 230 -6.2; 246 -5.9; 263 -5.6; 282 -5.1; 301 -4.7; 323 -4.3; 345 -3.8; 369 -3.5; 395 -3.1; 423 -2.5; 452 -2.1; 484 -1.8; 518 -1.5; 554 -1.0; 593 -0.5; 635 -0.2; 679 -0.1; 726 0.1; 777 0.5; 832 0.5; 890 0.3; 952 0.1; 1019 -0.2; 1090 -0.5; 1167 -0.5; 1248 -0.7; 1336 -1.1; 1429 -1.6; 1529 -2.1; 1636 -2.6; 1751 -2.9; 1873 -3.0; 2004 -3.1; 2145 -3.3; 2295 -3.5; 2455 -3.4; 2627 -3.5; 2811 -3.6; 3008 -2.5; 3219 -1.3; 3444 -0.0; 3685 -0.1; 3943 -0.9; 4219 -2.9; 4514 -5.0; 4830 -5.8; 5168 -5.2; 5530 -3.5; 5917 -1.2; 6331 0.2; 6775 1.3; 7249 1.2; 7756 0.2; 8299 -0.9; 8880 -1.4; 9502 -0.7; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-1.4578035779399394dB` and instead set Global volume in the UI for both channels to **-14**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Master Dynamic ME05 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-1.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -0.1dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 43 Hz   | 0.38 | -7.2 dB |
| Peaking | 130 Hz  | 0.78 | -4.7 dB |
| Peaking | 262 Hz  | 1.37 | -2.5 dB |
| Peaking | 2218 Hz | 1.78 | -3.7 dB |
| Peaking | 4870 Hz | 5.01 | -6.2 dB |
| Peaking | 806 Hz  | 1.74 | 1.7 dB  |
| Peaking | 1831 Hz | 0.23 | -0.5 dB |
| Peaking | 3586 Hz | 6.82 | 2.2 dB  |
| Peaking | 6966 Hz | 5.22 | 2.4 dB  |
| Peaking | 8843 Hz | 7.06 | -1.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Master%20Dynamic%20ME05/Master%20Dynamic%20ME05.png)