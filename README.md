# sleepmonitor
通过加速度传感器检测睡眠


# data_standard.ipynb
把加速度文件加工成要求的标准格式，通常有些文件不是标准格式，这个时候就需要这个文件
|时间|开机微妙|加速度值|角速度值|标签|

# 人工对data加标签
对加速度文件增加label列

# data_featured.ipynb
对加速度文件追加所有特征

# data_pca.ipynb
对加了特征的数据进行PCA,并取PCA的前4维度 pca1,pac2,pac3,pac4

# data2frames.ipynb
通过加了特征的csv数据生成帧图片数据

# frames2video.ipynb
把帧图片数据转换成视频




