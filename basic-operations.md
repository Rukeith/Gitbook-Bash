# Basic Operations

---

###   1. `export`

         顯示所有的環境變量。如果要顯示特定環境變量的詳細資訊，使用 `echo $ VARIABLE_NAME`。

  Example：

```
$ export
AWS_HOME=/Users/adnanadnan/.aws
LANG=en_US.UTF-8
LC_CTYPE=en_US.UTF-8
LESS=-R

$ echo $AWS_HOME
/Users/adnanadnan/.aws
```

###    2. `whatis`

           `whatis` 顯示使用者指令、系統呼叫、library 程式和其他的操作手冊中的描述

  Example：

```
$ whatis bash
bash (1)             - GNU Bourne-Again SHell
```

###   3. `whereis`

         使用系統自動建立的數據庫來搜索可執行文件，來源檔案和操作手冊。

  Example：

```
$ whereis php
/usr/bin/php
```

###   4. `which`

         只在環境變量 PATH 指定的目錄中搜索可執行文件，此命令將印出可執行文件的絕對路徑。

  Example：

```
$ which php
/c/xampp/php/php
```

###   5. `clear`

         清除列印在視窗上的內容

## 1.1 File Operations

###     1. `cat`

            它可以在 UNIX 或 Linux 下用於以下幾種目的：

* 在視窗顯示文字檔案
* 複製文字檔案
* 合併文字檔案
* 建立文字檔案

       Example：

```
cat filename
cat file1 file2
cat file1 file2 > newcombinedfile
cat < file1 > file2 #copy file1 to file2
```



