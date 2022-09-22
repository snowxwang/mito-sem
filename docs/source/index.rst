Mitochondria in Electron Microscopy (EM)
========================================

**Mito-EM** is a tutorial-based computational pipeline for reconstruction and analysis of mitochondria from images acquired EM or serial EM.

This repository provides tutorials, proofread datasets, and computational tools for *practicing biologists* to analyze electron microscopy data at large-scale. These tools focus on in-depth analyses **after** automatic/semi-automatic segmentation. We use examples of 3D data acquired from serial electron microscopy for demonstrations, but all the codes and scripts should be able to deal with other types of 3D images such as fluorescence microscopy image stacks.

The intended audience is the *practicing biologists/neuroscientists* - e.g., the students, researchers, and clinicians collecting volumeric image data in the hospital or laboratory. Some sections of this material can get pretty math-heavy, but we have tried to outline the main concepts as directly as possible, with hands-on implementations of all concepts.


.. note::

   This project is under active development.


Contents
--------

This site provides information and resources for dealing with images acquired using Serial Electron Microscopy. We are presnting the entire computational pipeline here. 


Contributors
------------

This repository is created by `Snow Wang <https://www.snowxwang.com>`_. Core developers and their contributions are listed below:


- Website Building & Contents Creation: Snow
- EM Tutorials: Snow, `Yulan (Mumu) Fang <https://github.com/MumuFang>`_
- Image Processing Tutorials: Snow
- Data Analysis: Snow, `Yutian (Tim) Fan <https://github.com/Anominious>`_, `Wenjie (Kelly) Yin <https://github.com/Kelly-Yin>`_
- Data Visualization: `Bowen Gong <https://github.com/BowenGong2000>`_, Kelly, Snow


Supported Image Data
--------------------

All the tools presented in this repository are designed to process or visualize annotated 3D datasets exhibiting the following features:

- labeled/segmented serial cross-sectional images
- segmentation files are sequence of 8-bit, 16-bit, or 24-bit grayscale images
- .PNG files are preferred


Supported Languages & Software
------------------------------

- Python
- MATLAB
- VAST
- 3ds Max

   
.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Mitochondria in EM

   /microscopy/digital_image
   /microscopy/electron_microscopy
   /microscopy/serial_em
   /microscopy/mito_in_em


.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Segmenting Mitochondria

   /mito_seg/annotation_vast
   /mito_seg/annotation_trakem
   /mito_seg/semantic_seg
   /mito_seg/instance_seg
   /mito_seg/proofreading


.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Analyzing Mitochondria

   /mito_analysis/vast_export


.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Visualizing Mitochondria

   /data_vis/ng_setup
   /data_vis/3dmax


.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Other Image Processing Techniques

   /image_processing/alignment
   /image_processing/feature_detection
