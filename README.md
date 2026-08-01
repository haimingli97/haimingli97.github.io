# 个人网站 — 部署与维护

## 文件说明

```
index.html      首页
research.html   研究
teaching.html   教学
style.css       样式（四个页面共用，改这一个文件就能改全站外观）
photo.jpg       你的照片（需要你自己放进来）
cv.pdf          你的 CV（需要你自己放进来）
papers/jmp.pdf  JMP 全文（以后放）
```

## 今天要做的事（约 15 分钟）

1. 注册 GitHub 账号（如果还没有）。
2. 新建一个仓库，名字必须是 `你的用户名.github.io`。
   比如用户名是 `haimingli`，仓库名就是 `haimingli.github.io`。
   设为 Public。
3. 在仓库页面点 **Add file → Upload files**，把这个文件夹里的所有文件拖进去，
   点 Commit changes。
4. 等两三分钟，访问 `https://你的用户名.github.io`，网站就上线了。

不需要装任何软件，不需要用命令行。

## 以后怎么改内容

在 GitHub 网页上打开要改的 `.html` 文件，点右上角的铅笔图标，
直接改文字，改完点 Commit changes。一两分钟后网站自动更新。

## 待填项

所有需要补的地方都用 `<span class="tbd">[TBD — ...]</span>` 标记，
在网页上会显示成黄色高亮，很好找。填好内容后把整个
`<span class="tbd">...</span>` 替换成实际文字即可。

黄色高亮只是给你自己看的提示。**上线前确保没有遗漏的 TBD**，
或者临时把 `style.css` 里 `.tbd` 的 `background` 改成 `transparent`。

## 关于域名（可以以后再说）

`用户名.github.io` 完全够用，很多经济学家就一直用这个。
如果以后想换成 `haimingli.com` 这类域名，在 Namecheap 或
Cloudflare 买一个（约 12 美元/年），然后在仓库
Settings → Pages → Custom domain 里填上就行。网址会自动切换。
