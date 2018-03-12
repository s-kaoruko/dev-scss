scssの構成について考える
====

## 構成

```
root/  
　├ styles/
　│　└ scss/  
　│　　　├ base/  
　│　　　├ config/  
　│　　　├ custom/  
　│　　　│　　├ components/  
　│　　　│　　├ utilities/  
　│　　　│　　├ _components.scss  
　│　　　│　　└ _utilities.scss  
　│　　　├ layout/  
　│　　　├ override/  
　│　　　├ partials/  
　│　　　│　　└ common/  
　│　　　├ tools/  
　│　　　├ vendor/  
　│　　　└ style.scss  
　└ README.md  
```  

### base/  
要素の基本的な設定  

## config/  
定義たち  

## tools/  
mixinたち  

## custom/components  
汎用性のあるスタイル（パーツ単位）  
接頭辞は'c-'  

## custom/utilities  
汎用性のあるスタイル（要素単位）  
接頭辞は'u-'  

## layout/  
レイアウト関連  

## partials/
セクションごとのスタイル  

## vendor/  
プラグインのスタイル  

## override/  
プラグインのスタイルを上書きするところ  

## style.scss
ここに必要なもの書いてコンパイルする  