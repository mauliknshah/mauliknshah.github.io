---
title: Neuron Finder
layout: post
icon: fa-lightbulb
icon-style: regular
---
#### Neuron finder for fMRI images using NMF and Deep Learning
#### Area: Computer Vision; Technologies: Python, OpenCV.
#### Links: [Github Repo](https://github.com/mauliknshah/Elders)

In the neuron finder, a huge fMRI image dataset of brain images has been segmented using classical computer vision techniques like non-nagetive matrix factorization(NMF), image filters, and deep learning framework Sigma FRCNN. The project was accomplished in a team of 3.

Explaining the dataset a bit, the images are height-by-width-by-time, and the model needs to learn a height-by-width mapping of pixels, where each pixel is either part of a neuron or isn’t. Each folder of training and testing images is a single plane, and the images are numbered according to their temporal ordering. The neurons in the images will “flicker” on and off, as calcium (Ca2+) is added, activating the action potential gates. The end goal was to locate the neurons and segment them out from the surrounding areas.
