## 需要完善的地方

### 管理页

* [x] 顶部的导航条
* [x] 概况页面
* [x] 创建文章时要校验 pathname 唯一
* [x] 文章内容必填，且必须包含 <!--more--> 来生成 summary
* [x] 发布文章的按钮放在右上角
* [x] 编辑文章时 pathname 不可修改
* [x] 文件上传，主要是图片上传。上传到 www/static/upload 目录下。后续考虑支持 七牛、又拍云
* [x] 文章列表页面要有分页
* [x] 文章列表页面不显示分类，需要显示的有：标题、作者、状态、创建日期、修改日期、操作
* [x] 添加文章页面，二级分类的样式显示不正确
* [x] 添加文章页面，发布日期点击后要隐藏【还需要输入时间，这个需求不做】
* [x] 添加分类页面，分类已经存在时，错误信息显示不正确
* [x] 添加分类页面，父级分类里只显示一级分类（不能显示二级分类）
* [x] 添加标签页面，标签已经存在时，错误信息显示不正确
* [x] 权限校验
* [x] 修改帐号信息时修改密码的问题
* [x] 系统设置 - 基本设置 - LOGO 后面添加个图片上传的按钮
* [x] 系统设置支持设置 favicon 的功能 - 在 options 表里的 key 为 favicon
* [x] 添加页面支持从 url 中读取 pathname，如： /admin/page/create?pathname=about
* [x] 文章列表里把页面也显示出来了
* [x] 添加统计代码的配置
* [x] 文章列表页没有显示作者
* [x] 文章列表页文章状态只显示了草稿，其他状态也要显示
* [x] 文章编辑报错
* [x] 添加文章页面样式，占满页面区域
* [x] 文件上传后显示的 链接文本 改为本地的文件名
* [x] 文件上传 - 网络抓取，如果地址不合法后，没有显示报错信息
* [x] 新增文章编辑区域 全屏 样式问题
* [x] 新增或者编辑文章时，定时将内容保存到 LocalStorage 中，避免异常情况导致丢失。保存成功后清除 LocalStorage 内容。打开时如果 LocalStorage 中有内容提示是否从 LocalStorage 中恢复。
* [x] 添加分类和添加标签页面 将表单宽度设置短点
* [x] 右上角 -> 修改密码
* [x] 编辑、新建不刷新的问题
* [x] 安装时从 wordpress 里导入数据
* [x] 文章/页面  编辑时，标题修改后显示 [Object Object]
* [ ] 需要支持评论的配置 - disqus 还是多说，并且要配置对应的名字
* [ ] 系统设置 - LOGO 设置，添加个是否显示为圆角，默认勾选，保存字段为 logo_radius 值为 1 或者 0，默认为 1
* [ ] 页面列表里添加 创建时间、修改时间、状态 列
* [ ] 顶部面包屑 第二个 点击后页面空白
* [x] 左侧功能列表的 icon 现在没有对应，可以找下 css 里对应的 class
* [x] 分页用大一号的样式，现在有点太小了
* [ ] 文章列表添加搜索的功能，使用数据库的 LIKE 实现即可
* [ ] 文章编辑器，切换为第一个模式，修改后自动切换为第二个模式
* [ ] 文章编辑器，默认切换到第一个模式吧，不然编辑区域太小了

### 前台

* [x] 评论显示
* [x] 支持多主题的设计
* [x] 同步评论数
* [x] 标签对应的文章列表页面
* [x] 分类对应的文章列表页面
* [x] 页面不存在的错误提示
* [x] 分页
* [x] 小屏幕小的显示问题
* [x] 编译脚本
* [x] 增加安装页面