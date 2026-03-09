# 少女與戰車 字幕模組中文化 (World of Tanks: Girls und Panzer Subtitles Traditional Chinese)

[![Game Version](https://img.shields.io/badge/Game-World%20of%20Tanks-red)](https://worldoftanks.com/)
[![Mod Version](https://img.shields.io/badge/Mod-GuP%20Subtitles-blue)](https://github.com/jack52267/gup.subtitles.zh-tw)

本專案將《戰車世界》官方提供的「少女與戰車字幕模組」文本進行**繁體中文化**。  
翻譯名詞對齊台灣代理版本，並參考 Grok AI 進行校驗。

> [!NOTE]
> 原官方字幕模組來源：[WGMods.net (6725)](https://wgmods.net/6725/)

---

## 🛠 安裝教學 (Installation)

根據您的需求，請選擇以下其中一種安裝方式：

### 方案 A：快速安裝 (無其他語音模組)
如果您**沒有**安裝其他語音模組，想直接一勞永逸：
1. 前往 [Releases](https://github.com/jack52267/gup.subtitles.zh-tw/releases) 下載檔名含 `xml` 的檔案：`gup.subtitles.tw_版號.xml.wotmod`。
2. 將檔案放入：`遊戲目錄/mods/[當前遊戲版本號]/` 即可。

### 方案 B：手動整合 (已有其他語音模組且想共存)
如果您已有安裝其他語音模組（如 `GuP_VoiceSelector` 或 `Aslain` 內的其他語音），若想共存使用請採此方式：
1. 下載 `gup.subtitles.tw_版號.wotmod` 並放入 `遊戲目錄/mods/[當前遊戲版本號]/`。
2. 編輯原有的 `res_mods/gui/soundModes/main_sound_modes.xml`。
3. 將 `Assets/how to add.txt` 內的代碼複製並貼入該 XML 檔案中。
   * *註：若無此 XML 檔案代表你裝的語音模組沒有整合選單，可直接使用 Assets 資料夾內提供的範本依照你安裝過的audioww內格式新增。*

> [!CAUTION]
> ## ⚠️ 注意事項與相容性 (Important Notes)
> - **觸發條件：** 必須在遊戲音效設定中套用**官方少女與戰車語音**才會出現字幕。
> - **第六感衝突：** 若有安裝其他整合音效包內自定義的「第六感」音效，可能會與此字幕模組產生衝突，請自行斟酌。
> - **語音優先權：** 乘員專屬語音的優先權較高。例如：乘員為「鮟鱇隊」但選單選擇「繼續高中」，系統會優先播放「鮟鱇隊」的語音。
> - **翻譯差異：** 由於原始文本為英文，雖然經過文字校對，但與原文本與日文原音可能存在些微語意差異，還請見諒。

---

## 📸 遊戲截圖 (Screenshots)

### 設定方式 (Settings)
<img src="./assets/P1.jpg" width="640" alt="設定選單">

### 遊戲效果 (In-game Preview)
<div align="center">
  <img src="./assets/P2.jpg" alt="遊戲內效果" width="49%">
  <img src="./assets/P3.jpg" alt="遊戲內效果" width="49%">
</div>

---

## 🌍 English Description

### Overview
This project provides **Traditional Chinese localization** for the official *World of Tanks* "Girls und Panzer" (GuP) subtitle mod. The translation adheres to the terminology used in the official Taiwanese version and has been verified using Grok AI to ensure accuracy.

### 🛠 Installation Guide

Please choose one of the following methods based on your current mod setup:

#### Method A: Standalone Installation (No other voice mods)
Choose this method if you **do not** have any other voice mods installed and want a simple setup.
1. Go to [Releases](https://github.com/jack52267/gup.subtitles.zh-tw/releases) and download the file with `xml` in its name (e.g., `gup.subtitles.tw_[version].xml.wotmod`).
2. Place the file into: `[WoT_Directory]/mods/[Current_Game_Version]/`.

#### Method B: Manual Integration (Coexist with other voice mods)
Choose this method if you already use other voice mods (such as `GuP_VoiceSelector` or voices within `Aslain's Modpack`) and want them to work together.
1. Download the standard `.wotmod` file (e.g., `gup.subtitles.tw_[version].wotmod`) and place it in the `mods/[Current_Game_Version]/` folder.
2. Edit (or create) the file: `res_mods/gui/soundModes/main_sound_modes.xml`.
3. Copy the code snippet from `Assets/how to add.txt` and paste it into that XML file.
   * *Note: If the XML file does not exist, you can use the template provided in the `Assets` folder.*

### ⚠️ Important Notes
* **Activation Requirement:** Subtitles will only appear when the official "Girls und Panzer" voice pack is selected in the in-game audio settings.
* **Compatibility:** Custom "Sixth Sense" audio may conflict with other voice mods.
* **Crew Priority:** Crew-specific unique voices have higher priority. For example, if your crew is the "Ankou Team" but you select "Jatkosota High School" in the menu, the "Ankou Team" voices will take precedence.
* **Translation Nuances:** Since the original source text is in English, there may be slight differences in nuance compared to the original Japanese voice lines.

---

## 💬 意見回饋 (Feedback)
如果您發現任何翻譯錯誤或改進建議，歡迎提交 **Issue** 或留言告知！  
If you encounter any translation errors or have suggestions for improvement, please feel free to open an **Issue** or leave a comment!
