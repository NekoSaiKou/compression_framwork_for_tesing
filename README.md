An End-to-End Compression Framework Based on Convolutional Neural Networks
==

## The testing code for end-to-end compression frame work

### Source

Repo forked from [here](https://github.com/compression-framework/compression_framwork_for_tesing).

[Paper source](https://ieeexplore.ieee.org/document/7923746)

### Modify

The original program is not compatible with current MatConvNet. To fix the bug, following code is added.

    net = vl_simplenn_tidy(net); 

This code takes the NET object and upgrades it to the current version of MatConvNet.

### Testing Result

#### Source

![](test.png)

#### Compressed image

![](compressed_image.jpg)

#### Reconstructed image

![](output.jpg)

#### Directly converted JPEG

![](JPEG-Directly.jpg)