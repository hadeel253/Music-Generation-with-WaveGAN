# Music-Generation-with-WaveGAN

In this study, we utilize the WaveGAN architecture to generate music segments on the GTZAN music genre classification dataset, comprised of 100 30-second music segments with 10 genre classes. We conducted two experiments to compare the performance of each method ([Sound examples](https://hadeel253.github.io/Music-Generation-with-WaveGAN/)).
 
- In the first experiment, we used the entire genre dataset for training and validation without label conditioning. Augmentation was applied to the music before trimming the 30-second audio clips into 1-second segments, which were then used for the WaveGAN model.
 
- In the second experiment, we limited the dataset to only the **blues** genre class, providing us with only 100 samples for training and validation. Augmentation was applied to increase the diversity and generalizability of the model, and the music was segmented into 1-second segments. 
 
Augmented music and generated music samples and are available to listen to [here](https://hadeel253.github.io/Music-Generation-with-WaveGAN/). Future work is intended to improve the quality of samples including using label conditioning and either a simpler dataset or a better suited model for the task.

This work is intended for **research purposes** only.

References:
 
GTZAN dataset https://arxiv.org/abs/1306.1461
 
Pytorch WaveGAN https://github.com/mostafaelaraby/wavegan-pytorch.git
