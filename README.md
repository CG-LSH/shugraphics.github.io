# shugraphics.github.io
Our online neuronal modeling site (http://47.100.48.237:8080/SWCweb)

And an executable program for Windows is also provided([exe](https://github.com/CG-LSH/shugraphics.github.io/tree/main/AdaptiveVolumeNueronModel_Realse_Exe)), the operation video is provided as well.([video](https://github.com/CG-LSH/shugraphics.github.io/tree/main/CSBJ_compressed.mp4)) 

Specific functions： 

Input parameters:
1. voxel size :  Control the fineness of the overall model, the smaller the value the more precise and relatively more time-consuming. Default value as 𝑣𝑜𝑥𝑒𝑙 𝑠𝑖𝑧𝑒 = 𝛼 ∗ 𝑟, where 𝑟 corresponds
to the minimum radius of the skeleton, and 𝛼 is a scaling factor ranging from 0.125 to 1.0;

2. edge_scale : Control the overall edge length of the mesh, the larger the value the more simplified the mesh. Default value is the average edge length, and the input value will be substituted as a multiplication factor;

3. is_adaptive: Whether to perform adaptive reconstruction of the mesh, the default value is 1, and the mesh is reconstructed according to the approximate curvature;

4. blending factor ts: The value range is 1.2 ~ 2.0, the blending control factor, which controls the convolution surface to a certain extent to eliminate over-fusion, the default value is changed according to the radius and the fixed blending sum factor.

5. fixed factor t: Theoretical value range 1.01 ~ 2.0.

...

Render Mode : 

SelcetMode "1" :Voxel topology ![figure.1](https://github.com/CG-LSH/shugraphics.github.io/tree/main/figure/1.png)  

SelcetMode "2" :Iso-surface  ![figure.2](https://github.com/CG-LSH/shugraphics.github.io/tree/main/figure/2.png)

SelcetMode "3" :Voxel particle   ![figure.3](https://github.com/CG-LSH/shugraphics.github.io/tree/main/figure/3.png)

SelcetMode "4" :Non-adaptive mesh   ![figure.4](https://github.com/CG-LSH/shugraphics.github.io/tree/main/figure/4.png)

SelcetMode "5" :Adaptive mesh  ![figure.5](https://github.com/CG-LSH/shugraphics.github.io/tree/main/figure/5.png)

...

