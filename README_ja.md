# Rime 河童日本語五筆型入力方法

![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/momijineko/Rime-KappaJP) ![GitHub](https://img.shields.io/github/license/momijineko/Rime-KappaJP)

[English](https://github.com/momijineko/Rime-KappaJP/blob/master/README.md) | [中文](https://github.com/momijineko/Rime-KappaJP/blob/master/README_zh.md) | | 日本語

## TODO

THIS README NEED TRANSLATE TO JAPANESE.

---

五筆86に基づく日本語入力スキームです。

這是一種通過 `漢字直接輸入`<sup>[漢字直接入力 - Wikipedia](https://ja.wikipedia.org/wiki/漢字直接入力)</sup> 方式進行日語輸入的方案。

## 声明

- 本方案原作者爲 [零尾河童](https://github.com/zerobikappa/rime-kappajp86)，本人只是移植到 rime 平臺。
- 本方案借用了 sgalal 製作的 [rime 訓讀み](https://github.com/sgalal/rime-kunyomi) 方案的 OpenCC 部分。
- 本方案遵循 MIT License 開源。

## 使用方法と注意事項

使用前請先閱讀 [Wiki](https://github.com/momijineko/Rime-KappaJP/wiki) 頁面。

將本倉庫根目錄下的文檔直接複製入 RIME 用戶文件夾部署即可。

本方案使用 OpenCC 進行平假名/片假名轉換，使用前請將 `hirakata.ocd` 和 `hira2kata.json` 兩個文件置於 `opencc` 文件夾中。

使用前需在 `default.custom.yaml` 中的 patch 分支下添加以下內容。

```yaml
patch:
  ...
  "key_binder/bindings":
    #- {accept: comma, send: Page_Up, when: paging}
    #- {accept: period, send: Page_Down, when: has_menu}
```

歡迎各位大佬共同對本方案的詞庫進行維護和提PR。
