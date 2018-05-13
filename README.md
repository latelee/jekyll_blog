github的个人博客
================
### 创建步骤
* 申请注册github账号，在仓库内建立名为<主页名称>.github.io的仓库，如latelee.github.io。注意，主页名与github账号名完全一致，才能使用xxx.github.io的形式，如果不是，则使用<用户名>.github.io/<仓库名>的形式访问。
* 克隆别人现成的模板到这个仓库（或者fork别人的模板仓库）。github主页使用Jekyll，网上有很多模板。
* 根据实际情况修改模板文件。
* 提交到自己的github仓库，稍等片刻，即可在https://<主页名称>.github.io/上看到博客内容。  
* 注意，文章必须位于_posts目录，且必须以“年-月-日-文章名.md”命名。日、月前面需补0，即1月，必须是01。  
* 文章为markdonw格式，里面必须按要求编写。

### 模板
在panxw提供的模板基础上修改，来源：https://github.com/panxw  

### 使用说明
#### 目录说明
* _includes：版权、页脚、广告等。
* _layouts：博客布局。
* _posts：文章所在目录，里面按分类目录存放，可自定义目录。
* assets：图片、文件存放目录，可建不同目录。
* css：css样式目录
* posts：分类目录
* favicon.ico：网站标志图片，由可png/jpeg生成ico格式。
* Robots.txt：如果不希望被搜索引擎搜索，则设置，默认是不被抓取。
* CNAME：自定义域名，必须要在域名后台设置cname为github地址。

#### _config.yml
* excerpt_separator：文章摘要分隔符，本模板为“<!-- more -->”，即markdown文件中必须带此标签才能正确分隔，可自行修改。
* github、email、name、domain等，根据实际情况修改。
* all_categories：分类名称、地址，根据示例添加即可。
* paginate：一页文章展示数量，默认为5，多于此数会显示下一页。
* timezone：时区，默认是东八区，一般不需要修改。
* 其它待补充。

#### 