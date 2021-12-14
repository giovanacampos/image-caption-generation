# Image Caption Generation

## Project based on the paper
----
<https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Vinyals_Show_and_Tell_2015_CVPR_paper.pdf>

## DevOps
----
### Install

1. Install virtual environment on Linux

```` 
sudo apt install -y virtualenv
````

### Setup

1. Setup virtual env. folder for python

````
virtualenv .venv
````

2. Activate environment sourcing

````
source .venv/bin/activate
````

3. Install requirements packages for code

````
pip install -r requirements.txt
````

### Start

1. Activate environment sourcing

````
source .venv/bin/activate
````

### Finish

1. Remove sourcing of virtual environment

````
deactive
````

## Dataset
----
Pascal VOC 2008: 1000 test

* <https://www.kaggle.com/sulaimannadeem/pascal-voc-2008>

Flickr8k: 6000 train; 1000 valid; 1000 test

* <https://www.kaggle.com/adityajn105/flickr8k>

Flickr30k: 28000 train; 1000 valid; 1000 test

* <https://www.kaggle.com/hsankesara/flickr-image-dataset>

MSCOCO: 82783 train; 40504 valid; 40775 test

* <https://cocodataset.org/#download>

SBU: 1M train

* <http://www.cs.virginia.edu/~vicente/sbucaptions/>