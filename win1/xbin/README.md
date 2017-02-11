```
1. 首先是初始化data数据目录；
```
2. 然后是记住这个root@localhost账户的临时密码；
```
3. 然后是启动Server；
```
4. 这时用mysql客户端工具连接Server服务，使用的密码就是刚才记住的临时密码；
```
5. 然后进行ALTER USER修改用户密码；
```
6. 后续可以通过mysqladmin程序来关闭Server；
```