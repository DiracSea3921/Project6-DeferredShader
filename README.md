------------------------------------------------------------------------------
CIS565: Project 6 -- Deferred Shader
-------------------------------------------------------------------------------
Fall 2014
-------------------------------------------------------------------------------
RESULTS:
-------------------------------------------------------------------------------

[Run The Demo](http://diracsea3921.github.io/Project6-DeferredShader/)

* Diffuse and Blinn-Phong shading

![](https://github.com/DiracSea3921/Project6-DeferredShader/blob/master/Untitled6.png)

![](https://github.com/DiracSea3921/Project6-DeferredShader/blob/master/Untitled2.png)

* Bloom

![](https://github.com/DiracSea3921/Project6-DeferredShader/blob/master/Untitled7.png)

![](https://github.com/DiracSea3921/Project6-DeferredShader/blob/master/Untitled3.png)

* "Toon" Shading (with normal based silhouetting)

![](https://github.com/DiracSea3921/Project6-DeferredShader/blob/master/Untitled8.png)

![](https://github.com/DiracSea3921/Project6-DeferredShader/blob/master/Untitled4.png)

* Screen Space Ambient Occlusion

![](https://github.com/DiracSea3921/Project6-DeferredShader/blob/master/Untitled5.png)

![](https://github.com/DiracSea3921/Project6-DeferredShader/blob/master/Untitled1.png)

-------------------------------------------------------------------------------
CONTROLS:
-------------------------------------------------------------------------------

The keyboard controls are as follows:
WASDRF - Movement (along w the arrow keys)
* W - Zoom in
* S - Zoom out
* A - Left
* D - Right
* R - Up
* F - Down
* ^ - Up
* v - Down
* < - Left
* > - Right
* 1 - World Space Position
* 2 - Normals
* 3 - Color
* 4 - Depth
* 5 - Bloom
* 6 - Toon Shading
* 7 - SSAO
* 0 - Full deferred pipeline

-------------------------------------------------------------------------------
PERFORMANCE:
-------------------------------------------------------------------------------

I did some test for Bloom and SSAO effect with different samples number. For the Bloom effect the fps drop very quickly with the samples number increasing.
I think it will be better to separate this step into two passes, which will greatly benefit the efficiency.
 
![](https://github.com/DiracSea3921/Project6-DeferredShader/blob/master/image.png)

![](https://github.com/DiracSea3921/Project6-DeferredShader/blob/master/image2.png)

-------------------------------------------------------------------------------
REFERENCES:
-------------------------------------------------------------------------------

* Bloom : [GPU Gems](http://http.developer.nvidia.com/GPUGems/gpugems_ch21.html) 
* Screen Space Ambient Occlusion : (http://john-chapman-graphics.blogspot.com/2013/01/ssao-tutorial.html)


