# Pandas Learning Project

## 项目简介
这是一个新手用于学习 Pandas 数据处理和分析并尝试代码的上传的练手项目。通过 Jupyter Notebook，我记录了 Pandas 的基本用法，主要包括数据结构（如 Series 和 DataFrame）、数据操作（如筛选、排序、聚合）等内容。

## 项目结构
```
pandas_learning/
├── Series.ipynb
├── dataframe.ipynb
├── output.csv
├── train.csv
└── README.md
```
- **`Series.ipynb`**：介绍 Pandas 中的 Series 数据结构及其基本操作。
- **`dataframe.ipynb`**：介绍 Pandas 中的 DataFrame 数据结构及其操作，包括数据筛选、排序和聚合等。
- **`output.csv`**：一个示例输出文件，用于展示数据处理的结果。
- **`train.csv`**：一个示例数据文件，用于练习数据处理和分析。

## 环境要求
- **Python**：推荐使用 Python 3.11。
- **Pandas**：用于数据处理和分析。
- **Jupyter Notebook**：用于运行和展示代码。

## 安装和运行
### 安装依赖
1. 确保你已安装 Python 和 pip。
2. 安装 Pandas 和 Jupyter Notebook：
   ```bash
   pip install pandas jupyter
   ```
### 运行 Notebook
1. 克隆本仓库：
   ```bash
   git clone https://github.com/Yeily/pandas_learning.git
   ```
2. 进入项目目录：
   ```bash
   cd pandas_learning
   ```
3. 启动 Jupyter Notebook：
   ```bash
   jupyter notebook
   ```
4. 在浏览器中打开 Jupyter Notebook，选择对应的 `.ipynb` 文件即可开始学习。

## 使用说明
- **`Series.ipynb`**：运行该 Notebook，逐步学习 Pandas 中的 Series 数据结构及其操作，如创建、索引、筛选等。
- **`dataframe.ipynb`**：运行该 Notebook，学习如何使用 DataFrame 进行复杂的数据处理，如数据筛选、分组、聚合等。
- **数据文件**：`train.csv` 是一个示例数据文件，你可以使用它来练习数据处理和分析。

## 示例代码
以下是一个简单的 Pandas 示例代码，展示如何创建一个 DataFrame 并进行基本操作：

```python
import pandas as pd

# 创建一个简单的 DataFrame
data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [25, 30, 35],
    'City': ['New York', 'Los Angeles', 'Chicago']
}
df = pd.DataFrame(data)

# 显示 DataFrame
print(df)

# 筛选年龄大于 30 的记录
filtered_df = df[df['Age'] > 30]
print(filtered_df)
```

## 学习资源
- [Pandas 官方文档](https://pandas.pydata.org/pandas-docs/stable/)
- [Jupyter Notebook 官方文档](https://jupyter-notebook.readthedocs.io/en/stable/)
- [Python 官方文档](https://docs.python.org/3/)

## 贡献指南
欢迎任何人对本项目进行贡献！如果你有任何改进意见或发现错误，请随时提交 Issue 或 Pull Request。

代码改编来源为[菜鸟教程](https://www.runoob.com/pandas/pandas-tutorial.html)

数据清洗csv来源为[kaggle 房价预测](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)

## 许可证
本项目采用 [MIT License](LICENSE)。

## 联系方式
- GitHub: [Yeily](https://github.com/Yeily)
- Email: yei1y@proton.me
