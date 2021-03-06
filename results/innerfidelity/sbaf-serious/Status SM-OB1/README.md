# Status SM-OB1
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.6; 25 -0.9; 28 -1.8; 31 -2.7; 34 -3.5; 37 -4.1; 41 -4.9; 45 -5.5; 49 -6.0; 54 -6.6; 60 -7.1; 66 -7.6; 72 -7.9; 79 -8.0; 87 -8.2; 96 -8.9; 106 -9.2; 116 -9.7; 128 -10.2; 141 -10.4; 155 -10.4; 170 -10.3; 187 -10.4; 206 -10.3; 227 -9.9; 249 -9.4; 274 -9.5; 302 -10.0; 332 -9.8; 365 -9.4; 402 -9.3; 442 -9.2; 486 -9.4; 535 -9.3; 588 -9.1; 647 -9.1; 712 -9.1; 783 -9.0; 861 -9.1; 947 -8.9; 1042 -8.6; 1146 -7.8; 1261 -7.7; 1387 -7.6; 1526 -7.2; 1678 -6.3; 1846 -5.5; 2031 -5.3; 2234 -5.4; 2457 -5.1; 2703 -4.5; 2973 -3.2; 3270 -2.6; 3597 -1.9; 3957 -0.5; 4353 -0.5; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -8.3; 10263 -6.8; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Status SM-OB1 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Status SM-OB1 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.9dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 22 Hz   | 1.09 | 6.3 dB  |
| Peaking | 151 Hz  | 0.66 | -3.7 dB |
| Peaking | 470 Hz  | 0.8  | -1.8 dB |
| Peaking | 930 Hz  | 1.55 | -1.7 dB |
| Peaking | 4562 Hz | 1.28 | 6.8 dB  |
| Peaking | 1515 Hz | 3.58 | -1.4 dB |
| Peaking | 1698 Hz | 2.05 | 1.2 dB  |
| Peaking | 4672 Hz | 6.21 | -0.9 dB |
| Peaking | 6264 Hz | 4.42 | 2.8 dB  |
| Peaking | 8883 Hz | 1.88 | -2.4 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.3dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 5.0 dB  |
| Peaking | 62 Hz    | 1.41 | -1.1 dB |
| Peaking | 125 Hz   | 1.41 | -3.2 dB |
| Peaking | 250 Hz   | 1.41 | -2.7 dB |
| Peaking | 500 Hz   | 1.41 | -2.1 dB |
| Peaking | 1000 Hz  | 1.41 | -2.0 dB |
| Peaking | 2000 Hz  | 1.41 | -0.2 dB |
| Peaking | 4000 Hz  | 1.41 | 6.9 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.2 dB  |
| Peaking | 16000 Hz | 1.41 | -0.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Status%20SM-OB1/Status%20SM-OB1.png)