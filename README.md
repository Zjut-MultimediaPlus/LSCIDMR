# LSCIDMR


## Brief Introduction
LSCIDMR is an opensource satellite cloud images dataset for Meteorological Research. 


People can infer the weather from clouds. Various
weather phenomena are linked inextricably to clouds, which
can be observed by meteorological satellites. Thus, cloud images
obtained by meteorological satellites can be used to identify
different weather phenomena to provide meteorological status
and future projections. How to classify and recognize cloud
images automatically, especially with deep learning, is an interesting
topic. BigData is the fuel of deep learning, and large-scale training data are
essential for training a high-precision and robust deep learning model.
LSCIDMR is proposed for this purpose.

This dataset contains 104390 image patches, and provides labels of 10 classes annotated in both single-label style and multi-label style. 
More details can be found in the paper: "LSCIDMR: Large-scale Satellite Cloud Image Database for Meteorological Research",submitted to IEEE Transcations on Cybernetics.

## Download
The dataset includes 3 files. Please download the dataset files from BaiduYun or Google Cloud.
1. BaiduYun:  https://pan.baidu.com/s/1J5zh0iygyZoCi0QZVPd3Wg   &nbsp;&nbsp;&nbsp;       Fetch Code: 2w3v.
2. Google Cloud:  https://drive.google.com/drive/folders/1GZlLFCcSJqIw-e04ABw_haByIwLgjsX8?usp=sharing  
<br>(The size of images in primary version of this dataset is 256 * 256 pixels named
“LSCIDMR”due to the limitaion of storage space. The file named “png” and “jpg” storage 1000*1000 pixels high resolution version.)

## Citation
Please cite our papers if the dataset is useful for you. Thank you !


C Bai, M Zhang, J Zhang*, J Zheng, SY Chen, LSCIDMR: Large-scale Satellite Cloud Image Database for Meteorological Research, IEEE Transactions on Cybernetics, 10.1109/TCYB.2021.308012

```
@article{bai2021lscidmr,
  title={LSCIDMR: Large-scale satellite cloud image database for meteorological research},
  author={Bai, Cong and Zhang, Minjing and Zhang, Jinglin and Zheng, Jianwei and Chen, Shengyong},
  journal={IEEE Transactions on Cybernetics},
  volume={52},
  number={11},
  pages={12538--12550},
  year={2021},
  publisher={IEEE}
}
```