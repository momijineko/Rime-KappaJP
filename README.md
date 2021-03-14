# Rime 河童日本語五筆入力

## 聲明

- 本方案原作者爲 [零尾河童](https://github.com/zerobikappa/rime-kappajp86)，本人只是移植到 rime 平臺。
- 本方案借用了 sgalal 製作的 [rime 訓讀み](https://github.com/sgalal/rime-kunyomi) 方案的 OpenCC 部分。
- 本方案遵循 MIT License。

## 使用方法和注意事項

使用前請先閱讀 [河童五筆簡介](https://github.com/momijineko/Rime-KappaJP/blob/master/%E6%B2%B3%E7%AB%A5%E4%BA%94%E7%AD%86%E7%B0%A1%E4%BB%8B.md) 。

將本倉庫根目錄下的文檔直接複製入 RIME 用戶文件夾部署即可。

本方案使用 OpenCC 進行平假名/片假名轉換，使用前請將 `hirakata.ocd` 和 `hira2kata.json` 兩個文件置於 `opencc` 文件夾中。

使用前可能需禁用 `default.yaml` 中的

```yaml
#- {accept: comma, send: Page_Up, when: paging}
#- {accept: period, send: Page_Down, when: has_menu}
```

本方案一級簡碼較之原版河童五筆有所改動。請查看 [一級簡碼表](https://github.com/momijineko/Rime-KappaJP/blob/master/%E4%B8%80%E7%B4%9A%E7%B0%A1%E7%A2%BC%E8%A1%A8.md)。

如有詞序不正確或是不和使用習慣者請自行編輯相關詞庫。

也歡迎各位大佬共同對本方案的詞庫進行維護和提PR。關於對新詞的收錄，本詞庫將不予收錄死語以及未來可能會變成死語的詞（比如部分NET用語）。
