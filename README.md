# Classify radio signals from space using Keras

## Introduction

Back in 2017, SETI institute announced a hackathon -
"Machine Learning for the Search for Extraterrestrial Intelligence Hackathon & Code Challenge".

Objective: To develop a signal classification algorithm that can accurately identify different types of radio signals, observed through SETI's Allen Telescope Array. 

Dataset: Simulated signals with labels, tranformed into spectrogram readings (which essentially makes it a 2D image classification problem).

Note: There are 4 different datasets provided by SETI.
1. Basic
2. Primary (small)
3. Primary (medium)
4. Primary (full)

For this experiment, we have used the basic dataset which has:
1. Only 4 different classes - squiggle, narrowband, noise and narrowbanddr (Primary dataset has 7 different signal types).
2. Only 4000 examples (1000 for each type).
3. Higher signal to noise ratio / larger amplitudes (easy to work on).

We develop a simple convolutional neural network in Keras, and see how it performs on the data.

## Reference

[1] https://www.seti.org/machine-learning-search-extraterrestrial-intelligence-hackathon-code-challenge
[2] https://arxiv.org/pdf/1803.08624.pdf

Project: based on Coursera

## License

MIT



