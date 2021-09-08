# Reactive - Sound processors library for reactive musical applications
### Description:


The __Reactive__ is a set of Pure Data patches used for sound processing and musical reactivity. Developed by the __Laboratory of Audio and Musical Technology (LATM)__ placed in __Escola de Artes, Ciências e Humanidades da Universidade de São Paulo (EACH/USP)__, it explores many possibilities of sound manipulation using the most varied tools.


The three __main__ objects are:

| Patch | Description |
| ------ | ------ |
| Reactor | Uses stecheometrical concepts metaforically so as to simulate a reaction out of two reagent sounds producing a third one |
| Timepitch |time-pitch transformer |
| Funew | Harmonic Progressive filter |


The distribution also includes __auxiliary__ objects:

| Patch | Description |
| ------ | ------ |
| Datatrack | Data management and control |
| Progcurve | Programable curve for data management and control in a Pure Data patch. |
| Ponta | Probe for verifying signal points in patches. |
| Patchbay | Router for several multichannel formats outputs |
| Espectro | Spectrum visualizer |
| Faixa | Range converter. |
| Instr | Instrument simulator. |
| Nano | Tool to expand Korg Nanokontrol2 surface controlability. |
| Antideadlock | Antideadlock for sliders. |
| Voluminho | Mono volume slider with on/off button. |
| Voluminhost | Stereo volume slider with on/off button. |

### Documentation and instructions (read carefully before using the patch):

For the correct object instantiation inside the Reactor patch, it needs some specific externals and libraries to be downloaded in your machine.

Required __Pure Data__ externals:
- __ggee__
- __iemlib v0.0__
- __cyclone__
- __zexy__
- __deken__

Other libraries:
- __Pdescriptors_v1.2/Spectral Features__

For Reactor: The __Pdescriptors__ is the only library that isn't an external and it should be added to your dependencies path (see below). It is a collection of objects used for sound description. It can be downloaded in the following link: https://sites.google.com/site/pdescriptors/.

__How to download Pd externals:__

1. Open the Pure Data
2. Access the __help__ tab
3. Click on __Find externals__ option
4. Search for the desired external by the names listed previously.

__Adding Pdescriptors to your libraries path:__

1. Access __File__ -> __Preferences__ -> __Path...__
2. Click on __New...__
3. Write the path to the Pdescriptors directory location

## Articles

1. Faria, Regis Rossi A.; Cunha Júnior, Ruy B.; Afonso, Eduardo da Silva. Reactive music: designing interfaces and sound processors for real-time music processing. In: Proceedings of the 11th International Symposium on Computer Music Multidisciplinary Research (CMMR), Plymouth, 2015.
2. Faria, Regis Rossi A., Afonso, Eduardo da Silva. , Junior, Ruy Borges da Cunha. Suíte de Software para Música Reativa. In: Congresso de Engenharia de Áudio, 11. , São Paulo, 2013. Disponível em: http://aesbrasil.org/congressos/anais/ 14 de setembro de 2015.

## License

CC BY (2013-2021)

  
