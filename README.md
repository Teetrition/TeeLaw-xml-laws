# 中文
本仓库储存[TeeLaw](https://www.teetrition.top)所刊载的日本法令中文译文的对应XML文件。

XML文件基于[e-Gov法令検索（e-Gov法令检索）](https://elaws.e-gov.go.jp/)所提供的[XML Schema](https://elaws.e-gov.go.jp/file/XMLSchemaForJapaneseLaw_v3.xsd)，有部分更改。

## 署名
以下是基于e-Gov要求的署名：

[「法令標準XML スキーマ」（e-Gov）](https://elaws.e-gov.go.jp/file/XMLSchemaForJapaneseLaw_v3.xsd)および[e-Gov法令検索](https://elaws.e-gov.go.jp/)において掲載された諸法令XMLファイルをもとにTeetritionが翻訳・変形等の翻案等をして作成。

Teetrition基于[「法令标准XML Schema」（e-Gov）](https://elaws.e-gov.go.jp/file/XMLSchemaForJapaneseLaw_v3.xsd)及[e-Gov法令检索](https://elaws.e-gov.go.jp/)刊载的各法令XML文件进行翻译、变形等改编制作。

e-Gov的许可协议与CC BY 4.0相兼容。本仓库所有文件基于CC BY-SA 4.0分享。参见LICENSE文件。

## 文件名说明

`140045_5050713`：
* 第1位：`1`为年号（`1`明治，`2`大正，`3`昭和，`4`平成，`5`令和）；
* 第2-3位：`40`为40年；
* 第4-6位：`045`为法律第45号，宪法统一为`000`；
* 第7位：`_`为默认分隔符，`!`代表法例（明治三十一年法律第十号）施行前未明确指定施行日期的法令，`p`代表部分有效。
* 第8位及以后：施行日期。其中第一位为年号，规则同上。如为`0000000`代表施行日期无意义，`0000001`代表尚未施行即被废止。第7位为`!`的法令，该施行日期为最早施行的府县的施行日期。

# 日本語
本レポジトリは、[TeeLaw](https://www.teetrition.top)において掲載される日本国法令の中国語訳のXMLファイルを格納するものである。

これらのXMLファイルは[e-Gov法令検索](https://elaws.e-gov.go.jp/)が提供する[XML スキーマ](https://elaws.e-gov.go.jp/file/XMLSchemaForJapaneseLaw_v3.xsd)に基づくものである。一部変更あり。

## 出典表記
以下は、e-Govの利用規約に基づく出典表記である。

[「法令標準XML スキーマ」（e-Gov）](https://elaws.e-gov.go.jp/file/XMLSchemaForJapaneseLaw_v3.xsd)および[e-Gov法令検索](https://elaws.e-gov.go.jp/)において掲載された諸法令XMLファイルをもとにTeetritionが翻訳・変形等の翻案等をして作成。

e-Govの利用規約は、クリエイティブ・コモンズ・ライセンスの表示4.0 国際（CC BY 4.0）と互換性がある。本レポジトリにおけるすべてのファイルは、CC BY-SA 4.0で利用することができる。詳細はLICENSE（ライセンス）を参照。

## ファイル名について

`140045_5050713`を例として、
* 第1桁：`1`は元号（`1`明治，`2`大正，`3`昭和，`4`平成，`5`令和）。
* 第2-3桁：`40`は40年。
* 第4-6桁：`045`は法律番号。ここは法律第45号。ただし、憲法は一律`000`とする。
* 第7桁：`_`はデフォルト区切り。`!`は法例（明治三十一年法律第十号）施行前、施行期日が明記されないものを示す。`p`は一部有効を示す。
* 第8桁以降：施行期日。その1桁は元号（ルール同上）。
ただし、`0000000`は施行期日が無意味であることを示す。`0000001`は未だ施行されていないうちに廃止されたものを示す。第7桁が`!`である法令は、この施行期日は施行が一番早い府県のものである。