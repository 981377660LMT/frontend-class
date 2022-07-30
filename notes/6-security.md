1. 正则表达式引起的 ReDos
2. XSS
   永远不要相信用户的提交内容
   永远不要将用户的提交内容直接转换成 DOM
3. iframe 攻击(CSRF 的一种)
   利用 iframe 可以发出同源请求的特点
   防御方法:
   响应头部设置 `X-Frame-Options`
   DENY:不能加载 iframe
   SAMEORIGIN:必须同源页面才能加载 iframe
