Title: samhain：比较变态的入侵检测系统
Date: 2008-08-20 08:27
Author: hmy
Category: Apps
Slug: samhain

[撰文/hmy]

主机完整性检查工具，说它变态是因为在编译的时候可以加入证书认证，配置文件也需要通过证书签名才能运行，检查结果也是证书签名的。最大限度的保障安全性。另外可以隐藏运行。另外还可以一个服务器端专门接收检测结果。遇到主机被入侵可以第一时间发现。

samhain
主要是通过对文件夹或者文件定义一些检测规则来实现主机一致性检查。最敏感的设置，可以发现一个文件的
atime（文件被读取的时间，用 stat filename 可以看到）的变化。

debian 库里有，希望对你有用。

详细研究参考主页：

<http://la-samhna.de/samhain/>
