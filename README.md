# Speech2Face

News 06/02/2021: Our repository reaches 100+ stars! Thanks for your interests for our work!

Implementation of CVPR 2019 paper: 'Speech2Face: Learning the Face Behind a Voice'

How much can we infer about a person's looks from the way they speak? In this paper, we study the task of reconstructing a facial image of a person from a short audio recording of that person speaking. We design and train a deep neural network to perform this task using millions of natural videos of people speaking from Internet/Youtube. During training, our model learns audiovisual, voice-face correlations that allow it to produce images that capture various physical attributes of the speakers such as age, gender and ethnicity. This is done in a self-supervised manner, by utilizing the natural co-occurrence of faces and speech in Internet videos, without the need to model attributes explicitly. Our reconstructions, obtained directly from audio, reveal the correlations between faces and voices. We evaluate and numerically quantify how--and in what manner--our Speech2Face reconstructions from audio resemble the true face images of the speakers.
