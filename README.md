# Rime 河童日本語五筆入力

※本方案原作者爲零尾河童，本人只是移植到 rime 平臺。  
※將本倉庫根目錄下的文檔直接複製入 RIME 用戶文件夾部署即可。

### 注意

特殊仮名：  
ー lg ヵlka ゖlke ヶlkk ゐwii ゑwee  
ぁla ぃli ぅlu ぇle ぉlo ゥlk  

**本方案借用了 sgalal 製作的 [rime 訓讀み](https://github.com/sgalal/rime-kunyomi) 方案的 OpenCC 部分，特此聲明。**<br/>
**本方案使用 OpenCC 進行平假名/片假名轉換，使用前請將 `hirakata.ocd` 和 `hira2kata.json` 兩個文件置於 `opencc` 文件夾中。**  

需要禁用 `default.yaml` 中的

```yaml
    #- {accept: comma, send: Page_Up, when: paging}
    #- {accept: period, send: Page_Down, when: has_menu}
```

**本方案一級簡碼較之原版河童五筆有所改動。請自行查看 `一級簡碼表.md`。**

如有詞序不正確或是不和使用習慣者自行編輯 `KappaJP.dict.yaml` 和 `KappaJP_express_fluency.dict.yaml` 將之位置調換即可。
