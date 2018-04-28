◆《参考》高機能エディタ『VScode』をもっと便利にするおすすめの使い方 - プロクラシスト
http://www.procrasist.com/entry/vscode-fallinlove


# [Markdown の基本言語サポート][note1]


## bold (VSC)
**text**

## italic (VSC)
*text*

## quote (VSC)
> text

## code (VSC)
`text`

## heading (VSC)
\# 
VSCでは \# の後空白が必須

## Tables (GFM)
prefix  |body
--------|-------
bold		|**text**
italic	|*text*
quote		|> text
code		|`text`
heading	|#
プレビューは GitHub Flavored Markdown の Tablesに対応

## Links (VSC:"link")
[text](http://link)

## Reference-style links
[Goolgeリンク][google]

## Images (VSC:"image")
<!-- 
![alt](http://link)
 -->

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

[note1]: file:C:\Program%20Files\Microsoft%20VS%20Code\resources\app\extensions\markdown-basics\snippets\markdown.json
[google]: https://www.google.co.jp/

## emoji
:smile:
さすがに VSC でも未対応
