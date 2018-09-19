### 重构功能清单：

1.重构首页内容列表的显示方式，分为：右图模式、大图模式、双图模式；

2.调整首页轮播图大小以及显示样式；

3.重构文章详情页页头部分，增加了thumhub_img图片，并优化了标题部分的显示样式；

4.重构专题页的列表显示排序样式，采用大图模式，并修复了缩略图的裁剪方式；

5.重头了readlog页面的list显示方式，去除正序列表，改成有序列表；

6.个人版本无法使用赞赏功能，所以去除了pay文件夹；


### 功能清单：

1.缩略图的方式显示文章列表，包括显示文章分类和发布时间，加载分页。

2.在首页用轮播方式显示置顶文章。

3.显示文章分类（专题），包括显示分类的封面图片（新版本更新：专题列表重新优化显示方式）。

4.显示文章内容页，包括文章站内链接跳转，站外链接复制到剪切板，显示猜你喜欢的相关文章。

5.显示文章评论，提交评论和回复评论，加载评论分页，显示微信用户评论者的头像。

6.显示文章排行

7.显示wordpress“页面”类文字（关于页面）。

8.对文章内容的全文搜索。

9.文章页面的分享、转发，复制。

10.WordPress 插件的配套功能。

11.文章浏览数显示及更新。

12.文章微信用户点赞及点赞的微信用户头像显示。

13.通过微信支付对文章赞赏。

14.赞赏后发送模版消息。

15.web-view内嵌网页跳转。

16.回复评论发送模板消息。

17.专题订阅。

18.文章海报（分享微信朋友圈的卡片）。

### 原作者开源地址

https://github.com/iamxjb/winxin-app-watch-life.net

技术支持：https://www.qiyuwg.com/4994.html

### 小程序配套wordpress插件：

本小程序完整使用需要配合原作者（imxjb）编写的wordpress插件wp-rest-api-for-app，才能完整使用，插件下载地址： https://github.com/iamxjb/wp-rest-api-for-app

### 小程序配套赞赏（微信支付）功能服务端程序：

本小程序赞赏功能需要配合原作者（imxjb）编写微信支付服务端php程序，才能使用，程序下载地址： https://github.com/iamxjb/weixin-app-wxpay

### 开源协议：MIT

### 技术支持微信：ryan_yuu


### 安装使用说明文档

<a href="https://www.watch-life.net/wordpress/weixin-app-install.html" target="_blank" rel="noopener">WordPress版微信小程序安装使用说明</a>


<a href="https://promotion.aliyun.com/ntms/yunparter/invite.html?userCode=ds9psss5"><img src="https://www.qiyuwg.com/wp-content/uploads/2018/04/F001Nl1PmClh000Tfc8R.png"></a>
	                                            <h2 class="title-article">最新版wordpress开发资讯微信小程序</h2>
<p>小程序从去年开始火热起来，微信的轻应用一栏，大大小小的出现了各式各样的传统App的衍生品。很多大的App也开始发力布局，并想要抢先在这一块丰腴的蛋糕上，占有一席之地。</p>
<p>那什么是小程序呢？</p>
<p>什么是微信小程序？<strong>简单而言，它就是一种不需要下载安装即可使用的应用，它实现了应用的“触手可及”的梦想，用户扫一扫或者搜一下即可打开应用。也体现了“用完即走”的理念，用户不用关心是否安装了太多应用的问题。应用将无处不在，随时可用，但又无需安装卸载。</strong></p>
<p>但是这个依托于第三方小程序应用平台生成的小程序终究是托管于第三方应用平台，<strong>所有的模板都是一模一样的，且自己没有任何的自主开发权限，想要修改一下版式、图标什么的都不行，</strong>实在是差强人意。</p>
<p>那到底如何才能搭建（零基础创建）一款完全属于自己的微信小程序呢？</p>
<p>功夫不负有心人，历经半个多月时间，我基于Github的一位大神的开源项目，结合公共开源的REST API接口，二次开发出<strong>一款完全属于自己的微信小程序</strong>，并且已经成功上线Beta版本，欢迎各位扫描下面的小程序二维码预览体验。</p>
<p>&nbsp;</p>
<p>演示：</p>
<div id="attachment_4951" style="width: 268px" class="wp-caption alignnone"><img class="lazy lazy-hidden" layer-src="//www.qiyuwg.com/wp-content/plugins/a3-lazy-load/assets/images/lazy_placeholder.gif" data-lazy-type="image" data-src="https://www.qiyuwg.com/wp-content/uploads/2018/08/gh_4e21d5c8563e_258.jpg" src="https://www.qiyuwg.com/wp-content/uploads/2018/08/gh_4e21d5c8563e_258.jpg" alt="《最新版wordpress开发资讯微信小程序》" /><noscript><img layer-src="https://www.qiyuwg.com/wp-content/uploads/2018/08/gh_4e21d5c8563e_258.jpg" src="https://www.qiyuwg.com/wp-content/uploads/2018/08/gh_4e21d5c8563e_258.jpg" alt="《最新版wordpress开发资讯微信小程序》" /></noscript></p>
<p class="wp-caption-text">小程序</p>
</div>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><img class="lazy lazy-hidden" layer-src="//www.qiyuwg.com/wp-content/plugins/a3-lazy-load/assets/images/lazy_placeholder.gif" data-lazy-type="image" data-src="https://www.qiyuwg.com/wp-content/uploads/2018/09/IMG_3492.png" src="https://www.qiyuwg.com/wp-content/uploads/2018/09/IMG_3492.png" alt="《最新版wordpress开发资讯微信小程序》" /><noscript><img layer-src="https://www.qiyuwg.com/wp-content/uploads/2018/09/IMG_3492.png" src="https://www.qiyuwg.com/wp-content/uploads/2018/09/IMG_3492.png" alt="《最新版wordpress开发资讯微信小程序》" /></noscript> 
