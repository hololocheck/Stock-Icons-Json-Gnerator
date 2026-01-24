# Stock Icons JSON Generator

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Web-green.svg)
![Version](https://img.shields.io/badge/version-1.0-orange.svg)

[日本語](#japanese) | [English](#english)

---

<a id="japanese"></a>
## 🇯🇵 日本語 (Japanese)

Keycap Generator v66で導入された「📦 内蔵アイコン (Stock Icons)」機能を拡張するための補助ツールです。SVGファイルをドラッグ＆ドロップするだけで、アイコンライブラリ定義ファイル（`icons.json`）を自動生成できます。

### 🌐 関連リンク
- **[ツールページ](https://hololocheck.github.io/Stock_Icons_Json_Generator/)**: ブラウザでこのツールを起動します。
- **[Keycap Generator (GitHub)](https://github.com/hololocheck/Keycap_Generator)**: カスタム対象の本体リポジトリはこちら。

### ⚠️ 注意点
このツールは、Keycap GeneratorのHTMLファイルをダウンロードして**ローカル環境（オフライン）**で実行し、独自のSVGアイコンを追加・カスタマイズしたいユーザー向けです。
- **オンライン版を利用の方へ**: Web版の Keycap Generator をそのまま利用している場合、**このツールは不要です。**

### ✨ 主な機能
- **ドラッグ＆ドロップで簡単追加**: SVGファイルを画面にドロップするだけでリストに追加され、「ID」「英語名」「日本語名」をファイル名から自動推測します。
- **スマートなカテゴリ自動判別**: ファイル名に含まれるキーワード（例: `arrow`, `play`）を解析し、適切なカテゴリ（Arrows, Mediaなど）を自動で割り当てます。
- **既存データの継承 (Update)**: 既存の `icons.json` を読み込ませることで、現在のデータを保持したまま新しいアイコンだけを追加できます。
- **メタデータ編集**: 自動入力された名前やカテゴリをGUI上で簡単に修正できます。

### 📖 使い方
1.  **起動:** [ツールページ](https://hololocheck.github.io/Stock_Icons_Json_Generator/) をブラウザで開きます。
2.  **読み込み (任意):** 更新する場合は、既存の `icons.json` をドロップします。
3.  **追加:** 追加したいSVGファイルをドロップします。
4.  **生成:** 「icons.json を生成・ダウンロード」ボタンを押します。
5.  **配置:** ダウンロードしたファイルを Keycap Generator の `stock-icons/` フォルダに配置します。

---

<a id="english"></a>
## 🇺🇸 English

A helper tool designed to expand the "Stock Icons" feature introduced in Keycap Generator v66. It automatically generates the icon library definition file (`icons.json`) simply by dragging and dropping SVG files.

### 🌐 Related Resources
- **[Tool Page](https://hololocheck.github.io/Stock_Icons_Json_Generator/)**: Launch this tool in your browser.
- **[Keycap Generator (GitHub)](https://github.com/hololocheck/Keycap_Generator)**: The main repository for customization.

### ⚠️ Important Notes
This tool is specifically designed for users who download the HTML to run in a **local environment** and wish to manually customize or expand the icon library.
- **For Online Users**: You do **not** need this tool if you are simply using the online version of Keycap Generator.

### ✨ Key Features
- **Easy Drag & Drop**: Simply drop SVG files onto the screen to add them. The tool automatically infers "ID", "English Name", and "Japanese Name" from the filename.
- **Smart Category Detection**: Automatically assigns appropriate categories (Arrows, Media, etc.) by analyzing keywords in the filename (e.g., `arrow`, `play`).
- **Update Existing Data**: Drop an existing `icons.json` first to keep your current icons while adding new ones.
- **Metadata Editor**: Easily edit auto-filled names or categories via the GUI.

### 📖 How to Use
1.  **Launch:** Open the [Tool Page](https://hololocheck.github.io/Stock_Icons_Json_Generator/) in your browser.
2.  **Load (Optional):** Drop your existing `icons.json` if you want to update it.
3.  **Add:** Drop the SVG files you want to add.
4.  **Generate:** Click the "Generate & Download icons.json" button.
5.  **Deploy:** Place the downloaded file into the `stock-icons/` folder of Keycap Generator.

---

### 📄 License / ライセンス
MIT License.
