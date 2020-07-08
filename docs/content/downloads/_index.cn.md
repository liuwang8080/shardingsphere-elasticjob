+++
pre = "<b>6. </b>"
title = "下载"
weight = 6
chapter = true
+++

## 最新版本

ElasticJob的发布版包括源码包及其对应的二进制包。由于下载内容分布在镜像服务器上，所以下载后应该进行GPG或SHA-512校验，以此来保证内容没有被篡改。

**ElasticJob**

| 版本 | 发布日期 | 说明 | 下载 |
| - | - | - | - |
| 3.0.0-alpha | Jul -, 2020  | 源码 | [[src]]() [[asc]]() [[sha512]]() |
|             |              | ElasticJob-Lite 二进制包 | [[tar]]() [[asc]]() [[sha512]]() |
|             |              | ElasticJob-Lite-Console 二进制包 | [[tar]]() [[asc]]() [[sha512]]() |

## 全部版本

全部版本请到[Archive repository](https://archive.apache.org/dist/shardingsphere/)查看。

## 校验版本

[PGP签名文件](https://downloads.apache.org/shardingsphere/KEYS)

使用PGP或SHA签名验证下载文件的完整性至关重要。可以使用GPG或PGP验证PGP签名。请下载KEYS以及发布的asc签名文件。建议从主发布目录而不是镜像中获取这些文件。

```shell
gpg -i KEYS
```

or

```shell
pgpk -a KEYS
```

or

```shell
pgp -ka KEYS
```

要验证二进制文件或源代码，您可以从主发布目录下载相关的asc文件，并按照以下指南进行操作。

```shell
gpg --verify apache-shardingsphere-********.asc apache-shardingsphere-*********
```

or

```shell
pgpv apache-shardingsphere-********.asc
```

or

```shell
pgp apache-shardingsphere-********.asc
```