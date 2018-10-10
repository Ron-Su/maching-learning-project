# 内容：非监督式学习
## 项目：创建客户细分

### 安装

本项目要求安装 **Python 2.7** 和以下 Python 库：

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

你还需要安装软件，才能运行并执行 [Jupyter Notebook](http://ipython.org/notebook.html)。
 
如果你尚未安装 Python，强烈建议你安装 Python  的 [Anaconda](http://continuum.io/downloads) 分发系统，该系统已经包含上述软件包，并且包含更多其他软件包。请确保你选择的是 Python 2.7 安装包，而不是 Python 3.x 安装包。

### 代码

你可以在 notebook 文件 `customer_segments.ipynb` 中找到代码模板。你还将被要求使用 Python 文件 `visuals.py` 和数据集文件 `customers.csv`  来完成你的任务。我们已经提供了一些初始代码来帮助你开始，你需要补充额外函数来顺利完成本项目。请注意，学员无需更改 `visuals.py` 中的代码。如果你对 notebook 中的可视化文件感兴趣，请随意探索。

### 运行

在终端或命令行窗口中，跳转至最上面的项目目录 `customer_segments/`（包含 README 文件），并运行如下命令：

```bash
ipython notebook customer_segments.ipynb
```  
或者
```bash
jupyter notebook customer_segments.ipynb
```

这将在你的浏览器中打开 iPython Notebook 软件和项目文件。browser.

## 数据

客户细分数据中包含 440 个数据点，均来自于一家位于葡萄牙里斯本的批发供应商。你可以在 [UCI 机器学习代码库](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers)中找到更多信息。

请注意 (m.u.) 是 *monetary units* 的缩写形式。

**特征**

* `Fresh`: 购买生鲜产品的年支出(m.u.)(连续)； 
* `Milk`: 购买奶制品的年支出(m.u.)(连续)；
* `Grocery`: 购买杂货品的年支出(m.u.)(连续)； 
* `Frozen`: 购买冷冻产品的年支出(m.u.)(连续)；
* `Detergents_Paper`: 购买清洁产品和纸制品的年支出(m.u.)(连续)；
* `Delicatessen`: 购买熟食的年支出(m.u.)(连续)； 
* `Channel`: {酒店/餐馆/咖啡厅 - 1, 零售 - 2} (Nominal)
* `Region`: {里斯本 - 1, 波尔图 - 2, 其他 - 3} (Nominal) 