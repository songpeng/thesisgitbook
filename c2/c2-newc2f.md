# 新结构化合物的格式提取
通常化合物的化学信息提取基于SMILES, SDF等格式。或者化
合物在常见的化合物数据库(如PubChem, ChEMBL)中有记录。当我们遇到化合物不能有上述
信息时，该如何处理？

目前主要的策略为将其结构在可视化的化学软件中画出来，然后转换为相应的格式。这里提
供一个具体的在线操作流程。

[Chemmine Tools](http://chemmine.ucr.edu) 提供了多种在线工具，其中通过**Add
Compounds**，选择**Draw a Molecule**，手动画好化合物2D结构后，点击提交。

这时会出现**My Compounds**页面，点击刚提交的化合物(系统自动命名)，会给出该化合
物的SMILES格式等。

该工具应该可以实现本地版本，具体流程暂时不清楚。希望能够得到大家的补充。
