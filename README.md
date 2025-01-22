# ZHOU-SHIHAO

python:3.8.20

cuda:11.8

数据集来自kaggle的公开数据集
The data set comes from Kaggle's public data set

https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone

每个类别图片全部用类别名重命名，标签csv文件有修改，第一列是图片本地地址，第二列是标签，修改后的csv文件已上传
All the images in each category are renamed with the category name. The label csv file has been modified. The first column is the local address of the image, and the second column is the label. The modified csv file has been uploaded

本项目按照标注的step顺序逐个执行即可
This project can be executed one by one in the order of the marked steps

requirement文件要求安装的依赖可能不全，不同的环境可能需要额外的依赖，如果出错的话请按照提示安装额外的包
The dependencies required to be installed in the requirement file may not be complete. Different environments may require additional dependencies. If an error occurs, please follow the prompts to install additional packages

本项目在本地运行，ipynb文件的路径是作者电脑的路径，如果需要重复实验请修改文件路径
This project runs locally. The path of the ipynb file is the path of the author's computer. If you need to repeat the experiment, please modify the file path

本项目中，模型训练时包含随机种子，意味着，可能重复实验不能得到100%相同的结果，但理论上不应该有很大区别
In this project, the model training includes random seeds, which means that repeated experiments may not get 100% the same results, but in theory there should not be a big difference
