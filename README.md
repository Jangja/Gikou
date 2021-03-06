# 将棋ソフト「技巧」

「技巧」は、2016年の世界コンピュータ将棋選手権で準優勝した将棋ソフトです。
人間的な評価項目(1駒の損得、2駒の効率、3玉の堅さ、4手番)を考慮した隙のない形勢判断などを特徴としています。

オープンソース・ソフトですので、どなたでも無料でお使いいただけます。
「将棋所」や「ShogiGUI」などのソフトに登録してご利用ください。

## 技巧のダウンロード

技巧（Windows版）は、以下のリンクから入手可能です。
皆様の将棋のご検討などにお役立ていただけますと幸いです。
- ダウンロード: https://drive.google.com/uc?id=0B98nJjsRgJHNT04tVXVpUF9RZDA&export=download

技巧の動作環境は、以下のとおりです。
（新しい技術を使っている関係で、古いパソコンでは動作しない場合もございます。）
- OS: 64ビット対応OS（Windows 10、Max OS X、Ubuntu Linux 14.04を推奨） 
- CPU: SSE 4.2 対応のCPU（インテルの Core-i シリーズのCPUを推奨）
- メモリ: 1GB以上の空きメモリ
- ディスク: 512MB以上の空きがあるHDD・SSD（SSDのほうが快適です）

## 使い方

1. 将棋所 または ShogiGUI をあらかじめインストールしておきます
2. 技巧のzipファイルを任意の場所に解凍します（ファイルはすべて同じフォルダに配置してください）
3. 将棋所 または ShogiGUI を起動します
4. 将棋所 または ShogiGUI に技巧の実行ファイル（gikou.exe）を登録します
5. 必要に応じて、技巧のオプションを設定してみてください（定跡などの設定ができます）

設定の方法など、詳しい使い方については、将棋所 や ShogiGUI のホームページをご覧ください。
- 将棋所 http://www.geocities.jp/shogidokoro/
- ShogiGUI https://sites.google.com/site/shogixyz/home/shogigui
 
## 開発者の皆様へ

現在のところ、技巧の推奨開発環境は、以下のとおりです。
- OS: Ubuntu Linux 14.04以上, Mac OS X 10.9.5以上
- コンパイラ等: g++ 4.8以上, make

技巧は、C++11で書かれており、コーディング規約等は概ね以下のページを参考にしています。
- コーディング規約: Google C++ Style Guide, https://google.github.io/styleguide/cppguide.html
- コメント表記: Doxygen, http://www.doxygen.org/

技巧の技術的特徴については、以下のスライドをご参照ください。
- 電王トーナメントPR文書（http://denou.jp/tournament2015/img/PR/Gikou.pdf）
- 世界コンピュータ将棋選手権PR文書（http://www2.computer-shogi.org/wcsc26/appeal/Gikou/gikou_appeal_wcsc26_ver3.pdf）

バグ、不具合、コメントの誤字脱字等を発見をされましたら、ご報告いただけますと幸いです。

## 謝辞

技巧の開発にあたっては、様々な文献やソースコードを参照いたしました。
主要なものについては、ソースコードのコメントやアピール文書等に参考文献として記載させていただいております。
こうした先人の偉大な研究がなければ、技巧を開発することは全く不可能でした。
この場をお借りして、心より御礼申し上げます。

「技巧」開発者 出村洋介