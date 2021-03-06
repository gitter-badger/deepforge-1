[![Release State](https://img.shields.io/badge/state-pre--alpha-red.svg)](https://img.shields.io/badge/state-pre--alpha-red.svg)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](./LICENSE)
[![Build Status](https://travis-ci.org/dfst/deepforge.svg?branch=master)](https://travis-ci.org/dfst/deepforge)
[![Stories in Ready](https://badge.waffle.io/dfst/deepforge.png?label=ready&title=Ready)](https://waffle.io/dfst/deepforge)
# DeepForge
DeepForge is an open-source visual development environment for deep learning. Currently, it supports Convolutional Neural Networks but we are planning on supporting additional deep learning classifiers such as RNNs and LSTMs. Additional features include real-time collaborative editing and version control.

## Quick Setup
After cloning the repo, run

```
npm install && npm start
```

Now, navigate to `localhost:8888` in a browser and create a new project. Select `nn` as the seed and start creating your neural nets!

## Caffe Support?
DeepForge uses Torch to perform the actual training and testing of the models. If you are interested in DeepForge using Caffe for actual training and testing, check out [DeepForge-Caffe](https://github.com/dfst/deepforge-caffe).

## Interested in contributing?
Contributions are welcome! Either fork the project and submit some PR's or shoot me an email about getting more involved!
