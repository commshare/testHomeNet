
#
##
50 722
55 7722
## sshd config multi port

ssh监听多个端口
vi /etc/ssh/sshd_config
Port 22
Port 2015 #这样就行啦, 想再多个端口就这样多写几个
service sshd restart #重启sshd就ok了
