# Advanced Alpha Shallow Pads

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.0dB
GraphicEQ: 10 -84; 20 1.2; 22 1.1; 23 1.1; 25 1.1; 26 1.1; 28 1.1; 30 1.2; 32 1.2; 35 1.3; 37 1.3; 40 1.2; 42 1.2; 45 1.2; 49 1.2; 52 1.2; 56 1.1; 59 1.1; 64 1.0; 68 0.9; 73 0.8; 78 0.8; 83 0.6; 89 0.2; 95 -0.2; 102 -0.4; 109 -0.6; 117 -0.8; 125 -1.2; 134 -1.5; 143 -1.7; 153 -2.0; 164 -2.1; 175 -2.2; 188 -2.4; 201 -2.5; 215 -2.6; 230 -2.6; 246 -2.6; 263 -2.8; 282 -2.7; 301 -2.5; 323 -2.5; 345 -2.4; 369 -2.2; 395 -2.0; 423 -1.5; 452 -1.5; 484 -1.2; 518 -1.1; 554 -0.9; 593 -0.2; 635 -0.0; 679 0.1; 726 0.1; 777 0.2; 832 0.1; 890 -0.1; 952 -0.2; 1019 0.0; 1090 -0.2; 1167 -0.2; 1248 -0.6; 1336 0.0; 1429 0.9; 1529 0.2; 1636 -0.4; 1751 0.1; 1873 1.3; 2004 -0.6; 2145 -2.1; 2295 -3.6; 2455 -4.8; 2627 -5.8; 2811 -6.9; 3008 -7.0; 3219 -6.0; 3444 -4.8; 3685 -3.7; 3943 -1.3; 4219 2.1; 4514 3.2; 4830 -2.6; 5168 -3.1; 5530 -0.8; 5917 -0.2; 6331 -0.4; 6775 0.5; 7249 0.0; 7756 -0.8; 8299 -2.2; 8880 -3.1; 9502 -2.6; 10167 -0.6; 10879 0.0; 11640 0.0; 12455 0.0; 13327 -1.2; 14260 -4.3; 15258 -2.9; 16326 -0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-3.993881560920858dB` and instead set Global volume in the UI for both channels to **-39**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Advanced Alpha Shallow Pads ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-1.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -0.1dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 251 Hz   | 1.04 | -3.0 dB |
| Peaking | 2906 Hz  | 3.01 | -7.7 dB |
| Peaking | 14447 Hz | 4.65 | -2.2 dB |
| Peaking | 14505 Hz | 4.56 | -2.5 dB |
| Peaking | 24000 Hz | 1.88 | -1.4 dB |
| Peaking | 40 Hz    | 0.86 | 1.5 dB  |
| Peaking | 2010 Hz  | 2.53 | 2.6 dB  |
| Peaking | 2235 Hz  | 4.01 | -3.0 dB |
| Peaking | 9043 Hz  | 3.46 | -4.9 dB |
| Peaking | 9543 Hz  | 1.26 | 1.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Advanced%20Alpha%20Shallow%20Pads/Advanced%20Alpha%20Shallow%20Pads.png)