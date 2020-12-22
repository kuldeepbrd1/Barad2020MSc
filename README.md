# Robust Navigation Framework for Proximity Operations around Uncooperative Spacecraft  
###Resources for CNN-based spacecraft navigation around uncooperative spacecraft



This repo contains resources from my Masters Thesis. A lot of them build upon existing works and repos, without which this work wouldn't be at all possible (See individual repos and thesis bibliography for details). 
Although this work received a great feedback and result, I believe it's still only a tiny step in understanding how to incorporate deep learning methods for spacecraft on-board operation. 


The resources (code+text) here are meant for:
1. To help (aerospace) beginners trying to break into deep learning for uncooperative pose estimation.
2. Intermediate practitioners who would like to quickly try out a method, tool or algorithm for pose estimation listed below without hassle.
3. (Probably) Established researchers to adapt, compare, evaluate or critique the methodology/results.

-------------------------------


## Thesis 
You can download my thesis report, in full directly from links below:
  - [PDF (final version 20/09/2020)](https://master-thesis-barad-2020.s3.eu-central-1.amazonaws.com/Barad2020MSc_submission.pdf)
  - [TU Delft Repositories (Last edit not incorporated)](https://repository.tudelft.nl/islandora/object/uuid%3A6dbf6f1d-b41b-42c1-ad78-619a6c6cf071?collection=education)


## Software Resources

- Keypoint Detection: [HRNet (adapted)](https://github.com/kuldeepbrd1/HRNet-spacecraft-pose)
- Object Detection: [Tensorflow OD API MobileNet-SSDLite (adapted)](https://github.com/kuldeepbrd1/models) (needs updating)
- Pose Estimation: [Modified MLPnP solver](https://github.com/kuldeepbrd1/modified_MLPnP)
- Dataset Augmentation ...
- Loosely-coupled Filter ...

Other links will be updated as soon as I stop distracting myself with a dozen unfinished projects. 

Meanwhile you can explore the resources from my [repositories](https://github.com/kuldeepbrd1?tab=repositories)


----------


## To do:
- [ ] Verify code generalization for spacecraft pose estimation in HRNet and SSDLite
- [ ] Update Tensorflow OD API repo from drive
- [ ] Add Colab notebooks
- [ ] Data pipeline files
- [ ] Add dataset augmentation code
- [ ] Notes/Resources?



For now you can only cite my masters thesis:
(I flopped the manuscript submission deadline for the accepted entry in [IAC astrodynamics symposium](https://iafastro.directory/iac/browse/IAC-20/C1/1/) due to COVID-19 induced academic, mental and economic crises. But well, I made it alive :)
```
@mastersthesis{Barad2020Msc,
    author={Barad, Kuldeep Rambhai},
    institution = {TU Delft Repository},
    school = {Delft University of Technology},
    title={Robust Navigation Framework for Proximity Operations around Uncooperative Spacecraft},
    year={2020}
}
```
NOTE: Please don't forget citing primary authors/works on which the resources above are built.
