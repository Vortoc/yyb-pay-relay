# yyb-pay-relay

yyb 收款中转页（GitHub Pages）。源码在 yyb 仓库 `relay/`，本仓库只做发布，不存任何收款数据。

页面读取 URL `#a=<yyb地址>&t=<票据>`，从 yyb 拉待收单，在微信里拉起 requestMerchantTransfer 并回报结果。没有参数时可手动粘贴收款单。
