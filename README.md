```
conda create -n deeph python=3.9
conda activate deeph
先升级gcc和gxx
conda install -c conda-forge gcc
conda install -c conda-forge gxx
安装pytorch 1.12.0+cu116
pip install torch==1.12.0+cu116 --extra-index-url https://download.pytorch.org/whl/cu116
pip install pyg_lib torch_scatter torch_sparse torch_cluster torch_spline_conv -f https://data.pyg.org/whl/torch-1.12.0+cu116.html
pip install pytorch-geometric
pip install numpy==1.25.0
~/work/deeph/DeepH-pack-main$ pip install .
deeph-train
`GLIBC_2.27' not found
pip uninstall torch-spline-conv
pip uninstall torch-sparse
pip uninstall pyg-lib
deeph-train
```
