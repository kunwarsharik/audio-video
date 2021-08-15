# audio-video
<h2>audio video trial 1</h2>
This file is initial trial. The aim is to extract features from audio and video seperately. To utilize dataset fully,
Add audio sample which is silent to only video samples from the dataset.</br>
Add black frames to audio samples which don't have video with them i.e. the audio only samples from the dataset.</br>
The Audio-Video samples have both audio and video.

Note: The dataset provided had only audio-video and only-video samples. The only-audio samples were downloaded from website link given.

Make shape for all the inputs same.

Train model for audio samples only. We get 68% accuracy. As shown in audio video 2.ipynb file. at 200 epochs.

I ran for video feature due to time limitation even after using multiple colabs with GPU it was not complete.
If given a chance I am confident it will easily give above 90% accuracy, utilizing full potetial of multimodality.

Another solution I thought was to use transformer architecture. Combine audio and video as single unit. Similarly breaking
Audio-video in 16x16. Then see how global multimodal features perform for this problem.
