# PAT-public-data

Jiahong Li a, Zhiyuan Zheng a, Zilong Li a, Yiguang Wang a, Yubin Cao a, Qiegen Liu a,* ,Xianlin Song a,* Establishment of data-domain sharing database for generative artificial intelligence-based photoacoustic tomography

If data from this database are used, please cite the above papers:"Establishment of data-domain sharing database for generative artificial intelligence-based photoacoustic tomography"-https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13248/132480U/Establishment-of-data-domain-sharing-database-for-generative-artificial-intelligence/10.1117/12.3033668.short
Date : Dec-6-2024


Traditional reconstruction algorithms use acoustic inversion analytical methods to reconstruct, such as time domain back-projection, time reversal, delayed summation, etc. To obtain high-quality imaging, one can utilize multi-element ultrasound detectors, such as a full-ring detector, spherical detection array, ring detection array, or planar detection array. Of course, this will make the system more complex and more expensive. Therefore, we use a single-probe photoacoustic system, which uses a rotating stage to drive the probe to rotate to different angles to collect photoacoustic signals, and then uses the collected photoacoustic data to reconstruct the image using a back-projection algorithm.
# System.
Our system consists of step control module, laser trigger module and data acquisition(DAQ) module. The stepping module consists of a vertical stepping motor and a horizontal rotating stage. The laser trigger module is composed of a laser. During acquisition, the laser pulse triggers DAQ to collect data. The rotating stage rotates every 2° and collects 180 times in one rotation. The sampling frequency of the DAQ is 500MHz and 50,000 points are sampled each time. The rotation radius of the ultrasonic probe is ~7cm. Finally, the collected photoacoustic signals are formed into a sinogram, and the back-projection algorithm is used to reconstruct the sample image.
![zong](https://github.com/yqx7150/PAT-public-data/assets/26964726/fcd4a251-1bad-4905-9e83-6f744f08d919)



DAQ sampling frequency：500MHz，

Sampling points：50000，

Rotation radius of rotary table~7cm，

360° imaging (scan every 2°, 180 times in total)



# Results.
![zong](https://github.com/yqx7150/PAT-public-data/assets/26964726/a50a2dea-9500-42df-b57c-75b4f05257a1)


Fig. 2.Reconstruction results of 180 angles,
     (a) (d) (g) (j) are black tape samples, 
     (b) (e) (h) (k) are the obtained sinograms, 
     (c) (f) (i) (l) are the back-projection reconstruction results 





## Other Related Projects
  * Accelerated model-based iterative reconstruction strategy for sparse-view photoacoustic tomography aided by multi-channel autoencoder priors       
[<font size=5>**[Paper]**</font>](https://onlinelibrary.wiley.com/doi/10.1002/jbio.202300281)   [<font size=5>**[Code]**</font>](https://github.com/yqx7150/PAT-MDAE)  
 * Generative model for sparse photoacoustic tomography artifact removal      
[<font size=5>**[Paper]**</font>](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12745/1274503/Generative-model-for-sparse-photoacoustic-tomography-artifact-removal/10.1117/12.2683128.short?SSO=1)         

 * Sparse-view reconstruction for photoacoustic tomography combining diffusion model with model-based iteration      
[<font size=5>**[Paper]**</font>](https://www.sciencedirect.com/science/article/pii/S2213597923001118)       [<font size=5>**[Code]**</font>](https://github.com/yqx7150/PAT-Diffusion)

 * Unsupervised disentanglement strategy for mitigating artifact in photoacoustic tomography under extremely sparse view      
[<font size=5>**[Paper]**</font>](https://www.sciencedirect.com/science/article/pii/S2213597923001118)       [<font size=5>**[Code]**</font>](https://github.com/yqx7150/PAT-ADN)

 * Score-based generative model-assisted information compensation for high-quality limited-view reconstruction in photoacoustic tomography  
[<font size=5>**[Paper]**</font>](https://www.sciencedirect.com/science/article/pii/S2213597923001118)       [<font size=5>**[Code]**</font>](https://github.com/yqx7150/Limited-view-PAT-Diffusion)


