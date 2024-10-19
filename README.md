Overview

Accurate spatial-temporal traffic flow prediction is crucial for effective traffic management and route optimization. In our paper, we propose a novel Spatial-Temporal Traffic Prediction model that leverages Graph Convolutional Networks (GCN) with a Tensor Decomposition approach to better capture complex spatial-temporal dependencies in traffic data. Our approach enhances the graph adjacency matrix construction by incorporating both spatial and temporal dependencies, leading to more accurate predictions with reduced computational cost.

Highlights

Spatial-Temporal Graph Adjacency Matrix: Reconstructed through tensor decomposition, providing a more informative representation of road network dependencies.
Spatial-Temporal Synchronous Graph Convolution: Captures localized spatial-temporal correlations.
Dilated Convolution Module: Models global spatial-temporal relationships efficiently.
Superior Prediction Accuracy: Achieved state-of-the-art performance on multiple real-world datasets.

Datasets

The proposed model is tested on four open-access datasets:

PEMS03: 358 sensors, time range 2018/9/1 - 2018/11/30

PEMS04: 307 sensors, time range 2018/1/1 - 2018/2/28

PEMS07: 883 sensors, time range 2017/5/1 - 2017/8/31

PEMS08: 170 sensors, time range 2016/7/1 - 2016/8/31

Citation

If you find this work useful, please cite our paper:

@article{li2023spatial,
  title={Spatial--temporal traffic modeling with a fusion graph reconstructed by tensor decomposition},
  author={Li, Qin and Yang, Xuan and Wang, Yong and Wu, Yuankai and He, Deqiang},
  journal={IEEE Transactions on Intelligent Transportation Systems},
  year={2023},
  publisher={IEEE}
}
