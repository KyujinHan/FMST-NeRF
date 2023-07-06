# [FST-NeRF](soon)
3D Real Scene Style Transfer of Neural Radiance Fields with Hash Encoding and HyperNet

# Abstract
(Soon)  

# Dataset
1) Download LLFF dataset.  
You can download [NeRF_llff_Dataset](https://drive.google.com/drive/folders/128yBriW1IG_3NJ5Rp7APSTZsJqdJdfc1) this link.
```
data
├── nerf_llff_data                    
│   ├── fern
|   ├── flower
│   ├── horns            
│   └── ...
```
  
2) Download Wikiart dataset. 
You can download [WikiArt](https://github.com/cs-chan/ArtGAN/blob/master/WikiArt%20Dataset/README.md) this link.
Also, you can find the WikiArt files other Stylization-NeRF-Project.  

# Training 
### Geometric training
------------

### Stylization training
------------

# Testing
(Soon)  

# Performance (Soon update)
------------  
LPIPS  
- Short consistency score (2 frames)
  
| Method | Fern | Flower | Horns | Orchids | Trex | Leaves |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| `MCCNet` | 0.1950 | 0.1541 | 0.1903 | 0.2220 | 0.1246 | 0.1306 |
| `ReReVST` | 0.2178 | 0.2093 | 0.2295 | 0.2770 | 0.1976 | 0.1776 |  
| `AdaIN` | 0.1498 | 0.1815 | 0.2443 | 0.2682 | 0.1899 | 0.1349 |
| `ARF` | 0.1600 | 0.1454 | 0.1786 | 0.2301 | 0.1041 | 0.1154 |
| `UPST` | **0.1246** | 0.1222 | NaN | NaN | NaN | 0.0931 |
| `StyleRF` | NaN | 0.1493 | 0.1957 | 0.2358 | 0.1225 | NaN |
| `Ours` | 0.1291 | **0.1217** | 0.1454 | 0.2101 | 0.0879 | **0.0879** |  
  
- Long consistency score (10 frames)
  
| Method | Fern | Flower | Horns | Orchids | Trex | Leaves |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| `MCCNet` | 0.4741 | 0.3693 | 0.4216 | 0.4468 | 0.3276 | 0.3655 |
| `ReReVST` | 0.4096 | 0.3550 | 0.4563 | 0.4577 | 0.3341 | 0.3361 |  
| `AdaIN` | 0.4106 | 0.3998 | 0.4610 | 0.4965 | 0.3575 | 0.3634 |
| `ARF` | 0.4451 | 0.3937 | 0.4497 | 0.4731 | 0.3039 | 0.3259 |
| `UPST` | **0.3969** | 0.3362 | NaN | NaN | NaN | 0.3081 |  
| `StyleRF` | NaN | 0.3543 | 0.4432 | 0.4557 | 0.3397 | NaN |  
| `Ours` | 0.4065 | **0.3167** | 0.3979 | 0.4108 | 0.2895 | **0.2911** |  

------------  
2) User Study


------------  
3) Style results (Some examples)
- **Room**  
![ezgif com-gif-maker](https://github.com/KyujinHan/FST-NeRF/assets/98331298/2df947f0-6522-4310-9936-eb782512a7b8)
  
- Flower
 

https://github.com/KyujinHan/FST-NeRF/assets/98331298/b218fee0-42bf-439a-bae7-58d811cc1c7e


  
- Horn


https://github.com/KyujinHan/FST-NeRF/assets/98331298/381aa559-d44e-4f45-bea4-2deb653d7132


  
# Citation
```
(Soon update)
```
  
# References
[HashNeRF](https://github.com/yashbhalgat/HashNeRF-pytorch)  
[HyperNetwork](https://github.com/vsitzmann/scene-representation-networks)  
[VAE](https://github.com/RoyalVane/ASM)  
[Style3D](https://github.com/ztex08010518/Stylizing-3D-Scene)  
[NeRF](https://github.com/yenchenlin/nerf-pytorch)  
