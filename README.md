## Hugo

```
brew install hugo

hugo version

hugo new site {sitename}

cd {sitename}

git init

# add a theme
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke

# add some content 
hugo new posts/my-first-post.md

# start a server
hugo server -D

# build static page
hugo -D

```

## Github page

1. 创建与用户名（lin559）关联的 repo 名 `lin559.github.io`
2. 在 blog 的目录下执行 `git init ` 等一系列关联仓库的操作
3. 如果有自己的域名，也可以解析到自己的域名下，blog 根目录 创建 `CNAME` 文件，填入自己的域名
4. repo Settings/Pages Custom domain 就会有你的域名，注意做好域名解析
5. 域名解析地址可以通过 `ping lin559.github.io` 查看地址


[HUGO](https://gohugo.io/getting-started/quick-start/)

[Hugo + GitHub Action，搭建你的博客自动发布系统](https://www.pseudoyu.com/zh/2022/05/29/deploy_your_blog_using_hugo_and_github_action/)

[基于 Github Action 自动构建 Hugo 博客](https://www.lixueduan.com/posts/blog/01-github-action-deploy-hugo/)
