# packer-alicloud-isucon
- isucon用imageをAlibabaCloud上にPackerで作成するためのもの

#＃ 事前準備
### AlibabaCloudのPackerプラグインをインストール
```
$ curl -O https://github.com/alibaba/packer-provider/releases/download/V1.4.2/packer-builder-alicloud-ecs_darwin-amd64.tgz
$ tar xfz packer-builder-alicloud-ecs_darwin-amd64.tgz
$ ls -l bin
total 73312
-rwxr-xr-x@ 1 xxxxx staff 18766172 8 3 11:46 packer-builder-alicloud-ecs
-rwxr-xr-x@ 1 xxxxx staff 18766172 8 3 11:46 packer-post-processor-alicloud-import
$ mkdir ~/.packer.d/plugins
$ mv bin/packer-* ~/.packer.d/plugins/
```
