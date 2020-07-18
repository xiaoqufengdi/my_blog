#[使用github搭建博客](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)
##创建一个没有父节点的分支gh-pages。因为github规定，只有该分支中的页面，才会生成网页文件
+ git checkout --orphan gh-pages

##github 创建对应的代码仓库
+ 关联本地仓库
>$ git remote add origin  https://github.com/xiaoqufengdi/my_blog.git
+ 推送到github代码仓
>$ git push origin gh-pages

##[个人博客地址] (http://xiaoqufengdi.github.io/my_blog)


##Hexo 
>一个快速、简洁且高效的博客框架。Hexo 使用 Markdown（或其他渲染引擎）解析文章，在几秒内，即可利用靓丽的主题生成静态网页。
+ install
> $ npm install hexo