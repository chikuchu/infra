
### 情報
* 公式サイト  
https://nginx.org/en/



### インストール
* CentOS系リポジトリ  
http://nginx.org/packages/mainline/centos/7/$basearch/
* yumのリポジトリに設定  
$sudo vi /etc/yum.repos.d/nginx.repo
```
[nginx]
name=nginx repo
baseurl=http://nginx.org/packages/mainline/centos/7/$basearch/
gpgcheck=0
enabled=1
```

### 自動起動設定
* systemctl  
$ sudo systemctl enable nginx
* 起動  
$ sudo systemctl start nginx
* 停止  
$ sudo systemctl stop nginx

### 設定ファイル
* default  
