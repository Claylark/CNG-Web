爱莉NFC自定义卡号工具是一个基于Web的应用程序，用于生成符合Luhn校验规则的银行卡号。该工具采用现代UI设计，支持深色模式切换和自定义背景上传。

## 功能特点

- 🏦 自定义银行卡号生成（BIN、自选部分、尾部部分）
- 自动应用Luhn校验算法
- 深色/浅色模式切换
- 自定义背景上传功能
- 卡号列表展示与验证
- 卡号复制功能

## 使用说明

1. **输入银行识别码(BIN)**：输入6位数字的银行识别码（例如：621486）
2. **设置中间部分**：可包含数字和星号(*)，星号表示生成所有可能的数字，可不填
3. **设置尾部定制部分**：4-6位数字或星号（例如：**8888）
4. **选择卡号长度**：12-19位之间的卡号长度
5. **生成卡号**：点击"生成所有有效卡号"按钮
6. **操作生成的卡号**：
   - 点击验证按钮检查卡号有效性
   - 点击复制按钮复制卡号到剪贴板

## 技术栈

- **前端**：
  - HTML5
  - CSS3 (Flexbox, Grid布局)
  - JavaScript (ES6)
- **UI框架**：
  - Font Awesome 图标
  - Google Fonts (Noto Sans SC)
- **特色技术**：
  - 毛玻璃效果 (backdrop-filter)
  - 响应式设计
  - 本地存储 (localStorage)
  - Luhn校验算法

## 安装与运行

这个项目是一个纯静态网页，无需安装任何依赖：

```bash
# 克隆仓库
git clone https://github.com/Claylark/CNG-Web.git

# 进入项目目录
cd CNG-Web

# 打开index.html文件
# 或者使用Live Server等工具运行
```

或者直接访问在线版本：[https://cng.elynfc.com](https://cng.elynfc.com)

## 贡献指南

欢迎贡献！请遵循以下步骤：

1. Fork 项目仓库
2. 创建新分支 (`git checkout -b feature/your-feature`)
3. 提交更改 (`git commit -am 'Add some feature'`)
4. 推送到分支 (`git push origin feature/your-feature`)
5. 创建 Pull Request

## 许可证

本项目采用 GPL v3.0 许可证 - 查看 [LICENSE](LICENSE) 文件了解更多详情

## 联系方式

- 项目主页：https://github.com/Claylark/CNG-Web
- 站长邮箱：0@elynfc.com
- 问题反馈：https://github.com/Claylark/CNG-Web/issues
