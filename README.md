# 基于Python的A股股票数据分析与可视化系统
> 个人数据分析实战项目｜Python｜Pandas｜Pyecharts｜网络爬虫

## 📌 项目简介
通过网络爬虫获取A股多支股票实时行情数据，包含股票名称、现价、涨跌幅、成交量、市值等字段；完成数据清洗、缺失值填充、排序筛选；利用Pyecharts实现成交量柱状图、市值饼图、涨跌幅折线图交互式可视化，完成股票数据分析。

## ✨ 项目亮点
1. 爬虫获取公开股票行情原始数据，自动保存CSV文件；
2. Pandas完成空值检测、缺失值填充、按成交量排序筛选；
3. Pyecharts绘制成交量柱状图、市值占比饼图、涨跌幅折线图；
4. 交互式网页图表，鼠标悬浮查看详细数值。

## 🛠 技术栈
Python、Pandas、NumPy、Pyecharts、requests

## 📁 仓库文件说明
- stock_analysis.ipynb：完整jupyter源码（和截图单元格一一对应）
- report.md：项目实验报告
- result.png：项目运行完整截图

## 📊 效果预览
![项目完整运行截图](./result.png)

## 🚀 运行步骤
1. 安装依赖
```bash
pip install -r requirements.txt
