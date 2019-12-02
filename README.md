# 主题依赖

## 添加子模块
```
git submodule add https://github.com/zwbetz-gh/cayman-hugo-theme.git themes/cayman-hugo-theme
git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke
git submodule add https://github.com/vjeantet/hugo-theme-casper.git themes/casper
```

## 更新主题
```
git submodule update --remote --merge
```

## Configuration
Copy the config.toml or config.yaml from the exampleSite, then edit as desired.

When editing the header background colors, this site has some nice color combinations.

# Favicons
Upload your image to [RealFaviconGenerator](https://realfavicongenerator.net/) then copy-paste the generated favicon files under static.