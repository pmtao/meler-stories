# 有声绘本故事屋

网站：https://meler-stories.melerpaine.com/

这里只放网页（HTML），由 GitHub Pages 从 `main` 分支根目录发布；音频、插图、动图短片放在 Cloudflare Pages 项目 `meler-stories-assets`（https://meler-stories-assets.melerpaine.com/），网页运行时按路径去那里取。

内容由 `children-stories/` 生成，不要直接改这里的文件；更新用 `children-stories/tools/publish.sh`。
`CNAME` 是自定义域名，不要删。
