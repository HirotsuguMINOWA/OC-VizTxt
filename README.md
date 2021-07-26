OC-NLP : NLP addon for Orange3
==============================

![screenshot](https://github.com/HirotsuguMINOWA/OC-NLP/blob/dev/doc/widgets/fig/workflow1.png)

# License
- Under GPL-3.0
   - This is depended on license of Orange Canvas which is under GPL-3.0.

# Abstract
Orange Canvasは日本語形態素解析に対応してません。Orange Canvasにより形態素解析できれば、[Janome](https://mocobeta.github.io/janome/)を利用した形態素

# Caution
1. ~~使用するPythonバージョン<3.9でなければなりません。~~
   1. ~~Python>=3.9は`orange3`のインストールに失敗する(2021.1.6現在)~~
2. If not showing widgets group "NLP4OC", Please install `orange3-timeseries`.
   1. Then, updated numpy version.

## 本アドオンの動作確認の手順
1. orange3を事前にインストール
   1. `pip install -U orange3`
2. Orange3に本addonを組み込む
   1. `python setup.py install`
3. Orangeを起動してインストールされている事を確認する
   1. `python -m Orange.canvas`


Installation
------------

How to install via https
   `pip install -e git+https://github.com/HirotsuguMINOWA/OC-NLP@master#egg=nlp4oc`

How to install via ssh
   `pip install -e git+ssh://git@github.com/HirotsuguMINOWA/OC-NLP@master#egg=nlp4oc`


To install the add-on, run

    pip install .

To register this add-on with Orange, but keep the code in the development directory (do not copy it to 
Python's site-packages directory), run

    pip install -e .

Documentation / widget help can be built by running

    make html htmlhelp

from the doc directory.

Usage
-----

After the installation, the widget from this add-on is registered with Orange. To run Orange from the terminal,
use

    python -m Orange.canvas

The new widget appears in the toolbox bar under the section Example.

