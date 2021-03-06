# Musical Fidelity MF100
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -1.7; 23 -2.3; 25 -2.9; 28 -3.7; 31 -4.2; 34 -4.6; 37 -4.9; 41 -5.2; 45 -5.3; 49 -5.2; 54 -5.2; 60 -5.2; 66 -5.0; 72 -4.8; 79 -4.4; 87 -3.6; 96 -3.9; 106 -4.0; 116 -3.8; 128 -3.6; 141 -3.1; 155 -3.1; 170 -2.7; 187 -2.6; 206 -2.4; 227 -2.0; 249 -1.5; 274 -0.9; 302 -0.9; 332 -0.6; 365 -0.8; 402 -1.1; 442 -1.2; 486 -1.4; 535 -1.3; 588 -0.9; 647 -0.7; 712 -0.5; 783 -0.9; 861 -2.4; 947 -3.4; 1042 -3.5; 1146 -3.4; 1261 -3.9; 1387 -3.8; 1526 -3.6; 1678 -4.0; 1846 -4.4; 2031 -4.8; 2234 -5.1; 2457 -4.9; 2703 -4.8; 2973 -4.7; 3270 -4.8; 3597 -4.5; 3957 -3.5; 4353 -4.9; 4788 -6.1; 5267 -4.1; 5793 -3.9; 6373 -3.6; 7010 -6.4; 7711 -6.1; 8482 -7.6; 9330 -7.7; 10263 -3.5; 11289 -3.4; 12418 -3.4; 13660 -3.4; 15026 -3.4; 16529 -3.4; 18182 -3.4; 20000 -3.4
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Musical Fidelity MF100 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Musical Fidelity MF100 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-3.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-3.3dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 18 Hz    | 1.5  | 2.9 dB  |
| Peaking | 47 Hz    | 0.84 | -2.3 dB |
| Peaking | 325 Hz   | 1.25 | 2.7 dB  |
| Peaking | 679 Hz   | 3.35 | 2.7 dB  |
| Peaking | 8399 Hz  | 2.22 | -4.2 dB |
| Peaking | 2520 Hz  | 1.1  | -1.6 dB |
| Peaking | 4027 Hz  | 6.63 | 1.2 dB  |
| Peaking | 4621 Hz  | 7.18 | -2.4 dB |
| Peaking | 6113 Hz  | 8.62 | 1.6 dB  |
| Peaking | 10739 Hz | 5.58 | 1.6 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.4dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -0.5 dB |
| Peaking | 62 Hz    | 1.41 | -1.8 dB |
| Peaking | 125 Hz   | 1.41 | -0.2 dB |
| Peaking | 250 Hz   | 1.41 | 1.6 dB  |
| Peaking | 500 Hz   | 1.41 | 2.6 dB  |
| Peaking | 1000 Hz  | 1.41 | 0.4 dB  |
| Peaking | 2000 Hz  | 1.41 | -1.5 dB |
| Peaking | 4000 Hz  | 1.41 | -0.5 dB |
| Peaking | 8000 Hz  | 1.41 | -3.0 dB |
| Peaking | 16000 Hz | 1.41 | 0.4 dB  |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Musical%20Fidelity%20MF100/Musical%20Fidelity%20MF100.png)