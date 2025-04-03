# 天地图地理编码查询工具 (CN Geocoder)

一个基于天地图API的地理编码批量查询工具，支持将地址批量转换为CGCS2000坐标系下的经纬度坐标。

A batch geocoding tool based on Tianditu API that converts addresses into longitude and latitude coordinates under CGCS2000 coordinate system.

## ✨ 功能特点 (Features)

- 🌏 支持全国范围的地址查询 (Support nationwide address queries)
- 📑 支持CSV/XLSX格式的批量查询 (Support batch processing of CSV/XLSX files)
- 🎯 使用CGCS2000坐标系 (Use CGCS2000 coordinate system)
- 🗺️ 可视化地图展示 (Visual map display)
- 📊 支持查询结果导出 (Export query results)
- 🔍 交互式结果查看 (Interactive result viewing)

## 🚀 快速开始 (Quick Start)

### 使用方法 (Usage)

1. 准备数据文件 (Prepare data file)
   - CSV或XLSX格式 (CSV or XLSX format)
   - 第一列为地址名称 (First column should be address names)

2. 上传文件 (Upload file)
   - 点击"选择文件"按钮 (Click "Choose File" button)
   - 选择准备好的数据文件 (Select your prepared data file)

3. 开始查询 (Start query)
   - 点击"开始查询"按钮 (Click "Start Query" button)
   - 等待查询完成 (Wait for completion)

4. 查看结果 (View results)
   - 在左侧面板查看列表 (View list in left panel)
   - 在地图上查看位置 (View locations on map)
   - 点击列表项定位到地图 (Click list item to locate on map)

5. 导出结果 (Export results)
   - 点击"导出结果"按钮 (Click "Export Results" button)
   - 自动下载XLSX文件 (XLSX file will be downloaded automatically)

## 📝 数据格式 (Data Format)

### 输入格式 (Input Format)

CSV/XLSX文件示例 (CSV/XLSX file example):
```
地址
北京市朝阳区朝阳门
上海市浦东新区陆家嘴
广州市天河区珠江新城
```

### 输出格式 (Output Format)

XLSX文件包含以下列 (XLSX file contains following columns):
- 地名 (Place Name)
- 地址 (Address)
- CGCS2000坐标 (CGCS2000 Coordinates)

## ⚠️ 注意事项 (Notes)

1. 必须使用本地服务器打开页面，直接打开HTML文件将无法使用
   (Must use local server to open the page, directly opening HTML file will not work)

2. 天地图API可能有调用频率限制，建议批量查询时控制数据量
   (Tianditu API may have rate limits, please control data volume for batch queries)

3. 坐标系统使用CGCS2000，与国家标准一致
   (Using CGCS2000 coordinate system, consistent with national standards)

## 🔧 技术栈 (Tech Stack)

- 天地图 JavaScript API (Tianditu JavaScript API)
- Papa Parse (CSV解析)
- SheetJS (Excel处理)
- Tailwind CSS (样式框架)

## 📄 许可证 (License)

MIT License

## 🤝 贡献 (Contributing)

欢迎提交Issue和Pull Request。
(Issues and Pull Requests are welcome.)

## 📞 联系方式 (Contact)

如有问题，请提交Issue。
(If you have any questions, please submit an issue.) 
