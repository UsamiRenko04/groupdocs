# 设置搜索引擎

> 此页面需要改进可读性。

如果需要类似于「输入关键词就能直接跳转到相应页面」的页面直达功能，可以向浏览器添加搜索引擎，以搜索引擎的形式实现页面直达。
下文如无说明，均以「中文 Minecraft Wiki」(简称为 Wiki) 为例。

## 需求描述

- 想要在搜索栏输入「告示牌」，按下回车后直接进入 [Wiki 上的告示牌页面](https://zh.minecraft.wiki/w/%E5%91%8A%E7%A4%BA%E7%89%8C)，而不必：
  - 在其它搜索引擎搜索「告示牌 mc wiki」→ 寻找 Wiki 页面 → 进入 Wiki 页面
  - 或进入 Wiki → 在 Wiki 内搜索「告示牌」→ 进入 Wiki 页面
  - 或手动输入 `zh.minecraft.wiki/w/告示牌`
- 想要在搜索栏输入「专辑」，按下回车后直接进入 [Wiki 上「专辑」的搜索结果页面](https://zh.minecraft.wiki/w/Special:%E6%90%9C%E7%B4%A2?search=%E4%B8%93%E8%BE%91)，而不必：
  - 在其它搜索引擎搜索「专辑 mc wiki」
  - 或进入 Wiki → 在 Wiki 内搜索「专辑」
  - 或手动输入 `zh.minecraft.wiki/w/Special:搜索?search=专辑`

## 操作方法

可以将 Wiki 添加为搜索引擎。同时，可以为该搜索引擎添加被称为「快捷方式」(Edge) 或「关键词」(Firefox) 的参数，这样只需在搜索时输入 `@wiki 专辑` 一类的关键词就会自动调用 Wiki 搜索「专辑」。
不同浏览器的不同版本在不同平台上可能有不同的操作方式，请以自己浏览器的实际操作方式为准，或参阅浏览器的官方帮助文档 (如有)。

### 链接资源

Wiki 的可用链接资源包括：

- `https://zh.minecraft.wiki/w/Special:%E6%90%9C%E7%B4%A2?search=%s`。该链接会调用搜索，如果有可用（可近似认为名称相同）的页面会直接重定向，如果没有则会显示「搜索结果」页面。
- `https://zh.minecraft.wiki/w/Special:%E6%90%9C%E7%B4%A2/%s`。与上方链接相同，长度稍微短一点。
- `https://zh.minecraft.wiki/w/%s`。该链接会直接指向可用的页面，但对于不可用的页面则会显示「此页面目前没有内容」。*不推荐使用此链接资源，现在网速快了又不差那一次重定向。*

### 配置方法（官方帮助文档）

- [Microsoft Edge 配置方法](https://support.microsoft.com/zh-cn/microsoft-edge/%E5%9C%A8-microsoft-edge-%E4%B8%AD%E6%9B%B4%E6%94%B9%E9%BB%98%E8%AE%A4%E6%90%9C%E7%B4%A2%E5%BC%95%E6%93%8E-cccaf51c-a4df-a43e-8036-d4d2c527a791)
- [Mozilla Firefox 配置方法](https://support.mozilla.org/zh-CN/kb/add-or-remove-search-engine-firefox)
- [Mozilla Firefox for Android 配置方法](https://support.mozilla.org/zh-CN/kb/%E5%9C%A8%20Firefox%20for%20Android%20%E4%B8%AD%E7%AE%A1%E7%90%86%E6%88%91%E7%9A%84%E9%BB%98%E8%AE%A4%E6%90%9C%E7%B4%A2%E5%BC%95%E6%93%8E)
- [Google Chrome 配置方法（国内无法访问）](https://support.google.com/chrome/answer/95426?hl=zh-Hans&co=GENIE.Platform%3DDesktop)