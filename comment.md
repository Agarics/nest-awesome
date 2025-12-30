## 评论组件

### [Utterances](https://utteranc.es)

https://github.com/utterance/utterances

特点：基于 GitHub Issues 的评论工具，将评论存储在仓库的 Issue 中。

优点：完全免费，无需后端，数据由 GitHub 托管，适合技术博客。

缺点：用户需有 GitHub 账号才能评论，功能较简单（无邮件通知）

### [giscus](https://giscus.app/)

https://github.com/giscus/giscus

特点：类似 Utterances，但基于 GitHub Discussions，支持 Markdown 和实时预览。

优点：完全免费，与 GitHub 生态深度集成，适合开发者社区。

缺点：仅限 GitHub 用户使用，无邮件提醒。

### [Twikoo](https://twikoo.js.org/)

https://github.com/twikoojs/twikoo

特点：基于云函数的轻量评论系统，支持 MongoDB 数据库，提供评论管理、邮件通知、反垃圾、Markdown 等功能。

优点：部署简单（如 Vercel 一键部署），免费且数据可控，界面简洁。

缺点：依赖云服务（如 Vercel/MongoDB），免费资源有限，需基础技术配置能力。

### [Waline](https://waline.js.org/)

https://github.com/walinejs/waline

特点：由 Valine 衍生而来，支持后端存储（MySQL、SQLite、MongoDB 等），具备完整的评论功能（邮件通知、反垃圾、Markdown 等）。

优点：免费开源，支持自托管（Vercel/CloudBase 等），可绑定域名，数据自主可控。

缺点：需自行部署后端服务，依赖云平台资源。

### [Remark42](https://remark42.com/)

https://github.com/umputun/remark42

特点：注重隐私的轻量级自托管评论系统，支持匿名评论、社交账号登录、Markdown 和反垃圾。

优点：完全免费且开源，无需数据库（使用文件存储），支持 Docker 部署。

缺点：需要自备服务器资源，配置稍复杂。

### [Cusdis](https://cusdis.com/)

https://github.com/djyde/cusdis

特点：极简的开源评论系统，支持自托管（Vercel/Heroku）或使用官方免费服务。

优点：轻量无依赖，支持 Webhook 通知，数据可导出。

缺点：功能较少，适合小型网站。

> 技术博客/开源项目：优先选 Utterances 或 Giscus（GitHub 生态友好）。
注重隐私与自托管：推荐 Remark42 或 Waline。
简单需求：尝试Twikoo
极简需求：尝试 Cusdis。
