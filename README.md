# 使用须知
该仓库为CC3200连接Onenet平台的工程代码。
相关博客地址：https://blog.csdn.net/weixin_43687233/article/details/118281672
若直接导出出错，可能是由于版本和相关路径不匹配。请先导入`mqtt_client`例程，然后将替换为本工程的文件。工程打开后的应该为

`i2c_if.c`是链接文件，一般在sdk的example的common下，若缺失请添加进工程，其他文件类似。