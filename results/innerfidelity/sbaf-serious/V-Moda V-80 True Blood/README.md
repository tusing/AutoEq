# V-Moda V-80 True Blood
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -4.1; 23 -4.4; 25 -4.7; 28 -5.0; 31 -5.3; 34 -5.5; 37 -5.6; 41 -5.8; 45 -5.9; 49 -6.0; 54 -6.2; 60 -6.4; 66 -6.6; 72 -6.8; 79 -6.9; 87 -7.0; 96 -7.6; 106 -7.7; 116 -7.5; 128 -7.7; 141 -8.0; 155 -8.0; 170 -7.6; 187 -7.6; 206 -7.3; 227 -7.9; 249 -7.3; 274 -6.2; 302 -5.0; 332 -4.3; 365 -3.8; 402 -3.2; 442 -2.6; 486 -2.0; 535 -1.3; 588 -0.7; 647 -0.9; 712 -1.5; 783 -2.1; 861 -3.2; 947 -4.3; 1042 -5.4; 1146 -6.4; 1261 -7.2; 1387 -7.8; 1526 -7.6; 1678 -6.9; 1846 -5.6; 2031 -4.2; 2234 -3.3; 2457 -2.6; 2703 -2.8; 2973 -3.3; 3270 -4.8; 3597 -4.2; 3957 -2.1; 4353 -1.2; 4788 -2.3; 5267 -0.5; 5793 -1.0; 6373 -2.0; 7010 -2.1; 7711 -4.0; 8482 -4.3; 9330 -4.3; 10263 -4.3; 11289 -4.3; 12418 -4.3; 13660 -4.3; 15026 -4.3; 16529 -4.3; 18182 -4.3; 20000 -4.3
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`V-Moda V-80 True Blood GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `V-Moda V-80 True Blood ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-3.6dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 125 Hz  | 0.52 | -3.5 dB |
| Peaking | 234 Hz  | 2.98 | -1.6 dB |
| Peaking | 588 Hz  | 1.11 | 4.3 dB  |
| Peaking | 1348 Hz | 2.17 | -4.5 dB |
| Peaking | 5226 Hz | 1.62 | 3.5 dB  |
| Peaking | 1643 Hz | 5.34 | -0.8 dB |
| Peaking | 1778 Hz | 3.87 | -0.8 dB |
| Peaking | 2516 Hz | 1.61 | 1.8 dB  |
| Peaking | 3360 Hz | 6.43 | -2.5 dB |
| Peaking | 8597 Hz | 3.4  | -0.8 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.1dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -0.5 dB |
| Peaking | 62 Hz    | 1.41 | -1.7 dB |
| Peaking | 125 Hz   | 1.41 | -3.1 dB |
| Peaking | 250 Hz   | 1.41 | -3.1 dB |
| Peaking | 500 Hz   | 1.41 | 4.6 dB  |
| Peaking | 1000 Hz  | 1.41 | -1.5 dB |
| Peaking | 2000 Hz  | 1.41 | -1.5 dB |
| Peaking | 4000 Hz  | 1.41 | 2.8 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.7 dB  |
| Peaking | 16000 Hz | 1.41 | -0.2 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/V-Moda%20V-80%20True%20Blood/V-Moda%20V-80%20True%20Blood.png)