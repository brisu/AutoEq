# Bowers & Wilkins P7 Wireless Bluetooth

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.6dB
GraphicEQ: 10 -84; 20 3.2; 22 2.6; 23 2.3; 25 1.8; 26 1.6; 28 1.2; 30 0.9; 32 0.6; 35 0.3; 37 0.1; 40 -0.1; 42 -0.3; 45 -0.4; 49 -0.6; 52 -0.7; 56 -0.9; 59 -1.0; 64 -1.2; 68 -1.3; 73 -1.5; 78 -1.6; 83 -1.7; 89 -1.9; 95 -2.2; 102 -2.2; 109 -2.3; 117 -2.3; 125 -2.4; 134 -2.4; 143 -2.6; 153 -2.6; 164 -2.8; 175 -2.5; 188 -2.4; 201 -2.5; 215 -2.4; 230 -2.3; 246 -2.1; 263 -1.8; 282 -1.2; 301 -0.5; 323 -0.0; 345 0.3; 369 0.5; 395 0.7; 423 0.7; 452 0.7; 484 0.6; 518 0.6; 554 0.7; 593 0.9; 635 0.9; 679 0.7; 726 0.6; 777 0.6; 832 0.3; 890 0.1; 952 -0.1; 1019 0.2; 1090 0.5; 1167 0.2; 1248 -0.1; 1336 -0.6; 1429 -1.3; 1529 -1.8; 1636 -2.3; 1751 -2.6; 1873 -2.5; 2004 -2.0; 2145 -1.8; 2295 -1.9; 2455 -2.0; 2627 -1.4; 2811 -0.1; 3008 3.2; 3219 5.5; 3444 4.5; 3685 2.4; 3943 0.2; 4219 -0.6; 4514 -0.2; 4830 0.2; 5168 1.2; 5530 2.4; 5917 1.5; 6331 2.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.645405278027587dB` and instead set Global volume in the UI for both channels to **-56**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Bowers & Wilkins P7 Wireless Bluetooth ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.1dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 21 Hz   | 2.07 | 3.1 dB  |
| Peaking | 136 Hz  | 0.9  | -2.9 dB |
| Peaking | 2118 Hz | 1.67 | -2.8 dB |
| Peaking | 3264 Hz | 5.59 | 6.8 dB  |
| Peaking | 6564 Hz | 5.23 | 3.9 dB  |
| Peaking | 241 Hz  | 2.01 | -1.9 dB |
| Peaking | 383 Hz  | 0.74 | 1.5 dB  |
| Peaking | 1377 Hz | 1.99 | 1.0 dB  |
| Peaking | 1450 Hz | 4.32 | -1.4 dB |
| Peaking | 1692 Hz | 6.04 | -1.1 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Bowers%20&%20Wilkins%20P7%20Wireless%20Bluetooth/Bowers%20&%20Wilkins%20P7%20Wireless%20Bluetooth.png)