# Music-Generation-with-WaveGAN

In this study, we utilize the WaveGAN architecture to generate music segments on the GTZAN music genre classification dataset, comprised of 100 30-second music segments with 10 genre classes. We conducted two experiments to compare the performance of each method.
 
In the first experiment, we used the entire genre dataset for training and validation, removing the labels from the dataset. Audio augmentation was applied to the music before trimming the 30-second audio clips into two 4-second segments, which were then passed through the WaveGAN model.
 
In the second experiment, we limited the dataset to only the blues genre class, providing us with 100 samples for training and validation. Augmentation was applied to increase the diversity and generalizability of the model, and the music was segmented into 7 segments of 4 seconds each. This resulted in 980 training samples and 210 validation samples.
 
Generated music segments are available to listen to below.
 
### Augmented music samples:


   

### Generated music samples:

   



This work is intended for **research purposes** only.


References:
 
GTZAN dataset https://arxiv.org/abs/1306.1461
 
Pytorch WaveGAN https://github.com/mostafaelaraby/wavegan-pytorch.git
