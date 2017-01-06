# Klasse10


## Modeltest #1

Programmieren Sie ein Patch, das Klangdatei "voice.wav" mit der Granularsynthese fünf mal länger als das Original ohne Tonhöheänderung abspielt. Sie müssen mit dem Sample-And-Hold und der OLA-Technik Klick-Noise vermeiden. (20 min.)

[voice.wav](Klasse10/voice.wav)

### Zero Crossing

![Zerox](Klasse10/png/zerox.png)

zerox~ zählt "zero crossing".

![](Klasse10/png/zerocross.png)


### Noise-Erkennung

![](Klasse10/png/noisiness.png)

### zerox~ mit gen~

![](Klasse10/png/gen_zerocross~.png)

### Waveset Distortion


![](Klasse10/png/waveset.png)

Trevor Wishart defined a waveset as the signal between two zerocrossings. For a simple sinusoid, this corresponds to the waveform. But for signals of richer harmonic content, it produces more complex artefacts.


![](Klasse10/png/waveforms.png)

#### Waveset-Erkennung

![](Klasse10/png/waveset_detect.png)

##### Erklärung

- > 0
![](Klasse10/png/exp.png)

- >
#### Waveset Distortion #1

![](Klasse10/png/waveset_main.png)
![](Klasse10/png/waveset_gen.png)


#### Waveset Distortion #2

![](Klasse10/png/waveset_2.png)



