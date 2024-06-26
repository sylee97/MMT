# MMTF (Multi Modal Trajecroy Prediction with Traffic Light)

## Setup
All code was developed and tested on Ubuntu 20.04 wuth python 3.7 and PyTorch 1.13.0.

## Data
[waterloo]
* location: mmt/datasets/waterloo/~
* [preprocessed data link](https://drive.google.com/drive/folders/1ygmCgEKaCdofBHC0nkbMqbiUk6yUqu0q)
  - img folder: image raw(.png), image feature file(.pkl) 
  - train2, val2, test2 folder: trajectory, agent state, traffic light information(.txt)
    
## Pretrained Models
[google drive](https://drive.google.com/drive/folders/1tSFcgzGzLxBCV8Fb6uLeQNBQzvCkONoh?usp=drive_link)

## Evaluate Models
> MMT/scripts/ python evaluate_noscene.py

## Train a model
> MMT/scripts/ ./run_traj_noscene_1.sh

## Draw Trajectory using plt
> MMT/ python /.visualization/draw_trajectory_noscene1.py

## Dataset
[Waterloo multi-agent traffic dataset: intersection](https://uwaterloo.ca/waterloo-intelligent-systems-engineering-lab/datasets/waterloo-multi-agent-traffic-dataset-intersection)

## Acknowledgement

Thanks for the model structure idea and code from [sgan](https://github.com/agrimgupta92/sgan), [d2-tpred](https://github.com/VTP-TL/D2-TPred) 
