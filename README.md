# RLTA2020
## 1、项目描述
本项目由西北工业大学和陕西科技大学进行协调完成，主要研究了合同网模型的改进，并将其应用到飞行器任务的实时在线分配。飞行器中段飞行时间长，弹道固定，容易成为防御系统拦截重点。利用深度强化学习算法结合动态窗口局部路径规划法完成飞行器突防航迹推演等关键技术研究。
## 2、环境依赖
MATLAB2016以上。
## 3、文件说明
1、"TSA"文件  
采用改进合同网模型通过模拟市场机制中的“招标-投标-中标”模式，采用多种合同类型，通过多个个体之间的相互通信和协商，在个体追求最优的基础上，寻求全局最优和次优。用智能体来表示合同网模型中的个体，每隔智能体都是具有互相通信和一定的信息处理能力的个体。  
2、“PDQN_161”文件  
已训练好的深度强化模型。  
## 4、运行步骤
运行文件夹PDQN_161中的PDQN160.m函数，但是需要修改报错路径和创建相应文件夹。  
## 5、示例图
![](https://s3.bmp.ovh/imgs/2022/08/08/a6c7d7a39f1d2221.png)

