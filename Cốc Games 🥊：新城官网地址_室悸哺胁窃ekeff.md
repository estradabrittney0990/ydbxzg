新城官网地址【Q-——333307——】新城官网地址【 辋芷《888yx●vip》 】
新城官网地址【Q-——333307——】新城官网地址【 辋芷《888yx●vip》 】

 从0到1搭建个人技术博客：GitHub Pages + Hexo 保姆级教程

> 还在羡慕大佬的炫酷博客？其实你离技术博主只差这一个部署教程。

大家好，我是专注于分享干货的编程爱好者。很多朋友问我，如何在不买服务器、不花一分钱的情况下，拥有一个专属的个人技术博客。今天这篇 GitHub Pages 搭建教程，将手把手带你完成从环境配置到免费部署的全过程，全文干货无尿点，建议先收藏再阅读。

 为什么选择 GitHub Pages + Hexo？

在众多博客方案中，这套组合是搜索引擎收录最友好的方案之一。GitHub Pages 提供免费静态托管，支持绑定自定义域名，且天生对 SEO优化 友好；而 Hexo 作为老牌静态博客框架，有着庞大的插件生态和极高的渲染速度。无论是为了沉淀知识还是打造个人IP，这都是性价比最高的选择。

 第一步：环境准备与安装

请确保你的电脑已安装 Node.js（建议版本16+）和 Git。打开终端，依次执行以下命令完成 Hexo 的全局安装：

```bash
npm install hexo-cli -g
```

 第二步：本地初始化博客项目

在你喜欢的目录下执行初始化命令，这里以 `myblog` 为例：

```bash
hexo init myblog
cd myblog
npm install
```

启动本地预览服务，访问 `http://localhost:4000` 即可看到默认博客页面，也可以结合 Volantis 或 Next 主题 进行个性化定制，让你的界面更符合技术博客风格。

 第三步：关联 GitHub 仓库并部署

1. 在 GitHub 上新建一个仓库，命名为 `你的用户名.github.io`（必须完全匹配）。
2. 安装自动部署工具：
   ```bash
   npm install hexo-deployer-git --save
   ```
3. 打开站点根目录下的 `_config.yml` 文件，在底部 `deploy` 区域添加你的仓库地址。

部署只需一行命令：

```bash
hexo clean && hexo g && hexo d
```

浏览器访问 `https://你的用户名.github.io`，你的博客就正式上线啦！

 高频问题排查与互动

问：部署后样式丢失怎么办？ 大概率是仓库地址填写错误，检查 `_config.yml` 中 `url` 和 `root` 是否与你的访问路径一致。

问：想被百度收录需要做什么？ 建议在 `head` 中主动添加百度站长平台的主动推送代码，并保持每周更新原创内容。

---

如果你在安装过程中遇到任何报错，或者有更好的主题推荐，欢迎在评论区留言，我看到后会逐一答复。如果这篇博客搭建教程对你有帮助，别忘了点赞和分享给身边需要的小伙伴，你们的支持是我持续输出干货的最大动力！

相关推荐：

https://github.com/brockchristina3892/lorsbq/blob/main/C%E1%BB%91c%20Games%20%F0%9F%A5%8A%EF%BC%9A%E6%96%B0%E5%9F%8E%E4%BB%A3%E7%90%86_%E8%B0%AE%E7%85%A7%E7%A8%9A%E4%BA%91%E5%88%88ioobb.md

<img src="https://i.postimg.cc/ZRr7z9hR/xincheng-00010.png" />

相关推荐：

https://github.com/brockchristina3892/lorsbq/commit/c4b60d97046df52cadb6d135ca21222fb6f639ee

<img src="https://i.postimg.cc/ncn5Z1rf/xincheng-00003.png" />
相关推荐：

https://github.com/estradabrittney0990/ydbxzg/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E6%96%B0%E5%9F%8Eapp_%E6%8E%A8%E5%A0%A4%E6%92%BC%E5%8F%AD%E5%85%B1xjdfm.md

<img src="https://i.postimg.cc/sXp6CBRv/xincheng-00011.png" />
相关推荐：

https://github.com/estradabrittney0990/ydbxzg/commit/840135846f84474e6bec9878e2b76a60117bf709

<img src="https://i.postimg.cc/wvhfYtdM/xincheng-00005.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
