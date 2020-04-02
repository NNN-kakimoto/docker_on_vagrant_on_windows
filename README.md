# Docker on Vagrant on Windows Home

快適にローカル環境で開発するためにDockerを導入するためにVagrantを導入し、セッティングするためのリポジトリ。

# Overview

1. `vagrant up`
1. `vagrant ssh`
1. change project directory
1. `docker-compose up` (example

# getting stated

以下のインストールとコマンドの実行が必要。  
1. gitの導入
1. Vagrant の [インストール](https://www.vagrantup.com/)
1. `git clone git@github.com:NNN-kakimoto/docker_on_vagrant_on_windows.git`
1. `vagrant box add development development.box`
1. `vagrant init development`
1. `vagrant up`
1. wait!
1. `vagrant ssh`
1. `docker run hello-world` (example

# reference
## installed commands
以下のコマンドがインストール済。 バージョン記載のあるものは明示的に指定している。

|コマンド|ver|
|:-----:|--:|
|vim||
|curl||
| ~git~ ||
|docker-ce||
|docker-compose|1.25.4|
