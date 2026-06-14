## **Single Image Dehazing Using K-Estimation Approach**
## Authors

* Saad Bin Sami
* Abdul Muqeet
* Humera Tariq

## Overview

Haze is a common atmospheric phenomenon caused by dust, smoke, mist, and other particles suspended in the air. It reduces image visibility, contrast, and color quality, making it difficult for computer vision systems and humans to interpret scenes accurately.

This thesis focuses on developing an efficient **single image dehazing technique** that removes haze from an image using a novel **K-estimation approach**. Unlike traditional methods that depend heavily on atmospheric light estimation, the proposed method aims to improve dehazing performance while reducing computational complexity and estimation errors.

## Problem Statement

Most existing dehazing techniques rely on estimating atmospheric light (A) and transmission maps. These estimations can become inaccurate in the presence of:

* Bright objects
* Large sky regions
* Dense haze conditions
* Improper patch selection

Such inaccuracies often lead to:

* Color distortion
* Halo artifacts
* Loss of image details
* Over-enhancement

## Objectives

The primary objectives of this research are:

1. Analyze existing image dehazing methods.
2. Identify limitations of atmospheric-light-based approaches.
3. Develop a dehazing model based on K estimation.
4. Improve image visibility and contrast.
5. Reduce dependency on atmospheric light estimation.
6. Evaluate performance using qualitative and quantitative measures.

## Literature Review Summary

The literature review discusses:

### Multi-Image Dehazing Methods

These methods require multiple images of the same scene captured under different haze conditions.

#### Advantages

* Accurate haze estimation
* Better restoration quality

#### Limitations

* Multiple images are required
* Not practical for real-world applications

### Single-Image Dehazing Methods

These methods remove haze using only one image.

Popular techniques include:

* Dark Channel Prior (DCP)
* Color Lines
* Haze Lines
* Atmospheric Scattering Model Based Methods

#### Advantages

* Practical
* Easy deployment
* Requires only one image

#### Limitations

* Sensitive to atmospheric light estimation
* Performance decreases in sky regions
* Can produce artifacts

## Theoretical Background

### Atmospheric Scattering Model

The image formation process in hazy environments is commonly represented by:

J(x) = I(x)t(x) + A(1 − t(x))

Where:

* J(x) = Observed hazy image
* I(x) = Scene radiance
* A = Atmospheric light
* t(x) = Transmission map

### Reflectance and Illumination Model

Jc(x) = ρc(x)Ac

Where:

* ρc(x) = Surface reflectance
* Ac = Illumination component

## Proposed Method

The thesis introduces a K-estimation strategy that:

* Avoids direct dependence on atmospheric light estimation.
* Simplifies haze removal calculations.
* Preserves image details.
* Produces visually enhanced images.
* Improves robustness across different haze conditions.

## Expected Benefits

* Better visibility restoration
* Improved contrast enhancement
* Reduced color distortion
* Lower computational complexity
* Enhanced applicability in real-world scenarios

## Applications

Image dehazing has applications in:

* Autonomous vehicles
* Surveillance systems
* Traffic monitoring
* Remote sensing
* Medical imaging
* Robotics
* Computer vision systems

## Conclusion

The research addresses limitations of conventional atmospheric-light-based dehazing techniques by proposing a K-estimation-based approach. The method aims to provide effective haze removal while maintaining image quality and reducing estimation errors, making it suitable for practical single-image dehazing applications.

## Keywords

Image Dehazing, Single Image Dehazing, Atmospheric Scattering Model, Transmission Map, Atmospheric Light, K Estimation, Computer Vision, Image Enhancement.
