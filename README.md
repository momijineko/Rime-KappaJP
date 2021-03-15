# Rime 河童日本語五筆入力

## 聲明

- 本方案原作者爲 [零尾河童](https://github.com/zerobikappa/rime-kappajp86)，本人只是移植到 rime 平臺。
- 本方案借用了 sgalal 製作的 [rime 訓讀み](https://github.com/sgalal/rime-kunyomi) 方案的 OpenCC 部分。
- 本方案遵循 MIT License 開源。

## 使用方法和注意事項

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

歡迎各位大佬共同對本方案的詞庫進行維護和提PR。關於對新詞的收錄，本詞庫將不予收錄死語以及未來可能會變成死語的詞（比如部分NET用語）。
