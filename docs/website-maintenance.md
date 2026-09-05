# 主页维护

个人主页：`_pages/about.md`。课题组主页：`_pages/group.html`。课题组名称为 **SUGAR (Soochow University Group of Advanced Retrieval)**。

## 日常只需改两个地方

1. 新论文：在 `_pages/about.md` 的 Conference and Journal Papers 添加一项，沿用现有标题行和作者行。课题组页直接链接到这个列表，无需复制论文。
2. 新消息：在 `_data/news.yml` 顶部添加日期和一句英文。个人主页和课题组页自动共用这些消息。日期请保留引号。

```yaml
- date: "2026.09"
  text: 'Your news here. **Bold text** is supported.'
```

课题组名称、简介、三个方向和成员名单集中在 `_data/group.yml`。成员照片准备好后，只需把对应成员的 `image` 改成 `images/` 下的文件路径；成员分组顺序和姓名也在这里维护。联系邮箱共用 `_config.yml` 的 `author.email`。

课题组页不重复维护论文列表，论文入口直接回到个人主页；News 也只维护一份。这样以后通常只需要编辑 `_data/news.yml` 和 `_data/group.yml`。

统一视觉样式：`assets/css/research.css`。顶部菜单：`_data/navigation.yml`。

本轮只修改源码并提供本地预览。上线仍通过原有 GitHub Pages 提交流程。
