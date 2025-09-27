# COM-code
COM-code is a programming language that is easy to write, easy to read, and beautiful.
----------------------
COM-code is a programming language designed to be easy to write, read, and learn.  
It focuses on clarity, simplicity, and beauty in code.  
**Made in Japan 🇯🇵**

## Features

- Simple syntax
- Loops, conditional statements, and functions
- Easy variable handling
- Scripts can run with minimal setup
- Designed for beginners and educational purposes

- ## COM-code Grammar

Basics

! : Call a function

? : Define a function

/ : Run a script command

@ : Declare or assign a variable

> Note: Each line must start with one of these symbols if it’s a COM-code command.



Variables
Declare or assign a variable:
@count = 0

Printing
Print a message or variable:
/print(:Hello, COM-code!)
/print(:Count is :count)

: before a variable inside print outputs its value.

Loops
While loop example:
/while(
/print(:Count is :count)
/wait(1)
@count = count + 1
)-if-<count<3>

/wait(seconds) pauses the loop for the given number of seconds
-if-<condition> checks the loop condition

Functions
Define a function:
?greet(name)
/print(:Hello, :name!)

Call a function:
!greet(:TAICHI)

Notes

Indentation is not required

Always start the line with !?/@ for COM-code commands

COM-code is designed to be easy to read, write, learn, and beautiful


---

# COM-code（日本語版）

COM-codeは、書きやすさ、読みやすさ、そして学習のしやすさを重視して設計されたプログラミング言語です。  
コードの明瞭さ、シンプルさ、そして美しさを重視しています。  
**日本製 🇯🇵**

## 機能

- シンプルな文法
- ループ、条件分岐、関数の利用
- 変数操作が簡単
- 最小限の設定でスクリプト実行可能
- 初心者や学習用途向け
