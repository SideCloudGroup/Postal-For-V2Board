# Postal-For-V2Board

## 介绍

为V2Board提供通过Postal API发送邮件的功能 \
与SMTP协议相比，Postal API提供了更高的发送速度和更低的延迟

## 安装

1. 下载文件[SendEmailJob.php](https://github.com/SideCloudGroup/Postal-For-V2Board/raw/main/app/Jobs/SendEmailJob.php)
   ，替换V2Board目录下的`/app/Jobs/SendEmailJob.php`
2. 在V2Board网站根目录下执行以下命令
    ```bash
    php composer.phar require "postal/postal:^2.0.1"
    ```

## 配置

在管理员面板`系统配置`-`邮件`中进行配置

`SMTP服务器地址`为Postal面板地址，以`https://`开头，结尾无需加`/` \
`SMTP密码`为Postal API Key \
`发件地址` 为发送邮件的发件地址 \
其余设置请留空

## 问题

如果您在使用过程中遇到任何问题，欢迎提出Issue