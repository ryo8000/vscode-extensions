# Visual Studio Code 拡張機能

### [English](./README.md) | 日本語

Visual Studio Code のおすすめの拡張機能です。

基本的には各項目内で、上から順におすすめの拡張機能を並べています。

---

### 基本

#### [Japanese Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-ja)

- VSCode を日本語化します。

#### [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

- ファイルの拡張子や、ディレクトリ名に応じたアイコンを表示します。
- どういったファイル・ディレクトリなのかが分かりやすくなります。
- vscode-icons の方が人気ですが、こちらの方が広くカバーしています。

![fileIcons](https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/master/images/fileIcons.png)

---

### Git

#### [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

- アクティビティバーからコミットの履歴やファイルの差分などを確認できるようになります。
- コミットメッセージが行末に表示されるようになります。

#### [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)

- コミットの履歴やファイルの差分などを確認できるようになります。
- Git の log が樹形図で表示されるため把握しやすくなります。

#### [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)

- アクティビティバーから GitHub の Pull Request が確認できるようになります。
- 変更ファイルや差分を確認することも可能です。

---

### TODO

#### [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

- TODO や FIXME などのアノテーションコメントを検索して、アクティビティバーに表示します。
- 見つかったアノテーションコメントは、開いているファイルの中で強調表示されます。

#### [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

- TODO や FIXME などのアノテーションコメントを強調表示します。
- Todo Tree があれば不要かもしれません。

---

### 各種サービス

#### [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

- アクティビティバーから Docker コンテナやイメージなどを操作できるようになります。
- サイドバーから docker-compose ファイルを右クリックして操作することもできます。
- Dockerfile、docker-compose の入力補完機能もあります。

#### [AWS Toolkit](https://marketplace.visualstudio.com/items?itemName=AmazonWebServices.aws-toolkit-vscode)

- アクティビティバーから AWS 上の Lambda を呼び出しなどの操作ができるようになります。
- AWS SAM のひな形を生成することも可能です。

---

### 整形・入力支援

#### [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

- 各種ファイルに対応したコードフォーマッターです。
- インストールしただけでは機能しません。VSCode の設定（settings.json）を編集する必要があります。
- 設定されたルールに基づいてコード整形しますが、構文チェックは行いません。利用する言語の構文チェックを行う拡張機能と併用することを推奨します。

#### [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

- スペルミスを検出して、波線で表示します。タイプミス防止のためにもインストールすることを推奨します。
- パネルの問題タブにも表示されます。
- command + .（Ctrl + .）で候補の単語を表示し、対象の単語を変換することができます。

![example](https://raw.githubusercontent.com/streetsidesoftware/vscode-spell-checker/master/packages/client/images/example.gif)

#### [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)

- 括弧に色がつきます。ペアの括弧は同じ色になります。
- 括弧の間にも同色の線が表示されます。
- どの括弧がペア関係にあるのかが分かりやすくなります。

![example](https://raw.githubusercontent.com/CoenraadS/BracketPair/master/images/example.png)

#### [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)

- AI による入力補完です。予測によって選ばれた補完の候補には ★ 印が付きます。

#### [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

- インデントをカラーリングしてくれます。インデントの深さによって配色が変わります。
- インデントの深さが分かりやすくなります。
- インデントが揃ってなかったりタブとスペースが混在していると強調表示してくれます。

![example](https://raw.githubusercontent.com/oderwat/vscode-indent-rainbow/master/assets/example.png)

#### [EvilInspector](https://marketplace.visualstudio.com/items?itemName=saikou9901.evilinspector)

- 全角スペースを強調表示します。
- zenkaku の方が人気ですが、zenkaku と違い、常時有効化の設定をする必要がありません。

#### [zenkaku](https://marketplace.visualstudio.com/items?itemName=mosapride.zenkaku)

- 全角スペースを強調表示します。
- デフォルトの設定では、VSCode を起動するたびに有効化する必要があります。設定を変更することを推奨します。
  （.vscode/extensions/mosapride.zenkaku-◯.◯.◯/extension.js の 下記値を true に変更します。）

```js
var enabled = false;
```

![example](https://raw.githubusercontent.com/mosapride/vscode-zenkaku/images/readme01.png)

#### [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

- HTML/XML タグの名前を変更する際に、ペアになっているタグも自動的に変換します。
- JavaScript などで変数の値として HTML/XML 形式の文字列を記述した場合にも反応します。

![example](https://raw.githubusercontent.com/formulahendry/vscode-auto-rename-tag/master/images/usage.gif)

#### [Highlight Matching Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)

- HTML/XML ファイルでペアのタグを強調表示します。
- JavaScript などで変数の値として HTML/XML 形式の文字列を記述した場合にも反応します。
- デフォルト設定では少々見づらいので、スタイルを変更しても良いかもしれません。

#### [change-case](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case)

- 単語をキャメルケース、パスカルケース、スネークケースなどの記法に変換できるようになります。

#### [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

- HTML/XML ファイルで「>」を入力すると、終了タグを自動的に追加します。
- HTML は、VSCode の設定「Auto Closing Tags」を ON にすることで、自動で終了タグを追加するよう設定できます。その場合この拡張機能は不要です。

#### [Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)

- 行末のスペースを強調表示します。
- VSCode の設定「trimTrailingWhitespace」を ON にすることで、保存時に自動で削除するよう設定できます。その場合この拡張機能は不要です。

![example](https://shardulm94.gallerycdn.vsassets.io/extensions/shardulm94/trailing-spaces/0.3.1/1554790489790/Microsoft.VisualStudio.Services.Icons.Default)

---

### リモート

#### [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)

- 複数人とリアルタイムで共同編集およびデバッグができるようになります（Microsoft アカウントか GitHub アカウントが必要です）。
- テキストチャットとボイスチャットも可能です（別途 Live Share 〇〇 と名のついた拡張機能のインストールが必要です）。
- ペアプログラミングが容易できるようになります。
- ホスト側マシンの環境にゲストがアクセスするかたちになるので、ゲスト側で環境構築が不要です。

---

### 各種ファイル

#### [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)

- CSV/TSV 開発用。列ごとに色分けして表示します。
- カーソルを乗せると列数とヘッダをツールチップで表示します。
- ステータスバーの「Align」をクリックすると、カラム幅を調整して縦の開始位置を揃えます。
- ステータスバーの「Query」をクリックすると、テーブル形式で表示します。SQL を使うようにデータを抽出することもできます。

#### [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

- Markdown を記述する際に便利なショートカットキーが使えるようになります。
- 例）Ctrl + B で**太字**。Alt + S で~~取り消し線~~。

#### [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

- Markdown のプレビューを表示しながら編集できるようになります。
- Markdown All in One でもプレビューは表示できますが、レイアウトが異なるので好みに応じてこちらを利用しても良いかもしれません。

#### [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)

- XML 開発用。

#### [XML to JSON](https://marketplace.visualstudio.com/items?itemName=buianhthang.xml2json)

- XML を JSON に変換できるようになります。

#### [Json Editor](https://marketplace.visualstudio.com/items?itemName=nickdemayo.vscode-json-editor)

- JSON をツリー形式で表示できるようになります。

#### [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

- JSON から Java や TypeScript などのクラスや関数を生成できるようになります。

![example](https://raw.githubusercontent.com/quicktype/quicktype-vscode/master/media/demo-interactive.gif)

#### [SQL Formatter](https://marketplace.visualstudio.com/items?itemName=adpyke.vscode-sql-formatter)

- .sql ファイル開発用。
- for update を認識できないなど、あまり挙動が良くありません。

#### [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)

- .env ファイル開発用。

#### [systemd-unit-file](https://marketplace.visualstudio.com/items?itemName=coolbear.systemd-unit-file)

- ユニットファイル開発用。

#### [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)

- PlantUML 開発用。プレビューを表示しながら編集できるようになります。
- Java の実行環境が必要です。

#### [Graphviz (dot) language support for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=Stephanvs.dot)

- PlantUML で ER 図などの開発用。
- Java の実行環境が必要です。

#### [Draw.io Integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)

- Draw.io 開発用。
- Web ブラウザ版とは差異があります。

#### [Log File Highlighter](https://marketplace.visualstudio.com/items?itemName=emilast.LogFileHighlighter)

- .log ファイルにカラーハイライトを追加します。
- デフォルトの動作で十分であればこの拡張機能は不要です。

---

### フロントエンド全般

#### [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

- エディター上に書いた内容をもとに HTTP リクエストを送信できるようになります。
- cURL リクエスト、GraphQL リクエストにも対応しています。
- command + option + C（Ctrl + Alt + C）で、各種言語に応じたリクエスト送信までのコードを自動生成します。
- テキストファイルの拡張子を .http または .rest にすると、シンタックスハイライトやコード補完のサポートが受けられます。
- ファイル内で変数を使用できます（.http または .rest の場合のみ）。
- サンプルファイルは[こちら](./sample/REST_Client.http)

#### [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

- CSS のカラーコードにカーソルを乗せると、ピッカーが表示されます。
- ピッカーから色を変更することも可能です。

#### [open in browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)

- HTML ファイルをブラウザで開くことが可能になります。その場で素早く確認したい場合などに良いでしょう。
- もちろん .vue ファイルなどのコンパイルが必要なファイルは開けません。

#### [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

- ステータスバーの「Go live」をクリックすると、ローカルサーバを起動できるようになります。
- http://127.0.0.1:5500 で起動します。
- Docker でサーバを起動させて HTML などを確認する場合には使う機会が少ないでしょう。

#### [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)

- HTML 用スニペット集です。
- VSCode に最初から用意されているのでインストール不要です。
- このスニペットに関する詳細は[こちら](./doc/VSCode_snippets.md)。

### JavaScript 系

#### [JavaScript Snippet Pack](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-javascript-snippet-pack)

- JavaScript 用スニペット集です。ES6 構文以降のものが含まれていません。
- なお、VSCode に最初から用意されているスニペットに関する詳細は[こちら](./doc/VSCode_snippets.md)。

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

- JavaScript 用スニペット集。ES6 構文のものが含まれています。

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

- JavaScript 開発用。「/\*\*」を入力後 Enter、もしくは control + option + D（Ctrl + Alt + D）を 2 回実行することで、ドキュメンテーションコメントのひな形を生成できるようになります。
- ドキュメンテーションコメント自体は VSCode に最初から用意されていますが、@return が生成されないなど挙動が良くないので、無効にしてこの拡張機能を利用することを推奨します。（VSCode の設定「completeJSDocs」を OFF にすることで、デフォルトのドキュメンテーションコメントを無効にできます。）

#### [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)

- JavaScript または TypeScript のコードをリアルタイムでコードの内容を実行、評価します。
- command + K → J（Ctrl + K → J）で開いたファイル内に、 JavaScript のコードを記述します。command + K → T（Ctrl + K → T）で TypeScript です。
- ちょっとした処理を試してみたい場合に適しています。
- 記述したコードのカバレッジも確認できます。
- 通知頻度が高いのが欠点です。

#### [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)

- Vue.js 開発用。

#### [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)

- package.json で定義された npm スクリプトを実行できるようになります。
- モジュールがインストール済みか確認することも可能です。
- yarn 版もあります。

#### [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)

- JavaScript や TypeScript で import したファイル容量を表示します。

### Perl 系

#### [Perl](https://marketplace.visualstudio.com/items?itemName=henriiik.vscode-perl)

- Perl 開発用。

### Python 系

#### [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

- Python 開発用。
- 用意されているスニペット集は[こちら](./doc/Python_snippets.md)

#### [Python Docstring Generator（旧：autoDocstring）](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)

- Python 開発用。「"」を 3 回入力後 Enter で、ドキュメンテーションコメントのひな形を生成できるようになります。
- Google スタイルや numpy スタイルに変更することも可能です。

#### [Python Extended](https://marketplace.visualstudio.com/items?itemName=tushortz.python-extended-snippets)

- Python 開発用。入力候補をより多く表示します。
- python snippets もインストールしていると、入力候補が大量に出てきます。

#### [python snippets](https://marketplace.visualstudio.com/items?itemName=frhtylcn.pythonsnippets)

- Python 用スニペット集。
- 普通のスニペット集というより、使用例を表示する機能と考えた方が良いでしょう。

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

- 正規表現の動作確認を手軽に行えるようになります。

![example](https://raw.githubusercontent.com/chrmarti/vscode-regex/master/images/in_action.gif)
