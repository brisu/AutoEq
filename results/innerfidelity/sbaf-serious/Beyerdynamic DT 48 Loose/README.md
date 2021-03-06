# Beyerdynamic DT 48 Loose

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 5.2; 78 4.6; 83 4.4; 89 3.9; 95 4.4; 102 2.3; 109 1.7; 117 0.8; 125 -0.3; 134 -1.0; 143 -1.6; 153 -2.3; 164 -2.5; 175 -3.7; 188 -4.5; 201 -4.8; 215 -4.9; 230 -4.6; 246 -4.3; 263 -4.0; 282 -3.8; 301 -3.6; 323 -2.8; 345 -2.3; 369 -1.8; 395 -1.0; 423 0.1; 452 1.1; 484 1.7; 518 2.4; 554 3.4; 593 4.4; 635 4.2; 679 3.5; 726 3.1; 777 2.9; 832 2.1; 890 1.5; 952 0.8; 1019 -0.4; 1090 -1.8; 1167 -3.1; 1248 -4.1; 1336 -4.7; 1429 -5.3; 1529 -6.2; 1636 -7.0; 1751 -7.4; 1873 -7.4; 2004 -7.4; 2145 -6.8; 2295 -5.4; 2455 -3.2; 2627 -1.0; 2811 0.3; 3008 0.7; 3219 0.8; 3444 1.7; 3685 2.4; 3943 3.5; 4219 3.3; 4514 3.9; 4830 5.1; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.1; 7756 -3.7; 8299 -7.1; 8880 -6.8; 9502 -4.3; 10167 -1.5; 10879 -0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 -2.3; 15258 -6.8; 16326 -9.1; 17469 -9.1; 18692 -7.0; 20000 -2.6
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beyerdynamic DT 48 Loose ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.4dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 40 Hz    | 0.85 | 7.3 dB   |
| Peaking | 1885 Hz  | 1.76 | -10.0 dB |
| Peaking | 7056 Hz  | 0.68 | 11.4 dB  |
| Peaking | 8505 Hz  | 2.47 | -17.6 dB |
| Peaking | 17031 Hz | 1.32 | -11.4 dB |
| Peaking | 40 Hz    | 1.06 | -8.2 dB  |
| Peaking | 54 Hz    | 0.32 | 7.8 dB   |
| Peaking | 204 Hz   | 0.65 | -8.7 dB  |
| Peaking | 619 Hz   | 1.22 | 6.2 dB   |
| Peaking | 1269 Hz  | 3.06 | -2.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Beyerdynamic%20DT%2048%20Loose/Beyerdynamic%20DT%2048%20Loose.png)