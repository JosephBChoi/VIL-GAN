# Deep learning for synthetic microstructure in a materials-by-design framework for heterogeneous energetic materials
<a href="https://arxiv.org/abs/2004.04814"><img src="https://img.shields.io/badge/cond.mat-arXiv%3A2004.04814-B31B1B.svg"></a>

[Sehuyn Chun, Sidhartha Roy, Yen Thi Nguyen, Joseph B. Choi, H.S. Udaykumar, Stephen S. Baek. (2020). Deep learning for synthetic microstructure in a materials-by-design framework for heterogeneous energetic materials._Scientific Report 10,_13307.](https://www.nature.com/articles/s41598-020-70149-0)

--- 
Planned changes: 
- migration to TensorFlow/Keras or PyTorch
- modularization
--- 

## Getter Started

### Virtual Environment

For an optimal setup, consider establishing a virtual environment using Anaconda or Miniconda. Installing the necessary dependencies for our GAN model within this isolated environment ensures smooth functioning. To create a virtual environment, enter the following command in your terminal or command prompt:

```
conda env create -f requirements.yml
```

Change the name of the virtual environment by modifying the first line of `requirements.yml` file. Otherwise, the created virtual environment will be named `VIL-GAN`. 


## Demo
The GAN model with training script is implemented in the `demo/gan.ipynb` notebook.


## Citation
To cite this work, please use the following: 
```
@article{chun2020gan,
  title={Deep learning for synthetic microstructure generation in a materials-by-design framework for heterogeneous energetic materials},
  author={Chun, Sehyun and Roy, Sidhartha and Nguyen, Yen Thi and Choi, Joseph B and Udaykumar, Holavanahalli S and Baek, Stephen S},
  journal={Scientific reports},
  volume={10},
  number={1},
  pages={13307},
  year={2020},
  publisher={Nature Publishing Group UK London}
}
```


