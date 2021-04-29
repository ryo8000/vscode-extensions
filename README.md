# Visual Studio Code Extensions

### English | [日本語](./README_JP.md)

These are the recommended extensions for Visual Studio Code.

Within each section, the recommended extensions are listed in order from the top.

---

### Basic

#### [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

- This extension displays an icon according to the file extension or directory name.
- This makes it easier to understand what kind of files and directories they are.
- vscode-icons is more popular, but this extension covers a wider range of topics.

![fileIcons](https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/master/images/fileIcons.png)

---

### Git

#### [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

- This extension allows you to see the commit history, file diffs, etc. in the activity bar.
- This extension also allows the commit message to be showed at the end of the line.

#### [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)

- This extension allows you to see the commit history, file diffs, etc.
- The Git logs are showed as a tree diagram. This makes it easier to keep track of your logs.

#### [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)

- This extension allows you to check GitHub Pull Requests in the activity bar.
- You can also check the changed files and differences.

---

### TODO

#### [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

- This extension your code searches for annotations like TODO and FIXME, and displays them in the activity bar.
- Found annotations can be highlighted in the open file.

#### [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

- Highlight TODO, FIXME and other annotations.
- You may not need this extension if you have Todo Tree.

---

### Various services

#### [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

- This extension allows you to manipulate Docker containers, images, etc. in the activity bar.
- You can also control Docker by right-clicking on the docker-compose file in the sidebar.
- There is also a completion function for Dockerfile and docker-compose.

#### [AWS Toolkit](https://marketplace.visualstudio.com/items?itemName=AmazonWebServices.aws-toolkit-vscode)

- This extension allows you to perform various operations such as calling AWS Lambda in the activity bar.
- You can also generate a template for AWS SAM.

---

### Formatting and Completion

#### [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

- This extension is code formatter that supports various types of files.
- This extension does not work just by installing it; you need to edit the VSCode settings (settings.json).
- This extension performs code formatting based on the set rules, but does not perform syntax checking. It is recommended that this extension be used in conjunction with an extension that performs syntax checking for the language you use.

#### [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

- This extension catches spelling errors and displays them with squiggly underline. It is recommended to install it to prevent typos.
- The detected words also appear in the problems tab of the panel.
- This extension allows you to type command + . (Ctrl + .) to see the suggested words and convert the target word.

![example](https://raw.githubusercontent.com/streetsidesoftware/vscode-spell-checker/master/packages/client/images/example.gif)

#### [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)

- This extension colorizes brackets. Pairs of brackets have the same color.
- A line of the same color as the bracket will also be showed between the brackets.
- This extension makes it easier to see which brackets are paired with each other.

![example](https://raw.githubusercontent.com/CoenraadS/BracketPair/master/images/example.png)

#### [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)

- This extension provides AI-powered input completion. Candidates selected by prediction are marked with ★.

#### [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

- It colors the indentations. The colors changes depending on the depth of the indentation.
- This extension makes it easier to see how deep the indentation is.
- If the indentation is not aligned or tabs and spaces are mixed, it highlights them.

![example](https://raw.githubusercontent.com/oderwat/vscode-indent-rainbow/master/assets/example.png)

#### [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

- This extension automatically converts the paired tags when renaming HTML/XML tags.
- This extension also works when HTML/XML format strings are written as variable values in JavaScript, etc.

![example](https://raw.githubusercontent.com/formulahendry/vscode-auto-rename-tag/master/images/usage.gif)

#### [Highlight Matching Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)

- It highlights paired tags in HTML/XML files.
- This extension also works when HTML/XML format strings are written as variable values in JavaScript, etc.
- That highlighting is a little hard to see with the default settings, so you may want to change the highlighting style.

#### [change-case](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case)

- This extension allows you to convert words into CamelCase, PascalCase, SnakeCase, and other notations.

#### [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

- If you type ">" in an HTML/XML file, it will automatically add the closing tag.
- HTML can be configured to add closing tags automatically by turning on "Auto Closing Tags" in the VSCode setting. In that case, this extension is not necessary.

#### [Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)

- It highlights spaces at the end of lines.
- By turning on "trimTrailingWhitespace" in the VSCode settings, you can set it to automatically remove it when saving. In that case, this extension is not necessary.

![example](https://shardulm94.gallerycdn.vsassets.io/extensions/shardulm94/trailing-spaces/0.3.1/1554790489790/Microsoft.VisualStudio.Services.Icons.Default)

---

### Remote

#### [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)

- This extension enables real-time collaborative editing and debugging with multiple people (Microsoft or GitHub account required).
- You can also text chat and voice chat (You need to install the extension named "Live Share XXX" separately).
- It makes pair programming easier.
- Since the guest accesses the environment of the host machine, there is no need to build the environment on the guest side.

---

### Various Files

#### [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)

- For CSV / TSV development. It shows each column in a different color.
- Tooltip for number of columns and header when hovering the cursor over them.
- Click "Align" in the status bar to adjust the column width and align the vertical start position.
- Click "Query" in the status bar to view the data in table format. You can also extract data as if you use SQL.

#### [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

- This extension allows you to use useful shortcut keys when writing Markdown.
- Sample: Ctrl + B for **bold**。Alt + S for ~~strikethrough~~。

#### [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)

- This extension allows you to edit Markdown while viewing a preview of it.
- You can also view the preview in Markdown All in One, but the layout is different, so you may want to use this one if you prefer.

#### [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)

- For XML development.

#### [XML to JSON](https://marketplace.visualstudio.com/items?itemName=buianhthang.xml2json)

- This extension allows you to convert XML to JSON.

#### [Json Editor](https://marketplace.visualstudio.com/items?itemName=nickdemayo.vscode-json-editor)

- This extension allows you to shows JSON in a tree format.

#### [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

- This extension allows you to generate classes and functions for Java, TypeScript, etc. from JSON.

![example](https://raw.githubusercontent.com/quicktype/quicktype-vscode/master/media/demo-interactive.gif)

#### [SQL Formatter](https://marketplace.visualstudio.com/items?itemName=adpyke.vscode-sql-formatter)

- For .sql file development.
- It does not behave well, for example, it does not recognize "for update".

#### [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)

- For .env file development.

#### [systemd-unit-file](https://marketplace.visualstudio.com/items?itemName=coolbear.systemd-unit-file)

- For unit file development.

#### [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)

- For PlantUML development. This extension allows you to edit while viewing a preview.
- It requires a java runtime environment.

#### [Graphviz (dot) language support for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=Stephanvs.dot)

- For developing ER diagrams in PlantUML.
- It requires a java runtime environment.

#### [Draw.io Integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)

- For Draw.io development.
- There are some differences from the web browser version.

#### [Log File Highlighter](https://marketplace.visualstudio.com/items?itemName=emilast.LogFileHighlighter)

- This extension adds color highlighting to log files.
- If the default behavior is sufficient, this extension is not necessary.

---

### Front End

#### [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

- This extension allows you to send HTTP requests based on what you write in the editor.
- It also supports cURL requests and GraphQL requests.
- This extension automatically generates the code to send a request according to various languages by typing command + option + C (Ctrl + Alt + C).
- Syntax highlighting and code completion support is available by setting the text file extension to .http or .rest.
- You can use variables in the file. (only if it is .http or .rest)
- The sample file is [here](./sample/REST_Client.http).

#### [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

- If you hover over the CSS color code, it shows you the picker.
- You can also change the color with the picker.

#### [open in browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)

- This extension allows you to open HTML files in your browser. This is good if you want to check it quickly on the spot.
- Files that need to be compiled, such as .vue files, cannot be opened.

#### [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

- This extension allows you to start a local server by clicking "Go live" in the status bar.
- Start it at http://127.0.0.1:5500 .
- You will not use it if you start a local server using Docker and check HTML, etc.

#### [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)

- HTML Snippet Pack.
- This is provided in VSCode, so you do not need to install it.
- For more information on snippets, see [here](./doc/VSCode_snippets.md).

### JavaScript

#### [JavaScript Snippet Pack](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-javascript-snippet-pack)

- JavaScript Snippet Pack. This does not contain snippets for JavaScript in ES6 syntax or later.
- For more information about the snippets provided in VSCode, see [here](./doc/VSCode_snippets.md).

```js
// Sample:
// Type ae
document.addEventListener('load', function (e) {
  // body
});
// Type pr
object.prototype.method = function(arguments) {
  // body
}
// Type gi
document.getElementById('id');
// Type jp
JSON.parse(obj);
// Type us
'use strict';
```

#### [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)

- JavaScript Snippet Pack. This contains snippets for JavaScript in ES6 syntax.

```js
// Sample:
// Type imp
import moduleName from 'module';
// Type req
const packageName = require('packageName');
// Type ecl
export default class className {
};
// Type nfn
const name = (params) => {
}
// Type dob
const {propertyName} = objectToDestruct;
// Type prom
return new Promise((resolve, reject) => {
});
// Type thenc
.then((result) => {

}).catch((err) => {

});
```

#### [jQuery Code Snippets](https://marketplace.visualstudio.com/items?itemName=donjayamanne.jquerysnippets)

- jQuery Snippet Pack.

```js
// Sample:
// Type jqClick
$(selector).click(function (e) {
  e.preventDefault();

});
// Type jqGet
$.get("url", data,
  function (data, textStatus, jqXHR) {

  },
  "dataType"
);
```

#### [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)

- For JavaScript development. This extension allows you to generate a documentation comment template by typing /\*\* and then Enter, or control + option + D (Ctrl + Alt + D) twice.
- Documentation comments are also provided in VSCode from the beginning, but it does not behave well, for example, @return is not generated, so it is recommended to disable it and use this extension. (The default documentation comments can be disabled by turning off the VSCode setting "completeJSDocs".)

#### [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)

- This extension executes and evaluates JavaScript or TypeScript code in real time.
- You will need to write the JavaScript code in the file opened by typing command + K → J (Ctrl + K → J). If command + K → J (Ctrl + K → J), then TypeScript code.
- This is good if you want to try out a small piece of code to see how it works.
- You can also check the coverage of the code you have written.
- The disadvantage is the high frequency of notifications.

#### [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)

- For Vue.js development.

#### [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script)

- This extension allows you to run npm scripts defined in package.json.
- You can also check if a module is already installed.
- There is also a yarn version of this.

#### [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)

- It shows the size of the imported file in JavaScript or TypeScript.

### Perl

#### [Perl](https://marketplace.visualstudio.com/items?itemName=henriiik.vscode-perl)

- For Perl development.

### Python

#### [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

- For Python development.
- For more information about the snippets provided, see [here](./doc/Python_snippets.md).

#### [Python Docstring Generator (autoDocstring)](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)

- For Python development. This extension allows you to generate a documentation comment template by typing " three times and then Enter.
- You can also change the documentation comments to Google style or numpy style.

#### [Python Extended](https://marketplace.visualstudio.com/items?itemName=tushortz.python-extended-snippets)

- For Python development. It shows you more input suggestions.
- If you also install python snippets, you will get a large number of input suggestions.

#### [python snippets](https://marketplace.visualstudio.com/items?itemName=frhtylcn.pythonsnippets)

- Python Snippet Pack.
- However, it is better to think of it as the extension that displays usage examples rather than a regular snippet.

```py
# Sample:
# Type built_in.type=>
a = ('apple', 'banana', 'cherry')
b = 'Hello World'
c = 33
x = type(a)
y = type(b)
z = type(c)

# Type for=>
fruits = ['apple', 'banana', 'cherry']
for x in fruits:
  print(x)

# Type list.comp=>_5
x = [double(x) for x in range(10) if x%2==0]
print(x)

# Type class=>with_attribute_1
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

### Ruby

#### [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)

- For Ruby development.

#### [erb](https://marketplace.visualstudio.com/items?itemName=CraigMaslowski.erb)

- For developing .erb files in Ruby.

### Other

#### [Regex Previewer](https://marketplace.visualstudio.com/items?itemName=chrmarti.regex)

- This extension allows you to easily check the behavior of regular expressions

![example](https://raw.githubusercontent.com/chrmarti/vscode-regex/master/images/in_action.gif)
