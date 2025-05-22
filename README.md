# Rust 项目模板

> 本文档基于 [tyr-rust-bootcamp/template](https://github.com/tyr-rust-bootcamp/template) 创建，向其致以诚挚的感谢！

## 推荐的 VS Code 插件

以下是推荐安装的 VS Code 插件，以提升开发体验：

- `aaron-bond.better-comments` - 提供更好的代码注释高亮。
- `eamodio.gitlens` - 增强 Git 功能。
- `esbenp.prettier-vscode` - 代码格式化工具。
- `fill-labs.dependi` - 依赖关系可视化工具。
- `hdevalke.rust-test-lens` - Rust 测试支持。
- `humao.rest-client` - REST API 测试工具。
- `oderwat.indent-rainbow` - 缩进可视化工具。
- `redhat.vscode-yaml` - YAML 文件支持。
- `rust-lang.rust-analyzer` - Rust 语言分析器。
- `swellaby.vscode-rust-test-adapter` - Rust 测试适配器。
- `tamasfe.even-better-toml` - TOML 文件支持。
- `usernamehw.errorlens` - 错误高亮显示。
- `vscode-icons-team.vscode-icons` - 图标主题。
- `wayou.vscode-todo-highlight` - TODO 高亮工具。

## 工具安装指南

### 安装 `cargo-binstall`

[cargo-binstall](https://github.com/cargo-bins/cargo-binstall) 是一个用于快速安装 Rust 二进制工具的工具。

```bash
cargo install cargo-binstall
```

### 安装 `pre-commit`

[pre-commit](https://pre-commit.com/) 是一个代码检查工具，可在提交代码前自动执行代码检查。

```bash
pip3 install pre-commit
```

### 安装 `cargo-generate`

[`cargo-generate`](https://github.com/cargo-generate/cargo-generate) 是一个用于生成项目模板的工具。它支持使用 GitHub 仓库作为模板生成新项目。

```bash
cargo binstall cargo-generate
```

### 安装 `typos`

[typos](https://github.com/crate-ci/typos) 是一个拼写检查工具，用于检测代码中的拼写错误。

```bash
cargo binstall typos-cli
```

### 安装 `git-cliff`

[git-cliff](https://github.com/orhun/git-cliff) 是一个生成变更日志（changelog）的工具。

```bash
cargo binstall git-cliff
```

### 安装 `cargo-nextest`

[cargo-nextest](https://github.com/nextest-rs/nextest) 是一个高效的 Rust 测试运行工具。

```bash
cargo binstall cargo-nextest --secure
```
