# PAT-public-data

Authors: Xianlin Song, Jiahong Li, Zhiyuan Zheng,Zilong Li,Guijun Wang,Wenhua Zhong,Qiegen Liu

Date : Dec-12-2023
Version : 1.0

Traditional reconstruction algorithms use acoustic inversion analytical methods to reconstruct, such as time domain back-projection, time reversal, delayed summation, etc. To obtain high-quality imaging, one can utilize multi-element ultrasound detectors, such as a full-ring detector, spherical detection array, ring detection array, or planar detection array. Of course, this will make the system more complex and more expensive. Therefore, we use a single-probe photoacoustic system, which uses a rotating stage to drive the probe to rotate to different angles to collect photoacoustic signals, and then uses the collected photoacoustic data to reconstruct the image using a back-projection algorithm.
# System.
Our system consists of step control module, laser trigger module and data acquisition(DAQ) module. The stepping module consists of a vertical stepping motor and a horizontal rotating stage. The laser trigger module is composed of a laser. During acquisition, the laser pulse triggers DAQ to collect data. The rotating stage rotates every 2° and collects 180 times in one rotation. The sampling frequency of the DAQ is 500MHz and 50,000 points are sampled each time. The rotation radius of the ultrasonic probe is ~7cm. Finally, the collected photoacoustic signals are formed into a sinogram, and the back-projection algorithm is used to reconstruct the sample image.
![xitongtuzong](https://github.com/yqx7150/PAT-public-data/assets/26964726/a3bda230-6f03-4a58-ac16-d04e7a0ba655)


Capture card sampling frequency：500MHz，

Sampling points：50000，

Rotation radius of rotary table~7cm，

360° imaging (scan every 2°, 180 times in total)



# Results.
![zong](https://github.com/yqx7150/PAT-public-data/assets/26964726/a50a2dea-9500-42df-b57c-75b4f05257a1)


Fig. 2.Reconstruction results of 180 angles,
     (a) (d) (g) (j) are black tape samples, 
     (b) (e) (h) (k) are the obtained sinograms, 
     (c) (f) (i) (l) are the back-projection reconstruction results 
