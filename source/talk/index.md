---
title: 说说
cover: true
date: 2021-02-05 15:08:00
---
<!-- 引用 HexoPlusPlus_Talk组件 -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/HexoPlusPlus/HexoPlusPlus@1.0.4/dist/talk.css" /> 
<script src="https://cdn.jsdelivr.net/gh/HexoPlusPlus/HexoPlusPlus@1.0.4/dist/talk_user.js"></script>
<!-- 创建HexoPlusPlus_Talk容器 -->
<div id="hpp_talk"></div>
<!-- 激活HexoPlusPlus_Talk -->
<script>
new hpp_talk({
id:"hpp_talk",//容器id
domain: "admin.yzsdcm.top",//您的HexoPlusPlus域名，如blogadmin.cyfan.top
limit: 10,//单次获取的最多条数
start: 0//从第几条开始
});
</script>
