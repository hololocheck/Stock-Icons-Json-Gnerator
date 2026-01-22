Stock Icons JSON Generator (v1.0)

**Release Date: 2026/01/22**

[日本語](#japanese) | [English](#english)

---

<a id="japanese"></a>
## 🇯🇵 日本語 (Japanese)

Keycap Generator v66で導入された「📦 内蔵アイコン (Stock Icons)」機能を拡張するための補助ツールを公開しました。
このツールを使用すると、誰でも簡単にアイコンライブラリ（`icons.json`）を編集・拡張し、自分好みのSVGアイコンセットをKeycap Generatorに追加できます。

### 🎯 開発の背景
Keycap Generator v66では、よく使うアイコン（矢印、メディアキーなど）をプリセットとして選択できる「内蔵アイコン機能」が搭載されました。
この機能は、拡張性を高めるためにSVGファイルと識別用JSONファイル（`icons.json`）で構成されていますが、手動でJSONを編集するのは手間がかかり、記述ミスの原因にもなります。

**Stock Icons JSON Generator** は、SVGファイルをドラッグ＆ドロップするだけで、このJSONファイルを自動生成・更新できる専用ユーティリティです。

### ✨ 主な機能
1.  **📂 ドラッグ＆ドロップで簡単追加:** SVGファイルを画面にドロップするだけでリストに追加され、「ID」「英語名」「日本語名」をファイル名から自動推測します。
2.  **🧠 スマートなカテゴリ自動判別:** ファイル名に含まれるキーワード（例: `arrow`, `play`）を解析し、適切なカテゴリ（Arrows, Mediaなど）を自動で割り当てます。
3.  **🔄 既存データの継承:** 既存の `icons.json` を読み込ませることで、現在のデータを保持したまま新しいアイコンだけを追加できます。
4.  **✏️ メタデータ編集:** 自動入力された名前やカテゴリをGUI上で簡単に修正できます。

### 📖 使い方
1.  **起動:** `Stock Icons JSON Generator` (`index.html`) をブラウザで開きます。
2.  **読み込み (任意):** 更新する場合は、既存の `icons.json` をドロップします。
3.  **追加:** 追加したいSVGファイルをドロップします。
4.  **生成:** 「icons.json を生成・ダウンロード」ボタンを押します。
5.  **配置:** ダウンロードしたファイルを Keycap Generator の `stock-icons/` フォルダに配置します。

---

<a id="english"></a>
## 🇺🇸 English

We have released a helper tool to expand the "📦 Stock Icons" feature introduced in Keycap Generator v66.
This tool allows anyone to easily edit and expand the icon library (`icons.json`) and add their own custom SVG icon sets to Keycap Generator.

### 🎯 Background
Keycap Generator v66 introduced the "Stock Icons" feature, allowing users to select common icons (arrows, media keys, etc.) as presets.
This system consists of SVG files and an identifier JSON file (`icons.json`) for extensibility. However, manually editing the JSON file is tedious and prone to errors.

**Stock Icons JSON Generator** is a dedicated utility that automatically generates and updates this JSON file simply by dragging and dropping SVG files.

### ✨ Key Features
1.  **📂 Easy Drag & Drop:** Simply drop SVG files onto the screen to add them. The tool automatically infers "ID", "English Name", and "Japanese Name" from the filename.
2.  **🧠 Smart Category Detection:** Automatically assigns appropriate categories (Arrows, Media, etc.) by analyzing keywords in the filename (e.g., `arrow`, `play`).
3.  **🔄 Update Existing Data:** Drop an existing `icons.json` first to keep your current icons while adding new ones.
4.  **✏️ Metadata Editor:** Easily edit auto-filled names or categories via the GUI.

### 📖 How to Use
1.  **Launch:** Open `Stock Icons JSON Generator` (`index.html`) in your browser.
2.  **Load (Optional):** Drop your existing `icons.json` if you want to update it.
3.  **Add:** Drop the SVG files you want to add.
4.  **Generate:** Click the "Generate & Download icons.json" button.
5.  **Deploy:** Place the downloaded file into the `stock-icons/` folder of Keycap Generator.
