<a href="https://blog.csdn.net/xianyu120"> <img src="https://img.shields.io/badge/csdn-博客-purple.svg" alt="CSDN" /></a> 
<a href="https://space.bilibili.com/399102586"> <img src="https://img.shields.io/badge/bilibili-%E8%A7%86%E9%A2%91-black.svg" alt="B站" /></a> 
 <a href="https://github.com/xianyu110"> <img src="https://img.shields.io/badge/github-github-yellow.svg" alt="github" /></a> 
     <a href="#QQ">
        <img src="https://img.shields.io/badge/QQ:1002569303-green.svg" alt="1002569303" />
    </a>
## Maynor的大模型网站
### 平平无奇的缝合怪


<iframe src="https://chat.jja8.cn/web/NewBingGoGo.html" width="400" height="650" title="newbing-画图"></iframe>  

<iframe src="https://ai.w3school.top/claude/" width="400" height="650" title="Claude网页版"></iframe>   

<iframe src="https://chat2.jinshutuan.com/#/chat/1685520884858" width="400" height="650" title="联网搜索"></iframe>

<iframe src="https://gptbot2.icu" width="400" height="650" title="GPT4"></iframe> 

<html>
<head>
<meta charset="utf-8">
<title>GPT问答</title>
</head>
<body>
<h1>GPT问答Demo</h1>
<p>输入你的问题或句子,回车提交:</p>
<input id="prompt">
<button onclick="sendQuery()">发送</button>
<p id="response"></p>
<script>
function sendQuery() {
var prompt = document.getElementById("prompt").value;
var url = "https://lgjkdppecfcr.cloud.sealos.io/ask?prompt=" + prompt + "&model=forefront";
fetch(url)
.then(response => response.text())
.then(data => {
document.getElementById("response").innerText = data;
})
}
</script>
</body>
</html>

### [个人知识库](http://125.94.145.128:3000/)
### [讯飞星火](https://xinghuo.xfyun.cn/desk)
### [文心一言](https://yiyan.baidu.com/welcome)
### [通义千问](https://tongyi.aliyun.com/)

<style>
/* 大于等于 1000px 屏幕 */  
@media (min-width: 1200px) { 
  iframe {
    width: 400px;
    height: 650px;
  }
}
/* 小于 1200px 屏幕 */
@media (max-width: 999px) { 
  iframe {
    width: 100%;
    height: 120%;
  }
}
</style>

