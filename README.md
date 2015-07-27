Linux学習用Vagrantセット
===

手順
---

+ [Vagrant](http://www.vagrantup.com/downloads.html) をインストール

~~~
vagrant --version
#=> Vagrant 1.7.4 って出ればOK
~~~

+ [Virtual Box](https://www.virtualbox.org/wiki/Downloads) をインストール
+ Vagrantのプラグインをターミナルからインストール

~~~
vagrant plugin install sahara
vagrant plugin install vagrant-proxyconf
~~~

+ vagrant upコマンドでマシンを起動(初回は10分くらいかかります

~~~
vagrant up
~~~

+ vagrant ssh コマンドでログイン

~~~
vagrant ssh
~~~
