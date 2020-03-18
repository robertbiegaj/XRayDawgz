<p align="left">
  <img src="https://github.com/X-ray-Dawgz/XRayDawgz/blob/master/banner.png" width="900">
</p>


[![Build Status](https://travis-ci.com/X-ray-Dawgz/XRayDawgz.svg?branch=master)](https://travis-ci.com/X-ray-Dawgz/XRayDawgz)
[![Coverage Status](https://coveralls.io/repos/github/X-ray-Dawgz/XRayDawgz/badge.svg?branch=master)](https://coveralls.io/github/X-ray-Dawgz/XRayDawgz?branch=master)
- UW DIRECT project of a general XRD image pattern classifier framework for predicting crystal structure.

## Table of Contents
- Background
- Purpose
- Repository Structure
- How to install
- Examples and Demos
- How to use our software
- License

## Background
All crystalline materials in nature have chemical and physical properties strongly dependent on atomic structures
  - Single-crystal X-ray diffraction
    - Limitations: nanosized crystals, intergrowth, and defects
  - Powder X-ray diffraction
    - Limitations: complex structures, multiphasic samples, impurities, peak overlaps
  - Alternatives: electron crystallography (EC), high-resolution transmission electron microscopy (HRTEM)
    - Requires considerable expertise on the operation of electron microscopes and crystallography

SOLUTION: to use CNN to predict crystal structure from any XRD pattern
  
## Purpose
This project will aim to use CNN to predict the crystal structure of a sample based upon its XRD pattern.


## Repository Structure 
```
  |- README.md
  |- Images/
      |- BCC_test
      |- BCC_train
      |- Cubic_BCC
      |- Cubic_FCC
      |- FCC_test
      |- FCC_train
  |- XRayDawgz/
      |- __init__.py
      |- core.py
      |- version.py
      |- tests/
        |- __init__.py
        |- test_core.py
        |- cut_image/
          |- Test/
          |- Train/
  |- docs/
      |- Tech_review.pdf
      |- functional_spec.md
      |- component_spec.md
  |- setup.py
  |- .travis.yml
  |- .coveragerc
  |- .coverage.yml
  |- environment.yml
  |- .gitignore
  |- LICENSE 
  |- banner.png
  |- requirements.txt
 ``` 

## How to install
1. Install tensorflow and keras

    ```conda install tensorflow```

    ```conda install keras```

2. Use the following method to clone repo

   First, press the green botton <img src="https://github.com/X-ray-Dawgz/XRayDawgz/blob/master/icon.png" width="80"> at 
   
   the home page of our repo, and choose "Download Zip". Finally, unzip the file and you would get the file name "XRayDawgz"  
   in your path.

## Examples and Demos


## How to use our software
1.First, the user needs to prepare the XRD diagram pictures which they want to make the prediction. These pictures need to   
  
  match our standard to test. 
  
  - The standard size is 432*288pxi
  - the range of the diffraction angle(2θ) needs to be 0-80 degree
  - the format of the pictures can be .jpg, .npg, .jpeg, .bmp

2.







## License
[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://pypi.python.org/pypi/ansicolortags/)
