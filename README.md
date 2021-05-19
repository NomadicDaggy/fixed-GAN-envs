# Fixed GAN environments

## Sources and python versions

* [Bridge-GAN](https://github.com/PKU-ICST-MIPL/Bridge-GAN_TCSVT2019) py 3.6.8
* [ControlGAN](https://github.com/mrlibw/ControlGAN) py 3.7.10
* [DF-GAN](https://github.com/tobran/DF-GAN) py 3.6.10
* [DM-GAN](https://github.com/MinfengZhu/DM-GAN) py 2.7.18
* [HDGAN](https://github.com/ypxie/HDGan) py 3.6.13
* [StackGAN++](https://github.com/hanzhanggit/StackGAN-v2) py 2.7.18

## Usage

To setup the GAN environment, follow all the usual instructions from its repository (links above), but just start with setting up an Anaconda environment with:

```sh
conda create --name ENV_NAME --file ./path/to/environment.yml python=PYTHON_VERSION
conda activate ENV_NAME
pip install -r ./path/to/requirements.txt
```

If any of these complain about needing cuDNN, version 7.6.5 (for CUDA 9) worked for me. A good write-up of the install process is available here: https://stackoverflow.com/questions/42013316/after-building-tensorflow-from-source-seeing-libcudart-so-and-libcudnn-errors/44147506#44147506

*Working on Ubuntu 20.04*
