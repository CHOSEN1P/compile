# 固件编译

1. fork lede

2. 更改/package/base-files/files/bin/config_generate中的lan口默认后台ip //150行

3. 搜索hostname修改主机名 //298行

4. 时区：timezone='CST-8' //

5. 时区名：zonename='Asia/Shanghai'

6. 修改/package/base-files/files/etc/shadow中默认登录密码为$1$wEehtjxj$YBu4quNfVUjzfv8p/PBo5.
   root:$1$wEehtjxj$YBu4quNfVUjzfv8p/PBo5.:0:0:99999:7:::

8. 修改workflow中yml文件
