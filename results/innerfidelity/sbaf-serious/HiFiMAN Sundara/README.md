# HiFiMAN Sundara

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.0dB
GraphicEQ: 10 -84; 20 4.9; 22 4.5; 23 4.4; 25 4.1; 26 4.0; 28 3.9; 30 3.8; 32 3.7; 35 3.6; 37 3.6; 40 3.5; 42 3.5; 45 3.5; 49 3.5; 52 3.3; 56 3.1; 59 2.9; 64 2.4; 68 2.1; 73 1.8; 78 1.7; 83 1.6; 89 1.4; 95 1.2; 102 1.0; 109 1.0; 117 0.9; 125 0.7; 134 0.5; 143 0.4; 153 0.4; 164 0.2; 175 0.2; 188 0.1; 201 -0.1; 215 -0.1; 230 -0.2; 246 -0.2; 263 -0.3; 282 -0.3; 301 -0.3; 323 -0.4; 345 -0.5; 369 -0.5; 395 -0.6; 423 -0.5; 452 -0.2; 484 0.3; 518 0.6; 554 0.5; 593 0.4; 635 -0.1; 679 -0.6; 726 -0.5; 777 -0.3; 832 -0.5; 890 -0.7; 952 -0.7; 1019 0.7; 1090 1.7; 1167 1.2; 1248 1.4; 1336 1.3; 1429 1.3; 1529 1.3; 1636 1.9; 1751 2.0; 1873 2.2; 2004 2.2; 2145 1.6; 2295 2.2; 2455 1.8; 2627 0.5; 2811 -0.2; 3008 -0.2; 3219 -1.3; 3444 -0.7; 3685 -0.2; 3943 -0.9; 4219 -2.1; 4514 -2.4; 4830 -2.2; 5168 -1.9; 5530 -0.3; 5917 -1.7; 6331 2.1; 6775 -0.9; 7249 -1.0; 7756 -1.2; 8299 -2.2; 8880 -2.4; 9502 -0.4; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-4.988075763297844dB` and instead set Global volume in the UI for both channels to **-49**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `HiFiMAN Sundara ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -4.6dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 18 Hz   |  0.81 | 4.3 dB  |
| Peaking | 50 Hz   |  1.06 | 2.4 dB  |
| Peaking | 1862 Hz |  1.71 | 2.4 dB  |
| Peaking | 4532 Hz |  2.99 | -2.6 dB |
| Peaking | 8517 Hz |  5.96 | -2.6 dB |
| Peaking | 329 Hz  |  2.15 | -0.6 dB |
| Peaking | 946 Hz  |  3.43 | -2.2 dB |
| Peaking | 1075 Hz |  4.18 | 2.5 dB  |
| Peaking | 3181 Hz | 10.48 | -1.4 dB |
| Peaking | 6389 Hz | 19.1  | 2.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/HiFiMAN%20Sundara/HiFiMAN%20Sundara.png)