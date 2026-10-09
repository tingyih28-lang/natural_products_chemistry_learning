# 天然药物化学学习网站

中英文对照的天然药物化学知识库，包含母核编号、分类与代表化合物、理化性质、鉴别原理及练习题。

## 在线访问

[打开网站](https://tingyih28-lang.github.io/natural_products_chemistry_learning/)

## 内容与使用

- 11 个课程模块，保留植物图鉴风格与逐级折叠的分类树。
- 398 道练习题；通常每套 20 题，包含单选、填空和简答。
- 填空提交后核对答案，简答依据参考答案与评分要点自行评价。
- 章节、题目和结构图附课程来源；题目同时参考补充复习资料。
- 学习进度与错题记录保存在当前浏览器，换浏览器或清理数据后不会同步。
- PubChem 和维基百科链接需要联网。

## 文件与部署

`site/` 包含可以直接使用的静态网页和本地资源。下载仓库后可打开 `site/index.html` 或 `site/home.html`，请保持 `assets/` 文件夹的位置。

`.github/workflows/deploy-pages.yml` 在 `main` 分支更新时将 `site/` 自动发布到 GitHub Pages，无需安装依赖或运行构建。

更新时替换 `site/` 中的网页与资源，并让 `index.html` 与 `home.html` 保持一致，再提交到 `main`。

随站字体的许可见 `site/assets/font-license.txt`。原课件、复习资料文档和 GitHub 登录凭据不包含在此仓库中。
