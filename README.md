# python-docker
Python の開発環境を Docker でやってみる試み

# 環境

- centos
- Python3.5.2


# 実行

- `$ docker build -t sample-python .`
- `$ docker run -it --rm --name running-python sample-python /bin/bash`



# 参考
- [Docker上のCentOSにPython3と、関連ライブラリpip, virtualenvとフレームワークDjango, bottle, Flaskのインストール！これらをまとめたDockerfile付き！ - Qiita](http://qiita.com/RyosukeKamei/items/eca9687162b7fe122094)
