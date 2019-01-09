## 帰宅困難者を対象とした避難所位置情報オープン化の実践　−目黒区を例として−

世界で起こる大地震の20％は日本で起こっており、日本と災害は切り離せない存在となっている。甚大な被害を引き起こした2011年の東日本大震災時においては避難場所と避難所が区別されていなかったため、内閣府は平成25年に災害対策基本法（昭和36年法律第223号）を改正し、指定緊急避難場所と指定避難所を区別しなければならないこととした。又、災害ごとに指定しなくてはならず、その内容は住民に知らされなければならないとされている。
現状では、避難所情報は目黒区の公式サイト又は地理院地図指定緊急避難場所、東京都防災マップから確認できた。しかし見るサイトによって地図の書き方が違う、区全体を写していて避難所への細かいアクセス方法が見づらいなどの問題点があったため、誰でもアクセスできて編集できるOpenStreetMapで避難所情報を確認できるようにすべきだと考えた。又、東日本大震災時において帰宅困難者の受け入れについて問題があったため、首都直下型地震が想定される東京の渋谷区及び目黒区において主に帰宅困難者を対象とした施設を入力した。本研究は目黒を対象地域としたものである。
現状では、避難所情報は区の公式サイト又は地理院地図指定緊急避難場所、東京都防災マップから確認できた。しかし見るサイトによって地図の書き方が違う、地図が区全体を写していて避難所への細かいアクセス方法が見づらい等の問題点があったため、誰でもアクセスが可能であり、更に編集もできるOpenStreetMapで避難所情報を確認できるようにすべきだと考えた。又対象地域については、東日本大震災時において帰宅困難者の受け入れについて問題があった、首都直下型地震が想定される東京の渋谷区及びその付近の目黒区とした。対象施設は主に帰宅困難者向けの建物とし、本研究は目黒区を対象地域としたものである。


### osm：目黒区の現在の状況

方法として、目黒区公式サイトと国土地理院の地理院地図指定緊急避難場所の地図情報から避難所をリストアップし、OpenStreetMapの現状で避難所タグが入力されていないのを確認した。その後OpenStreetMapで避難所のタグの種類を調査し、emergency＝assembly＿pointのタグが適当であるとして避難場所と広域避難場所に該当する建物に情報を入力した。

```markdown
結果として、まず避難所と避難場所に使用するemergency=assembly_pointのタグの日本語訳ページを作成し、OpenStreetMapの目黒地区においてまだ入力されていない避難所情報を新しく57箇所入力した。渋谷区と目黒区の調査を通して、避難所や避難場所の定義は同じだが区ごとで分類方法が異なることが分かった。又OpenStreetMapにおける帰宅困難者支援施設に該当するタグのみがまだなかった為、共同研究にて帰宅困難者支援施設のタグを考察しOpenStreetMap Wikiに新たなタグとして提案した。

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Activity

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/furuhashilab/www4yamaguchishiori/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

### new

new
