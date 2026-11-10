# 巴别塔圣歌 · 字符抄录本 v1.0 / Chants of Sennaar Glyph Console v1.0

《Chants of Sennaar》五语族字符输入台：**单文件、离线、无需联网**，字形字体已内嵌。

A glyph input console for the five languages of *Chants of Sennaar*: **single-file, offline, no network required**, with the glyph font embedded.

支持 信徒 / 战士 / 诗人 / 炼金 / 隐者 五种文字，含各语族数字系统。

Supports the Devotees, Warriors, Bards, Alchemists and Anchorites scripts, including each language's numeral system.

> **免责声明 / Disclaimer**：本作品为非官方粉丝作品，与《巴别塔圣歌》（Chants of Sennaar）的开发商 Rundisc 及发行商 Focus Entertainment 无关。游戏内文字字形、图像、音频等素材版权归原权利人所有。本项目仅供学习交流使用，不作任何商业用途；如权利人要求，将立即停止分发。
>
> This is an unofficial fan work, not affiliated with Rundisc (developer) or Focus Entertainment (publisher) of *Chants of Sennaar*. In-game glyphs, images and audio remain the property of their respective owners. This project is for study and personal use only, with no commercial purpose; distribution will cease immediately upon request from the rights holders.

## 使用 / Usage

双击 `巴别塔圣歌-字符输入台-v1.0.html` 即开即用。

Double-click `巴别塔圣歌-字符输入台-v1.0.html` to run — no installation needed.

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
- 炼金术士四位数字形态、连接符与小数点。
  Alchemist four-form numerals, connectors and decimal point.
- **电脑端与手机端都自适应**：电脑端 UI 按屏幕宽度等比缩放（1280～4K）；手机竖屏使用专门的布局（书页占上半屏、底部胶囊形操作键、可滚动字形面板），手机底部还带「复制图」按钮。
  **Responsive on desktop and mobile**: desktop UI scales with screen width (1280–4K); mobile portrait uses a dedicated layout (book occupies the top half, pill-shaped bottom controls, scrollable glyph panel) plus a 「复制图 / Copy image」 button.

## 手机端操作 / Mobile controls

| 操作 / Action | 效果 / Effect |
| --- | --- |
| 轻点字形 / Tap a glyph | 插入字符 / Insert the glyph |
| 长按字形（约半秒）/ Long-press (~0.5 s) | 显示释义气泡，不会插入 / Show the meaning bubble, no insertion |
| 底部 ⌫ / ‹ / ↵ / › | 退格 / 上一页 / 换行 / 下一页 — Backspace / previous page / new line / next page |
| 底部「复制图」/ 「Copy image」 | 把当前两页的字符导出成一张字形图 / Export both pages as one glyph image（复制到剪贴板；不支持时自动下载 PNG / copied to clipboard, or downloaded as PNG when unsupported） |

## 文件说明 / Files

| 文件 / File | 说明 / Description |
| --- | --- |
| `巴别塔圣歌-字符输入台-v1.0.html` | 主程序（单文件）/ Main app (single file) |
| `index.html` | GitHub Pages 入口（与主程序内容相同）/ GitHub Pages entry (same content) |
| `塔歌字形表.xlsx` | 字形总表（词义的唯一来源）/ Master glyph table (single source of truth for meanings) |
| `readme.txt` | 详细说明与致谢 / Detailed notes and credits |

> 字体更新相关的维护工具（`更新字体.bat`、`update_font.ps1`、`sync_meanings.py`、`renumber_xlsx.py`、`verify_glyphs.py`、`check_advance.py`、`字体/` 源字体）**不在发布包里**，放在作者桌面上的 `巴别塔圣歌-维护工具/` 文件夹里；需要改字体或改词义时才用，普通使用不需要。
>
> Maintenance tools (`更新字体.bat`, `update_font.ps1`, `sync_meanings.py`, `renumber_xlsx.py`, `verify_glyphs.py`, `check_advance.py` and the source font folder `字体/`) are **not included** in the release package — they live in the author's `巴别塔圣歌-维护工具/` folder and are only needed when editing the font or meanings.

## 面板顺序（词性序）/ Panel order (by part of speech)

- 排序读 `塔歌字形表.xlsx` 最后一列「词性」：按 **人 → 动词 → 形容词 → 名词 → 工具类 → 场所 → 其他** 分组。
  Ordering reads the last column 「词性 / part of speech」 of `塔歌字形表.xlsx`, grouping as **person → verb → adjective → noun → tool → place → other**.
- 词性列**留空**的行保持原相对顺序，排在最后；**整列全空时面板完全保持原顺序不动**。
  Rows with an **empty** part-of-speech keep their relative order and go last; **if the whole column is empty the panel keeps its original order untouched**.
- 想改顺序：给行填「词性」→ 双击 `更新字体.bat` → 刷新页面。
  To change ordering: fill in the part of speech → double-click `更新字体.bat` → refresh the page.
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

## 如何加入新字形 / Adding new glyphs

1. **画字形 / Draw it**：在 FontCreator 里选一个没用过的 PUA 码位（建议接在对应族扩充段的末尾），画好后导出 OTF，覆盖维护工具目录 `巴别塔圣歌-维护工具/字体/` 里的字体文件。
   In FontCreator, pick an unused PUA code point (ideally right after that family's extension block), draw the glyph, export an OTF and overwrite the font in `巴别塔圣歌-维护工具/字体/`.
2. **加表行 / Add a table row**：在 `塔歌字形表.xlsx` 末尾加一行 —— 语族（信徒 / 战士 / 诗人 / 炼金 / 隐者）、码位（`U+Exxxx`）、字形字符、中文释义、备注。「#」列随便填，脚本会自动重排成 1..N。
   Append a row to `塔歌字形表.xlsx`: family, code point (`U+Exxxx`), glyph character, Chinese meaning, note. The 「#」 column can be anything — the script renumbers it to 1..N.
   - 字形列（D 列）可以把那个字符直接填进去，用 Excel 公式 `=UNICHAR(HEX2DEC("E198"))` 或 Word 里输入 `E198` 后按 `Alt+X` 转成字符再粘贴。
     For the glyph column (D) you may paste the character itself, produced with Excel `=UNICHAR(HEX2DEC("E198"))` or by typing `E198` in Word and pressing `Alt+X`.
3. **跑更新 / Run the update**：双击维护工具目录里的 `更新字体.bat`（它和 v1.0 包要放在同一个文件夹）。它会依次：嵌入字体 → 按表同步词义 → 重排编号 → **码位/字形核验**（有码位但字体里没字形的行会被点名；字形列填了字符的会自动改正码位）→ 字宽核对 → 重新打包。
   Double-click `更新字体.bat` (it must sit next to the v1.0 folder). It will: embed the font → sync meanings from the table → renumber → **verify code points vs glyphs** (rows whose glyph is missing are reported; rows whose D column has a character get their code point auto-corrected) → check advance widths → repack.
4. **刷新页面 / Refresh**：新字形出现在对应语族面板末尾；切到「码位序」会按码位自动排到正确位置。
   The new glyph appears at the end of that family's panel; in 「码位序」 mode it lands at its proper code-point position.

说明：表里释义写「(未知)」「(未知）」「（未知）」的行只作记录，不会同步进面板。

Note: rows whose meaning contains 「未知 / unknown」 are kept for records only and are not synced into the panel.
