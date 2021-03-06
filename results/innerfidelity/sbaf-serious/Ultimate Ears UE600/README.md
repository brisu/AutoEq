# Ultimate Ears UE600

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 3.4; 22 3.2; 23 3.2; 25 3.1; 26 3.1; 28 3.0; 30 2.9; 32 2.9; 35 2.8; 37 2.7; 40 2.5; 42 2.4; 45 2.3; 49 2.2; 52 2.0; 56 1.9; 59 1.7; 64 1.5; 68 1.2; 73 0.9; 78 0.6; 83 0.3; 89 -0.1; 95 -0.4; 102 -0.6; 109 -0.7; 117 -0.8; 125 -1.0; 134 -1.3; 143 -1.5; 153 -1.6; 164 -1.8; 175 -1.9; 188 -1.9; 201 -2.0; 215 -2.0; 230 -1.9; 246 -2.0; 263 -2.0; 282 -1.8; 301 -1.8; 323 -1.8; 345 -1.6; 369 -1.6; 395 -1.5; 423 -1.2; 452 -1.1; 484 -1.1; 518 -1.0; 554 -0.6; 593 -0.1; 635 0.1; 679 0.1; 726 0.2; 777 0.4; 832 0.4; 890 0.3; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 -0.2; 1248 -0.1; 1336 -0.3; 1429 -0.4; 1529 -0.5; 1636 -0.4; 1751 -0.0; 1873 0.6; 2004 1.4; 2145 2.0; 2295 2.9; 2455 4.0; 2627 4.8; 2811 5.6; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.7; 4219 4.0; 4514 3.1; 4830 3.6; 5168 5.4; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.0; 8880 -0.6; 9502 -0.1; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999999573946dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Ultimate Ears UE600 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 22 Hz   | 0.61 | 3.2 dB  |
| Peaking | 56 Hz   | 1.4  | 1.1 dB  |
| Peaking | 213 Hz  | 0.64 | -2.2 dB |
| Peaking | 3226 Hz | 1.81 | 6.5 dB  |
| Peaking | 5827 Hz | 3.48 | 5.7 dB  |
| Peaking | 763 Hz  | 2.95 | 0.8 dB  |
| Peaking | 1577 Hz | 2.44 | -1.2 dB |
| Peaking | 2490 Hz | 5.32 | 1.1 dB  |
| Peaking | 6596 Hz | 9.05 | 1.8 dB  |
| Peaking | 8200 Hz | 2.38 | -1.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Ultimate%20Ears%20UE600/Ultimate%20Ears%20UE600.png)