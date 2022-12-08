51CTO 博客
脑机接口社区 博主文章分类：数据分析与可视化
seaborn系列 的jupyter notebook 代码。
seaborn-data.zip 是用到的数据文件，解压后放到jupyter notebook根目录下，
就可以如下在代码中加载本地数据了：
tips = sns.load_dataset("tips", data_home='./seaborn-data', cache=True)
