# Pump Audio Earphones

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.3dB
GraphicEQ: 10 -84; 20 -13.9; 22 -14.0; 23 -14.0; 25 -14.0; 26 -14.0; 28 -13.9; 30 -13.9; 32 -13.8; 35 -13.7; 37 -13.7; 40 -13.6; 42 -13.6; 45 -13.5; 49 -13.4; 52 -13.4; 56 -13.3; 59 -13.3; 64 -13.2; 68 -13.2; 73 -13.1; 78 -13.1; 83 -13.1; 89 -13.0; 95 -13.0; 102 -12.8; 109 -12.5; 117 -12.3; 125 -12.2; 134 -12.0; 143 -11.7; 153 -11.4; 164 -11.1; 175 -10.7; 188 -10.3; 201 -10.0; 215 -9.5; 230 -9.1; 246 -8.6; 263 -8.2; 282 -7.6; 301 -7.1; 323 -6.7; 345 -6.1; 369 -5.6; 395 -5.1; 423 -4.5; 452 -3.9; 484 -3.6; 518 -3.1; 554 -2.5; 593 -1.3; 635 -1.0; 679 -0.8; 726 -0.4; 777 0.1; 832 0.2; 890 0.2; 952 0.1; 1019 0.0; 1090 0.1; 1167 -0.0; 1248 -0.0; 1336 -0.3; 1429 -0.8; 1529 -1.1; 1636 -1.7; 1751 -2.3; 1873 -2.9; 2004 -2.9; 2145 -3.1; 2295 -3.0; 2455 -2.3; 2627 -1.9; 2811 -1.0; 3008 0.5; 3219 1.7; 3444 2.6; 3685 2.2; 3943 1.1; 4219 -1.4; 4514 -4.3; 4830 -7.6; 5168 -9.6; 5530 -5.4; 5917 0.3; 6331 3.2; 6775 3.8; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-4.293059451361583dB` and instead set Global volume in the UI for both channels to **-42**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Pump Audio Earphones ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -1.3dB.

| Type    | Fc      |     Q | Gain     |
|:--------|:--------|:------|:---------|
| Peaking | 19 Hz   |  0.33 | -12.1 dB |
| Peaking | 138 Hz  |  0.35 | -9.7 dB  |
| Peaking | 2076 Hz |  1.16 | -9.5 dB  |
| Peaking | 2310 Hz |  0.4  | 6.7 dB   |
| Peaking | 5003 Hz |  5.18 | -13.5 dB |
| Peaking | 2720 Hz |  7.3  | -1.1 dB  |
| Peaking | 3480 Hz |  5.28 | 1.9 dB   |
| Peaking | 5452 Hz | 12.45 | -3.0 dB  |
| Peaking | 6504 Hz |  4.32 | 5.3 dB   |
| Peaking | 7726 Hz |  1.17 | -2.1 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Pump%20Audio%20Earphones/Pump%20Audio%20Earphones.png)