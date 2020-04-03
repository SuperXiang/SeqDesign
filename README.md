# SeqDesign

## Installation

We recommend using SeqDesign with a GPU that supports CUDA, especially for training.
If a GPU is available, install the [TensorFlow GPU dependencies](https://www.tensorflow.org/install/gpu), 
then install the SeqDesign dependencies with:
> pip install -r requirements_gpu.txt

An example script for tensorflow-gpu installation is available at [linux_setup.sh](linux_setup.sh).
As tested, installation on a clean install of Ubuntu 18.04 LTS took 5 minutes.

If no GPU is available, use:  
> pip install -r requirements.txt  

Then install SeqDesign:
> python setup.py install

### Used packages and the versions tested:
- tensorflow - 1.12  
- numpy - 1.15  
- scipy - 0.19  
- sklearn - 0.18  

Tested on Ubuntu 18.04 LTS and CentOS 7.2

## Examples

See [examples/README.md](examples/README.md)


## Usage

### Training

Given a fasta file of training sequences, run:

> run_autoregressive_fr <your_dataset>.fa
