# Tascam TH-02
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -2.4; 23 -2.9; 25 -3.3; 28 -3.8; 31 -4.3; 34 -4.6; 37 -4.8; 41 -4.9; 45 -5.0; 49 -5.0; 54 -5.1; 60 -5.4; 66 -5.7; 72 -6.0; 79 -6.3; 87 -6.7; 96 -7.0; 106 -7.4; 116 -7.9; 128 -8.5; 141 -9.0; 155 -9.3; 170 -9.5; 187 -9.6; 206 -9.6; 227 -9.5; 249 -9.6; 274 -9.7; 302 -9.7; 332 -9.7; 365 -9.3; 402 -8.6; 442 -8.4; 486 -9.1; 535 -9.7; 588 -10.2; 647 -10.5; 712 -10.6; 783 -10.7; 861 -10.1; 947 -8.8; 1042 -8.4; 1146 -8.3; 1261 -8.8; 1387 -9.1; 1526 -9.5; 1678 -9.4; 1846 -7.9; 2031 -5.9; 2234 -3.6; 2457 -1.5; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.5; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -2.0; 7010 -4.1; 7711 -7.7; 8482 -10.7; 9330 -10.5; 10263 -8.8; 11289 -6.9; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Tascam TH-02 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Tascam TH-02 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.3dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.9dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 515 Hz  | 0.21 | -4.0 dB |
| Peaking | 1635 Hz | 2.34 | -4.7 dB |
| Peaking | 3779 Hz | 0.49 | 8.6 dB  |
| Peaking | 8839 Hz | 2.19 | -8.5 dB |
| Peaking | 17 Hz   | 0.83 | 4.5 dB  |
| Peaking | 65 Hz   | 1.14 | 1.6 dB  |
| Peaking | 431 Hz  | 3.38 | 1.9 dB  |
| Peaking | 798 Hz  | 2    | -2.3 dB |
| Peaking | 962 Hz  | 2.33 | 1.4 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-9.1dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 2.8 dB  |
| Peaking | 62 Hz    | 1.41 | 1.1 dB  |
| Peaking | 125 Hz   | 1.41 | -1.8 dB |
| Peaking | 250 Hz   | 1.41 | -2.7 dB |
| Peaking | 500 Hz   | 1.41 | -2.1 dB |
| Peaking | 1000 Hz  | 1.41 | -3.4 dB |
| Peaking | 2000 Hz  | 1.41 | -0.3 dB |
| Peaking | 4000 Hz  | 1.41 | 9.2 dB  |
| Peaking | 8000 Hz  | 1.41 | -2.8 dB |
| Peaking | 16000 Hz | 1.41 | -0.1 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Tascam%20TH-02/Tascam%20TH-02.png)