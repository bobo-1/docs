# flow.ci 文档写作规范

1、推荐 MD 编辑器：[ LightPaper 点击下载 ](http://lightpaper.42squares.in/)

2、MD 文件命名举例：

```·
flow.ci 简介 ：intro_ 开头
安装部署章节：cf_
快速入门：quick_
yml 配置文件：yml_
管理员文档：admin_
```

3、内容书写：

- 页面内只能包含两级标题，如下

```·
# 一级标题 （ 用于章节标题 ）
### 二级标题 （ 用于章节子标题 ）
```

- 英文与中文前后保持一个空格。

4、如果二级标题需要添加 ID（方便引用），如下方式：

```.
### <a name="whats_flowci"> flow.ci 是什么？</a>

whats_flowci 是二级标题 ID
```

5、页面底部添加章节导航 上一节 & 下一节：

```·
<a id="bom" href="./intro_framework.md">下一节：flow.ci 整体架构 </a>
```

6、页面底部导入页面使用 CSS（直接复制即可） ：

```·
<link rel="stylesheet" rev="stylesheet" href="flow.css" type="text/css"/> 
```
7、页面如需引入特定CSS，请在 flow.css 文件中添加。

8、页面本地图片暂存文件夹： pics

9、页面引用图片网络存储地址：

```·
https://shimo.im/doc/Wz4XE30WokID9G5y?r=7G9J1E
```











