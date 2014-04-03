# PreFormatted coding
## Indent
Indents as you think proper.

* Indent length is 2 with space-only.
 * Because dislike dependent tab length.

good coding:

    if x > 0
      if y > 0
        puts “x > 0 && y > 0”
      end
    end

## display digit
* characters per line is 80.

## blank-line
* separate some classes.
* separate methods, attributes, and more that inner class; but ignore first/last line

good coding:

    class Foo
      …
    end
     
    class Bar
      …
    end

bad coding:

    class Foo
      …
    end
    class Bar
      …
    end

good coding:
    
    class Foo
      attr :bar
       
      def baz
        …
      end
      
      def quux
        …
      end
    end

bad coding:

    class Foo
    
      attr :bar
       
      def baz
        …
      end
      
      def quux
        …
      end
    
    end

## Comment
* Don't written comment inner method.
 * Because Just do refactering when you need comments.
* Class, Module and public-method need describe the behavior in RDocSyle.

    # コンマ区切の文字列+str+を分割し、結果を配列にして返す。
    def split_csv(str)
      return str.split(/,/)
    end

# Syntax Rule
## クラスの構成要素
## アクセサの定義
## メソッドの定義
## クラスメソッドの定義
## メソッド呼び出し
## Block

## return
* MUST use return when method expectation the return value.
* return syntax without parenthesis.

## yield
## 条件分岐
## looping
## 論理演算子
## 三項演算子
## 文字列リテラル
# 命名規約
## General
## Class/Module
## Method
## 定数名
## 変数名
## ファイル名
