# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

```mermaid
graph LR
    A[开始] --> B{是否正常?}
    B -->|是| C[结束]
    B -->|否| D[排查问题]
    D --> B
```

```mermaid
graph TD
    subgraph 准备阶段
        A1[需求分析] --> A2[方案设计]
    end
    subgraph 执行阶段
        B1[开发] --> B2[测试]
    end
    A2 --> B1
    B2 --> C[发布上线]
```