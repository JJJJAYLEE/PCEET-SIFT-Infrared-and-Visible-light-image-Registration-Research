# Infrared and Visible light image Registration Research Based on the Combination of Phase Consistency and Edge Extreme Points with SIFT Algorithm
Infrared and Visible light image Registration Research Based on the Combination of Phase Consistency and Edge Extreme Points with SIFT Algorithm

说明：
main.py脚本为主脚本，运行main.py脚本时,输入参数--des_way 2 表示采用pytorch张量形式并用cuda计算，可以加快计算速度，强烈建议采用，--data data/(数据文件名名称如similar）。

数据准备：data文件夹的images(或者其他名字的文件夹）文件夹用来存放原始图片，其中images1存放原始红外图片，images2存放原始可见光图片

重要脚本说明：

main.py——项目主脚本，

affine,py——配准时进行仿射变换的脚本

count_corners_and_angles.py——计算特征点和主方向脚本

dataloads.py——加载数据脚本

descriptor_and_match.py——计算描述符和粗匹配脚本

registration.py——配准主要脚本

show.py——可视化脚本

注：各脚本具体作用以实际代码为准，此处只提供主要作用

项目运行注意事项：
请按requirement.txt内的要求安装外部库



注意：此代码为李杰(2973137145@qq.com)原创，未经本人允许不准用于其他地方，暂时只用于论文审查使用, project.rar文件为代码文件，需要输入解压密码才能解压，需要采用WinRAR软件进行解压，其他解压软件可能解压失败


Instructions:

main.py script is the main script. When running the main.py script, input parameter
--des_way 2 indicates the use of PyTorch tensor format and CUDA computation, which can accelerate the calculation speed. It is strongly recommended to use this option. Additionally,
--data data/(data file name, such as "similar") is required.

Data preparation: The "images" folder (or any other named folder) within the data directory is used to store original images. Within this folder, "images1" stores the original infrared images, 
while "images2" stores the original visible light images.
Key Script Descriptions:

main.py: Main script of the project.

affine.py: Script for affine transformations during registration.

count_corners_and_angles.py: Script for computing feature points and main directions.

dataloads.py: Script for loading data.

descriptor_and_match.py: Script for computing descriptors and performing coarse matching.

registration.py: Main script for registration operations.

show.py: Script for visualization.

Project Execution Notes:

Please ensure the installation of external libraries as specified in requirement.txt.

Note: This code is original work by Jie Li (2973137145@qq.com). Use for purposes other than academic review without the 
author's permission is prohibited. The project.rar file is a code file, you need to enter the decompression password to decompress, you need to use WinRAR software to decompress, other decompression software may fail to decompress




