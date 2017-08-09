# Registered Tongue Meshes of the Ultrax Project

## Introduction

This repository contains some registered and reconstructed tongue meshes that were derived from MRI data of the [Ultrax project][1] and of [Adam Baker][2].

## Components

This repository provides you with the following files:

- sampleDatabase.yaml : This is a [sample database][4] ready to be used with the [model-builder][5] tool to derive a multilinear tongue model from the registered meshes.
- meshes : This folder contains the registered and reconstructed meshes.

## Notes for deriving the model

The sample database contains relative paths of the meshes.
Thus, you should call **model-builder** from the same folder as **sampleDatabase.yaml**.

## License

This work is licensed under the Creative Commons BY-NC-ND.
Thus, you should

- give appropriate credit if you use the work,
- not use it for commercial purposes,
- and not create derivatives of it.

Have a look at [https://creativecommons.org/licenses/by-nc-nd/4.0/](https://creativecommons.org/licenses/by-nc-nd/4.0/) for details.
    
[1]: http://www.ultrax-speech.org
[2]: http://adambaker.org/qmu.php
[3]: https://github.com/m2ci-msp/mri-shape-tools/tree/master/model-builder
[4]: https://github.com/m2ci-msp/mri-shape-tools/blob/master/dataFormats/sampleDatabase.md
