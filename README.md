# honeypot-nguseragent
ハニーポットで収集した不審な User-Agent です。自己責任でご自由にお使いください。

# 使い方
Apache の .htaccess ファイルに ng_useragent.txt の内容を追記するだけです。該当の User-Agent が含まれる通信は、アクセスが拒否されます。

# 検証
$ wget --user-agent=Hello http://設定したサイトのURL/

***
- Author: @morihi_soc (https://www.morihi-soc.net/ )
