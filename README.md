Coding Style
====

コーディングスタイル、命名規約。

一般的なルール
====

+ UpperCamelCase - 大文字キャメルケース
+ lowerCamelCase - 小文字キャメルケース
+ UPPER\_SNAKE\_CASE - 大文字スネークケース
+ lower\_sname\_case - 小文字スネークケース
+ UPPER-CHAIN-CASE - 大文字ハイフン区切り
+ lower-chain-case - 小文字ハイフン区切り

※参考: [キャメルケース](https://ja.wikipedia.org/wiki/キャメルケース)

UpperCamelCase - 大文字キャメルケース
----

Javaクラス名など

lowerCamelCase - 小文字キャメルケース
----

Javaメソッド名、変数名など

UPPER_SNAKE_CASE - 大文字スネークケース
----

Java static final 定数

lower_sname_case - 小文字スネークケース
----

???

UPPER-CHAIN-CASE - 大文字ハイフン区切り
----

???

lower-chain-case - 小文字ハイフン区切り
----

???

DB/SQL
====

1. select COL\_NM from TAB\_NM
2. SELECT col\_nm FROM tab\_nm
3. SELECT COL\_NM FROM TAB\_NM
4. select col\_nm from tab\_nm

1か2がいいけど、3でも4でも。どれがいいかな。  
1がいい。理由はテーブル名やカラム名を注目させたい目立たせたいから。

ファイル名
====

通常ファイル名
----

lower-chain-case - 小文字ハイフン区切り

Javaファイル名
----

UpperCamelCase - 大文字キャメルケース

JSON
====

lowerCamelCaseかlower\_sname\_caseが良い。  
lower-chain-caseはJavaやJavaScriptで扱いにくい。

```JSON
{
    "lower_sname_case": "これか",
    "lowerCamelCase": "これだな",
    "lower-chain-case": "それはない"
}
```

URL/API
====

URLは小文字がいいと思う。  
ファイル名にも使うlower-chain-caseがいい。  
lower\_sname\_caseでもいいかな。

```
/xyz/
/xyz/index.html
/xyz/api/users
```
