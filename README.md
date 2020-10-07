<h1 align="center">InShaDe: Invariant Shape Descriptors for visual analysis of histology 2D cellular and nuclear shapes</h1>
<h3 align="center"><a href="mailto:magus@hbku.edu.qa">Marco&nbsp;Agus</a><sup>1</sup>&nbsp;&nbsp; 
Khaled&nbsp;Al-Thelaya<sup>1</sup>&nbsp;&nbsp; 
Corrado&nbsp;Cal&igrave;<sup>2</sup>&nbsp;&nbsp; 
Marina&nbsp;M.&nbsp;Boido<sup>2</sup>&nbsp;&nbsp; 
Yin&nbsp;Yang<sup>1</sup>&nbsp;&nbsp; 
Giovanni&nbsp;Pintore<sup>3</sup>&nbsp;&nbsp; 
Enrico&nbsp;Gobetti<sup>3</sup>&nbsp;&nbsp; 
<a href="mailto:jeschneider@hbku.edu.qa">Jens&nbsp;Schneider</a><sup>1</sup>&nbsp;&nbsp;</h3><br/>

<p align="center"><sup>1&nbsp;</sup>College of Science and Engineering, Hamad Bin Khalifa University, Qatar<br/>
<sup>2&nbsp;</sup>NICO, University of Turin, Italy<br/>
<sup>3&nbsp;</sup>Visual Computing, CRS4, Italy
</p>

<img src="https://drive.google.com/file/d/13bNpMV9-iGreXGgdOrUfbqXnQA_JKnP4/view?usp=sharing"  align="center" alt="InShaDe Pipeline Overview" />
<p align="justify">
Figure 1: <b>InShaDe:</b> from cell contours extracted from digital histology images, our pipeline computes invariant energy curvature-based Fourier descriptors. These synthetic descriptors can be used for visual analysis, proof-reading, segmentation, and domain-specific clustering according to specific taxonomies.</p>

<h2>Copyright Notice</h2>
<p align="justify">This software is <b>(c) 2020 by M. Agus, K. Al-Thelaya, Y. Yang and J. Schneider, CSE, Hamad Bin Khalifa University</b>.
It is distributed under the <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/legalcode">CC-NC-ND 4.0 licence</a>. For use in commercial projects, kindly contact <a href="mailto:magus@hbku.edu.qa">Marco Agus</a>. If you use this software in a publication, kindly cite the below reference.</p>

<h2>Abstract</h2>
<p align="justify">
We present a shape processing framework for visual exploration of cellular nuclear envelopes extracted from histology images.The framework is based on a novel shape descriptor of closed contours relying on a geodesically uniform resampling of discrete curves to allow for discrete differential-geometry-based computation of unsigned curvature at vertices and edges. Our descriptor is, by design, invariant under translation, rotation and parameterization. Moreover, it additionally offers the option for uniform-scale-invariance. The optional scale-invariance is achieved by scaling features to z-scores, while invariance under parameterization shifts is achieved by using elliptic Fourier analysis (EFA) on the resulting curvature vectors. These invariant shape descriptors provide an embedding into a fixed-dimensional feature space that can be utilized for various applications: (i) as input features for deep and shallow learning techniques; (ii) as input for dimension reduction schemes for providing a visual reference for clustering collection of shapes.</p>

<h2>Reference</h2>
<p align="left">The full paper can be downloaded <a href="https://diglib.eg.org/bitstream/handle/10.2312/vcbm20201173/061-070.pdf">here</a>.
It should be cited as:</br>

M. Agus, K. Al-Thelaya, C. Cali, M. M. Boido, Y. Yang, G. Pintore, E. Gobbetti, J. Schneider,<br/>
InShaDe: Invariant Shape Descriptors for visual analysis of histology cellular and nuclear shapes,<br/>
10<sup>th</sup> Eurographics Workhop on Visual Computing for Biology and Medicine (EG VCBM), pp 61-70, 2020, DOI 10.2312/vcbm.20201173.</p>

<h2>Using the Code</h2>
Just download the jupyter notebook and the test images and put in the same directory.


Dependecies:
  numpy, matplotlib, sklearn, umap, palettable, umap, hdbscan
  
  
Enjoy!!!

