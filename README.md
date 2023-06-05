# Redes Neuronales: Proyecto Final

> Juan Pablo Yamamoto Zazueta
> [jpyamamoto@ciencias.unam.mx](mailto:jpyamamoto@ciencias.unam.mx)

## Instruciones

1. Clonar el repositorio.
2. Descargar el archivo [modelo_final.pt](https://huggingface.co/jpyamamoto/whale/blob/main/models/modelo_final.pt). Se encuentra almacenado en la plataforma *HuggingFace* porque GitHub no me permitió subir un archivo pesado.
3. Colocar el archivo descargado en `models/modelo_final.pt`.
4. Ejecutar una por una las celdas en el notebook.

## Detección de Ballenas

En el notebook adjunto [Detección de Ballenas]("Detección de Ballenas.ipynb") hicimos el procesamiento de archivos de audio para transformarlos en espectrogramas que recaben la información necesaria sobre los archivos en formato `.aiff`.

Estos archivos fueron transformados en imágenes PNG de tamaño 64x64.

Posteriormente, desarrollamos una red neuronal convolucional basada en AlexNet que entrenamos para categorizar imágenes según si el espectrograma corresponde a un audio con una ballena presente, o no.

Finalmente, evaluamos el desempeño de la red.

## Referencias

- ["Getting to Know the Mel Spectrogram" - Dalya Gartzman](https://towardsdatascience.com/getting-to-know-the-mel-spectrogram-31bca3e2d9d0)
- [Python Audio](https://www.audiolabs-erlangen.de/resources/MIR/FMP/B/B_PythonAudio.html)
- ["Extracting Mel Spectrograms with Python" - Valerio Velardo - The Sound of AI](https://youtu.be/TdnVE5m3o_0)
- ["Mel Spectrograms Explained Easily" - Valerio Velardo - The Sound of AI](https://youtu.be/9GHCiiDLHQ4)
- ["Why do we perceive logarithmically?" - Lav R. Varshney & John Z. Sun](https://rss.onlinelibrary.wiley.com/doi/pdf/10.1111/j.1740-9713.2013.00636.x)
- ["Whale Sounds Lab" - Mr. Van Arsdale](https://mrvanarsdale.com/marine-science/online-textbook/chapter-2-cetaceans/whale-sounds-lab/)
- ["Introduction to Speech Processing - Waveform" - Tom Bäckström, et al.](https://speechprocessingbook.aalto.fi/Representations/Waveform.html)
- ["Nyquist Frequency" - MathWorld](https://mathworld.wolfram.com/NyquistFrequency.html)
- ["North Atlantic Right Whale" - University of Rhode Island and Inner Space Center](https://dosits.org/galleries/audio-gallery/marine-mammals/baleen-whales/north-atlantic-right-whale/)
- ["Why is the output of the FFT symmetrical?" - Mark Newman](https://youtu.be/IIofPiVVC64)
- ["Sound Visualization" - Maël Fabien](https://maelfabien.github.io/machinelearning/Speech10/#)
- ["Digital Audio Explained" - Computer Science](https://youtu.be/Ibrf6LHloGc)
- ["CNNs for Audio Classification" - Papia Nandi](https://towardsdatascience.com/cnns-for-audio-classification-6244954665ab)
- [ConvNet Calculator](https://madebyollin.github.io/convnet-calculator/)
- ["AlexNet Architecture" - Upendra Kumar](https://hackmd.io/@imkushwaha/alexnet)
- ["AlexNet - An Explanation of Paper with Code" - Abhishek Verma](https://towardsdatascience.com/alexnet-8b05c5eb88d4)
- ["A suitable way to punish mis-classification via nn.CrossEntropyLoss?" - Andrew](https://discuss.pytorch.org/t/a-suitable-way-to-punish-mis-classification-via-nn-crossentropyloss/94343)
