# Multilinear Tongue Model

## Introduction

This repository contains a multilinear tongue shape model that was derived from MRI data.
We used the dataset of the [Ultrax project](http://www.ultrax-speech.org/) and the one of [Adam Baker] (http://adambaker.org/qmu.php) to create the model.

## Components

This repository provides you with the following files:

- tongue_model.yaml : This is the YAML version of the model. Here, the core tensor is encoded in Base64 to save some space.
- tongue_model.json : In this version, the model is saved in JSON format and no Base64 encoding is used.

## Using the model

Have a look at [multilinear-model-tools] (https://github.com/m2ci-msp/multilinear-model-tools) for example code using the model.

## License

This work is licensed under the Creative Commons BY-NC-ND.
Thus, you should

- give appropriate credit if you use the work,
- not use it for commercial purposes,
- and not create derivatives of it.

Have a look at [https://creativecommons.org/licenses/by-nc-nd/4.0/](https://creativecommons.org/licenses/by-nc-nd/4.0/) for details.

In case, you are using our model, please cite for the time being the following paper:

    @article{HewerWSR16,
        author    = {Hewer, Alexander and Wuhrer, Stefanie and Steiner, Ingmar and Richmond, Korin},
        title     = {A Multilinear Tongue Model Derived from Speech Related {MRI} Data of the Human Vocal Tract},
        journal   = {CoRR},
        volume    = {abs/1612.05005},
        year      = {2016},
        url       = {http://arxiv.org/abs/1612.05005}
    }
    
