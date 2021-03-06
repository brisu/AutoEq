# Fostex T20RP Mk3

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.8; 42 5.4; 45 4.3; 49 2.9; 52 1.9; 56 0.8; 59 -0.1; 64 -1.3; 68 -2.2; 73 -3.2; 78 -4.0; 83 -4.5; 89 -5.1; 95 -5.4; 102 -5.6; 109 -5.5; 117 -5.4; 125 -5.2; 134 -4.9; 143 -4.7; 153 -4.4; 164 -4.0; 175 -3.5; 188 -3.1; 201 -2.8; 215 -2.4; 230 -2.3; 246 -2.2; 263 -1.9; 282 -1.7; 301 -2.0; 323 -1.8; 345 -0.8; 369 -0.1; 395 0.1; 423 0.3; 452 0.5; 484 2.3; 518 2.2; 554 2.3; 593 2.5; 635 3.0; 679 2.9; 726 2.7; 777 2.9; 832 1.9; 890 1.2; 952 0.7; 1019 0.0; 1090 0.2; 1167 -0.3; 1248 1.0; 1336 -0.3; 1429 0.3; 1529 1.5; 1636 1.5; 1751 2.1; 1873 1.6; 2004 2.6; 2145 2.7; 2295 2.4; 2455 2.7; 2627 2.8; 2811 2.5; 3008 2.2; 3219 1.9; 3444 1.4; 3685 0.6; 3943 -0.7; 4219 -1.6; 4514 -1.1; 4830 0.9; 5168 5.1; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.2; 8299 -2.5; 8880 -5.3; 9502 -6.1; 10167 -4.3; 10879 -0.5; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000001dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Fostex T20RP Mk3 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 39 Hz   | 0.5  | 11.2 dB  |
| Peaking | 85 Hz   | 0.56 | -11.0 dB |
| Peaking | 629 Hz  | 1.18 | 3.4 dB   |
| Peaking | 5985 Hz | 3.06 | 7.0 dB   |
| Peaking | 9282 Hz | 4.14 | -7.4 dB  |
| Peaking | 315 Hz  | 7.49 | -1.1 dB  |
| Peaking | 1166 Hz | 1.93 | -2.0 dB  |
| Peaking | 2780 Hz | 0.73 | 3.4 dB   |
| Peaking | 4438 Hz | 2.1  | -5.4 dB  |
| Peaking | 5247 Hz | 7.85 | 4.0 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Fostex%20T20RP%20Mk3/Fostex%20T20RP%20Mk3.png)