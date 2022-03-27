# GraphDTApro
Graduation Project: 基于图卷积网络的药物-靶标结合亲和力预测(Drug-target Binding Affinity Prediction Based on Graph Neural Networks)  
Author: 邵嘉阳(Shao Jiayang)  
University: 北京化工大学(Beijing University of Chemical Technology)  
Major: 计算机科学与技术(Computer Science and Technology)  
Advisor: 程勇(Cheng Yong)  

## Prerequisites
### Notice
1. As some new features, such as built-in modules and functions, appear in the newer version of PyG(currently 2.0.4, 2022.3.27) compared to the one I used when starting my graduation project(2.0.1 at that time, ,maybe 2021.11), code written before may not work any more or can be replaced by a more brief form.
2. I use Ubuntu 18.04 in this project.
3. PyG guides can be found at https://github.com/rusty1s/pytorch_geometric.
### Installation
**PyTorch 1.11 + pytorch_geometric(PyG) 2.0.4(Recommend)**  
`conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch`(currently it works, 2022.3.27)  
or  
`conda install pytorch=1.11.0 torchvision=0.12.0 torchaudio=0.11.0 cudatoolkit=10.2`  
then
`conda install pyg -c pyg` or `conda install pyg=2.0.4 -c pyg`  
**PyTorch 1.8 + pytorch_geometric(PyG) 2.0.1**  
`conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch-lts`(currently it works, 2022.3.27)  
or  
`conda install pytorch=1.8.2 torchvision=0.9.2 torchaudio=0.8.2 cudatoolkit=10.2`  
then  
`conda install pyg -c pyg` or `conda install pyg=2.0.1 -c pyg`  
**rdkit**  
`conda install rdkit -c conda-forge`  
## Step-by-step Running
