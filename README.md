# 职场沟通方法论 · 三版合集

基于 **269 份真实职场材料** 深度分析，三个版本，不同视角。

## 三本书

| 版本 | 书名 | 特点 |
|------|------|------|
| [Sonnet 4.6 版](books/sonnet/) | 职场沟通与人际关系方法论：从认知差异到权力赋能 | 16章，底层认知 + 方法论体系，100+ 案例 |
| [智慧版](books/wisdom/) | 职场沟通的底层逻辑 | 19章，7部分，含领导力情商与团队管理 |
| [Haiku 版](books/haiku/) | 职场沟通方法论：从认知差异到系统化框架 | 16章，精简提炼，系统地图 |

## 目录结构

```
books/
├── sonnet/     # Sonnet 4.6 版
├── wisdom/     # 智慧版（30年HR大高管方法论）
└── haiku/      # Haiku 版
docs/           # 构建输出（GitHub Pages）
├── index.html  # 三书入口
├── sonnet/
├── wisdom/
└── haiku/
```

## 本地构建

```bash
cargo install mdbook

mdbook build books/sonnet
mdbook build books/wisdom
mdbook build books/haiku

# 预览某一本
mdbook serve books/sonnet
```

**最后更新**：2026 年 3 月 20 日
