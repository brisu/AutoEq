# Sony MDR-AS50G

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -0.7; 22 -1.2; 23 -1.4; 25 -1.8; 26 -2.0; 28 -2.3; 30 -2.5; 32 -2.8; 35 -3.1; 37 -3.3; 40 -3.5; 42 -3.7; 45 -3.9; 49 -4.2; 52 -4.4; 56 -4.6; 59 -4.7; 64 -5.0; 68 -5.2; 73 -5.4; 78 -5.6; 83 -5.8; 89 -6.1; 95 -6.1; 102 -6.2; 109 -6.2; 117 -6.3; 125 -6.4; 134 -6.4; 143 -6.4; 153 -6.3; 164 -6.2; 175 -6.1; 188 -5.9; 201 -5.7; 215 -5.4; 230 -5.2; 246 -5.0; 263 -4.8; 282 -4.5; 301 -4.1; 323 -3.7; 345 -3.3; 369 -2.9; 395 -2.7; 423 -2.4; 452 -2.1; 484 -1.8; 518 -1.5; 554 -1.1; 593 -0.7; 635 -0.4; 679 -0.3; 726 -0.2; 777 -0.0; 832 0.1; 890 0.1; 952 0.2; 1019 -0.0; 1090 -0.3; 1167 -0.6; 1248 -0.9; 1336 -1.4; 1429 -2.2; 1529 -3.3; 1636 -3.9; 1751 -4.2; 1873 -4.2; 2004 -4.1; 2145 -3.8; 2295 -3.2; 2455 -2.1; 2627 -0.6; 2811 1.8; 3008 4.8; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.9; 4219 3.4; 4514 -0.0; 4830 -2.5; 5168 -3.6; 5530 -2.6; 5917 -1.0; 6331 -0.4; 6775 -1.2; 7249 -3.9; 7756 -6.5; 8299 -6.5; 8880 -3.3; 9502 -0.1; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 -1.6; 14260 -5.2; 15258 -3.2; 16326 -0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.0999999970362095dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-AS50G ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.3dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 88 Hz    | 0.47 | -5.4 dB |
| Peaking | 215 Hz   | 0.91 | -2.9 dB |
| Peaking | 1976 Hz  | 1.92 | -5.2 dB |
| Peaking | 3398 Hz  | 3.16 | 8.2 dB  |
| Peaking | 7935 Hz  | 3.95 | -7.2 dB |
| Peaking | 868 Hz   | 2.49 | 1.1 dB  |
| Peaking | 4043 Hz  | 8.94 | 3.2 dB  |
| Peaking | 5069 Hz  | 5.1  | -4.5 dB |
| Peaking | 12944 Hz | 0.81 | 1.6 dB  |
| Peaking | 14426 Hz | 3.82 | -7.0 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sony%20MDR-AS50G/Sony%20MDR-AS50G.png)