# LG Quadbeat HSS-F420
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -4.3; 23 -4.3; 25 -4.4; 28 -4.5; 31 -4.6; 34 -4.7; 37 -4.8; 41 -4.9; 45 -5.1; 49 -5.2; 54 -5.4; 60 -5.7; 66 -6.0; 72 -6.3; 79 -6.6; 87 -7.0; 96 -7.4; 106 -7.7; 116 -7.8; 128 -8.0; 141 -8.2; 155 -8.4; 170 -8.4; 187 -8.3; 206 -8.3; 227 -8.0; 249 -7.9; 274 -7.6; 302 -7.2; 332 -6.9; 365 -6.5; 402 -6.1; 442 -5.5; 486 -5.2; 535 -4.7; 588 -3.9; 647 -3.6; 712 -3.3; 783 -2.8; 861 -2.7; 947 -2.9; 1042 -3.0; 1146 -3.2; 1261 -3.4; 1387 -3.8; 1526 -4.3; 1678 -4.6; 1846 -4.5; 2031 -4.3; 2234 -4.3; 2457 -4.0; 2703 -3.7; 2973 -2.7; 3270 -1.3; 3597 -0.5; 3957 -0.8; 4353 -2.2; 4788 -2.4; 5267 -1.7; 5793 -2.1; 6373 -2.2; 7010 -2.5; 7711 -4.3; 8482 -4.6; 9330 -4.6; 10263 -4.6; 11289 -4.6; 12418 -4.6; 13660 -4.6; 15026 -4.8; 16529 -5.7; 18182 -4.6; 20000 -4.6
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`LG Quadbeat HSS-F420 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `LG Quadbeat HSS-F420 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.5dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 105 Hz   | 1.21 | -1.4 dB |
| Peaking | 206 Hz   | 0.68 | -3.4 dB |
| Peaking | 826 Hz   | 1.33 | 2.4 dB  |
| Peaking | 3626 Hz  | 3.12 | 4.0 dB  |
| Peaking | 5790 Hz  | 2.41 | 2.6 dB  |
| Peaking | 21 Hz    | 1.09 | 0.4 dB  |
| Peaking | 1764 Hz  | 4.67 | -0.5 dB |
| Peaking | 16030 Hz | 4.58 | -1.6 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.4dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 0.4 dB  |
| Peaking | 62 Hz    | 1.41 | -0.7 dB |
| Peaking | 125 Hz   | 1.41 | -3.2 dB |
| Peaking | 250 Hz   | 1.41 | -3.2 dB |
| Peaking | 500 Hz   | 1.41 | 0.1 dB  |
| Peaking | 1000 Hz  | 1.41 | 2.2 dB  |
| Peaking | 2000 Hz  | 1.41 | -1.0 dB |
| Peaking | 4000 Hz  | 1.41 | 4.0 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.3 dB  |
| Peaking | 16000 Hz | 1.41 | -0.8 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/LG%20Quadbeat%20HSS-F420/LG%20Quadbeat%20HSS-F420.png)