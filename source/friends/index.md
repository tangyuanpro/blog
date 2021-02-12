---
layout: friends # 必须
title: 我的朋友们 # 可选，这是友链页的标题
cover: true
---

{% issues sites | api=https://api.github.com/repos/tangyuanpro/tangyuanpro.github.io/issues?sort=updated&state=open&page=1&per_page=100 | group=version:来自基安的小伙伴们,暂时离开的朋友们 %}

<!-- more -->

施工中
