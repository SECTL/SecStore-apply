# SecStore 软件列表

> 存储SecStore相关软件的索引、介绍、下载链接等信息。

## 📋 软件发布指南

### ⚠️ 重要注意事项

在发布软件之前，请确保满足以下要求：

1. **Release 发布**：在您的软件 GitHub 仓库中至少发布了一个 Release（将软件打包成可执行文件或安装包上传），否则软件将无法在 SecStore 中下载。

2. **软件图标**：您的软件显示在 SecStore 的图标需要放置在您的软件仓库主文件夹下，**图标文件的名称必须与软件仓库名称相同**，建议使用 `.png` 格式。

### 🚀 发布步骤

若要发布软件，请按以下步骤操作：

1. **Fork 本项目**
2. **修改软件列表**：编辑 `./apply/software_list.json` 文件，按照指定格式添加您的软件信息
3. **提交审核**：提交 PR 等待审核即可

### 📝 软件信息格式

```json
{
    "其他软件...": {
        ...
    },
    // 在这里添加您的软件信息
    "您的软件仓库名称": {
        "name": "软件在 SecStore 显示的名称",
        "description": "软件的简介",
        "version_format": "软件版本号格式（如：v0.0.0.0）",
        "author": "软件作者的 SecStore 名称",
        "url": "您的 GitHub 软件仓库链接 (例如：https://github.com/SECTL/SecRandom)",
        "icon": "您的 软件图标链接(例如:https://github.com/SECTL/SecRandom/blob/main/resources/SecRandom.png)",
        "banner": "您的 软件宣传图片链接(例如:https://github.com/SECTL/SecRandom/blob/main/resources/banner.png)",
        "branch": "软件仓库的分支（如：main）",
        "category": "软件分类（如：屏幕批注与白板软件、课表与看板类软件、辅助类软件与实用工具等）", 
        "platform": "支持的平台列表（如：[windows, linux, macos]）",
        "download": "软件下载链接列表（如：["https://github.com/SECTL/SecRandom/releases/download/【tag】", "或者是你自己的下载链接，如果是不支持的软件或者是没有包含GitHub文本则会直接打开界面让用户手动下载"]）
    }
}
```

## 📂 软件分类

SecStore 支持以下软件分类：

- **屏幕批注与白板软件**：屏幕标注、白板绘图、批注工具等
- **课表与看板类软件**：课程管理、看板工具、日程规划等
- **辅助类软件与实用工具**：系统辅助、实用工具、效率工具等
