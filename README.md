# Visual Studio Code 拡張機能

使ってみた Visual Studio Code の拡張機能です。
基本的には各項目内で、上から順に良かった機能を並べています。

---

### 基本

#### [Japanese Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-ja)

- VSCode を日本語化。

#### [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

- 拡張子に合わせてアイコンを表示してくれる。
- vscode-icons の方が人気だが個人的にはこちらの方が好み。

![fileIcons](https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/master/images/fileIcons.png)

---

### Git

#### [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

- アクティビティバーからコミットの履歴やファイルの差分などを確認できるようになる。
- コミット時のコメントが、行末に表示されるようになる。

#### [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)

- コミットの履歴やファイルの差分などを確認できるようになる。
- Git log が樹形図で表示されるため見やすい。

#### [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)

- アクティビティバーから GitHub 上の Pull Request が確認できるようになる。
- 変更ファイルや差分も確認することも可能。

---

### TODO

#### [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

- TODO や FIXME などのアノテーションコメントを検索し、アクティビティバーに表示してくれる。
- Todo+ も人気だが個人的にはこちらの方が好み。

#### [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

- TODO や FIXME などのアノテーションコメントを強調表示してくれる。
- Todo Tree があれば不要かもしれない。

---

### 各種サービス

#### [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

- アクティビティバーから Docker コンテナやイメージの操作などが行えるようになる。
- サイドバーから docker-compose ファイルを右クリックして操作もできる。
- Dockerfile、docker-compose の入力補完機能もある。

#### [AWS Toolkit](https://marketplace.visualstudio.com/items?itemName=AmazonWebServices.aws-toolkit-vscode)

- アクティビティバーから AWS 上の Lambda を呼び出しなどが行えるようになる。
- AWS SAM のひな形を生成することも可能。

---

### 整形・入力支援

#### [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

- 各種ファイルに対応したコードフォーマッター。
- VSCode の設定「Format On Save」を ON にすることで、保存時にソースコードを自動で整形してくれる。

#### [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

- スペルミスを検出して、波線で表示してくれる。
- パネルの問題タブにも表示される。
- 「Ctrl + .」で候補の単語を表示し、スペルミスの単語を変換することができる。

![example](https://raw.githubusercontent.com/streetsidesoftware/vscode-spell-checker/master/packages/client/images/example.gif)

#### [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)

- 括弧に色がつくようになる。ペアの括弧は同じ色になる。
- ぱっと見でどの括弧がどれに対応するのかが分かりやすくなる。
- 新たに [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2) が出ているので、そちらをインストールすること。

![example](https://raw.githubusercontent.com/CoenraadS/BracketPair/master/images/example.png)

#### [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)

- AI による入力補完。予測によって選ばれた補完の候補には ★ 印が付く。

#### [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

- インデントを虹色で表示してくれる。
- インデントが揃ってなかったりタブとスペースが混在していると強調表示してくれる。

![example](https://raw.githubusercontent.com/oderwat/vscode-indent-rainbow/master/assets/example.png)

#### [EvilInspector](https://marketplace.visualstudio.com/items?itemName=saikou9901.evilinspector)

- 全角スペースを強調表示してくれる。
- zenkaku の方が人気だが、zenkaku と違い、常時有効化の設定をする必要がない。

#### [zenkaku](https://marketplace.visualstudio.com/items?itemName=mosapride.zenkaku)

- 全角スペースを強調表示してくれる。
- デフォルトの設定では、VSCode を起動するたびに有効化する必要があるので、設定の変更を推奨。
  （.vscode/extensions/mosapride.zenkaku-◯.◯.◯/extension.js の 下記値を true に変更する。）

```js
var enabled = false;
```

![example](https://raw.githubusercontent.com/mosapride/vscode-zenkaku/images/readme01.png)

#### [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

- HTML/XML タグの名前を変更する際に、ペアになっているタグも自動的に変換してくれる。
- JavaScript などで変数の値として HTML/XML 形式の文字列を記述した場合にも反応する。

![example](https://raw.githubusercontent.com/formulahendry/vscode-auto-rename-tag/master/images/usage.gif)

#### [Highlight Matching Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)

- HTML/XML ファイルでペアのタグをハイライトしてくれる。
- JavaScript などで変数の値として HTML/XML 形式の文字列を記述した場合にも反応する。
- デフォルト設定では少々見づらいので、スタイルを変更しても良いかもしれない。

#### [change-case](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case)

- 単語をキャメルケース、パスカルケース、スネークケースなどの記法に変換できるようになる。

#### [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

- HTML/XML ファイルで「>」を入力すると、終了タグを自動的に追加してくれる。
- HTML は、VSCode の設定「Auto Closing Tags」を ON にすることで、自動で終了タグを追加するよう設定できる。その場合この拡張機能は不要。

#### [Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)

- 行末のスペースを強調表示してくれる。
- VSCode の設定「trimTrailingWhitespace」を ON にすることで、保存時に自動で削除するよう設定できる。その場合この拡張機能は不要。

![example](https://shardulm94.gallerycdn.vsassets.io/extensions/shardulm94/trailing-spaces/0.3.1/1554790489790/Microsoft.VisualStudio.Services.Icons.Default)

---

### リモート

#### [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)

- 複数人とリアルタイムで共同編集およびデバッグができるようになる。（Microsoft アカウントか GitHub アカウントが必要）
- テキストチャットとボイスチャットも可能。（別途、Live Share 〇〇 と名のついた拡張機能のインストールが必要）
- ペアプログラミングが容易できるようになる。
- ホスト側マシンの環境にゲストがアクセスするかたちになるので、ゲスト側で環境構築が不要になる。

---

### 各種ファイル

#### [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)

- CSV/TSV 開発用。列ごとに色分けして表示してくれる。
- カーソルを乗せると列数とヘッダをツールチップで表示。
- ステータスバーの「Align」をクリックすると、カラム幅を調整して縦の開始位置を揃える。
- ステータスバーの「Query」をクリックすると、テーブル形式で表示。SQL っぽくデータを抽出することもできる。

#### [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

- Markdown を記述する際に便利なショートカットキーが使えるようになる。
- 例）「Ctrl + B」で**太字**。「Alt + S」で~~取り消し線~~。

#### [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

- Markdown のプレビューを表示しながら編集できるようになる。
- エディター内上部のプレビュー表示アイコンからでも、Markdown All in One でもプレビューは表示できるが個人的にはこちらの方が好み。

#### [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)

- XML 開発用。

#### [XML to JSON](https://marketplace.visualstudio.com/items?itemName=buianhthang.xml2json)

- XML を JSON に変換できるようになる。

#### [Json Editor](https://marketplace.visualstudio.com/items?itemName=nickdemayo.vscode-json-editor)

- JSON をツリー形式で表示できるようになる。

#### [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

- JSON から Java や TypeScript などのクラスや関数を生成できるようになる。

![example](https://raw.githubusercontent.com/quicktype/quicktype-vscode/master/media/demo-interactive.gif)

#### [SQL Formatter](https://marketplace.visualstudio.com/items?itemName=adpyke.vscode-sql-formatter)

- .sql ファイル開発用。
- for update を認識できなかったり、少し微妙。

#### [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)

- .env ファイル開発用。

#### [systemd-unit-file](https://marketplace.visualstudio.com/items?itemName=coolbear.systemd-unit-file)

- ユニットファイル開発用。

#### [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)

- PlantUML 開発用。プレビューを表示しながら編集できるようになる。
- Java の実行環境が必要。

#### [Graphviz (dot) language support for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=Stephanvs.dot)

- PlantUML で ER 図などの開発用。
- Java の実行環境が必要。

#### [Draw.io Integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)

- Draw.io 開発用。
- Webブラウザ版とは差異がある。

#### [Log File Highlighter](https://marketplace.visualstudio.com/items?itemName=emilast.LogFileHighlighter)

- .log ファイルに色がつくようになる。
- デフォルトの動作で十分であればこの拡張機能は不要。

---

### フロントエンド全般

#### [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

- エディター上に書いた内容をもとに HTTP リクエストを送信できるようになる。
- cURL リクエスト、GraphQL リクエストにも対応。
- 「Ctrl + Alt + C」で、各種言語に応じたリクエスト送信までのコードを自動生成する。
- テキストファイルの拡張子を .http または .rest にすると、シンタックスハイライトやコード補完のサポートが受けられる。
- 変数を使用できる。（.http または .rest のみ）
- サンプルファイルは[こちら](./sample/REST_Client.http)

#### [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

- CSS のカラーコードにカーソルを乗せると、ピッカーを表示してくれる。
- ピッカーから色を変更することも可能。
- VS Color Picker も人気だが個人的にはこちらの方が好み。

#### [open in browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)

- HTML ファイルをブラウザで開くことが可能になる。その場で素早く確認したい場合など。
- .vue ファイルなどコンパイルが必要なファイルは当然開けない。

#### [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

- ステータスバーの「Go live」をクリックすると、ローカルサーバを起動できるようになる。
- http://127.0.0.1:5500 で起動する。
- 最近は docker で起動させて HTML など確認することが多いので使っていない。

#### [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)

- HTML 用スニペット集。
- VSCode に最初から用意されているのでインストール不要。（詳細は[こちら](./doc/VSCode_snippets.md)）

### JavaScript 系

#### [JavaScript Snippet Pack](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-javascript-snippet-pack)

- JavaScript 用スニペット集。ES6 構文以降のものが含まれていない。
- なお、VSCode に最初から用意されているスニペット集は[こちら](./doc/VSCode_snippets.md)

```js
// 例）
// ae と入力
document.addEventListener('load', function (e) {
  // body
});
// pr と入力
object.prototype.method = function(arguments) {
  // body
}
// gi と入力
document.getElementById('id');
// jp と入力
JSON.parse(obj);
// us と入力
'use strict';
```

#### [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)

- JavaScript 用スニペット集。ES6 構文のものが含まれている。

```js
// 例）
// imp と入力
import moduleName from 'module';
// req と入力
const packageName = require('packageName');
// ecl と入力
export default class className {
};
// nfn と入力
const name = (params) => {
}
// dob と入力
const {propertyName} = objectToDestruct;
// prom と入力
return new Promise((resolve, reject) => {
});
// thenc と入力
.then((result) => {

}).catch((err) => {

});
```

#### [jQuery Code Snippets](https://marketplace.visualstudio.com/items?itemName=donjayamanne.jquerysnippets)

- jQuery 用スニペット集。

```js
// 例）
// jqClick と入力
$(selector).click(function (e) {
  e.preventDefault();

});
// jqGet と入力
$.get("url", data,
  function (data, textStatus, jqXHR) {

  },
  "dataType"
);
```

#### [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)

- JavaScript 開発用。「/\*\*」を入力後 Enter、もしくは「Ctrl + Alt + D」を 2 回実行で、ドキュメンテーションコメントのひな形を生成できるようになる。
- ドキュメンテーションコメント自体は VSCode に最初から用意されているが、@return が生成されないなど挙動が微妙なので、無効にしている。
  （VSCode の設定「completeJSDocs」を OFF にすることで、デフォルトのドキュメンテーションコメントを無効にできる。）

#### [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)

- JavaScript または TypeScript のコードをリアルタイムでコードの内容を実行、評価してくれる。
- 「Ctrl + K」→「J」で開いたファイル内で JavaScript コードを記述する。「Ctrl + K」→「T」で TypeScript。
- ちょっとした処理を試してみたい時に最適。
- 記述したコードのカバレッジも確認できる。
- Pro 版の通知頻度が高く、邪魔に感じる。

#### [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)

- vue.js 開発用。

#### [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)

- package.json で定義された npm スクリプトを実行できるようになる。
- モジュールがインストール済みか確認することも可能。
- yarn 版もある。

#### [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)

- JavaScript や TypeScript で import したファイル容量を表示してくれる。

### Perl 系

#### [Perl](https://marketplace.visualstudio.com/items?itemName=henriiik.vscode-perl)

- Perl 開発用。

### Python 系

#### [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

- Python 開発用。
- 用意されているスニペット集は[こちら](./doc/Python_snippets.md)

#### [Python Docstring Generator（旧：autoDocstring）](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)

- Python 開発用。「"」を 3 回入力後 Enter で、ドキュメンテーションコメントのひな形を生成できるようになる。
- Google スタイルや numpy スタイルに変更することも可能。

#### [Python Extended](https://marketplace.visualstudio.com/items?itemName=tushortz.python-extended-snippets)

- Python 開発用。入力候補をより多く表示してくれる。
- python snippets も入れていると、入力候補が大量に出てくる。

#### [python snippets](https://marketplace.visualstudio.com/items?itemName=frhtylcn.pythonsnippets)

- Python 用スニペット集。
- 普通のスニペットというより、使用例を表示する機能と考えた方がいい。

```py
# 例）
# built_in.type=> と入力
a = ('apple', 'banana', 'cherry')
b = 'Hello World'
c = 33
x = type(a)
y = type(b)
z = type(c)

# for=> と入力
fruits = ['apple', 'banana', 'cherry']
for x in fruits:
  print(x)

# list.comp=>_5 と入力
x = [double(x) for x in range(10) if x%2==0]
print(x)

# class=>with_attribute_1 と入力
class Parrot:

# class attribute
 species = 'bird'

# instance attribute
 def __init__(self, name, age):
    self.name = name
    self.age = age

# instantiate the Parrot class
blu = Parrot('Blu', 10)
woo = Parrot('woo', 15)

# access the class attributes
print('Blu is a {}'.format(blu.__class__.species))
print('Woo is also a {}'.format(woo.__class__.species))
# access the instance attributes
print('{} is {} years old'.format( blu.name, blu.age))
print('{} is {} years old'.format( woo.name, woo.age))
```

### Ruby 系

#### [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)

- Ruby 開発用。

#### [erb](https://marketplace.visualstudio.com/items?itemName=CraigMaslowski.erb)

- Ruby の.erb ファイル開発用。

### その他

#### [Regex Previewer](https://marketplace.visualstudio.com/items?itemName=chrmarti.regex)

- 正規表現の動作確認を手軽に行えるようになる。

![example](https://raw.githubusercontent.com/chrmarti/vscode-regex/master/images/in_action.gif)
