# Polk Audio UltraFocus 8000
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -11.2; 23 -10.6; 25 -10.0; 28 -9.3; 31 -8.8; 34 -8.3; 37 -7.9; 41 -7.5; 45 -7.3; 49 -7.0; 54 -6.8; 60 -6.6; 66 -6.5; 72 -6.3; 79 -6.2; 87 -6.1; 96 -6.0; 106 -6.0; 116 -6.1; 128 -6.1; 141 -6.0; 155 -5.9; 170 -6.0; 187 -6.0; 206 -6.0; 227 -5.9; 249 -5.9; 274 -5.7; 302 -5.5; 332 -5.1; 365 -5.0; 402 -5.0; 442 -4.8; 486 -4.7; 535 -4.6; 588 -4.6; 647 -4.3; 712 -4.4; 783 -4.3; 861 -4.3; 947 -4.0; 1042 -4.2; 1146 -4.1; 1261 -4.2; 1387 -4.3; 1526 -4.9; 1678 -5.4; 1846 -5.6; 2031 -5.5; 2234 -4.8; 2457 -3.6; 2703 -2.8; 2973 -2.7; 3270 -3.5; 3597 -4.8; 3957 -7.0; 4353 -7.4; 4788 -7.3; 5267 -5.6; 5793 -3.1; 6373 -0.5; 7010 -2.1; 7711 -4.3; 8482 -4.6; 9330 -4.6; 10263 -4.6; 11289 -5.2; 12418 -6.7; 13660 -7.6; 15026 -7.0; 16529 -6.8; 18182 -7.0; 20000 -4.6
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Polk Audio UltraFocus 8000 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Polk Audio UltraFocus 8000 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.0dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.5dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 2985 Hz  | 3.55 | 2.9 dB  |
| Peaking | 4459 Hz  | 2.44 | -3.7 dB |
| Peaking | 6525 Hz  | 4.08 | 5.3 dB  |
| Peaking | 15927 Hz | 0.75 | -2.8 dB |
| Peaking | 17 Hz    | 0.85 | -6.4 dB |
| Peaking | 49 Hz    | 0.28 | -1.1 dB |
| Peaking | 219 Hz   | 1.14 | -0.9 dB |
| Peaking | 1287 Hz  | 0.63 | 0.8 dB  |
| Peaking | 1834 Hz  | 2.7  | -1.9 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-1.7dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -5.0 dB |
| Peaking | 62 Hz    | 1.41 | -0.7 dB |
| Peaking | 125 Hz   | 1.41 | -1.0 dB |
| Peaking | 250 Hz   | 1.41 | -1.1 dB |
| Peaking | 500 Hz   | 1.41 | 0.2 dB  |
| Peaking | 1000 Hz  | 1.41 | 0.5 dB  |
| Peaking | 2000 Hz  | 1.41 | 0.2 dB  |
| Peaking | 4000 Hz  | 1.41 | -1.1 dB |
| Peaking | 8000 Hz  | 1.41 | 1.6 dB  |
| Peaking | 16000 Hz | 1.41 | -3.7 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Polk%20Audio%20UltraFocus%208000/Polk%20Audio%20UltraFocus%208000.png)