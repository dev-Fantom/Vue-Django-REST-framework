# Vue with Django REST framework

### Building SPA with Vue.js and Django REST Framework

We have set up a two-page configuration, each with a different URL, and we can add three pages, four pages, and so on by adding more functions and routing in views.py.

### Vue.jsとDjango REST FrameworkでSPA構築

それぞれ違うURLで表示する2ページの構成にしました。views.pyの関数とルーティングを増やしていけば3ページ、4ページ…と構成を増やすことができます。

- Python 3.10.0
- Django 4.1.7
- Vue 3.2.47

## Usage / 使い方

Install Library form requirements.txt.

requirements.txtからライブラリをインストール


	pip install -r requirements.txt

Specify API key in .env

.envにAPIキーを指定

    touch .env

	DEEPL_API_KEY=YOURAPIKEY
	
## Sample usage / 実行方法

	python translate_deepl.py

## Result / 結果
"DeepLの翻訳技術を使って日本語を英語に翻訳します。"

↓ 

"Translate Japanese into English using the translation technology at DeepL."


## Author / 作成者

- [Fantom, Inc. (JP)](https://twitter.com/Fantomcojp)