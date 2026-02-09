# pose
In this repository I use the `OneSLAM` algorithm to recover the 3D camera pose from a given laparoscopy video.

For further details on the method, see the following article and GitHub repo:
- [Article](https://link.springer.com/article/10.1007/s11548-024-03171-6)
- [GitHub repo](https://github.com/arcadelab/OneSLAM)

#### Installation
Follow installation instructions on the `OneSLAM` repo. Ideally, clone the repo in this directory. <br>
Other than that, you may just need a few packages which can be installed easily with pip or conda. <br>

#### Note
The camera intrinsics should be formated in a certain way, see `./preproc/calibration.json`
