# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6

# 太字・斜体（文字修飾）
*test*

**Test**

***Test***

# 取り消し線
~~取り消したい文字~~

# 色
<!-- 色名で指定する方法 -->
<font color="red">sample text</font>
<font color="blue">sample text</font>
<font color="green">sample text</font>

<!-- カラーコードで指定する方法 -->
<font color="0c907d">sample text</font>
<font color="ffb677">sample text</font>
<font color="b5592a">sample text</font>

# 改行
テキスト1

テキスト2

テキスト3

テキスト4  
テキスト5

# 入れ子リスト
- リスト1
    - ネスト リスト1_1
        - ネスト リスト1_1_1
        - ネスト リスト1_1_2
    - ネスト リスト1_2
- リスト2
- リスト3

# 番号付きリスト
1. 番号付きリスト1
    1. 番号付きリスト1_1
    1. 番号付きリスト1_2
1. 番号付きリスト2
1. 番号付きリスト3

# 引用
> お世話になります。xxxです。
> 
> ご連絡いただいた、バグの件ですが、仕様です。

# 二重引用
> お世話になります。xxxです。
> 
> ご連絡いただいた、バグの件ですが、仕様です。
>> お世話になります。 yyyです。
>> 
>> あの新機能バグってるっすね

# コードブロック
```html:index/html
<!DOCTYPE html>
<html lang="ja">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Document</title>
    </head>
    <body></body>
</html>
```

# コードブロックのpre記法(スペース4 or タブ)
    # Tab
    class Hoge
        def hoge
            print 'hoge'
        end
    end

---

    # Space
    class Hoge
      def hoge
        print 'hoge'
      end
    end

# code記法
インストールコマンドは `gem install hoge` です

# イタリック体
normal *italic* normal

normal _italic_ normal

# 太字（強調）
normal **bold** normal

# イタリック体と太字の併用
normal ***bold*** normal

normal ___bold___ normal

# 水平線
***
---

# リンク
[Google](https://www.google.co.jp/)

# 定義参照リンク
[こっちからgoogle][google]

その他の文章

[こっちからもgoogle][google]

[google]: https://www.google.co.jp/

# 箇条書きリスト
* 散歩した
* ショッピングした
* 公園へ行った

- リスト1
- リスト2
- リスト3

# 番号付きリスト
1. リスト1
2. リスト2
3. リスト3

# チェックボックス
- [ ] HTML
- [x] CSS
- [ ] VBA

# テーブル
| TH 左寄せ | TH 中央寄せ | TH 右寄せ |
| :--- | :---: | ---: |
| TD | TD | TD |
| TD | TD | TD |

# 画像
![はてな](https://cdn-ak.f.st-hatena.com/images/fotolife/k/kagerou_ts/20171206/20171206105633.jpg)

# 画像リンク
[![はてな](https://cdn-ak.f.st-hatena.com/images/fotolife/k/kagerou_ts/20171206/20171206105633.jpg)
](https://hatenablog.com/) 

# インラインHTML
<font color="red">赤</font>

# エスケープ
`<pre>`

# 特殊文字
&amp;

# コマンド認識
`` ` ``

``` `` ```

` `` ` `` ` ``

[Ctrl]+[S]で上書き保存ができるよ.

# リンク
<http://example.com>

# エスケープ
\   backslash  
`   backtick  
*   asterisk  
_   underscore  
{}  curly braces  
[]  square brackets  
()  parentheses  
#   hash mark  
+   plus sign  
-   minus sign (hyphen)  
.   dot  
!   exclamation mark  

# リンク
[google](https://www.google.co.jp/ "ぐーぐる")と[yahoo](https://www.yahoo.co.jp/ "やふー")  
[あっちにgoogle][google]（その他の文章）[こっちにyahoo][yahoo]  
URL( https://www.google.co.jp/ )だけではリンクは作成されない。  
サイト内は[mdファイル](index.md)の指定で変換できます。

[google]: https://www.google.co.jp/ "ぐーぐるさん"
[yahoo]: https://www.yahoo.co.jp/ (やふーさん)

# リスト
*   Red
*   Green
    *   Blue
---
+   Red
+   Green
    +   Blue
---
-   Red
-   Green
    -   Blue
---
1.  Bird
1.  McHale
    1.  Parish

# エスケープ
\ # タイトル

# コメントアウト
<!-- コメントアウトを書きます -->

# 警告文(Material利用)
!!! Note
    Noteです。

!!! summary
    summaryです。

!!! Tip
    Tipです。

!!! Success
    Successです。

!!! Warning
    Warningです

!!! Failure
    Failureです。

!!! Danger
    Dangerです。

!!! Bug
    Bugです。

 # 注釈(Material利用)
 注釈の 注釈[^1][^2] をつけます。

[^1]: 注釈を付ける単語は左右を半角で空ける  
[^2]: 注釈はページの一番下

# Keys(Material利用)
アプリケーションを強制終了するには ++ctrl+f4++ を押します。

例: <font color="red">sample text</font> → ![sample text](https://via.placeholder.com/15/f03c15/000000?text=+) sample text）

# 注釈
これはテキストです。[^1]

別の文にも注釈を使うことができます。[^2]

[^1]: これが注釈の説明です。
[^2]: 別の注釈の説明です。

# 以下GFM
# リンク
https://www.google.co.jp

# 取り消し線
~~取り消し線~~

# pre記法
~~~
# チルダ
#!/usr/bin/bash
ls | grep hoge
~~~
```
# バッククオート
#!/usr/bin/bash
ls | grep hoge
```

# シンタックスハイライト
~~~bash
# チルダ
#!/usr/bin/bash
ls | grep hoge
export hogehoge=herohero
~~~

# 表組み
|header1|header2|header3|
|:--|:--:|--:|
|align left|align center|align right|
|a|b|c|

# ページ内リンク
## menu
* [to header1](#header1)
* [to header2](#header2)


[return to menu](#menu)
### header1
### header2

<h2><a name="user-content-menu" href="#menu">menu</a></h2>
<a href="#header1">to header1</a>
<a href="#header2">to header2</a>

<!-- some long code -->

<a href="#menu">to menu</a>
<h3><a name="user-content-header1" href="#header1">header1</a></h3>
<h3><a name="user-content-header2" href="#header2">header2</a></h3>

# GitHub Flavored Markdown (GFM) の例

## コードブロックとシンタックスハイライト

```python
def hello_world():
    print("Hello, World!")
```

# 折り畳み
一部のHTMLタグのサポート
<details>
<summary>詳細を表示</summary>
これは詳細の内容です。
</details>

<details>
<summary>すごく長い文章とかプログラムとか</summary>
<div>

```python
print('Hello world!')
```

</div>
</details>

# 絵文字
:smile: :computer: :octocat:

 # リスト
 - 番号なし
- 番号なし
    - 番号なし     <!-- スペース4個 -->
    - 番号なし

1. 番号あり
1. 番号あり
    1. 番号あり
    1. 番号あり  

- [ ] タスクリスト
- [x] タスクリスト
    - [ ] タスクリスト
    - [x] タスクリスト
    - 
# リンク
記法例a  ［表示テキスト](URL)       :  [ホーム](https://github.com/nmakimoto)  
記法例b  ［表示テキスト](#見出し)   :  [先頭へ](#gfmの書き方見え方の確認)  <!-- 見出しはURL向けに微修正 -->  
記法例c !［代替テキスト](画像URL)   : ![画像へ](https://avatars2.githubusercontent.com/u/15310551?v=4&s=60)  
記法例d  ユーザ/リポジトリ#issue    :  (略)  
記法例e  ユーザ/リポジトリ＠コミット:  nmakimoto/nmlib@6508ec7c796bdea1ad72164ed419f67ff089fb8c

# misc
強調:   *Italic*, **Bold**, ***Bold Italic***  
取消:   ~~取消~~       (GFM拡張)  
通知:   @ユーザ名      (例: @nmakimoto)  <!-- 「@」入力で候補一覧 -->  
絵文字: :絵文字コード: (例: :+1:)        <!-- 「:」入力で候補一覧 -->  
エスケープ: 円マーク   (例: \< \> \[ \] \* \@ ...)  

> 引用行1  
> 引用行2  
> > 引用行3  
> > 引用行4  

<!-- 区切り: --- or *** or ___ -->
---

# 注釈
テキスト[^1]  
[^1]: 注釈内容

# 疑似的な注釈
注釈のようなことを実現可能です<sup>[1](#note1)</sup>

<small id="note1">無理やりですが</small>

# info, warn, alert（かんたんMarkdown独自）
<p class="info">**ポイント** ちょっとした情報です。</p>
<p class="warn">**注意** 気をつけてください</p>
<p class="alert">**警告** 細心の注意を払ってください</p>

# CSSの入れ込み

1. るる
    - ～かどうか確認する。
        - ～の場合アレをアレする。
    - ～する。


<div style="color: blue; font-size: 16px; font-weight: bold;">
  これは青くて太字のテキストです。
</div>

<style scoped>
    body {
        font-family: 'MS Gothic';
    }
    li{
        margin-top:1px;
        margin-bottom:1px;
    }
    li:before{
        content: '☑';
        color:#DDDDDD;
        margin-right:3px;
    }

    pre {
        background-color: #f8f8f8;
        border: 1px solid #ccc;
        font-size: 13px;
        line-height: 19px;
        overflow: auto;
        padding: 6px 10px;
        border-radius: 3px;
    }
</style>

