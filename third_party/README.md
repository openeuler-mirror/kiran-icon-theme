# Third-Party Components

本目录包含集成至 kiran-icon-theme 的第三方组件及其来源说明。

## Notwaita Cursor Theme

本目录包含来自 [Notwaita Cursor Theme](https://github.com/ful1e5/notwaita-cursor) 项目的第三方组件。

### 组件说明

- **包含主题**：Notwaita-White、Notwaita-Black
- **集成版本**：`v1.0.0-alpha1`
- **目录位置**：`third_party/notwaita-cursor/`

### 源码仓库

| 说明 | 链接 |
| --- | --- |
| 上游项目 | [ful1e5/notwaita-cursor](https://github.com/ful1e5/notwaita-cursor) |
| 原始作品 | [donut2/notwaita-cursor-theme](https://gitlab.com/donut2/notwaita-cursor-theme) |

### 许可证信息

Notwaita Cursor Theme 以 **GNU Lesser General Public License v3.0 或更高版本**（`LGPL-3.0-or-later`）发布。

完整许可证文本见本仓库：

- [`licenses/notwaita-cursor.LICENSE`](../licenses/notwaita-cursor.LICENSE)

上游项目 `COPYING` 文件亦说明部分素材可在 GNU LGPL v3 或 [Creative Commons Attribution-ShareAlike 3.0 United States License](https://creativecommons.org/licenses/by-sa/3.0/)（`CC-BY-SA 3.0`）条款下使用。详见上游仓库中的 `COPYING`、`COPYING_LGPL`、`COPYING_CCBYSA3` 文件。

### 获取源码

#### 1. 克隆完整源码仓库

```bash
git clone https://github.com/ful1e5/notwaita-cursor.git
```

#### 2. 获取与本目录集成的特定版本

```bash
git clone --branch v1.0.0-alpha1 --depth 1 \
  https://github.com/ful1e5/notwaita-cursor.git
```

#### 3. 从 GitHub Releases 下载发布包

<https://github.com/ful1e5/notwaita-cursor/releases>

#### 4. 浏览指定版本的源码树

<https://github.com/ful1e5/notwaita-cursor/tree/v1.0.0-alpha1>

### 修改说明

`third_party/notwaita-cursor/` 中的文件为从上游项目选取并集成的光标主题资源。如需完整源码、构建脚本、SVG 源文件及其他变体（如 Notwaita-Gray、Windows 版本等），请访问上述源码仓库获取。
