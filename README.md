# Differentiable point clouds in pytorch

Pytorch implementation of paper https://arxiv.org/abs/1810.09381

To install dependencies use [conda](https://docs.conda.io/en/latest/miniconda.html).
 
Install with: 
```sh
conda create -n point_clouds python=3.7
conda activate point_clouds
conda install pytorch torchvision scipy matplotlib open3d=0.7 tqdm jupyter -c pytorch -c open3d-admin
jupyter notebook
```

Then use [point_cloud.ipynb](./point_cloud.ipynb) to train and evaluate model.
