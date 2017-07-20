# deeplearning_handson
Documents and ipynb files for deep learning hands on.

ディープラーニングの入門用のスライドとjupyter用のファイルです。自分も初心者ですが、さらに全くの初心者に説明する用に作成しました。
Anaconda3-4.2.0環境下でtensorflowとkerasをpipで入れた環境で動作を確認しています。

ハンズオンのファイルは、普通のノートパソコンでCPUのみで利用することを前提に作成されています。

流れとしてはDL_handson.pdfを説明した後に、pythonについて簡単に0.numpy_etc.ipnb程度の計算について説明し、ハンズオン開始。

ハンズオンのファイルの内訳は、

　1.TensorflowとKerasを用いて多層パーセプトロンでディープラーニング

　2.TensorflowとKerasで畳み込みニューラルネットワークでディープラーニング

　3.TensorflowとKerasでディープラーニング（犬と猫の2クラス認識）

と3段階になっています。

3の犬と猫の画像データはこちらには含まれていないので、実際に使う場合にはあらかじめhttps://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition からダウンロードしてtestとvalidateに分けて準備しておく必要があります。
