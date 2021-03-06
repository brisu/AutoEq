# Sony MDR-XB1000

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -0.7; 22 -1.5; 23 -1.9; 25 -2.7; 26 -3.1; 28 -3.9; 30 -4.6; 32 -5.2; 35 -5.8; 37 -6.0; 40 -6.3; 42 -6.5; 45 -6.6; 49 -6.9; 52 -7.3; 56 -7.9; 59 -8.2; 64 -8.5; 68 -8.7; 73 -8.9; 78 -9.1; 83 -9.4; 89 -9.6; 95 -9.9; 102 -10.1; 109 -10.3; 117 -10.5; 125 -10.8; 134 -10.9; 143 -11.0; 153 -11.1; 164 -11.1; 175 -11.3; 188 -11.4; 201 -11.3; 215 -11.2; 230 -11.1; 246 -10.9; 263 -10.5; 282 -9.9; 301 -9.3; 323 -8.8; 345 -8.2; 369 -7.7; 395 -7.2; 423 -6.4; 452 -5.7; 484 -4.8; 518 -4.0; 554 -3.4; 593 -1.4; 635 0.3; 679 1.7; 726 2.5; 777 4.0; 832 4.3; 890 3.4; 952 1.7; 1019 -0.5; 1090 -2.9; 1167 -4.6; 1248 -4.4; 1336 -3.1; 1429 -1.0; 1529 0.9; 1636 3.0; 1751 5.5; 1873 6.0; 2004 6.0; 2145 3.8; 2295 -3.3; 2455 -8.3; 2627 -7.9; 2811 -5.8; 3008 -4.3; 3219 -3.6; 3444 -2.7; 3685 -2.7; 3943 -2.9; 4219 -2.7; 4514 -2.2; 4830 2.1; 5168 6.0; 5530 4.1; 5917 -0.2; 6331 -3.4; 6775 -2.0; 7249 0.6; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.7; 10167 -1.6; 10879 -1.3; 11640 -0.6; 12455 -0.0; 13327 0.0; 14260 -0.3; 15258 -1.7; 16326 -2.5; 17469 -2.0; 18692 -1.3; 20000 -0.9
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.114170731874704dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-XB1000 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.5dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 103 Hz   | 0.37 | -9.3 dB  |
| Peaking | 290 Hz   | 0.85 | -6.9 dB  |
| Peaking | 1277 Hz  | 3.06 | -10.6 dB |
| Peaking | 1984 Hz  | 0.72 | 26.2 dB  |
| Peaking | 2517 Hz  | 1.17 | -28.4 dB |
| Peaking | 497 Hz   | 3.49 | -1.8 dB  |
| Peaking | 793 Hz   | 4.57 | 4.0 dB   |
| Peaking | 5246 Hz  | 5.67 | 12.3 dB  |
| Peaking | 5387 Hz  | 1.77 | -5.3 dB  |
| Peaking | 16888 Hz | 1.55 | -2.5 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sony%20MDR-XB1000/Sony%20MDR-XB1000.png)