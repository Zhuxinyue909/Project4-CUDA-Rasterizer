CUDA Rasterizer
===============

**University of Pennsylvania, CIS 565: GPU Programming and Architecture, Project 4**

* Xinyue zhu
* Tested on: Windows 10, i7- @ 2.22GHz 22GB, GTX 960M

========================
## Description:
 <p>This is a rasterizer.</p>
It includes the following pipeline:<br/>
1)vertex transformation with camera movement</br>
2)Tessellation shader</br>
3)Bling-phong shader and blending</br>
4)rasterization brute force scan line->boundingbox scan line</br>
5)depth test</br>
6)anti-aliansing:Super sampling - random  </br>
the base color is normal map</br>
<img src="1.png"  width="380" height="400">  <img src="2.png"  width="400" height="380"></br>

https://www.youtube.com/watch?v=IY66btfDzQ0&feature=youtu.be

### Performance Analysis
<img src="p1.png"  width="600" height="150">
<p>The CPU are all used for opengl related funtions. The computation mostly happened in GPU
<p> a breakdown of time spent in each pipeline stage 
<img src="pipe_line.png"  width="600" height="280">



