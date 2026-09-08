# FoxFairy · AI 实战与深度笔记

目标域名：https://blog.stellakjbk.top
GitHub 仓库：https://github.com/zfcdvcs/stellakjbk-blog

网站包含 6 篇长文导读与 3 篇创作笔记，支持分类和独立文章页面。正文为编辑整理，附原帖链接；浏览量为 2026-09-08 采集快照。

## 发布

site.zip 为已验证的静态发布包，解压后首页 index.html 位于根目录。GitHub Actions 解压并发布到 GitHub Pages。更新 site.zip 后将自动重新发布。

源码保存在 source.zip。使用 Node.js 22.13 或更高版本，运行 npm ci、npm run build，静态产物位于 dist/client。生成新的 site.zip 时应保持目录结构，包含 .nojekyll 文件。

仓库 Settings → Pages 的 Source 选择 GitHub Actions，自定义域名填写 blog.stellakjbk.top。