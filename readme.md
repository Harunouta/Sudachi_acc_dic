<h1>Sudachi_acc.dic</h1>
これは<a href= "https://github.com/WorksApplications/Sudachi" >Sudachi</a>にアクセント情報を付与しようと目論んだ辞書です。<br>
辞書未完成のため、終止形の出力やA,B.C単位での出力切り替えといったSudachiらしいことができません。<br>
また、すべてのSudachi辞書にエントリーされている単語には対応していません。現状は対応する単語にのみ「読み」のカラムに情報が追加されています。<br>
<h1>【配布場所】</h1><br>
容量の関係で<a href= "https://drive.google.com/drive/folders/1TcSJvUk8dtSvzZsWVTtfBQDqQ8rKIyvd?usp=sharing" >こちら</a>で配布しています。<br>
<h1>【出力例】</h1>

$ sudachipy -a<br>

選挙管理委員会のアルバイトに応募したいと考えているけどどう思う？<br>
選挙管理委員会	名詞,固有名詞,一般,*,*,*	選挙管理委員会	選挙管理委員会	センキョカンリイインカイ/8.0/C1/*	1	[]<br>
の	助詞,格助詞,*,*,*,*	の	の	ノ/1/C3/*	1	[]<br>
アルバイト	名詞,普通名詞,サ変可能,*,*,*	アルバイト	アルバイト	アルバイト/3/C1/*	1	[]<br>
に	助詞,格助詞,*,*,*,*	に	に	ニ	0	[]<br>
応募	名詞,普通名詞,サ変可能,*,*,*	応募	応募	オーボ/0/C2/*	1	[]<br>
し	動詞,非自立可能,*,*,サ行変格,連用形-一般	為る	する	シ	[]<br>
たい	助動詞,*,*,*,助動詞-タイ,終止形-一般	たい	たい	タイ/1/C3/*	[]<br>
と	助詞,格助詞,*,*,*,*	と	と	ト	0	[]<br>
考え	動詞,一般,*,*,下一段-ア行,連用形-一般	考える	考える	カンガエ	[]<br>
て	助詞,接続助詞,*,*,*,*	て	て	テ	0	[]<br>
いる	動詞,非自立可能,*,*,上一段-ア行,終止形-一般	居る	いる	イル	[]<br>
けど	助詞,接続助詞,*,*,*,*	けれど	けど	ケド/1/動詞%F2@0/*	1	[]<br>
どう	副詞,*,*,*,*,*	どう	どう	ドウ/1/*/*	1	[]<br>
思う	動詞,一般,*,*,五段-ワア行,終止形-一般	思う	思う	オモウ/2/*/*	[]<br>
？	補助記号,句点,*,*,*,*	?	?	キゴウ	0	[]<br>
EOS
<br>
<br>
<br>
<h1>【アクセント核の付与について】</h1>
Unidicに存在する単語は<a href= "https://clrd.ninjal.ac.jp/unidic/back_number.html" >unidic-csj-202302</a>からそのまま取ってきています。<br>
Ipadicに存在する単語は<a href= "https://open-jtalk.sp.nitech.ac.jp/" >OPENJTALK1.11</a>の中にあるmecab-naist-jdicからとってきました。<br>
<a href= "https://github.com/neologd/mecab-ipadic-neologd" >mecab-ipadic-neologd</a>と
Sudachiにしかない単語については、<a href= "https://github.com/PKSHATechnology-Research/tdmelodic/blob/master/docs/index.rst" >tdmelodic</a>で推測したデータを入れました。
<br>
<h1>【動作条件】</h1>
<a href= "https://github.com/WorksApplications/Sudachi" >Sudachi</a>と
<a href= "http://sudachi.s3-website-ap-northeast-1.amazonaws.com/sudachidict/" >sudachi-dictionary-20230711-full</a>
での動作を想定しています。<br>
ユーザー辞書に本辞書(Sudachi_acc.dic)のpathを設定してください。<br>
「読み」のエントリーに入れたので読みを表示(-a)させないと見えません。<br>
<h1>【出力の読みかた】</h1>
<br>
吹奏楽部<br>
吹奏楽部	名詞,普通名詞,一般,*,*,*	吹奏楽部	吹奏楽部	スイソウガクブ/5.0/C1/*	1	[]<br>
EOS<br>
<br>
通常の設定のままならば、<br>
読みの部分に「読み/アクセント型(aType)/アクセント結合型(aConType)/アクセント修飾型(aModType) 」と入っています。詳しい用語の解説は<a href= "https://clrd.ninjal.ac.jp/unidic/UNIDIC_manual.pdf" >unidicのドキュメント</a>へ<br>


<h1>【発表予定】</h1>
本研究は、<br>
YANS 8/30(水): シンポジウム1日目
[17:50-18:50] ポスターセッション (3)
<a href= "https://yans.anlp.jp/entry/yans2023program#1750-1850-%E3%83%9D%E3%82%B9%E3%82%BF%E3%83%BC%E3%82%BB%E3%83%83%E3%82%B7%E3%83%A7%E3%83%B3-3" >[S3-P23] Sudachi+Ginzaを用いた係り受けを考慮したTTS</a> ○青柳詠美 (フリー)<br>
で発表します。特に新しいことはないので、研究・実装・検証のご助言いただけると大変助かります。<br>
<h2>【連絡先】</h2>
青柳　詠美<br>
utaharunomar17@gmail.com
