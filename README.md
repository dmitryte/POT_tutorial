# OpenVINO toolkit hands-on training

## What are we going to do here?

### This tutorial consists of 2 parts:

### Basic review of OpenVINO tools:
* Model Optimizer - tool that facilitates the transition between the training and deployment environment, performs static model analysis, and adjusts deep learning models for optimal execution on end-point target devices.
* Inference Engine - a unified API to allow high performance inference on many hardware.
* Accuracy Checker - tool to measure accuracy of a model.
* Post-Training Optimization Toolkit - tool designed to convert a model into a more hardware-friendly representation by applying specific methods that do not require re-training, for example, post-training quantization.
* Benchmark Application - Python sample for getting best performance with the OpenVINO Inference Engine.
* Python API for Inference Engine

### [ADVANCED](https://github.com/avbelova/POT_tutorial/blob/master/POT_tutorial_ADVANCED.ipynb) covers complicated cases and focuses on custom funtionality, discovering secrets of Accuracy Checker - the base of POT.
* Accuracy checker architecture
* How to analyze the model
* How to support custom dataset 
* How to add custom pre- and post- processing
* YoloV3 example
* DCSCN example

## Prerequisites:
1. [Intel(R) Distrubution of OpenVINO Toolkit](https://software.intel.com/content/www/us/en/develop/tools/openvino-toolkit.html) 2020.2 for Linux.
2. Installed OpenVINO [Accuracy Checker](https://docs.openvinotoolkit.org/latest/_tools_accuracy_checker_README.html) Tool with all dependencies.
3. Installed OpenVINO [Post-Training Optimization Toolkit](https://docs.openvinotoolkit.org/latest/_README.html) with all dependencies.

## Getting Started:
#### You can run the titorial at your own machine:
1. Clone or download the repo:

`$ git clone https://github.com/avbelova/POT_tutorial.git`

2. Go to the tutorial directory:

`$ cd POT_tutorial`

3. Set up OprnVINO environment:

`$ source /opt/intel/openvino/bin/setupvars.sh`

4. Run Jupyter Notebook

`$ jupyter notebook`

   or Jupyter lab

`$ jupyter lab`

#### Other option is to run it on the [Intel® DevCloud for the Edge](https://devcloud.intel.com/edge/). In this case you don't need to install anything and source environment variables. You should just clone the repo, proceed to the directory and run Jupyter notebook/lab.
