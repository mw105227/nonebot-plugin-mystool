## Changelog

### 更新内容

[//]: # (#### 💡 新特性)

#### 🐛 修复
- 修复为全部用户执行游戏签到和米游社任务的 **`/签到 *`** 和 **`/任务 *`** 命令 (#364) (#384, @dontdot)

#### 🔧 杂项
- 已**移除微博签到**相关功能 (#383, @dontdot)
- [Wiki 文档](https://github.com/Ljzd-PRO/nonebot-plugin-mystool/wiki) 已更新

### 更新方式

如果使用的是镜像源，可能需要等待镜像源同步才能更新至最新版

- 使用 nb-cli 命令：
  ```
  nb plugin update nonebot-plugin-mystool
  ```

- 或 pip 命令（如果使用了虚拟环境，需要先进入虚拟环境）：
  ```
  pip install --upgrade nonebot-plugin-mystool
  ```

### 兼容性

- V2 (`>=v2.0.0`) 的相关文件为 _`configV2.json`, `dataV2.json`, `.env`_，如果存在 V1 版本的文件，**会自动备份和升级**
- V1 (`>=v1.0.0, <v2.0.0`) 插件配置/数据文件为 _`plugin_data.json`_
- `<v1.0.0` 插件配置文件为 _`pluginConfig.json`_

**Full Changelog**: https://github.com/Ljzd-PRO/nonebot-plugin-mystool/compare/v2.8.1…v2.9.0