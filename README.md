#sshp
基于sshpass的shell脚本， 用于
1. 避免ssh登录时的密码重复输入问题。
2. 使用shortname解决用户名、ip、密码 不利于记忆的问题。

##安装
1. 安装sshpass 
2. copy sshp to /usr/local/bin & chmod 777 /usr/local/bin/sshp 
3. copy sshp_pass to ~/.ssh 

##使用
```sshp vim```: 用于修改sshp_pass中 "shortname user@host password" 
```sshp```: 用于查看 shortname 对应的 user@host 
```sshp shortname```: 用于登录相应的host. 比如 ```sshp hwgao1``` 
