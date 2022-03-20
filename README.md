# 项目名称

## 介绍

多模态可解释融合项目

备注：pytorch、先跑通main.ipynb，然后再将内部内容提炼成.py程序文件。

## 项目开发计划
1. 跑通main.ipynb，提供baseline。
2. 从main.ipynb中提取dao.py、model.py、train.py、inference.py、experiment脚本
3. 修改model，然后设计新的train。

## 项目结构

```txt
----.\
    |----config.py    项目配置文件  
    |----main.ipynb    项目主程序
    |----train.py    模型训练代码
    |----inference.py    模型推理代码
    |----experiments.ipynb    实验脚本/notebook工程
    |----README.md    工程文档
    |----assets\    生成文件缓存区
    |----data\    数据文件夹
    |    |----dao.py   数据访问工具类
    |----models\    模型文件夹
    |    |----model.py    模型代码
    |    |----state_dicts\    训练参数缓存区
```

## 使用说明


## 参与贡献

