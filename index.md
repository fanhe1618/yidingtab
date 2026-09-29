# 一丁新标签 隐私政策 / Privacy Policy

**生效日期 / Effective date:** 2026-09-29
**适用版本 / Applies to:** 一丁新标签 (iTab) 3.8.2 及之后版本 / version 3.8.2 and later

[中文](#中文) | [English](#english)

---

## 中文

### 一、概述

「一丁新标签」（以下简称"本扩展"）是一个浏览器新标签页与书签导航扩展。**我们不运营任何服务器，不收集、不上传、不出售你的个人信息。** 本扩展没有账号系统，没有广告，没有统计分析或行为追踪代码。

### 二、保存在你本地的数据

以下数据仅保存在你浏览器的本地扩展存储（`chrome.storage.local`）中，不会发送给开发者：

- 你创建的书签、文件夹、分区及其排序
- 搜索引擎列表与当前选择
- 外观设置（背景、布局、字号等）；如果你上传了本地背景图片，图片也保存在本地
- 坚果云 / WebDAV 同步配置（服务器地址、用户名、应用密码），仅当你主动填写时才保存
- 通过右键菜单"添加到导航书签"时，临时保存的页面标题与网址（用于弹出添加窗口，使用后即删除）

卸载本扩展后，上述本地数据会随之被浏览器删除。

### 三、本扩展如何使用浏览器权限

| 权限 | 用途 |
| --- | --- |
| `storage` | 在本地保存你的书签和设置 |
| `tabs` | 在你使用"添加到导航书签"时，读取当前标签页的标题和网址，并在添加后切回原页面 |
| `contextMenus` | 提供右键菜单"添加到导航书签" |
| `bookmarks` | 读取浏览器自带书签，用于在新标签页显示书签栏；数据仅在本地显示，不上传 |
| `https://dav.jianguoyun.com/*` | 访问坚果云 WebDAV，用于你主动发起的备份与恢复 |
| 可选主机权限 | 仅当你填写其他 WebDAV 服务器地址时，浏览器会弹窗请求你授权访问该服务器；不授权则不会访问 |

### 四、会向第三方发送的数据

本扩展在以下情况会从**你的浏览器直接**向第三方发送请求（开发者无法看到这些请求）。这些第三方能看到你的 IP 地址和请求内容，其处理方式适用它们各自的隐私政策。

1. **网站图标服务**：为书签自动获取网站图标时，会向以下服务发送该网站的域名或网址：Google（`google.com/s2/favicons`）、DuckDuckGo（`icons.duckduckgo.com`）、`favicon.im`、`api.iowen.cn`、`favicon.cccyun.cc`、`api.7ed.net`。你也可以为书签手动上传图标，避免使用这些服务。
2. **Unsplash 在线壁纸**：只有当你使用"在线图片"功能时，才会向 `api.unsplash.com` 发送你选择的分类关键词，并从 Unsplash 加载图片。
3. **WebDAV 同步（你主动配置时）**：当你点击上传、下载、删除备份，或开启自动备份后，本扩展会把备份文件（书签、文件夹、搜索引擎、外观设置）以及你填写的账号和应用密码（HTTP Basic 认证）发送到**你自己配置的** WebDAV 服务器（默认为坚果云）。备份文件由你的服务商保存，开发者无法访问。
4. **搜索引擎**：你在搜索框中搜索时，页面会跳转到你选择的搜索引擎（如百度、Google、必应等），搜索内容由该搜索引擎按其隐私政策处理。

除上述情况外，本扩展不会与任何第三方共享数据。

### 五、我们不做的事

- 不收集姓名、邮箱、位置、浏览历史或身体、财务、健康等信息
- 不读取或记录你访问的网页内容
- 不出售、出租或用于广告、信用评估、与本扩展功能无关的其他用途
- 不使用远程托管的代码；扩展的全部代码都包含在安装包内

### 六、你的选择与数据删除

- 你可以随时在扩展内编辑、删除书签和设置，或断开同步连接。
- 卸载扩展即可删除本地保存的全部数据。
- 已上传到 WebDAV 服务器的备份，请在你的服务商处（如坚果云）或本扩展的同步面板中删除。
- 不希望向图标服务发送域名，可以为书签手动设置图标。

### 七、数据安全

本地数据存储在浏览器的扩展存储中，受浏览器和操作系统账户保护。与第三方的网络通信使用 HTTPS（你自行填写的 WebDAV 地址除外，建议使用 HTTPS 地址）。请注意，任何能使用你电脑和浏览器账户的人，也可能看到你保存的书签。

### 八、儿童隐私

本扩展不针对 13 岁以下儿童，也不会有意收集儿童的个人信息。

### 九、政策更新

如功能或数据处理方式发生变化，我们会更新本政策并修改上方的生效日期。重大变化会在扩展更新说明中提示。

### 十、联系方式

如对本政策有疑问，请联系：fanhe1618@gmail.com

---

## English

### 1. Overview

"一丁新标签" (iTab) (the "Extension") is a browser extension that replaces the new tab page with a customizable bookmark dashboard. **We do not operate any server, and we do not collect, upload, or sell your personal information.** The Extension has no account system, no advertising, and no analytics or tracking code.

### 2. Data stored locally on your device

The following data is stored only in your browser's local extension storage (`chrome.storage.local`) and is never sent to the developer:

- Bookmarks, folders, partitions and their order that you create
- The list of search engines and your current selection
- Appearance settings (background, layout, font size, etc.), including a background image if you upload one
- WebDAV / Jianguoyun sync settings (server URL, username, app password), saved only if you enter them
- The page title and URL temporarily stored when you use the "Add to navigation bookmarks" context menu (deleted after use)

Uninstalling the Extension removes this local data.

### 3. Permissions and why they are needed

| Permission | Purpose |
| --- | --- |
| `storage` | Save your bookmarks and settings locally |
| `tabs` | When you use "Add to navigation bookmarks", read the current tab's title and URL and switch back to the original tab afterward |
| `contextMenus` | Provide the "Add to navigation bookmarks" right-click menu |
| `bookmarks` | Read your browser bookmarks to display a bookmarks bar on the new tab page; the data is displayed locally and not uploaded |
| `https://dav.jianguoyun.com/*` | Connect to Jianguoyun WebDAV for backup and restore that you initiate |
| Optional host permissions | Only if you enter another WebDAV server, the browser asks you to grant access to that specific server; without your approval, no access happens |

### 4. Data sent to third parties

In the cases below, requests are sent **directly from your browser** to third parties. The developer cannot see them. These third parties can see your IP address and the request content, and handle it under their own privacy policies.

1. **Favicon services:** To fetch website icons for your bookmarks, the domain or URL of the site is sent to: Google (`google.com/s2/favicons`), DuckDuckGo (`icons.duckduckgo.com`), `favicon.im`, `api.iowen.cn`, `favicon.cccyun.cc`, and `api.7ed.net`. You can avoid this by uploading icons manually.
2. **Unsplash online wallpapers:** Only when you use the "online images" feature, the category keyword you choose is sent to `api.unsplash.com`, and images are loaded from Unsplash.
3. **WebDAV sync (only if you configure it):** When you upload, download, or delete a backup, or enable automatic backup, the Extension sends the backup file (bookmarks, folders, search engines, appearance settings) and the account name and app password you entered (HTTP Basic authentication) to **the WebDAV server you configured** (Jianguoyun by default). The backup is stored by your provider; the developer has no access to it.
4. **Search engines:** When you search from the search box, the page navigates to the search engine you selected (e.g. Baidu, Google, Bing) and your query is handled under that engine's privacy policy.

Apart from the above, the Extension does not share data with any third party.

### 5. What we do not do

- We do not collect names, emails, location, browsing history, or health, financial or physical data
- We do not read or record the content of the web pages you visit
- We do not sell or transfer user data, and do not use it for advertising, credit evaluation, or any purpose unrelated to the Extension's single purpose
- We do not use remotely hosted code; all code is included in the installed package

### 6. Your choices and data deletion

- You can edit or delete bookmarks and settings, or disconnect sync, at any time within the Extension.
- Uninstalling the Extension deletes all locally stored data.
- To delete backups already uploaded to a WebDAV server, use your provider (e.g. Jianguoyun) or the Extension's sync panel.
- To avoid sending domains to favicon services, set icons for your bookmarks manually.

### 7. Security

Local data is stored in the browser's extension storage and protected by your browser and operating-system account. Network communication with third parties uses HTTPS (except for a WebDAV address you enter yourself; we recommend using an HTTPS address). Anyone with access to your computer and browser profile may also be able to see your saved bookmarks.

### 8. Children's privacy

The Extension is not directed to children under 13 and does not knowingly collect personal information from children.

### 9. Changes to this policy

If features or data handling change, we will update this policy and the effective date above. Significant changes will be noted in the Extension's update notes.

### 10. Contact

For questions about this policy, contact: fanhe1618@gmail.com
