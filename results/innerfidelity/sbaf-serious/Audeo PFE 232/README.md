# Audeo PFE 232
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -7.5; 23 -7.6; 25 -7.7; 28 -7.8; 31 -8.0; 34 -8.1; 37 -8.2; 41 -8.2; 45 -8.4; 49 -8.5; 54 -8.7; 60 -9.0; 66 -9.3; 72 -9.5; 79 -9.8; 87 -10.2; 96 -10.5; 106 -10.8; 116 -10.8; 128 -11.0; 141 -11.1; 155 -11.1; 170 -11.0; 187 -10.8; 206 -10.6; 227 -10.3; 249 -10.0; 274 -9.6; 302 -9.1; 332 -8.6; 365 -8.0; 402 -7.5; 442 -6.8; 486 -6.4; 535 -5.8; 588 -5.0; 647 -4.6; 712 -4.3; 783 -3.8; 861 -3.6; 947 -3.5; 1042 -3.7; 1146 -3.8; 1261 -4.0; 1387 -4.3; 1526 -4.7; 1678 -5.0; 1846 -4.8; 2031 -4.5; 2234 -4.1; 2457 -2.9; 2703 -1.5; 2973 -0.5; 3270 -0.5; 3597 -0.9; 3957 -0.9; 4353 -1.2; 4788 -1.0; 5267 -0.9; 5793 -1.0; 6373 -3.8; 7010 -3.5; 7711 -5.4; 8482 -7.1; 9330 -9.4; 10263 -7.4; 11289 -5.7; 12418 -5.7; 13660 -11.0; 15026 -14.4; 16529 -5.9; 18182 -5.7; 20000 -5.7
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Audeo PFE 232 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audeo PFE 232 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.6dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 40 Hz    | 0.14 | -1.7 dB  |
| Peaking | 163 Hz   | 0.51 | -4.2 dB  |
| Peaking | 801 Hz   | 1.19 | 2.7 dB   |
| Peaking | 3876 Hz  | 1.12 | 5.5 dB   |
| Peaking | 14610 Hz | 3.28 | -10.1 dB |
| Peaking | 2940 Hz  | 2.86 | 3.7 dB   |
| Peaking | 3133 Hz  | 1.2  | -2.5 dB  |
| Peaking | 5605 Hz  | 3.52 | 2.5 dB   |
| Peaking | 9320 Hz  | 4.29 | -4.5 dB  |
| Peaking | 12186 Hz | 3.39 | 1.9 dB   |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -1.9 dB |
| Peaking | 62 Hz    | 1.41 | -2.4 dB |
| Peaking | 125 Hz   | 1.41 | -4.7 dB |
| Peaking | 250 Hz   | 1.41 | -4.0 dB |
| Peaking | 500 Hz   | 1.41 | 0.1 dB  |
| Peaking | 1000 Hz  | 1.41 | 2.3 dB  |
| Peaking | 2000 Hz  | 1.41 | -0.1 dB |
| Peaking | 4000 Hz  | 1.41 | 6.5 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.1 dB |
| Peaking | 16000 Hz | 1.41 | -5.4 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Audeo%20PFE%20232/Audeo%20PFE%20232.png)