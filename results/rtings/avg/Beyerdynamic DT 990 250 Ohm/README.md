# Beyerdynamic DT 990 250 Ohm
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -1.0; 25 -1.5; 28 -2.3; 31 -2.9; 34 -3.4; 37 -3.7; 41 -4.2; 45 -4.5; 49 -4.8; 54 -5.0; 60 -5.4; 66 -5.8; 72 -6.1; 79 -6.4; 87 -6.7; 96 -7.0; 106 -7.3; 116 -7.5; 128 -7.6; 141 -7.7; 155 -7.6; 170 -7.5; 187 -7.3; 206 -7.0; 227 -6.6; 249 -6.2; 274 -5.8; 302 -5.4; 332 -5.0; 365 -4.6; 402 -4.4; 442 -4.4; 486 -4.6; 535 -4.4; 588 -3.9; 647 -3.4; 712 -3.0; 783 -2.9; 861 -2.8; 947 -2.8; 1042 -2.8; 1146 -2.8; 1261 -2.9; 1387 -2.9; 1526 -3.1; 1678 -3.8; 1846 -4.7; 2031 -5.1; 2234 -4.7; 2457 -4.2; 2703 -4.7; 2973 -5.1; 3270 -4.9; 3597 -3.5; 3957 -1.3; 4353 -5.0; 4788 -6.4; 5267 -5.0; 5793 -5.2; 6373 -8.2; 7010 -6.8; 7711 -6.8; 8482 -11.0; 9330 -11.8; 10263 -7.6; 11289 -6.3; 12418 -9.4; 13660 -11.6; 15026 -10.4; 16529 -8.6; 18182 -10.7; 20000 -16.3
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Beyerdynamic DT 990 250 Ohm GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beyerdynamic DT 990 250 Ohm ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.8dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 22 Hz    | 2.15 | 4.8 dB  |
| Peaking | 1024 Hz  | 1.06 | 2.9 dB  |
| Peaking | 3904 Hz  | 7.8  | 4.4 dB  |
| Peaking | 8967 Hz  | 5.47 | -6.0 dB |
| Peaking | 20799 Hz | 0.12 | -7.5 dB |
| Peaking | 38 Hz    | 2.34 | 1.0 dB  |
| Peaking | 137 Hz   | 1.05 | -2.7 dB |
| Peaking | 11179 Hz | 4.76 | 3.2 dB  |
| Peaking | 13641 Hz | 2.42 | -2.8 dB |
| Peaking | 16760 Hz | 2.23 | 3.1 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.7dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 3.3 dB  |
| Peaking | 62 Hz    | 1.41 | -0.6 dB |
| Peaking | 125 Hz   | 1.41 | -2.6 dB |
| Peaking | 250 Hz   | 1.41 | -0.8 dB |
| Peaking | 500 Hz   | 1.41 | 0.9 dB  |
| Peaking | 1000 Hz  | 1.41 | 2.9 dB  |
| Peaking | 2000 Hz  | 1.41 | -0.0 dB |
| Peaking | 4000 Hz  | 1.41 | 2.2 dB  |
| Peaking | 8000 Hz  | 1.41 | -4.2 dB |
| Peaking | 16000 Hz | 1.41 | -6.7 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Beyerdynamic%20DT%20990%20250%20Ohm/Beyerdynamic%20DT%20990%20250%20Ohm.png)