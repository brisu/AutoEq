# Sony MDR-7502

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 6.0; 143 6.0; 153 6.0; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 6.0; 230 6.0; 246 6.0; 263 6.0; 282 6.0; 301 6.0; 323 6.0; 345 6.0; 369 6.0; 395 6.0; 423 6.0; 452 6.0; 484 6.0; 518 5.0; 554 3.7; 593 2.8; 635 2.0; 679 1.4; 726 1.3; 777 1.3; 832 1.0; 890 0.4; 952 0.1; 1019 0.0; 1090 -0.1; 1167 -0.3; 1248 -0.4; 1336 -0.9; 1429 -1.9; 1529 -2.7; 1636 -2.4; 1751 -2.1; 1873 -1.8; 2004 -0.8; 2145 -0.1; 2295 1.1; 2455 2.2; 2627 3.3; 2811 4.3; 3008 5.2; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000003dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-7502 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 53 Hz   | 0.13 | 6.2 dB  |
| Peaking | 398 Hz  | 1.3  | 3.3 dB  |
| Peaking | 1698 Hz | 1.19 | -4.1 dB |
| Peaking | 3384 Hz | 1.3  | 6.8 dB  |
| Peaking | 5644 Hz | 2.83 | 4.6 dB  |
| Peaking | 501 Hz  | 5.55 | 1.7 dB  |
| Peaking | 606 Hz  | 1.71 | -0.9 dB |
| Peaking | 1240 Hz | 6.78 | 0.9 dB  |
| Peaking | 6561 Hz | 7.29 | 2.2 dB  |
| Peaking | 7915 Hz | 2.24 | -1.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sony%20MDR-7502/Sony%20MDR-7502.png)