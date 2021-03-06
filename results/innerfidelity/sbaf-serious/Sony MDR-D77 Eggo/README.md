# Sony MDR-D77 Eggo

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 5.7; 45 5.2; 49 4.4; 52 4.0; 56 3.5; 59 3.2; 64 2.7; 68 2.4; 73 2.1; 78 1.9; 83 1.7; 89 1.4; 95 1.2; 102 1.1; 109 1.2; 117 1.3; 125 1.5; 134 1.4; 143 1.3; 153 1.1; 164 1.2; 175 1.4; 188 1.5; 201 1.5; 215 1.9; 230 2.1; 246 2.4; 263 2.6; 282 3.0; 301 3.4; 323 3.5; 345 3.0; 369 2.7; 395 3.2; 423 3.4; 452 3.3; 484 2.7; 518 2.2; 554 1.8; 593 1.4; 635 1.0; 679 0.7; 726 0.5; 777 0.5; 832 0.2; 890 0.1; 952 0.1; 1019 -0.2; 1090 -0.4; 1167 -0.3; 1248 0.7; 1336 2.0; 1429 1.8; 1529 0.0; 1636 -1.1; 1751 -1.8; 1873 -1.8; 2004 -1.3; 2145 -0.6; 2295 0.4; 2455 1.8; 2627 2.7; 2811 3.9; 3008 5.0; 3219 5.6; 3444 5.4; 3685 4.3; 3943 4.2; 4219 4.9; 4514 5.8; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.4; 9502 -0.1; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-D77 Eggo ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 29 Hz   | 0.68 | 6.5 dB  |
| Peaking | 350 Hz  | 1.09 | 3.4 dB  |
| Peaking | 1923 Hz | 3.53 | -3.1 dB |
| Peaking | 3218 Hz | 2.02 | 4.8 dB  |
| Peaking | 5411 Hz | 2.26 | 6.0 dB  |
| Peaking | 464 Hz  | 6.52 | 0.8 dB  |
| Peaking | 1230 Hz | 1.63 | -1.3 dB |
| Peaking | 1360 Hz | 6.12 | 3.5 dB  |
| Peaking | 6485 Hz | 6.84 | 2.5 dB  |
| Peaking | 7958 Hz | 2.08 | -1.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sony%20MDR-D77%20Eggo/Sony%20MDR-D77%20Eggo.png)