# 如何访问 GitHub

由于服务器不在国内及 GFW 封锁等，该网站在部分地区 (特别是大多数国内地区) 加载较为缓慢，有时可能显示报错「连接超时」「无法找到服务器 IP 地址」等。

以下方法或许可以加速访问。不过，如果没有效果，也请勿苛责。

## CLI & 客户端

对于访问仓库内容，[Git](https://git-scm.com/downloads) 是极好的方式。**Git**Hub 本身即基于 Git。  
至少在使用 SSH URL 时，Git 的网速可达 MB/s 量级。

[GitHub CLI](https://cli.github.com/) 亦是如此，但其功能与 Git 并非完全重叠。

GitHub 客户端在某些场景似乎使用了不同的链接通路，至少在 Android 客户端上，加载速度相对较快。(但 Releases 下载速度和图片加载速度依旧很差)  
  客户端分为[桌面版](https://github.com/apps/desktop)和[移动版](https://github.com/mobile)。Android 移动端需用特殊方式获取安装包。

## 修改 Hosts

实践之一为 [GitHub520](https://github.com/521xueweihan/github520) 项目。

## 某些加速软件

加速原理通常是本地反代、域前置等。

实践包括 [Watt Toolkit (原名 Steam++)](https://steampp.net/)、[steamcommunity 302](https://www.dogfight360.com/blog/686/) 等。在下载后，可能还需要进行一定设置才能有加速效果。

## 镜像站

实践之一为 [KGitHub 镜像站](https://kkgithub.com/)。  
以下来自 [KGitHub Help](https://help.kkgithub.com/questions/) (虽然这似乎不完全算「存在的问题」……)：

> 本站目前存在的问题：
>
> 1. 不能注册
> 2. 不能上传文件，可以登录，可以在线编辑
> 3. 来自 raw.githubusercontent.com 的下载可使用 raw.kkgithub.com 替代

## 代理加速下载网站

只需要下载时可以使用。

实践之一为 [GitHub Proxy](https://mirror.ghproxy.com/)。

## CDN

只需要获取仓库内容时可以使用。

实践之一为 [jsDelivr](https://www.jsdelivr.com/)。

链接格式为：

- `https://cdn.jsdelivr.net/gh/<用户名>/<仓库名>/`
- `https://www.jsdelivr.com/package/gh/<用户名>/<仓库名>`

局限性：

- 无法提供图片和可执行程序加速服务
- 不能加载大小大于 50 MB 的仓库文件列表，但仍然可以通过直接输入文件路径进行下载
- 使用「Low latency “Near China” network」(低延迟的「临近中国」的网络) 进行服务，但仍可能无法访问  
  如有此类情况发生，可以使用以下非官方的国内镜像站点访问：  
  `https://cdn.jsdmirror.com/gh/<用户名>/<仓库名>/`

## VPN

俗称「魔法」「梯子」。

不到万不得已不建议使用，可能违反相关法律。  
群文档亦不对这一方式提供指导。