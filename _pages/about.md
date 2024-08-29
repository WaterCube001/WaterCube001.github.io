---
permalink: /
title: "Welcome, glad to know you! This is a brife introduction to Me~"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Say hello here! My name is Miao Sun. I am currently a Research Fellow in the College of Electrical and Electronic Engineering at Nanyang Technological University (NTU), Singapore. I received my PhD in Autumn 2023 from the [School of Microelectronics at Fudan University](https://sme.fudan.edu.cn/), where I was mentored by [Prof. Patrick Yin Chiang](https://sme.fudan.edu.cn/5f/e4/c31146a352228/page.htm). My research focuses on digital circuit and system design for SPAD (Single-Photon Avalanche Diode)-based imaging platform and depth completion technology. Following a year dedicated to advancing metalens-based LiDAR imaging systems at NTU, I am eager to explore further opportunities in digital circuit design. I am actively seeking academic roles that focus on digital system design, digital processing, and near-sensor applications. Passionate about pushing the boundaries of chip design, I aim to collaborate with leading experts in integrated circuits worldwide. I am open to discussions and would appreciate any recommendations!

Academic Biography
======
During her doctoral studies, Dr. Sun specialized in the design and implementation of a dedicated accelerator chip for deep sensor imaging algorithms. As the lead author, I developed a dToF (direct time-of-flight) depth completion accelerator, successfully fabricating and validating it using the 40nm process technology from Semiconductor Manufacturing International Corporation (SMIC). My research was published in the journal TCAS-II. Additionally, I proposed a novel single-point imaging system based on dToF. This system utilized monocular depth imaging algorithms derived from RGB images to precisely reconstruct depth images from the full histogram produced by the depth sensor, marking a unique advancement in single-point depth sensor imaging.

Education
======

### __Fudan University__ `2018.9 - 2023.6`
```
- Ph.D. in Microelectronics and Solid State Electronics
- Grade: CGPA: 3.42
- Honor: Outstanding Graduates from Fudan University
- Keywords: SPAD Imaging, SoC design, DNN Accelerator, Depth Completion
```

### __Southwest University__ `2014.9 - 2018.6`
```
- B.S. in Electronic Science and Technology
- Grade: CGPA: 3.81
- Honor: Outstanding Graduates from Chongqing
- Keywords: Digital Circuit, Analog Circuit, Neural Network,Transconductance Amplifier
```

Work Experience
======
<!-- #### [__TiMESiNTELLi Technology__](https://www.timesintelli.com/) `2020.10 - 2022.12`
#### Digital Circuits Designer - R&D department
> + Offer the quantization scheme for Face Detector App. on edge platform. 
> + Design and implement the DSA(Domain Specific Accelerator) for depth completion neural network.
> + Experience of twice type-out in 40 nm SMIC technology.
> + Optimazition the metrics of DMA and PEU by the self-developed tool.  -->

#### [__NVIDIA__](https://developer.nvidia.com/drive/simulation) `2023.1 - 2023.7`
#### Senior Sensor Simulation Specialist - DRIVE Sim
> + Support physically accurate sensor models in Omniverse.
> + Verify the similarity between real LiDAR sensor and simulated sensor by ray trace.
> + Support the different LiDAR sensors on market to access to Omniverse.

#### [__NTU__](https://www.ntu.edu.sg/cics) `2023.11 - Now`
#### Research Fellow
> + Metalens-based miniaturized low-cost LiDAR system.
> + 1K frame rate LiDAR imaging system with event-driven camera.

Representative Work
======
The proposed S2D(sparse to dense) is a real-time depth-completion neural network accelerator SoC designed in 40nm CMOS technology. The chip is capable of completing sparse 32x32 point cloud images into 640x480 depth images, accelerating the post-processing part of algorithms by implementing a RISC-V with a vector processor. It is currently the only hardware acceleration work in the field of depth completion, providing practical solutions for the implementation and deployment of LiDAR automatic driving. This work has received unanimous recommendations from reviewers.

<div  align="center">   
<img src="http://watercube001.github.io/images/algorithm.png" width="60%" height="60%" />
</div>
<center>Figure: Computation flow of the proposed depth completion.</center>

<div  align="center">   
<img src="http://watercube001.github.io/images/Fig2.jpg" width="60%" height="60%" />
</div>
<center>Figure: Overall architecture of the accelerator SoC.</center>

<div  align="center">   
<img src="http://watercube001.github.io/images/layout.png" width="40%" height="40%" />
</div>
<center>Figure: Chip Micrograph.</center>