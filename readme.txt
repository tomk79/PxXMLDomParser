

#============================================================================
#	PxXMLDomParser
#	varsion 1.0.4
#	(C)Tomoya Koyanagi.

PxXMLDomParserは、XHTMLなどのXMLファイルをDOM解析し、
特定の部分を抜き出したり、書き換えたりするためのPHPクラスライブラリです。

他のクラスに依存することなく単体で動作します。
オリジナルのクラス名は PxXMLDomParser となっていますが、
環境に合わせて任意に変更しても動作します。
ただし、コンストラクタの関数名も同名にしてください。


【ファイル構成】

PxXMLDomParserライブラリの本体である [PxXMLDomParser.php] のみの構成です。


【インストール】

PHPのお使いの環境の任意の場所に設置してください。

ただし、mbstring が有効である必要があります。


【システム要件】

PHP4系または5系。


【更新履歴】

■PxXMLDomParser 1.0.4 (2013/09/26)
・タグ検索のパフォーマンス向上。

■PxXMLDomParser 1.0.3 (2013/09/01)
・innerHTMLがない閉じタグがある場合に、outerHTMLが閉じない状態で出力される不具合を修正。

■PxXMLDomParser 1.0.2 (2010/09/08)
・属性がない要素をreplace()した時にforeach構文でエラーが起こる不具合を修正。

■PxXMLDomParser 1.0.1 (2010/08/15)
・PHP5系で、大きなデータを扱うと正しく解析できないことがある不具合を修正。
・設定を入出力するためのメソッド config() を追加。
・設定項目 tags_case_sensitive を追加。タグの大文字小文字を区別するかどうか。デフォルトを「区別する」にした。
・設定項目 atts_case_sensitive を追加。属性の大文字小文字を区別するかどうか。デフォルトを「区別する」にした。

■PxXMLDomParser 1.0.0 (2010/01/13)
・初版リリース


【その他の情報】

下記のウェブページを参照してください。
http://www.pxt.jp/ja/service/pxxmldomparser/index.html



#============================================================================
(C)Tomoya Koyanagi.
http://www.pxt.jp/

