# geonamesjp_vs_wikipedia
GeoNames.jp と Wikipedia (日本語版) のリンクセット

## What's this?
[GeoNames Ontology](http://www.geonames.org/ontology/documentation.html) で定義された
<http://www.geonames.org/ontology#wikipediaArticle> プロパティを使用して
GeoNames.jp の地名と Wikipedia (日本語版) の関連付けを行うリンクセットです。

## Example


	@prefix gn:    <http://www.geonames.org/ontology#> .
	@prefix gnjp:  <http://geonames.jp/resource/> .

	gnjp:福島県福島市  gn:wikipediaArticle  <http://ja.wikipedia.org/wiki/福島市> .
	gnjp:徳島県板野郡北島町  gn:wikipediaArticle  <http://ja.wikipedia.org/wiki/北島町> .
	gnjp:群馬県吾妻郡長野原町  gn:wikipediaArticle  <http://ja.wikipedia.org/wiki/長野原町> .
	gnjp:秋田県山本郡  gn:wikipediaArticle  <http://ja.wikipedia.org/wiki/山本郡> .
	gnjp:北海道美唄市  gn:wikipediaArticle  <http://ja.wikipedia.org/wiki/美唄市> .
	gnjp:京都府京都市上京区  gn:wikipediaArticle  <http://ja.wikipedia.org/wiki/上京区> .
	gnjp:鹿児島県大島郡与論町  gn:wikipediaArticle  <http://ja.wikipedia.org/wiki/与論町> .
	gnjp:熊本県下益城郡  gn:wikipediaArticle  <http://ja.wikipedia.org/wiki/下益城郡> .
	gnjp:秋田県鹿角郡  gn:wikipediaArticle  <http://ja.wikipedia.org/wiki/鹿角郡> .
	gnjp:岡山県岡山市中区  gn:wikipediaArticle  <http://ja.wikipedia.org/wiki/中区 (岡山市)> .


 
## Note
* ボキャブラリの妥当性を検討するためのベータ版の状態です (2015/04/21 時点)
* 2,332 Triples (2015/04/21 時点)
* [日本の地方公共団体一覧 - Wikipedia](http://ja.wikipedia.org/wiki/%E6%97%A5%E6%9C%AC%E3%81%AE%E5%9C%B0%E6%96%B9%E5%85%AC%E5%85%B1%E5%9B%A3%E4%BD%93%E4%B8%80%E8%A6%A7) に含まれる都道府県・郡・市区町村を対象としています
* 過去自治体・小地域への対応は計画中です
* リンクセットのトリプルに加えて、リンクセット自体のメタデータを [VoID Vocabulary](http://www.w3.org/TR/void/) で記述しています。 
 