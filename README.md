# SecStore 软件列表

> 存储SecStore相关软件的索引、介绍、下载链接等信息。

## 📋 软件发布指南

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
        "download": "软件下载链接列表（如：["https://github.com/SECTL/SecRandom/releases/download/【tag】", "或者是你自己的下载链接，如果是不支持的软件或者是没有包含GitHub文本则会直接打开界面让用户手动下载"]）",
        "isweb": "是否是网页软件（如：true 或 false）",
        "note": "软件发布注意事项（如：需要管理员权限等）",
        "qq": "软件作者的 QQ 群号（如：123456789）",
        "qq_name": "软件作者的 QQ 群名称（如：SecStore 软件群）",
        "official_website": "软件的官方网站链接（如：https://example.com）",
        "license": "软件的开源协议（如：GPL-3.0）",
        "license_url": "软件的开源协议链接（如：https://www.gnu.org/licenses/gpl-3.0.html）"
    }
}
```
#### 字段填写说明
**若软件信息中某些字段无对应内容，请将该字段设为空字符串（即 `""`），填写时请保留字段的引号。**

- **若软件没有官方网站，可将 `"official_website"` 字段设置为 `""`。**
- **若软件没有开源协议，可将 `"license"` 字段设置为 `""`。**
- **若为布尔值，可将 `"isweb"` 字段设置为 `true` 或 `false`。**
- **若软件没有 QQ 群，可将 `"qq"` 字段设置为 `""`。**
- **若软件没有 QQ 群名称，可将 `"qq_name"` 字段设置为 `""`。**
- **若软件没有注意事项，可将 `"note"` 字段设置为 `""`。**
- **若软件没有开源协议链接，可将 `"license_url"` 字段设置为 `""`。**
- **若软件没有软件宣传图片，可将 `"banner"` 字段设置为 `""`。**

## 📂 软件分类

SecStore 支持以下软件分类：

- **屏幕批注与白板软件**：屏幕标注、白板绘图、批注工具等
- **课表与看板类软件**：课程管理、看板工具、日程规划等
- **辅助类软件与实用工具**：系统辅助、实用工具、效率工具等
