# Moonbound-Serpent---theme
JiKook ao3 skin
## 快速开始

1. 登录 [Archive of Our Own（AO3）](https://archiveofourown.org/)。
2. 在 GitHub 打开 [`ao3-jikook-black-white-site-skin.css`](ao3-jikook-black-white-site-skin.css)。
3. 点击文件页面右上角的 **Raw**，然后复制页面中的全部 CSS 内容。
4. 在 AO3 中打开 **Dashboard → Skins → My Site Skins → Create Site Skin**。
5. 填写皮肤名称，把 CSS 粘贴到 **CSS** 输入框。
6. 点击 **Submit** 保存，然后点击 **Use**（或 **Apply**）启用皮肤。

保存后刷新 AO3 页面即可看到效果。第一次使用通常几分钟内就能完成。

## 详细操作步骤

### 1. 从 GitHub 复制 CSS

推荐使用 GitHub 的 Raw 页面复制，这样不会把 GitHub 页面上的文件名、行号或 Markdown 格式一起复制进去。

1. 打开本仓库中的 `ao3-jikook-black-white-site-skin.css`。
2. 点击 **Raw**（部分 GitHub 页面会显示为 **Copy raw file**）。
3. 在 Raw 页面按 `Ctrl+A` 全选，再按 `Ctrl+C` 复制。
4. 确认复制内容从 CSS 第一行开始，到文件最后一行结束。

粘贴到 AO3 时只粘贴 CSS 本身，不要添加以下内容：

- Markdown 代码围栏（例如三反引号加上 `css`）；
- HTML 标签，例如 `<style>...</style>`；
- README 中的说明文字。

### 2. 在 AO3 创建 Site Skin

你需要先登录 AO3 账号，然后按以下路径进入创建页面：

**Dashboard → Skins → My Site Skins → Create Site Skin**

在创建表单中填写：

- **Title**：填写一个容易辨认的名称，例如 `Jikook Black & White`。
- **CSS**：粘贴刚才复制的完整 CSS。
- **Media**：保持默认即可，让皮肤适用于常规设备；如果页面提供媒体条件选项，不要随意填写手机专用条件。
- **Public skin**：不需要公开时保持未勾选。只勾选公开选项，才会把皮肤提交为可供其他 AO3 用户使用的公共皮肤。

确认 CSS 已完整粘贴后，点击页面底部的 **Submit**。

### 3. 启用皮肤

创建成功后，打开 **My Site Skins**，找到刚创建的皮肤，点击 **Use** 或 **Apply**。然后刷新 AO3 页面。

如果没有立即看到变化：

1. 确认皮肤状态显示为正在使用；
2. 强制刷新页面（Windows/Linux：`Ctrl+F5`，macOS：`Cmd+Shift+R`）；
3. 确认浏览器没有启用会覆盖 AO3 CSS 的扩展或其他用户样式。

## 停用或切换回 AO3 默认样式

进入 **Dashboard → Skins → My Site Skins**，在当前皮肤旁边选择 **Disable**、**Stop Using** 或切换到其他 Site Skin。停用皮肤不会删除 CSS，之后仍可以重新启用。

常见问题

### AO3 提示 CSS 无法保存

请依次检查：

1. 是否复制了整个 CSS 文件，而不是只复制可见的一部分；
2. 是否误粘贴了 Markdown 三反引号代码围栏或 `<style>` 标签；
3. 是否把说明文字粘贴进了 CSS 输入框；
4. 是否把多个 CSS 文件直接拼接在一起；
5. 错误信息中是否指出了某一条不被 AO3 允许的 CSS 属性。按提示删除或修改该属性后再保存。

### 保存成功但页面没有变化

确认已经点击 **Use/Apply**，然后刷新页面。也可以暂时停用其他 Site Skin，避免多个皮肤同时覆盖样式。

### 图标或背景没有显示

这通常是外部图片地址无法访问、图片直链失效或浏览器扩展拦截了图片请求。检查图片地址是否仍能直接打开，并确认地址以 `https://` 开头。

### 我应该创建 Site Skin 还是 Work Skin？

本仓库的主 CSS 用于修改整个 AO3 网站界面，所以应创建 **Site Skin**。Work Skin 只用于改变某一篇作品的排版，不能完整应用这套网站界面样式。

## 参考

- [AO3：Skins and Archive Interface FAQ](https://archiveofourown.org/faq/skins-and-archive-interface)

## 许可与使用

这是个人 AO3 界面样式项目。使用、修改或分享修改版时，请保留原作者信息，并检查 CSS 中引用的图片素材是否允许再分发。
