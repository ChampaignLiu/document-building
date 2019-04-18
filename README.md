# document-building
项目文档很必要，借助工具可以制作出漂亮的文档

## GitHub Pages
### 了解Github Pages
- https://help.github.com/en/articles/what-is-github-pages
- https://help.github.com/en
- https://help.github.com/en/articles/about-github-pages-and-jekyll

> GitHub提供的将`'用户名.github.io'`仓库发布成网址为`'https://用户名.github.io/'`的静态博客，仓库名和网址可以修改，参看https://help.github.com/en/articles/using-a-custom-domain-with-github-pages ，除了支持常规HTML内容，GitHub Pages还支持Jekyll，一个流行的静态站点生成器。

### 开始行动
- https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages
- https://help.github.com/en/articles/adding-a-jekyll-theme-to-your-github-pages-site-with-the-jekyll-theme-chooser
- https://help.github.com/en/articles/adding-a-jekyll-theme-to-your-github-pages-site

> 创建仓库，添加主题，主题的配置信息写在_config.yml文件中，借助jekyll制作精美博客

## Jekyll搭建静态博客网站
- https://www.cnblogs.com/yehui-mmd/p/6286271.html
- http://jekyllcn.com/
- https://jekyllrb.com/

> _site文件夹存储的是转化生成的html css文件，GitHub不需要，GitHub Pages会用jekyll转化。

## Hexo高效博客框架
> Hexo发布的是html静态页面，GitHub Pages也就不用转化，直接可以展示了。

- https://hexo.io/zh-cn/
- https://www.jianshu.com/p/465830080ea9
- https://www.cnblogs.com/visugar/p/6821777.html
- https://www.cnblogs.com/liuxianan/p/build-blog-website-by-hexo-github.html
- https://www.zhihu.com/question/24422335

```_config.yml
deploy:
  type: git
  repo: https://github.com/ChampaignLiu/ChampaignLiu.github.io.git
  branch: master
```
```shell
hexo init
hexo g
hexo d
hexo server
hexo clean
hexo generate
hexo deploy
```
```shell
…or create a new repository on the command line

echo "# norm-consciousness" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/ChampaignLiu/norm-consciousness.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/ChampaignLiu/norm-consciousness.git
git push -u origin master
```

## WordPress
- https://cn.wordpress.org/
> 需要使用数据库

## Mkdocs
- https://zhuanlan.zhihu.com/p/41509998
- https://www.mkdocs.org/

## Markdown
- https://daringfireball.net/projects/markdown/
- https://www.jianshu.com/p/1e402922ee32
- http://www.markdown.cn/

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).


## Sphinx

## reStructuredText
http://docutils.sourceforge.net/rst.html
