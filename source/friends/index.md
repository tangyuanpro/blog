---
layout: friends # 必须
title: 我的朋友们 # 可选，这是友链页的标题
cover: true
---
## 大伙伴们

{% issues sites | api=https://api.github.com/repos/tangyuanpro/tangyuanpro.github.io/issues?sort=updated&state=open&page=1&per_page=100&labels=active %}

<!-- more -->

{% timeline 如何添加自己的博客链接 %}

{% timenode 第一步：新建 [Issue](https://github.com/tangyuanpro/tangyuanpro.github.io/issues/) 按照格式填写并提交 %}

```json
{
    "title": "",
    "description": "",
    "screenshot": "",
    "url": "",
    "avatar": ""
}
```

为了提高图片加载速度，建议优化图片尺寸：
1. 建议将图片的高度调整到 `360px` 后下载。
2. 上传到图床并使用此图片链接作为截图链接。

{% endtimenode %}

{% timenode 第二步：等待审核 %}

回来刷新即可生效。

{% endtimenode %}

{% timenode 第三步：刷新 %}

审核成功后回来刷新即可生效。

{% endtimenode %}

{% endtimeline %}

{% note info, 以上文案为Volantis官方友链文案修改而成（滑稽） %}

{% note success, 只要是正规站就会通过（不管是小白还是大佬，备案的或者是没备案的，是放在Github...平台上的……都会通过） %}
