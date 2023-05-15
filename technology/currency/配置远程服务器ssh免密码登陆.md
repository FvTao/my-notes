# 配置远程服务器ssh免密码登陆

- 在本机生成ssh密钥

    ```shell
    ssh-keygen -t ed25519 -C "[comment]" -f [file_name] -N '' -q
    ```

    详细命令说明参考https://man.openbsd.org/ssh-keygen

- 将ssh公钥发送给服务器

    ```shell
    ssh-copy-id [-i [identity_file]] [user@]machine
    ```

    例如：

    ```shell
     ssh-copy-id -i ~/.ssh/id_rsa.pub user@<server ip>
    ```