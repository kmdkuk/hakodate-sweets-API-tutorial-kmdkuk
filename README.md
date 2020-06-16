# hakodate-sweets-API-tutorial

初めてRails触るけれど，公式のRailsチュートリアルは重そうだったので作成してみました．  
始めるときは．このリポジトリーをフォークして自分のところに置いて作業を追加してみてください．  
開始時点の環境は，hakodate-sweets-APIの環境とほぼほぼ揃えておいてあります．  
なので作業するときには，Docker, docker-composeを準備してください．  

このリポジトリーをクローンしてきて，  
```sh
$ docker-compose up -d
```
するといくつかのコンテナが立ち上がります．  
http://localhost:10000  
に完成しているAPIを叩くことができるSwaggerが立ち上がります．

すべてのAPIを叩くことができるようになるまで書けるようになったら，  
hakodate-sweets-APIの方もおそらく書けるようになっていると思われます．

## 作業手順
1. ShopについてのAPI作成
2. CategoryについてのAPI作成
3. SweetsについてのAPI作成
3.1. ShopとSweetsを1対多の表現で表す(1つの店舗は，複数のお菓子を持つ)
3.2. SweetsとCategoryを多対多の表現で表す(あるスイーツは，多くのカテゴリーを持つ．あるカテゴリーに含まれているお菓子は，たくさん存在する．)
