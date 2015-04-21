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
* 現存する都道府県・郡・市区町村を対象としています (順次、過去自治体・小地域へ拡大予定)
 