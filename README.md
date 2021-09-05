# modern-slam-tutorial-python
- Learning and feeling SLAM together with hands-on-experiments :grinning: :smiley:	:laughing:

## Dependencies
- Most of the examples are based on GTSAM. use `$ pip install gtsam` and I prefer using conda environment. 
    - Also, I'll (want to) also use Pytorch to study recent differentiable factor-graph optimization works.  

- Create the same environment using anaconda and `requirements.txt`.  

    For example,  
    ```
    conda create -n modern-slam-tutorial python=3.7  
    conda activate modern-slam-tutorial  
    pip install -r requirements.txt  
    ```
- Install [CloudCompare](https://snapcraft.io/install/cloudcompare/ubuntu) for point cloud data visualization and comparison.  


## Contents 
1. [robust_pgo](https://github.com/gisbi-kim/modern-slam-tutorial-python/tree/main/robust_pgo): a robust pose-graph optimization 
    - [Tutorial video](https://youtu.be/zOr9HreMthY)
    - Dependencies: numpy, GTSAM (python)
    - The datasets are available from https://lucacarlone.mit.edu/datasets/

*To be continued ...*

## Contact
- `gisbi.kim@gmail.com`

## Plan
- Other geometric optimization for SLAM
    - Non-rigid ICP 
    - Rotation initialization 
    - ...
- Trying GTSAM integration with Open3D, scipy, Pytorch, etc ... 


