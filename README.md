# Splatter a Video: Video Gaussian Representation for Versatile Processing



### Quantitative Comparison on Video Reconstruction (PSNR)
Table R1.  Comprehensive comparison with existing methods on Tap-Vid benchmark (DAVIS). 

| Metric | PSNR ↑ | SSIM ↑ | LPIPS ↓ | AJ ↑ | $\delta_{avg}^x ↑$ | OA ↑ | TC ↓ | Training Time | GPU Memory | FPS |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 4DGS | 18.12 | 0.5735 | 0.5130 | 5.1 | 10.2 | 75.45 | 8.11 | ~40 mins | 10G | 145.8 |
| RoDyF | 24.79 | 0.723 | 0.394 | \ | \ | \ | \ | > 24 hours | 24G | > 1min |
| Deformable Sprites | 22.83 | 0.6983 | 0.3014 | 20.6 | 32.9 | 69.7 | 2.07 | ~30 mins | 24G | 1.6 |
| Omnimotion | 24.11 | 0.7145 | 0.3713 | **51.7** | **67.5** | **85.3** | **0.74** | > 24 hours | 24G | > 1min |
| CoDeF | 26.17 | 0.8160 | 0.2905 | 7.6 | 13.7 | 78.0 | 7.56 | ~30 mins | 10G | 8.8 |
| Ours | **28.63** | **0.8373** | **0.2283** | 41.9 | 57.7 | 79.2 | 1.82 | ~30 mins | 10G | 149 |


