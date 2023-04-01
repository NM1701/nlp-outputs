## ワードクラウド

### MeCabインストール
- Anacondaに入れる場合はAnaconda Promptで下記コマンドを実行し、MeCabと辞書をインストール<br>
```sh
conda install -c mzh mecab-python3
conda install -c conda-forge unidic-lite
```
### 手順
1. stopwords設定(creating_stopwords.ipynb)
2. wordcloud描画(wordcloud.ipynb)

### 参考
- [User Documentation](https://amueller.github.io/word_cloud/generated/wordcloud.WordCloud.html)
- [日本語テキストをワードクラウドで可視化する](https://techblog.gmo-ap.jp/2021/06/15/text-visualization-wordcloud/)
- [nlplotでアンケート結果を可視化してみた](https://blog.since2020.jp/data_analysis/nlplot_questionnaire/)
- [ワードクラウドで特許データを分析してみた](https://qiita.com/ip_design/items/7b52611d756043b5eb3b)
- [形態素解析エンジン MeCabをPythonで利用する](https://emotionexplorer.blog.fc2.com/blog-entry-349.html)