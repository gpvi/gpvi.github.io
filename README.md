# Jekyll 博客

这是从 `D:\Blog` 迁移出来的独立 Jekyll 项目，不依赖 Hexo。原项目保留在 `D:\Blog`。当前迁移了 22 篇文章、文章图片资源和个人简历；分类、标签和归档页面由 Jekyll 根据文章 Front Matter 生成。

## 本地运行

先安装 Ruby（Windows 可使用 RubyInstaller with DevKit），然后在此目录运行：

```powershell
bundle install
bundle exec jekyll serve --livereload
```

浏览器打开 `http://127.0.0.1:4000/`。静态站点可用以下命令生成到 `_site`：

```powershell
bundle exec jekyll build
```

文章放在 `_posts`，采用 `YYYY-MM-DD-title.md` 文件名；站点设置在 `_config.yml`；布局和样式分别位于 `_layouts` 与 `assets/css`。

原始文章中有 4 个 Obsidian 图片引用在 `D:\Blog` 的源文件里找不到对应图片，已在迁移文章中标出。
