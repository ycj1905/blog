---
title: Shell Script 筆記
date: 2018-03-16 17:27:11
tags: shell
---

>身為一個很 Hack 的攻城獅, 寫些自動化程式讓生活更美好 ! 
[自動化所有超過90秒的工作](https://www.bnext.com.tw/ext_rss/view/id/1099271 "Title")

### note
ditto : 覆蓋重複檔案, 並保留未更動檔案
```shell
$ditto src target
```

terminal 與 user 互動
```shell
read -p "Enter your first name: " firstname
read -p "Enter your last name: " lastname
echo -e "\nYour full name is ${firstname} ${lastname}"
```

argument: $0 $1 $2 ...

```shell
$echo $(( 13 % 3 ))
$echo "123.123*55.9" | bc
```

source 可以把變數暴露在環境中
```shell
source target
```
