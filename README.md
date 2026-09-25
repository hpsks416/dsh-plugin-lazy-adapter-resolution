# dsh-plugin-lazy-adapter-resolution

DSH 插件在 `apply()` 阶段不要同步解析「可能还没注册好」的内层 provider 适配器，改为请求时懒解析。

## 适用对象

- DeepSeek Harness（DSH）用户：一个可由 AI agent 按需自动加载的 skill，克隆即用、无需构建。
- 写 DSH 插件、依赖其他 LLM provider 适配器的开发者

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
