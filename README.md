# dsh-plugin-lazy-adapter-resolution

Use when writing a DSH plugin that depends on an LLM provider adapter registered by another plugin.

## 这是什么

DSH（DeepSeek Harness）skill —— 一个可由 AI agent 按需自动加载的能力单元。克隆到 skill 目录后，DSH 会依据上方描述自动发现并触发它，无需构建。

## 安装

最简单：用 [dsh-config](https://github.com/hpsks416/dsh-config) 的一键脚本 `install.ps1` 批量安装全部 skill。单个安装：

    # GitHub
    git clone https://github.com/hpsks416/dsh-plugin-lazy-adapter-resolution.git "$env:USERPROFILE\.dsh\skills\dsh-plugin-lazy-adapter-resolution"
    # 或 Gitee（国内直连更快）
    git clone https://gitee.com/hpsks416/dsh-plugin-lazy-adapter-resolution.git "$env:USERPROFILE\.dsh\skills\dsh-plugin-lazy-adapter-resolution"

克隆后 DSH 会自动重新发现，无需重启。更新用：

    git -C "$env:USERPROFILE\.dsh\skills\dsh-plugin-lazy-adapter-resolution" pull

## 目录结构

    dsh-plugin-lazy-adapter-resolution/
    ├── SKILL.md    技能入口与工作流
    （无附加文件，纯指令型 skill）

## 依赖

无运行时依赖，纯指令型 skill（由 agent 直接执行 Markdown 工作流）。

## License

MIT License. See [LICENSE](LICENSE).
