# 品优商城项目

这个项目是学完HTML5，继模仿天猫商城项目后的第二个静态网页项目。

该项目包含三个静态页面：首页、手机商品详情页、注册页面。

对HTML和CSS相关知识作了一个总结以及项目训练。

## 项目结构

- images		样式图片
- css				样式
  - base.css			CSS初始化
  - common.css	CSS公共样式
- upload		产品图片  
- js					脚本
- fonts			字体类

- index.html		首页
- list.html        列表页(只做了手机页面的)
- register.html     注册页面

- favicon.ico		网站图标（必须是ico文件）



# 项目习得经验

## 网站TDK三大标签SEO优化

1. title

   ```html
   <title>品优商城-综合网购首选-正品低价、品质保障、配送及时-轻松购物</title>
   ```

2. description

   ```html
   <meta name="description" content="品优商城-专业的综合网上购物商城,销售家电、数码通讯、电脑、家居百货、服装服饰、母婴、图书、食品等数万个品牌优质商品.便捷、诚信的服务，为您提供愉悦的网上购物体验!">
   ```

3. keywords

   ```html
   <meta name="keywords" content="网上购物,网上商城,手机,笔记本,电脑,MP3,CD,VCD,DV,相机,数码,配件,手表,存储卡,品优商城">
   ```

## LOGO SEO 优化

1. logo里面放入**h1**标签，目的是提权，告诉搜索引擎

2. h1里放入 **链接**，用来返回首页，logo的背景图片给链接

3. 为了搜索引擎收录，链接里要放入 **文字（网站名称）**，但是文字不要显示出来

   - 方法1： 淘宝

     ```css
     text-indent:-9999px;
     overflow:hidden;
     ```

   - 方法2：京东

     ```css
     font-size:0;
     ```

4. 最后给链接一个 **title** 属性，鼠标移入时可以看到提示文字



## 文字溢出显示为省略号

```css
overflow: hidden;
white-space: nowrap;
text-overflow: ellipsis;
```



## 免费空间远程服务器

http://free.3v.do

需要激活FTP