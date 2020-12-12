# Markdown について学んでみた

As Kanye West said:

> We're living the future so
> the present is our past.


```markdown
シンタックスハイライト付きのコードブロック

# 見出し1
## 見出し2
### 見出し3
...
###### 見出し6

- 点の
- リスト
  * 点の
  * リスト

1. 数字の
2. リスト

""ボールド""

_イタリック_ 

`コード` 

普通の文章

[リンク](アドレス)
![画像](アドレス)

quote:
> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

tasks lists:
- [x] This is a complete item
- [ ] This is an incomplete item

table:
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

@mentions:
@tn991 who the f r u

Strikethrough:
~Any word wrapped with two \~s will appear crossed out.~

Emoji:
:+1:, :sparkles:, :camel:, :tada:, :rocket:, :metal:, :octocat:, etc.

backslash escape
\ followed by {\,`,*,_,{,},[,],(,),#,+,-,.,!}

```


# 見出し1
## 見出し2
### 見出し3
...
###### 見出し6

- 点の
- リスト
  * 点\*の
  * リスト

1. 数字の
2. リスト

""ボールド""

_イタリック_ 

`Code` 

普通の文章

[リンク](https://mapotofu9.github.io/)
![画像](octocat(2).png)

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

tasks lists:
- [x] This is a complete item
- [ ] This is an incomplete item

> When you include a task list in the first comment of an Issue, you will see a helpful progress bar in your list of issues. It works in Pull Requests, too!
> If you include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list. It also works in Pull Requests!

table:
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

@mentions:
@tn991 who the f r u

Strikethrough:
~Any word wrapped with two \~s will appear crossed out.~

Emoji:
:+1:, :sparkles:, :camel:, :tada:, :rocket:, :metal:, :octocat:, etc.
https://help.github.com/articles/basic-writing-and-formatting-syntax/#using-emoji
https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md

### Syntax guide(basic):
- Headers:#
- Emphasis:*,_
- List:*,[0-9]
- Img:![name](path), Format: ![Alt Text](url)
- Link:http://url - automatic, [link name](url)
- Quotes:>
- Inline code:`code`

### GFM(GitHub Flavored Markdown)
- Syntax highlighting: ```
- Task Lists
- Tables
- SHA references
- Issue references within a repository
- @mentions
- Automatic linking(URL)
- Strikethrough:
- Emoji: :+1:

see [this cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) and [this](https://guides.github.com/features/mastering-markdown/) for reference.
