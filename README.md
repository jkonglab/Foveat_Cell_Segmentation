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

## License
This tool is available under the GNU General Public License (GPL) (https://www.gnu.org/licenses/gpl-3.0.en.html) and the LGPL (https://www.gnu.org/licenses/lgpl-3.0.en.html).
