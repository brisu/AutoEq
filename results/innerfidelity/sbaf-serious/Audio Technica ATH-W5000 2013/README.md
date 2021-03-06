# Audio Technica ATH-W5000 2013

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 5.9; 56 5.3; 59 4.5; 64 3.6; 68 3.4; 73 3.2; 78 2.6; 83 1.7; 89 0.8; 95 0.2; 102 -0.1; 109 -0.2; 117 -0.2; 125 -0.4; 134 -0.5; 143 -0.5; 153 -0.5; 164 -0.4; 175 -0.2; 188 -0.3; 201 -0.3; 215 -0.2; 230 0.0; 246 0.1; 263 -0.1; 282 0.0; 301 0.2; 323 0.7; 345 1.1; 369 1.5; 395 2.0; 423 3.1; 452 4.3; 484 4.9; 518 5.2; 554 5.3; 593 4.9; 635 3.9; 679 3.2; 726 2.5; 777 2.3; 832 1.7; 890 0.9; 952 0.4; 1019 -0.1; 1090 -0.6; 1167 -0.9; 1248 -1.2; 1336 -1.4; 1429 -1.7; 1529 -2.0; 1636 -1.4; 1751 -0.7; 1873 -0.6; 2004 -1.1; 2145 -1.3; 2295 0.2; 2455 2.5; 2627 4.9; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 3.7; 4219 1.5; 4514 1.2; 4830 1.0; 5168 3.7; 5530 5.8; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.0; 9502 -1.8; 10167 -1.1; 10879 -0.1; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000001dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audio Technica ATH-W5000 2013 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.1dB.

| Type    | Fc       |     Q | Gain    |
|:--------|:---------|:------|:--------|
| Peaking | 38 Hz    |  0.45 | 8.6 dB  |
| Peaking | 540 Hz   |  0.06 | -4.3 dB |
| Peaking | 541 Hz   |  0.93 | 9.0 dB  |
| Peaking | 3112 Hz  |  1.9  | 10.0 dB |
| Peaking | 6021 Hz  |  3.08 | 8.0 dB  |
| Peaking | 100 Hz   |  4.87 | -0.9 dB |
| Peaking | 195 Hz   |  2.75 | 0.9 dB  |
| Peaking | 2155 Hz  | 11.99 | -1.7 dB |
| Peaking | 3761 Hz  | 15.3  | 2.5 dB  |
| Peaking | 13050 Hz |  2.46 | 0.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Audio%20Technica%20ATH-W5000%202013/Audio%20Technica%20ATH-W5000%202013.png)