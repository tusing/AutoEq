# Pioneer SE-A1000
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -0.5; 45 -0.5; 49 -0.5; 54 -0.5; 60 -0.5; 66 -1.5; 72 -3.0; 79 -4.4; 87 -5.6; 96 -6.5; 106 -7.1; 116 -7.3; 128 -7.7; 141 -7.8; 155 -7.8; 170 -7.6; 187 -7.6; 206 -7.4; 227 -7.1; 249 -6.9; 274 -6.7; 302 -6.6; 332 -6.6; 365 -6.1; 402 -5.9; 442 -5.6; 486 -5.1; 535 -4.7; 588 -4.8; 647 -5.0; 712 -5.3; 783 -5.2; 861 -5.7; 947 -5.8; 1042 -6.1; 1146 -6.3; 1261 -6.0; 1387 -5.8; 1526 -5.6; 1678 -5.1; 1846 -4.2; 2031 -3.2; 2234 -3.0; 2457 -2.9; 2703 -4.0; 2973 -4.6; 3270 -4.3; 3597 -3.6; 3957 -9.4; 4353 -14.1; 4788 -12.8; 5267 -9.7; 5793 -7.7; 6373 -5.8; 7010 -4.4; 7711 -7.7; 8482 -10.2; 9330 -11.4; 10263 -10.7; 11289 -7.2; 12418 -6.5; 13660 -6.5; 15026 -6.6; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Pioneer SE-A1000 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Pioneer SE-A1000 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.3dB**.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 35 Hz   | 0.92 | 7.2 dB   |
| Peaking | 3576 Hz | 6.69 | 4.1 dB   |
| Peaking | 4474 Hz | 2.15 | -15.7 dB |
| Peaking | 4584 Hz | 0.53 | 7.6 dB   |
| Peaking | 9353 Hz | 2.25 | -8.1 dB  |
| Peaking | 63 Hz   | 2.4  | 4.0 dB   |
| Peaking | 113 Hz  | 0.58 | -2.3 dB  |
| Peaking | 580 Hz  | 1.15 | 2.0 dB   |
| Peaking | 1398 Hz | 0.79 | -1.5 dB  |
| Peaking | 2179 Hz | 2.88 | 2.0 dB   |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.7dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 6.6 dB  |
| Peaking | 62 Hz    | 1.41 | 4.5 dB  |
| Peaking | 125 Hz   | 1.41 | -2.5 dB |
| Peaking | 250 Hz   | 1.41 | -0.7 dB |
| Peaking | 500 Hz   | 1.41 | 1.9 dB  |
| Peaking | 1000 Hz  | 1.41 | -0.7 dB |
| Peaking | 2000 Hz  | 1.41 | 4.2 dB  |
| Peaking | 4000 Hz  | 1.41 | -2.7 dB |
| Peaking | 8000 Hz  | 1.41 | -2.1 dB |
| Peaking | 16000 Hz | 1.41 | -0.0 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Pioneer%20SE-A1000/Pioneer%20SE-A1000.png)