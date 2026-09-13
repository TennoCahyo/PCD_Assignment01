# PCD Assignment 01
## Down Sampling and Up Sampling

This repository contains the implementation and analysis for **PCD Assignment 01**.  
The project focuses on comparing several image down sampling and up sampling methods using Google Colab and Python.

## Objectives

The objectives of this assignment are:

- Implement different down sampling methods.
- Implement different up sampling methods.
- Compare the visual results of each method.
- Analyze the effects of sampling methods on image quality.

## Methods

### Down Sampling

Three down sampling methods are implemented:

1. **Max Down Sampling**
   - Selects the maximum pixel value within each block.

2. **Average Down Sampling**
   - Calculates the average pixel value within each block.

3. **Median Down Sampling**
   - Sorts the pixel values and selects the middle value.

For RGB images, the calculation is performed separately for the Red, Green, and Blue channels.

### Up Sampling

Three up sampling methods are implemented:

1. **Nearest Neighbor**
   - Uses the value of the nearest pixel.
   - Produces a relatively fast but more pixelated result.

2. **Bilinear**
   - Uses neighboring pixels and linear interpolation.
   - Produces a smoother result than Nearest Neighbor.

3. **Bicubic**
   - Uses more surrounding pixels for interpolation.
   - Generally produces a smoother and more natural-looking result
