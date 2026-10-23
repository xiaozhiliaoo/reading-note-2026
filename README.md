# mdbook-template

## Run

需要前置Rust开发环境

cargo install mdbook

如果已经安装好，每次运行执行以下命令：

mdbook clean && mdbook build && mdbook serve

也可以执行脚本./start.sh

本地访问地址：http://localhost:3000/

## Config

需要配置book.toml中github地址

## 安装mdbook插件

rustc --version
rustc 1.99.1 (58cf8f9c3 2026-10-13)

cargo --version
cargo 1.99.1 (5f94df478 2026-08-27)

cargo install mdbook --version "^0.4" --force

cargo install mdbook-mermaid --version 0.14.0 --force

