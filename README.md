# 微金所

## 目录结构

- wjs.............项目文件夹
  - js...................js文件目录      
  - lib..................第三方框架目录
  - images...............图片文件目录
  - css..................css文件目录
  - fonts..............字体图标目录
  - favicon.ico..........网站图标
  - index.html...........站点入口

```html
<link rel="icon" href="favicon.ico" type="image/x-icon" />
```

响应式布局：bootstrap插件的使用、less进行css预编译

## 页面结构

```html
<!--头部开始-->
<div class="wjs_header"></div>
<!--头部结束-->

<!--导航开始-->
<div class="wjs_nav"></div>
<!--导航结束-->

<!--轮播图开始-->
<div class="wjs_banner"></div>
<!--轮播图结束-->

<!--信息开始-->
<div class="wjs_info"></div>
<!--信息结束-->

<!--产品开始-->
<div class="wjs_product"></div>
<!--产品结束-->

<!--新闻开始-->
<div class="wjs_news"></div>
<!--新闻结束-->

<!--合作伙伴开始-->
<div class="wjs_partner"></div>
<!--合作伙伴结束-->
```



向css文件中引入图标字体模板：

```css
@font-face {
  	font-family: 'iconfont';
    src: url('iconfont.eot');
    src: url('iconfont.eot?#iefix') format('embedded-opentype'),
    url('iconfont.woff') format('woff'),
    url('iconfont.ttf') format('truetype'),
    url('iconfont.svg#iconfont') format('svg');
}
```

