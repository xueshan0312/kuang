原版ETH抽水脚本 原作者锁定抽水0.3%  版本号 4.0.0T6 作者承诺 不开抽水永久不抽水。。。
备注 我不是作者，我只是个搬运工。写的详细点。让你们自己复制粘贴就可以搭建。

UBUNTU推荐20，Centos我自己用7.8
ubuntu下
apt update
apt install wget

centos下
yum update
yum install wget

# 运行3.0.3稳定版
mkdir minerProxy303
cd minerProxy303
wget https://raw.githubusercontent.com/Char1esOrz/minerProxy/master/release/v3.0.3/minerProxy_web
chmod 777 minerProxy_web
./minerProxy_web

# 运行4.0.0测试版
mkdir minerProxy
cd minerProxy
wget https://github.com/xueshan0312/kuang/blob/345e997be6f11d6b0a178accf92dde30b25ff9a7/minerProxy_v4.0.0T6_linux_amd64
chmod 777 minerProxy_v4.0.0T6_linux_amd64
./minerProxy_v4.0.0T6_linux_amd64

以上结束。 访问 IP地址:18888  
访问密码 安装完毕以后 会有提示。


# 运行之后查看webtoken
tail -f nohup.out
