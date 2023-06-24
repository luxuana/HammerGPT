# Pandora-Vercel
本项目克隆自[pandora-vercel](https://github.com/chrysoljq/pandora-vercel)，修改了 [Pandora-Cloud](https://github.com/pengzhile/pandora-cloud) 的代码结构，使其能够在 [Vercel](https://vercel.com) 部署。
`开源项目可以魔改，但请保留原作者信息。确需去除，请联系作者，以免失去技术支持，否则就会这样`
![CROS](https://github.com/JERRY-SYSTEM/ChatGPT_Pandora/assets/106425163/5cb0478f-61dd-4d74-92be-779b528c88b0)
![报错](https://github.com/pengzhile/pandora/assets/106425163/c69504a0-d54f-4b5c-9ffe-e4f3a5d4d61a)
更多说明看官方仓库。

## 一键部署
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FJERRY-SYSTEM%2FChatGPT_Pandora&project-name=chatgpt-pandora&repository-name=chatgpt-pandora&framework=other)
+ 测试网站 [https://chat.lovepcsys.top](https://chat.lovepcsys.top)

## **环境变量**
#### `CHATGPT_API_PREFIX`  
对话 api 请求地址，默认为 `https://ai.fakeopen.com`，可以设置为你的部署后的域名（仅限 vercel），如默认网址 `https://xxxxx.vercel.app`，或其他反向代理地址（任意平台）。

#### `LOGIN_LOCAL`  
是否启用账号密码登录。Pandora 现已支持直接登录，故默认为 `True`或 1。




