# Amzayo_template_fin_net 哪吒自定义主题

原贴：https://blog.amzayo.com/index.php/archives/29/

## 前言

此项目的目的：
- 一是原帖里的下载地址没法正常下载了，我看了一下旧版本帖子能下载，然后我突发奇想旧的地址用的是旧的CDN，新的地址换了另外一个CDN，我直接改成用旧的CDN域名就能下载了，很神奇。[https://cdn.amzayo.top/static/public/amzayo_template_fin_net.zip](下载地址)
- 二是该项目是二改该主题，在这里感谢Amzayo大佬的制作。

**该项目基本由Clude3.5以及我的前端朋友(工具人)的帮助下二改的，本人不擅长前端，看到史代码轻点喷。**

## 二改特性

- 新增了到期时间显示
- 修改了渲染交换Swap逻辑，如果Swap为0则不渲染
- 新增服务器名字超出宽度时触发浮动文字效果

## 效果图

![1.png](images/1.png)

## 食用方法

1.template里面的文件放到服务端/opt/nezha/dashboard/theme-custom/template目录里面

2.static里面的文件放到服务端/opt/nezha/dashboard/theme-custom/static目录里面

2.重启哪吒面板服务

3.在哪吒面板后台主题选择Custom(local)

4.将 custom.css 里面的内容复制到哪吒面板后台的“自定义代码”文本框里

## 到期时间设置

在后台里面，打开服务器设置，在公开备注添加以下信息
```json
{
   "billingDataMod": {
       "startDate": "2024-11-25T00:00:00+08:00",
       "endDate": "2024-12-25T23:59:59+08:00"
   }
}
```

## 其它说明：

修改顶部左边的图片就是修改static里面的那张名字为head.png的图片，文件名要一致。如果文件名不一致，请去menu.heml第5行修改

站点图标header.html文件的第17行，替换掉https://cdn.amzayo.top/static/public/luban/luban_head.png

底部版权信息footer.html文件的第4到8行，依照demo底部的文字按需替换
