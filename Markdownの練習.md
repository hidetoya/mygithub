
# Markdownメモ

## bold (VSC)
**text**

## italic (VSC)
*text*

## quote (VSC)
> text

## code (VSC)
`text`

## heading (VSC)
\# text

VSC, github.com では \# の後空白が必須。Qiitaは不要らしい。

## Tables (GFM)
prefix  |body
--------|-------
bold		|**text**
italic	|*text*
quote		|> text
code		|`text`
heading	|# text

プレビューは GitHub Flavored Markdown の Tablesに対応。

## Links (VSC:"link")
[text](http://link)

## Reference-style links
[Goolgeリンク][google]
以前のVSCはこのタイプのリンクに対応していなかったらしいが、
最新のバージョンでは対応済み。

[google]: https://www.google.co.jp/

## Images (VSC:"image")

![sample of image](./image.png)


ここからは長いっ。最初の数文字を入力して c+spc すればいいけど

## fenced codeblock (VSC)(GFM)
```language

```
for example:
```javascript
	console.log("hello, world.")
```
これはGFMだけど VSCで 基本言語サポート となっている。

## unordered list (VSC)
- first
- second
- third

## ordered list (VSC)
1. first
2. second
3. third

## horizontal rule (VSC)

----------
↑この上は空行が必須(でないと見出しと判断されてしまう)

## emoji
:smile:
さすがに これは VSC でも未対応。

## 参考
* VSC: Markdown の基本言語サポート; このマークが付いてるものは [file:C:\Program%20Files\Microsoft%20VS%20Code\resources\app\extensions\markdown-basics\snippets\markdown.json](file:C:\Program%20Files\Microsoft%20VS%20Code\resources\app\extensions\markdown-basics\snippets\markdown.json) に 含まれるスニペットで、`C+spc`で呼び出すことができる。
    * なお VSCは、textのない裸のリンク(GFM)には対応しているが、fileスキームの場合、略式のURIはNGで、"`file:///...`"で始まるものにしなければならない(これ以降のパスの区切りはバックスラッシュでもOK。これでもプレビューからリンク先を表示できないが、ソースファイルからctrlキー併用でリンク先を表示することができる)。あるいは従来からのリンク "`\[...\](...)`" で記述する(こちらはスキーム区切りのない "`file\:C:\...`" でもよい)。
* 高機能エディタ『VScode』をもっと便利にするおすすめの使い方 - プロクラシスト  
http://www.procrasist.com/entry/vscode-fallinlove
