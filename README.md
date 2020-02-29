# MDLatLRR: A novel decomposition method for infrared and visible image fusion

IEEE Trans. Image Process.

doi: 10.1109/TIP.2020.2975984

## Note
In 'main.m' file, you will find how to run these codes.

## Platform

MATLAB R2017b on 2.8 GHz Intel(R) Core(TM) i5-8400 CPU with 16 GB RAM.

## Fusion framework
![](https://github.com/hli1221/imagefusion_mdlatlrr/blob/master/figures/framework.png)

## Latent Low-Rank Representation
<img src="https://github.com/hli1221/imagefusion_mdlatlrr/blob/master/figures/latentlrr.png" width="600">

## Multi-level decomposition with Latent LRR

### DLatLRR and MDLatLRR
<img src="https://github.com/hli1221/imagefusion_mdlatlrr/blob/master/figures/DLatLRR.png" width="600">

### MDLatLRR
<img src="https://github.com/hli1221/imagefusion_mdlatlrr/blob/master/figures/MDLatLRR.png" width="600">


## MDLatLRR for RGBT visual object tracking
The VOT-RGBT2019 sub-challenge benchmark is available at [here](http://www.votchallenge.net/vot2019/dataset.html).

The frames fused by MDLatLRR are fed into two trackers ([LADCF](https://github.com/XU-TIANYANG/LADCF), [GFSDCF](https://github.com/XU-TIANYANG/GFS-DCF)).

The frames in first row and second row are selected from 'car10' and 'car41' (VOT-RGBT 2019), respectively. 

First three columns are the results of LADCF. And the last three columns are the tracking results of GFSDCF. 

The [RGB] and [infrared] denote the input of trackers is just one modality data (RGB or infrared). The [level-1] to [level-4] demonstrate that the input of trackers is the fused frames which are generated by MDLatLRR.


![](https://github.com/hli1221/imagefusion_mdlatlrr/blob/master/figures/rgbt-label-all.png)



If you have any question about this code, feel free to reach me(hui_li_jnu@163.com) 

# Citation


For code:
```
@misc{li2019mdlatlrr,
    author = {Hui Li},
    title = {Codes for MDLatLRR},
    year = 2019,
    note = {\url{https://github.com/hli1221/imagefusion_mdlatlrr}},
  }
```
