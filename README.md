# FovealBoosted

This a tool for nuclei segmentation.
## files


File name | Description
------------ | -------------
make_foveal.py | foveal blurred image generation
unet.py | unet model definition
test.py | main entrance of test of deep learning system
train.py | main entrance of training of deep learning system
resized_prior.mat | per-defined shape prior

## Directories

Dirs | Description
------------ | -------------
image/ | *.tif original pathology images
foveal/ | *.mat containing foveal blurred images
cells/ | *.mat containing nuclei-level masks
weights/ | containing trained weights
results/ | containing testing results

## Reference
Hongyi Duanmu, Fusheng Wang, George Teodoro, Jun Kong, “Foveal Blur-Boosted Segmentation of Nuclei in Histopathology Images with Shape Prior Knowledge and Constraints,” Oxford Bioinformatics,2021.
