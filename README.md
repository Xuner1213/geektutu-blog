# Geektutu's Blog

[极客兔兔的博客](https://geektutu.com)， 使用主题[geektutu](https://github.com/geektutu/hexo-theme-geektutu)

如果你喜欢该主题，点个 [Star](https://github.com/geektutu/hexo-theme-geektutu) 吧。

## 使用步骤

```bash
npm i      # 安装npm模块
npm update # 下载主题到 themes/geektutu
npm build  # 将posts的文章拷贝到source目录下的_posts，并执行hexo clean, hexo generate
npm deploy # 部署到_config.xml中配置的仓库地址
```

如果你使用的是yarn，将下面的npm换成yarn即可。

## 注意事项

posts目录的存在仅仅是为了博主做博客分类使用， npm build时会拷贝到source/_posts。
因此， 直接新建source/_posts目录，并直接在该文件夹下写文章是没有问题的。

可以在package.json里的scripts部分，定制你自己的npm/yarn命令。
