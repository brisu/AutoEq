# Sony MDR-7520

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -7.2dB
GraphicEQ: 10 -84; 20 7.1; 22 5.9; 23 5.4; 25 4.4; 26 4.0; 28 3.1; 30 2.3; 32 1.6; 35 0.5; 37 -0.1; 40 -0.9; 42 -1.5; 45 -2.2; 49 -3.1; 52 -3.7; 56 -4.4; 59 -4.8; 64 -5.5; 68 -5.9; 73 -6.3; 78 -6.7; 83 -7.1; 89 -7.4; 95 -7.8; 102 -7.9; 109 -7.9; 117 -7.7; 125 -7.5; 134 -7.1; 143 -6.3; 153 -5.8; 164 -6.1; 175 -4.6; 188 -3.2; 201 -2.6; 215 -1.8; 230 -1.3; 246 -0.4; 263 0.4; 282 0.3; 301 0.0; 323 0.8; 345 0.7; 369 0.4; 395 0.1; 423 -0.1; 452 -0.3; 484 -0.5; 518 -0.5; 554 -0.3; 593 0.1; 635 0.3; 679 0.3; 726 0.2; 777 0.3; 832 0.3; 890 0.2; 952 0.1; 1019 -0.0; 1090 -0.3; 1167 -0.5; 1248 -0.9; 1336 -1.6; 1429 -2.5; 1529 -3.6; 1636 -4.7; 1751 -5.7; 1873 -6.5; 2004 -7.9; 2145 -8.6; 2295 -8.3; 2455 -7.3; 2627 -6.7; 2811 -5.5; 3008 -3.9; 3219 -2.7; 3444 -0.9; 3685 1.9; 3943 5.3; 4219 6.0; 4514 6.0; 4830 6.0; 5168 5.8; 5530 3.6; 5917 2.9; 6331 4.2; 6775 3.9; 7249 1.3; 7756 -1.0; 8299 -6.7; 8880 -10.6; 9502 -10.8; 10167 -7.8; 10879 -2.7; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-7.1930022998878105dB` and instead set Global volume in the UI for both channels to **-71**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-7520 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.5dB.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 23 Hz   | 1.8  | 7.0 dB   |
| Peaking | 99 Hz   | 0.97 | -8.6 dB  |
| Peaking | 2381 Hz | 1.49 | -11.5 dB |
| Peaking | 4769 Hz | 0.95 | 8.6 dB   |
| Peaking | 9184 Hz | 3.53 | -14.6 dB |
| Peaking | 161 Hz  | 3.66 | -2.0 dB  |
| Peaking | 284 Hz  | 1.96 | 1.9 dB   |
| Peaking | 1711 Hz | 0.76 | 3.3 dB   |
| Peaking | 1757 Hz | 1.77 | -4.4 dB  |
| Peaking | 3217 Hz | 5.38 | -2.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sony%20MDR-7520/Sony%20MDR-7520.png)