# RubyChristianCalendarConversion
西暦から和暦を割り出す

## 処理
昭和元年から10年までの西暦和暦変換を行います

## コード
```
for seireki in 1926..1935
    print "西暦#{seireki}は"
    syowa = seireki - 1925
    puts "昭和#{syowa}年です"
end
```

## 出力結果  
```
西暦1926は昭和1年です
西暦1927は昭和2年です
西暦1928は昭和3年です
西暦1929は昭和4年です
西暦1930は昭和5年です
西暦1931は昭和6年です
西暦1932は昭和7年です
西暦1933は昭和8年です
西暦1934は昭和9年です
西暦1935は昭和10年です
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
