# Nocs NS800

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -0.3; 22 -0.3; 23 -0.3; 25 -0.3; 26 -0.3; 28 -0.3; 30 -0.3; 32 -0.4; 35 -0.4; 37 -0.5; 40 -0.5; 42 -0.6; 45 -0.7; 49 -0.9; 52 -1.0; 56 -1.2; 59 -1.3; 64 -1.4; 68 -1.5; 73 -1.8; 78 -2.0; 83 -2.2; 89 -2.3; 95 -2.4; 102 -2.6; 109 -2.7; 117 -2.7; 125 -2.9; 134 -3.0; 143 -3.1; 153 -3.3; 164 -3.2; 175 -3.3; 188 -3.3; 201 -3.2; 215 -3.2; 230 -3.1; 246 -3.1; 263 -2.9; 282 -2.8; 301 -2.6; 323 -2.4; 345 -2.1; 369 -1.9; 395 -1.7; 423 -1.6; 452 -1.3; 484 -1.2; 518 -1.0; 554 -0.7; 593 -0.4; 635 -0.2; 679 0.1; 726 0.3; 777 0.4; 832 0.4; 890 0.3; 952 0.2; 1019 -0.0; 1090 -0.3; 1167 -0.4; 1248 -0.7; 1336 -0.9; 1429 -1.3; 1529 -1.6; 1636 -1.7; 1751 -1.6; 1873 -1.5; 2004 -1.2; 2145 -1.1; 2295 -1.0; 2455 -0.8; 2627 -0.9; 2811 -1.0; 3008 -0.3; 3219 2.0; 3444 5.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999892437424dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Nocs NS800 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 130 Hz  | 0.66 | -2.7 dB |
| Peaking | 266 Hz  | 1.2  | -1.7 dB |
| Peaking | 1832 Hz | 1.87 | -2.6 dB |
| Peaking | 2821 Hz | 4.18 | -3.7 dB |
| Peaking | 4414 Hz | 1.23 | 7.3 dB  |
| Peaking | 798 Hz  | 3.3  | 0.9 dB  |
| Peaking | 3588 Hz | 7.99 | 2.2 dB  |
| Peaking | 6231 Hz | 2.65 | 5.3 dB  |
| Peaking | 6332 Hz | 0.95 | -2.6 dB |
| Peaking | 7591 Hz | 3.33 | -1.7 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Nocs%20NS800/Nocs%20NS800.png)