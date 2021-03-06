# Sony MDR-Z1R sn3922

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -4.0; 22 -4.3; 23 -4.4; 25 -4.6; 26 -4.7; 28 -4.8; 30 -4.8; 32 -4.9; 35 -5.0; 37 -5.0; 40 -5.0; 42 -4.9; 45 -4.9; 49 -4.8; 52 -4.7; 56 -4.6; 59 -4.4; 64 -4.0; 68 -4.0; 73 -4.6; 78 -5.2; 83 -5.7; 89 -6.2; 95 -6.5; 102 -6.7; 109 -6.7; 117 -6.6; 125 -6.8; 134 -6.8; 143 -6.6; 153 -6.0; 164 -4.9; 175 -5.4; 188 -5.0; 201 -4.4; 215 -4.0; 230 -3.6; 246 -3.5; 263 -3.3; 282 -3.0; 301 -2.7; 323 -2.5; 345 -2.3; 369 -2.1; 395 -1.9; 423 -1.6; 452 -1.5; 484 -1.4; 518 -1.1; 554 -0.5; 593 -0.2; 635 -0.1; 679 -0.1; 726 0.0; 777 0.2; 832 0.1; 890 0.0; 952 0.1; 1019 0.1; 1090 0.3; 1167 0.2; 1248 0.1; 1336 -0.2; 1429 -0.7; 1529 -1.2; 1636 -1.7; 1751 -2.0; 1873 -2.1; 2004 -1.9; 2145 -1.4; 2295 -0.7; 2455 0.1; 2627 1.9; 2811 3.8; 3008 0.8; 3219 -3.6; 3444 -0.9; 3685 3.8; 3943 6.0; 4219 6.0; 4514 5.9; 4830 4.7; 5168 4.1; 5530 3.5; 5917 4.0; 6331 2.9; 6775 -0.3; 7249 -0.3; 7756 0.3; 8299 -1.6; 8880 -6.1; 9502 -9.8; 10167 -9.5; 10879 -5.0; 11640 -0.3; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999017734476dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-Z1R sn3922 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.1dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 28 Hz    | 0.81 | -4.3 dB  |
| Peaking | 126 Hz   | 0.66 | -6.3 dB  |
| Peaking | 1873 Hz  | 3.37 | -2.6 dB  |
| Peaking | 4633 Hz  | 2.02 | 6.3 dB   |
| Peaking | 9755 Hz  | 4.5  | -11.8 dB |
| Peaking | 2860 Hz  | 6.83 | 6.1 dB   |
| Peaking | 3211 Hz  | 4.89 | -7.3 dB  |
| Peaking | 3784 Hz  | 8.15 | 2.9 dB   |
| Peaking | 3971 Hz  | 6.54 | 1.1 dB   |
| Peaking | 12020 Hz | 7.28 | 1.7 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sony%20MDR-Z1R%20sn3922/Sony%20MDR-Z1R%20sn3922.png)