# Data Augmentation

Here we developed 3 data augmentations on our data.
'Audio Augmentation (Time-shift, Noise)' is running 2 augmentations on the Audio (wav files).
'Image Augmentation (S&P)' is running augmentation on the Spectograms (png files).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for running and testing purposes.

### Prerequisites

* python 3

Following libraries needs to be installed in order to run the project-

* pandas
* matplotlib
* numpy
* scipy
* librosa
* PIL
* Jupiter Notebook

Windows-
You will also need to install Anaconda


### Installing

Windows-

Install all packages using the conda-install command as following-

```
conda install -c anaconda pandas 
```


Ubuntu-
```
sudo apt-get install python3-pandas 
```

PyPI-
```
pip install pandas 
```


And repeat on all libraries from the 'Prerequisites' if the libraies are not installed on your local computer (or conda virtual env)


## Running the Notebook

Windows-
Open you Anaconda Navigator and Launch the Jupiter Notebook application (make sure you are on the right virtual env)

Ubuntu-
Open a Terminal window and run following command-
```
jupiter notebook 
```


The notebook will open. You can either run one cell at a time or click 'Cell' --> 'Run All'