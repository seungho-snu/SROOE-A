# SROOE

Pytorch implementation of our paper: Perception-Oriented Single Image Super-Resolution using Optimal Objective Estimation

### Environments
- Pytorch 1.10.0
- CUDA 11.3
- Python 3.8

### Test

    python test.py -opt options/test/test_SROOE_4x.yml

### Test models

- Download the pretrained SR 4x model <a href="https://www.dropbox.com/s/v7lx9qoji1ndonx/SR.pth?dl=0">Link</a>   
- Download the pretrained OOE model <a href="https://www.dropbox.com/s/hoykbrpadzozlab/OOE.pth?dl=0">Link</a>

### Visual and quantitative comparison between the results of SROOE and FxSR for 4x
<p align="center"><img src="figure/SROOE Vs FxSR - 4x.PNG" width="700"></p>
