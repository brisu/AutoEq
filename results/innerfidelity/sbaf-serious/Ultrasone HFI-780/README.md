# Ultrasone HFI-780

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 5.9; 59 5.8; 64 5.7; 68 5.6; 73 5.6; 78 5.7; 83 5.7; 89 5.3; 95 5.1; 102 5.0; 109 5.0; 117 5.2; 125 5.3; 134 5.2; 143 5.4; 153 5.5; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 6.0; 230 5.5; 246 4.1; 263 3.2; 282 2.3; 301 1.2; 323 0.1; 345 -0.5; 369 -1.0; 395 -1.2; 423 -1.0; 452 -0.7; 484 -0.5; 518 -0.2; 554 0.2; 593 0.6; 635 0.7; 679 0.6; 726 0.6; 777 0.8; 832 0.5; 890 0.3; 952 0.1; 1019 0.0; 1090 0.4; 1167 0.1; 1248 -0.2; 1336 -0.5; 1429 -1.4; 1529 -2.2; 1636 -2.8; 1751 -2.9; 1873 -3.1; 2004 -2.0; 2145 0.9; 2295 5.3; 2455 5.9; 2627 3.9; 2811 3.6; 3008 3.4; 3219 2.0; 3444 1.2; 3685 1.4; 3943 2.4; 4219 2.4; 4514 1.7; 4830 1.4; 5168 2.8; 5530 3.8; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.3; 9502 -1.9; 10167 -2.4; 10879 -1.9; 11640 -1.6; 12455 -1.5; 13327 -0.9; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.112666682960116dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Ultrasone HFI-780 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 39 Hz    | 0.33 | 6.3 dB  |
| Peaking | 188 Hz   | 1.99 | 4.6 dB  |
| Peaking | 1935 Hz  | 2.34 | -7.9 dB |
| Peaking | 2345 Hz  | 2.27 | 9.2 dB  |
| Peaking | 6080 Hz  | 4.34 | 6.3 dB  |
| Peaking | 374 Hz   | 0.86 | 2.6 dB  |
| Peaking | 383 Hz   | 1.73 | -5.0 dB |
| Peaking | 4138 Hz  | 7.32 | 1.5 dB  |
| Peaking | 10543 Hz | 2.42 | -2.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Ultrasone%20HFI-780/Ultrasone%20HFI-780.png)