# Yuwei Du - Academic Homepage

Personal academic homepage built with [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll theme.

## Live Site

- **当前配置**（仓库在 Hiimingway 下）：https://hiimingway.github.io/duyuwei.github.io/
- **若使用 duyuwei.github.io**：需将仓库迁移到 `duyuwei/duyuwei.github.io`，并将 `_config.yml` 中 `baseurl` 改为 `""`

## 部署步骤（解决 404）

1. **启用 GitHub Pages**：仓库 → Settings → Pages → Build and deployment → Source 选择 **GitHub Actions**
2. **推送代码**：`git push origin main` 后会自动触发构建
3. **访问地址**：
   - 当前：https://hiimingway.github.io/duyuwei.github.io/
   - 若想用 https://duyuwei.github.io：需创建 `duyuwei/duyuwei.github.io` 仓库并迁移代码，将 `baseurl` 改为 `""`

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000（本地需加 baseurl：http://localhost:4000/duyuwei.github.io/）

## Structure

- `_config.yml` - Site configuration
- `index.md` - Homepage content
- `_data/publications.yml` - Publication list
- `_includes/` - Custom includes
- `assets/files/` - CV and other files

## Customization

- Update `_config.yml` for profile info, links, and SEO
- Edit `index.md` for bio and research description
- Add publications in `_data/publications.yml`
- Replace `assets/files/CV_YuweiDu_phd.pdf` with your latest CV
- Add `assets/img/avatar.png` for profile photo (uncomment in _config.yml)
