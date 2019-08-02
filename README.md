# packer-alicloud-isucon
- isucon用imageをAlibabaCloud上にPackerで作成するためのもの

#＃ 事前準備

### AlibabaCloudのPackerプラグインをインストール(Mac)
```
$ wget https://github.com/alibaba/packer-provider/releases/download/V1.4.2/packer-builder-alicloud-ecs_darwin-amd64.tgz
$ tar xfz packer-builder-alicloud-ecs_darwin-amd64.tgz
$ ls bin
packer-builder-alicloud-ecs           packer-post-processor-alicloud-import
$ mkdir ~/.packer.d/plugins
$ mv bin/packer-* ~/.packer.d/plugins/
```
