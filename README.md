# 菜品选择系统

一个基于 Python 和 Tkinter 的双端菜品管理系统，包含厨师端（管理菜品）和顾客端（点餐系统）。

## 功能特性

### 厨师端
- 📋 查看所有菜品列表
- ➕ 添加新菜品（名称 + 图片）
- 🗑️ 删除现有菜品
- 🖼️ 菜品图片预览
- 🎲 随机推荐菜品

### 顾客端
- 📖 浏览菜品菜单
- 🖼️ 查看菜品预览图片
- 🛒 添加菜品到购物车
- 🗑️ 删除购物车中的菜品
- 🎲 随机推荐菜品
- ✅ 确认下单

## 安装和运行

### 环境要求
- Python 3.7+
- Windows/Linux/macOS

### 安装步骤

1. **克隆项目**
```bash
git clone https://github.com/你的用户名/dish-selector.git
cd dish-selector
```

2. **创建虚拟环境（推荐）**
```bash
python -m venv .venv

# Windows
.venv\Scripts\activate

# Linux/macOS
source .venv/bin/activate
```

3. **安装依赖**
```bash
pip install -r requirements.txt
```

4. **运行程序**
```bash
cd src
python main.py
```

## 使用说明

1. 运行程序后会出现选择界面
2. 选择"厨师端"进行菜品管理
3. 选择"顾客端"进行点餐
4. 菜品数据保存在 `dishes.json` 文件中
5. 菜品图片存储在 `images/` 文件夹中

## 项目结构

```
dish-selector/
├── README.md           # 项目说明
├── requirements.txt    # Python依赖
├── dishes.json        # 菜品数据
├── check_data.py      # 数据检查工具
├── images/            # 菜品图片文件夹
└── src/               # 源代码
    ├── main.py        # 主程序入口
    ├── chef_app.py    # 厨师端界面
    ├── customer_app.py # 顾客端界面
    ├── dishes/        # 菜品相关模块
    ├── mytypes/       # 类型定义
    └── utils/         # 工具函数
```

## 技术栈

- **界面**: Tkinter
- **图片处理**: Pillow (PIL)
- **数据存储**: JSON
- **语言**: Python 3


## 贡献
XZY
