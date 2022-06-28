# sgb
Linuxのコマンドラインからシェル芸を実行する

## 使い方
`sgb [options] <command>`

`-h` `--help`: ヘルプを表示します。  
`-i <string>` `--image=<string>`: 添付画像を指定します。  
`-d <string>` `--save-dir=<string>`: 画像の保存先を指定します。(デフォルトではカレントディレクトリに保存）

## 使用例
```
$ sgb unko.shout HELL
＿人人人人＿
＞　HELL　＜
￣Y^Y^Y^Y^￣
　　　　　　👑
　　　　（💩💩💩）
　　　（💩👁💩👁💩）
　　（💩💩💩👃💩💩💩）
　（💩💩💩💩👄💩💩💩💩）
 
$ sgb -i image.png ls /media
0

$ sgb 'echo unko | textimg -s'; ls
sgb_0.png
```

## 謝辞
jiro4989氏の[websh](https://websh.jiro4989.com/)を使用させていただいています。素晴らしいサービスをありがとうございます。
