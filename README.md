# 💻 資料結構與演算法入門：簡報投影片

這是一套使用 [LaTeX Beamer](https://ctan.org/pkg/beamer) 製作的教學簡報，涵蓋資料結構與演算法的基礎主題，適合初學者與課程講義用途。每個章節為獨立投影片檔案（如 `chapter0.tex`），可單獨編譯為 PDF。

> 👤 作者：悠太翼 Yuuta Tsubasa  
> 🛠️ 引擎：XeLaTeX + Beamer Madrid Theme  
> 📘 字體支援：CJK（繁體中文）

---

## 🧾 範例章節

- `chapter0.tex`：什麼是資料結構與演算法？  
  包含圖片、虛擬碼、C++ 與 Lisp 程式碼範例，並介紹遞迴與基礎概念。

---

## 🏗️ 自動編譯（GitHub Actions）

本專案已設定 GitHub Actions，自動將所有章節編譯成 PDF。  
你可以在 [Actions](https://github.com/YuutaTsubasa/DataStructureAndAlgorithmsSlides/actions) 中查看每次編譯的產出結果。

### 📂 編譯輸出

每次 Push 後，會自動產生：

- `chapter0.pdf`
- `chapter1.pdf`
- ⋯

> 所有 PDF 會被打包成 `compiled-chapters.zip` 可供下載。

---

## 🛠️ 本地編譯

若想在本機編譯：

### 安裝 XeLaTeX（建議使用 TeX Live 或 MacTeX）

```bash
sudo apt install texlive-full  # Ubuntu/Debian
brew install --cask mactex     # macOS
```

### 編譯範例章節

```bash
xelatex chapter0.tex
```

## 📁 專案結構

```bash
.
├── chapter0.tex            # 第一章：簡介
├── chapter1.tex            # 第二章：複雜度分析
├── ...                     # 後續的章節
├── images/                 # 投影片用圖
│   ├── array_example.png
│   ├── sort_example_students.png
│   └── ...
├── .github/workflows/
│   └── build.yml           # GitHub Actions 設定
└── README.md               # 本說明文件
```

## 📜 授權
本專案以 MIT 授權釋出，歡迎自由使用與改作，並保留原作者署名。

---

📫 如有建議或錯誤回報，歡迎開 Issue 或 PR！
