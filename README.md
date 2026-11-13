# 巴别塔圣歌 · 字符抄录本 v1.0 / Chants of Sennaar Glyph Console v1.0

《Chants of Sennaar》五语族字符输入台：**单文件、离线、无需联网**，字形字体已内嵌。

A glyph input console for the five languages of *Chants of Sennaar*: **single-file, offline, no network required**, with the glyph font embedded.

支持 信徒 / 战士 / 诗人 / 炼金 / 隐者 五种文字，含各语族数字系统。

Supports the Devotees, Warriors, Bards, Alchemists and Anchorites scripts, including each language's numeral system.

> **免责声明 / Disclaimer**：本作品为非官方粉丝作品，与《巴别塔圣歌》（Chants of Sennaar）的开发商 Rundisc 及发行商 Focus Entertainment 无关。游戏内文字字形、图像、音频等素材版权归原权利人所有。本项目仅供学习交流使用，不作任何商业用途；如权利人要求，将立即停止分发。
>
> This is an unofficial fan work, not affiliated with Rundisc (developer) or Focus Entertainment (publisher) of *Chants of Sennaar*. In-game glyphs, images and audio remain the property of their respective owners. This project is for study and personal use only, with no commercial purpose; distribution will cease immediately upon request from the rights holders.

## 使用 / Usage

- **在线使用**：直接打开 `https://eoviniaashka.github.io/-/`（GitHub Pages）。
- **本地使用**：把 `巴别塔圣歌-字符输入台-v1.0.html` 下载到电脑，双击用浏览器打开（推荐 Chrome / Edge / Safari / Firefox）。不需要安装任何软件，也不需要联网。


- **Online**: open `https://eoviniaashka.github.io/-/` (GitHub Pages).
- **Local**: download `巴别塔圣歌-字符输入台-v1.0.html` and double-click it to open in a browser (Chrome / Edge / Safari / Firefox recommended). Nothing to install, no internet connection required.


## 功能 / Features

- 点击右侧面板字符插入书页；空格键插入空格，退格删除。
  Click a glyph in the right panel to insert it into the book page; `Space` inserts a space, `Backspace` deletes.
- 数字键 `1`–`5` 或顶部标签切换语族。
  Press `1`–`5` or use the top tabs to switch language.
- 悬停字符显示释义（**手机端长按字形显示，不会误插入**）。
  Hover a glyph to see its meaning (**on mobile, long-press; it won't insert**).
- 底部「复制字符」导出当前两页的字符文本（.txt）；选中书页文字后 `Ctrl+C`、或设置页「复制字形图」，导出字形图（透明背景、按内容裁剪，大小跟随字号）。
  Bottom 「复制字符 / Copy characters」 exports the current two pages as a `.txt`; select page text and press `Ctrl+C`, or use 「复制字形图 / Copy glyph image」 in Settings, to export a glyph image (transparent background, cropped to content, sized by the font-size slider).
- 设置页可调字号、颜色、界面语言（中文 / Français / English）。
  Settings lets you adjust font size, colour and UI language (中文 / Français / English).
- 设置页可切换面板排序：**词性序**（人→动词→形容词→名词→工具类→场所→其他）或 **码位序**。
  Settings toggles panel ordering: **by part of speech** (person → verb → adjective → noun → tool → place → other) or **by code point**.
- 支持从别处**粘贴**：汉字、英文字母数字、以及本页的字形字符都能粘进书页（其它杂质自动丢弃）。
  **Paste** works: Chinese characters, Latin letters/digits and this page's glyphs can be pasted into the book page (other junk is dropped automatically).
- 炼金术士四位数字形态、连接符与小数点。
  Alchemist four-form numerals, connectors and decimal point.
- **电脑端与手机端都自适应**：电脑端 UI 按屏幕宽度等比缩放（1280～4K）；手机竖屏使用专门的布局（书页占上半屏、底部胶囊形操作键、可滚动字形面板），手机底部还带「保存图」按钮（直接保存 PNG）；手机右上角齿轮可打开全屏设置页。
  **Responsive on desktop and mobile**: desktop UI scales with screen width (1280–4K); mobile portrait uses a dedicated layout (book occupies the top half, pill-shaped bottom controls, scrollable glyph panel) plus a 「保存图 / Save image」 button (saves a PNG directly); the gear at the top-right opens the full-screen Settings page on mobile.

## 手机端操作 / Mobile controls

| 操作 / Action | 效果 / Effect |
| --- | --- |
| 轻点字形 / Tap a glyph | 插入字符 / Insert the glyph |
| 长按字形（约半秒）/ Long-press (~0.5 s) | 显示释义气泡，不会插入 / Show the meaning bubble, no insertion |
| 底部 ⌫ / ‹ / ↵ / › | 退格 / 上一页 / 换行 / 下一页 — Backspace / previous page / new line / next page |
| 底部「保存图」/ 「Save image」 | 把当前两页的字符**直接保存成 PNG 图片**（下载到手机）/ **Save both pages as a PNG image** (downloads to the phone) |
| 右上角齿轮 / Gear (top-right) | 打开全屏设置页（字号、颜色、语言、排序）/ Open the full-screen Settings page (size, colour, language, order) |

## 文件说明 / Files

| 文件 / File | 说明 / Description |
| --- | --- |
| `巴别塔圣歌-字符输入台-v1.0.html` | 主程序（单文件）/ Main app (single file) |
| `index.html` | GitHub Pages 入口（与主程序内容相同）/ GitHub Pages entry (same content) |
| `塔歌字形表.xlsx` | 字形总表（词义的唯一来源）/ Master glyph table (single source of truth for meanings) |
| `readme.txt` | 详细说明与致谢 / Detailed notes and credits |

> 字体更新相关的维护工具（`更新字体.bat`、`update_font.ps1`、`sync_meanings.py`、`verify_glyphs.py`、`check_advance.py`、`字体/` 源字体）**不在发布包里**，放在作者桌面上的 `巴别塔圣歌-维护工具/` 文件夹里；需要改字体或改词义时才用，普通使用不需要。
>
> Maintenance tools (`更新字体.bat`, `update_font.ps1`, `sync_meanings.py`, `verify_glyphs.py`, `check_advance.py` and the source font folder `字体/`) are **not included** in the release package — they live in the author's `巴别塔圣歌-维护工具/` folder and are only needed when editing the font or meanings.

## 面板顺序（词性序）/ Panel order (by part of speech)

- 排序读 `塔歌字形表.xlsx` 最后一列「词性」：按 **人 → 动词 → 形容词 → 名词 → 工具类 → 场所 → 其他** 分组。
  Ordering reads the last column 「词性 / part of speech」 of `塔歌字形表.xlsx`, grouping as **person → verb → adjective → noun → tool → place → other**.
- 词性列**留空**的行保持原相对顺序，排在最后；**整列全空时面板完全保持原顺序不动**。
  Rows with an **empty** part-of-speech keep their relative order and go last; **if the whole column is empty the panel keeps its original order untouched**.
- 设置里的「码位序」模式不看词性表，直接按码位排。
  The 「码位序 / By code point」 mode ignores the table and sorts strictly by code point.

## 关于代码 / About the code

本项目的主程序代码（HTML / CSS / JavaScript）由 **AI 辅助编写与调试**；字形绘制、字形释义与词表整理由人工完成。

The main program code (HTML / CSS / JavaScript) was **written and debugged with AI assistance**; glyph drawing, meanings and table curation were done by hand.

游戏背景图、音效等美术与音频素材版权归原权利人（Rundisc / Focus Entertainment）所有，非本项目原创。

Background art, sound effects and other art/audio assets remain the property of their rights holders (Rundisc / Focus Entertainment) and are not original to this project.

## 致谢 / Credits

详细说明与扩充字形的贡献者鸣谢见 `readme.txt`。

Detailed notes and the list of contributors for extended glyphs are in `readme.txt`.
