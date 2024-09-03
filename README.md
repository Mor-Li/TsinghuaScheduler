# TsinghuaScheduler

TsinghuaScheduler 是一个专为清华大学设计的选课志愿概率计算脚本。该脚本帮助学生根据志愿报名情况，预测自己在不同志愿下的录取概率，从而更好地进行选课规划。

## 功能介绍

本项目主要根据课程志愿报名情况与可选容量的关系，将课程划分为三类，并分别计算每类课程中不同志愿下的录取概率。

## 使用方法

1. 克隆本项目到本地：
    ```bash
    git clone https://github.com/DseidLi/TsinghuaScheduler.git
    ```

2. 进入项目目录：
    ```bash
    cd TsinghuaScheduler
    ```

3. 使用 `dev.ipynb` 文件进行操作：
   - 首先，请登录清华大学的选课系统，查询每门课的当前志愿填写情况。
   - 将查询到的课程号、课序号、课程名、可选容量、以及各志愿的报名人数等信息复制并粘贴到 `dev.ipynb` 文件中的 `data` 变量里。
   - 运行脚本并查看结果。

## 贡献

欢迎对本项目进行贡献。如果发现问题或有改进建议，请通过GitHub提交Issue或Pull Request。

## 许可

本项目采用 Do Anything You Want License (DAWYL) 许可协议。