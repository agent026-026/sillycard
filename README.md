# Sillycard
macOS上管理Silly Tavern角色卡

**Sillycard** 是一款面向 **Silly Tavern** 生态的 **PNG 角色卡**工具：在本地集中浏览、预览元数据与嵌入世界书、编辑 JSON 并写回 PNG。元数据保存在图片的 `tEXt` 块中，解析顺序与 SillyTavern 主仓库 [`character-card-parser.js`](https://github.com/SillyTavern/SillyTavern/blob/release/src/character-card-parser.js) 一致（**`ccv3` 优先于 `chara`**；保存时写入 `chara`，并在 JSON 可解析时附加 `ccv3`）。应用侧重离线文件工作流。

隐私协议，用户使用协议，使用指引见[关于Sillycard]()
