# 待办看板 · TodoQuadrant

Windows 桌面待办客户端，按**艾森豪威尔四象限法**（紧急 × 重要）组织任务。
纯本地运行、不联网，任务数据只保存在你自己的电脑上。

> 本仓库只存放安装包。源代码在私有仓库中维护，不公开。

## 下载最新版

**固定链接（永远指向最新发布）**

```
https://github.com/C985211/todo-quadrant-download/releases/latest/download/TodoQuadrant-1.0.0-x64-setup.exe
```

| 版本 | 日期 | 安装包 | 大小 |
|---|---|---|---|
| v1.0.0 | 2026-11-05 | [TodoQuadrant-1.0.0-x64-setup.exe](https://github.com/C985211/todo-quadrant-download/releases/download/v1.0.0/TodoQuadrant-1.0.0-x64-setup.exe) | 77.9 MB |

## 功能（v1.0.0）

- 四象限看板：紧急重要 / 重要不紧急 / 紧急不重要 / 不紧急不重要
- 新建、编辑、删除、完成
- 拖拽卡片直接换象限
- 本地存储，原子写 + 备份，崩溃不丢数据
- 系统托盘常驻，关闭窗口最小化不退出
- 开机自启（可在注册表 `Run` 键查看或手工清除）
- 单实例运行，重复双击不会开出第二个窗口

## 安装

1. 下载 `TodoQuadrant-1.0.0-x64-setup.exe`，双击运行
2. 未做代码签名，Windows SmartScreen 可能提示"Windows 已保护你的电脑" ——
   点「更多信息」→「仍要运行」
3. 可自选安装目录，安装完桌面会有「待办看板」图标

## 环境要求

Windows 10 / 11，64 位。
