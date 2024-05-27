# my_sommelier
### サービス概要
- ワインタイプ診断から自分の好みにあったワインがおすすめされるサービス
- 診断されたワインタイプをもとに、スーパーやコンビニなど身近で買えるワインが表示される
- 様々なワインタイプを通してワインの知識が広まる


### このサービスへの思い・作りたい理由
- ワインが好きで、ソムリエとして飲食店で色々なお客様にワインをお勧めしてきた。

飲食店でワインを提供していた時、ワインの楽しさを感じてくれ、ハマっていくお客様やスタッフを見てきた。自分自身もワインに出会ってから、日々の食卓や外食先、旅行先での楽しみが増え、人生が豊かになった。「ハードルが高い」と思われがちなワインで、日常が豊かになる感覚をより多くの人に広めたい。
だが、自分自身も最初は何から飲めばいいか、どうやって知識を広めていけばいいか分からなかった。そんな人のために、ワインを楽しむステップとなるツールを作りたい。


### ユーザー層について
- ワインに興味はあるが、何を買っていいか分からない、ワイン初心者向け


　ワインショップやレストランのメニューに記載されているワインコメントは、ワイン初心者にとっては少し難しく、専門用語も多い。その説明で何が書かれているか分からず、ワインを買うのをやめてしまったり、他の馴染みのあるドリンクを注文してしまう。ワインはもっと親しみやすく楽しいものだと伝えたい。そのためにも、深くはまっていくための道標や順序をわかりやすく伝えたい。


### サービスの利用イメージ
- ワインを楽しむためには、まずは自分がどんなワインが好きか、を知ることが大事だと考える。ワインをタイプに分け、自分の好みという視点から分類されたワインに触れる。タイプの違いを知ることでワインを自分の中でジャンル分けすることができ、捉えやすくなる。

- 雑誌やネットでは専門的で細かい情報が出過ぎてしまって、何から試せばいいか分からない人向けに、その人へのおすすめワインや、診断を通して入門的な知識とワインをわかりやすく伝える

- 利用シーン別おすすめワインでは、その日の気分やシーンによって合うワインをソムリエに相談する感覚で、ワイン選びをすることができる


### ユーザーの獲得について
- SNSで流れてきてサービスを知る


### サービスの差別化ポイント・推しポイント
- 既存サービスだと情報量が多すぎたり、ある程度知識が前提として必要。結果的にワインに対するハードルが高くなってしまう→情報を絞り、わかりやすい表現にする
- 日本のスーパーやコンビニで手に入りやすいものをお勧めする（アルパカ、コノスルを含む）
- 好み診断だけでなく、「今日の食事（イタリアン、和食、フレンチ、つまみ）」や「利用シーン（友人とのホームパーティー、お祝いの席、恋人とのデート、疲れている時の一人飲み）」からもおすすめできる
- 自分の飲んだワインを投稿できる（投稿者のワインタイプも表示され、自分に近い好みを持った人の感想が見られる）


### 機能候補
MVP
- 会員登録
- ログイン
- 診断機能
  - 診断結果が「あなたのワインタイプ」として会員情報に登録される
- ワイン一覧
  - 産地別
  - ワインタイプ別
- お気に入り機能
- 利用シーン別おすすめワイン

本リリース
- 「今日の食事」別おすすめワイン
- 投稿機能
  - 投稿者の「ワインタイプ」が表示され、自分の好みに近い人の投稿が確認できる


### 機能の実装方針予定
- ユーザ登録及び認証機能: Sorcery
- 診断、レコメンド機能：アルゴリズム