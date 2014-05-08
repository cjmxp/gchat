gchat
=====

xmpp im client for ubuntu touch

一个xmpp 即时通讯客户端，当然也可以用作google talk客户端。
使用qml + golang (感谢go-qml项目:https://github.com/go-qml/qml)

此应用依赖于ubuntu-sdk和golang
所以请先安装以上两个必须品：

$ sudo apt-get install ubuntu-sdk

golang环境请参考golang官网：golang.org

以上环境准备好后：

$ go get github.com/ginuerzh/gchat

$ cd gchat/proj/dir

$ go run main.go
