# dsh-plugin-lazy-adapter-resolution

DSH 插件在 `apply()` 阶段不要同步解析「可能还没注册好」的内层 provider 适配器，改为请求时懒解析。

## 环境依赖

- 操作系统：Windows
- 运行时：Node.js
- 第三方软件：无（仅依赖系统自带的 PowerShell / 标准库）

## 目录结构

    dsh-plugin-lazy-adapter-resolution/
    ├── SKILL.md    技能入口与工作流

## 安装

    # GitHub
    git clone https://github.com/hpsks416/dsh-plugin-lazy-adapter-resolution.git "$env:USERPROFILE\.dsh\skills\dsh-plugin-lazy-adapter-resolution"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/dsh-plugin-lazy-adapter-resolution.git "$env:USERPROFILE\.dsh\skills\dsh-plugin-lazy-adapter-resolution"

克隆后 DSH 自动重新发现，无需构建。

## License

MIT License. See [LICENSE](LICENSE).
