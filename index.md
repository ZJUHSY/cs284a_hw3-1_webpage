
# cs284a_hw3-1_webpage

### Project Overview


### Part1: Ray Generation and Scene Intersection

#### 1-1 Walk through the ray generation and primitive intersection parts of the rendering pipeline.

#### 1-2 Explain the triangle intersection algorithm you implemented in your own words.

#### 1-3 Show images with normal shading for a few small .dae files.

### Part2: Bounding Volume Hierarchy

#### 2-1 Walk through your BVH construction algorithm. Explain the heuristic you chose for picking the splitting point.

#### 2-2 Show images with normal shading for a few large .dae files that you can only render with BVH acceleration.

#### 2-3 Compare rendering times on a few scenes with moderately complex geometries with and without BVH acceleration. Present your results in a one-paragraph analysis.

### Part3: Direct Illumination

#### 3-1 Walk through both implementations of the direct lighting function.

#### 3-2 Show some images rendered with both implementations of the direct lighting function.

#### 3-3 Focus on one particular scene with at least one area light and compare the noise levels in soft shadows when rendering with 1, 4, 16, and 64 light rays (the -l flag) and with 1 sample per pixel (the -s flag) using light sampling, not uniform hemisphere sampling.

#### 3-4 Compare the results between uniform hemisphere sampling and lighting sampling in a one-paragraph analysis.

### Part4: Global Illumination

#### 4-1 Walk through your implementation of the indirect lighting function.

#### 4-2 Show some images rendered with global (direct and indirect) illumination. Use 1024 samples per pixel.

#### 4-3 Pick one scene and compare rendered views first with only direct illumination, then only indirect illumination. Use 1024 samples per pixel.

#### 4-4 For CBbunny.dae, compare rendered views with max_ray_depth set to 0, 1, 2, 3, and 100 (the -m flag). Use 1024 samples per pixel.

#### 4-5 Pick one scene and compare rendered views with various sample-per-pixel rates, including at least 1, 2, 4, 8, 16, 64, and 1024. Use 4 light rays.

#### 4-6 You will probably want to use the instructional machines for the above renders in order to not burn up your own computer for hours.

### Part5: Adaptive Sampling

#### 5-1 Walk through your implementation of the adaptive sampling.

#### 5-2 Pick one scene and render it with at least 2048 samples per pixel. Show a good sampling rate image with clearly visible differences in sampling rate over various regions and pixels. Include both your sample rate image, which shows your how your adaptive sampling changes depending on which part of the image you are rendering, and your noise-free rendered result. Use 1 sample per light and at least 5 for max ray depth.

### Extra Credits





For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).


