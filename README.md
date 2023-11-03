# CRATI: Contrastive representation-based multimodal sound event localization and detection

This is a PyTorch implementation of our submitted manuscript [CRATI: Contrastive representation-based multimodal sound event localization and detection]().

**Abstract**
Sound event localization and detection (SELD) refers to classifying sound categories and locating their locations with acoustic models on the same multichannel audio. Recently, SELD has been rapidly evolving by leveraging advanced approaches from other research areas, and the benchmark SELD datasets have become increasingly realistic with simultaneously captured videos provided. Vibration produces sound, we usually associate visual objects with their sound, i.e., we hear footsteps from a walking person, hear jangle from one running bell, and hear applause from a person clapping. It comes naturally to think about using multimodal information (image-audio-text vs audio merely), to strengthen sound event detection (SED) accuracies and decrease sound source localization (SSL) errors. In this paper, we propose one contrastive representation-based multimodal acoustic model (CRATI) for sound event localization and detection, which is designed to learn contrastive audio representations from audio, text, and image in an end-to-end manner. Experiments on the real dataset of STARSS23 and the synthesized dataset of TAU-NIGENS Spatial Sound Events 2021 dataset both show that our CRATI model can learn more effective audio features with additional constraints to minimize the difference among audio, image, and text (SED and SSL annotations in this work). Compared to the baseline system, our model increases the SED F-score by 11% and decreases the SSL error by 31.02° on the STARSS23 dataset, respectively.

## Acess to this source code

**Note: The source code is free for non-commercial research and education purposes.** Any commercial use should get formal permission first.

The code and relevant supplementary materials are released under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode) for NonCommercial use only.

Please cite our paper if you use any part of our source code or data in your research.

## Requirement

*   python>=3.9.7
*   audioread>=2.1.9
*   PyTorch>=1.12.1
*   torchvision>=0.13.1
*   pandas>=1.4.4
*   librosa>=0.8.1
*   h5py>=3.7.0
*   numpy>=1.20.3
*   scikit-learn>=1.0.1
*   scipy>=1.7.3

## Usage

The source codebase is coming soon...

## SELD outputs visualization
[![SELD prediction demo]((https://github.com/Cratial/CRATI_SELD/blob/main/viz/video_frame.png)](https://github.com/Cratial/CRATI_SELD/blob/main/viz/crati_seld_starss23.mp4)

[![Watch the video](https://img.devbox.cn/3cccf/16086/243/7a4ce818aebe26ff.png)](https://youtu.be/vt5fpE0bzSY)


## Code References

In this Codebase, we utilize code from the following source(s):

*   [crnn-based seld](https://github.com/sharathadavanne/seld-dcase2022)
*   [einv2-based seld](https://github.com/Jinbo-Hu/DCASE2022-TASK3)

