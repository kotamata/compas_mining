# compas_mining

### ファイルの説明
1. compas_train_mining.csv
 - compasの訓練データをone-hot encodingでバイナリー化したデータ
   - 元々の特徴量数 : 7
   - バイナリー化した特徴量数 : 19
2. compas_test_mining.csv
- compasのテストデータをone-hot encodingでバイナリー化したデータ
 - 元々の特徴量数 : 7
 - バイナリー化した特徴量数 : 19
3. term_dict.txt
- https://github.com/corels/corels のdata/compas_train.outファイルの中のマイニングされた分岐条件（antecedents, cond）のみを取り出し、辞書化したファイル

4. term_dict.pkl
- term_dict.txt をpklファイルにしたもの

5. term_over1.pkl
- https://www.aaai.org/GuideBook2018/16343-70634-GB.pdf の論文の実験と合わせるため、term_dictの中からラベルの割合が50％以上のタームを取り出したファイル


出来たプログラム

https://colab.research.google.com/drive/1LNxWPS-lYxhij1YTGmzAHbVxVJweCvh3?usp=sharing 
