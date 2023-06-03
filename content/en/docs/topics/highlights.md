---
title: "Research highlights"
lead: "Current and past research at a glance"
date: 2020-10-06T08:48:57+00:00
lastmod: 2020-10-06T08:48:57+00:00
draft: false
images: []
menu:
  research:
    parent: "topics"
weight: 100
toc: true
---

## Post-doctoral research

**Direct Visual Alignment from Spherical Images**

![Spherical image sampling](https://antoineandre.github.io/images/research/post-doc/pyramnidal_sphere_sample.gif)

Provide a high resolution orientation estimation based on omnidirectional images mapped on a subdivided icosahedron.

**Visual Gyroscope 3-step pipeline for omnidirectional images stabilization**

To be presented in CVPR OmniCV 2023 Workshop

## Ph.D. research

**Encoded Periodic pattern for nanometric pose estimation on decimetric range**

![Pose measurement process through encoded periodic pattern phase analysis](https://antoineandre.github.io/images/research/post-doc/tmech_pose_measure_process.png)

Pose estimation process, ($a$) acquired target image, ($b$) Modulus of the 2D discrete Fourier transform. Circles exhibit the two frequency peaks of the two directions of the target image. The application of a Gaussian filter and inverse Fourier transform, result in the wrapped phase maps ($c_1$) and ($c_2$) representative of the line position with respect to the image pixel frame. ($d_1$) presents the binary decoding necessary to identify the coding cells and the 2D LFSR sequences. ($d_2$) zooms on a single coding cell with colored squares discriminating corners from coding line and column. As a result, ($e$) shows the fine and absolute registration of the current image within the encoded target.

![Robust decoding of absolute encoded periodic pattern position](https://antoineandre.github.io/images/research/post-doc/explicationThumbnailRatio.png)

Binary value determination from the thumbnail foreground intensity image. ($a_{1}$) thumbnail of an image altered by white noise, occlusion and variable light. For each set of three lines and columns, bars in ($a_{2}$) and ($a_{3}$) compare the mean coding intensity (magenta) to the foreground (yellow) and background (green) mean intensities with the determined binary value indicated beside. ($b_{1}$) shows the dynamics allowed by the $12$~bits quantification. ($b_{2}$) depicts the decision criterion for the coding column within the red rectangle in ($a_{1}$) with respect to the $4096$ gray level range.

**Applications to microrobotics**

These works were conducted by other researchers (mainly from AS2M research department) who needed to embed a _contactless highly-resolute on a large range_ position sensor.
