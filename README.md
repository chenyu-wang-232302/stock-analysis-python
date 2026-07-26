# stock-analysis-python
# 基于Python的沪深300股票市场趋势分析与可视化系统
> 个人数据分析实战项目｜Python｜Pandas｜Pyecharts｜Matplotlib

## 📌 项目简介
针对沪深300指数5年历史交易数据开展数据分析，完成原始交易数据清洗、缺失值填充、异常波动识别、统计分析、趋势可视化，搭建自动化数据分析脚本，挖掘股价涨跌规律，为投资趋势研判提供可视化参考工具。

## ✨ 项目亮点
1. 使用Pandas完成批量预处理：去重、空值填补、异常点位标记；
2. 计算每日涨跌幅，识别大幅波动交易日；
3. Matplotlib绘制股价长期趋势图；
4. Pyecharts实现交互式涨跌幅折线图；
5. 代码模块化，可更换数据源复用。

## 🛠 技术栈
Python、Pandas、NumPy、Matplotlib、Pyecharts

## 📁 仓库文件说明
- stock_analysis.ipynb：完整可复现代码
- report.md：项目分析报告
- images/result.png：项目运行结果截图

## 📊 效果预览
![运行结果截图](./images/result.png)

## 🚀 运行步骤
1. 安装依赖
```bash
pip install -r requirements.txt
