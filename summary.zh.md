
# {{Paj.Toe}}

本章的主题是处理互联网的持续发展. 互联网不断吸引更多的用户,并且随着诸如视频流之类的应用变得更加带宽密集,每个用户发送更多的流量. 因此,虽然互联网已被证明是一个可扩展的系统,但新的缩放问题仍然需要解决方案. 除了缩放之外,互联网还需要发展以支持新的能力和服务. 

当今的主要缩放问题是随着因特网的发展,地址空间的有效利用和路由表的增长. 分级IP地址格式,其网络和主机部分,给我们一个层次的层次管理规模. 路由区域提供了另一层次的层次结构. 自治系统允许我们将路由问题划分为两个部分,域间路由和域内路由,每个部分都比总的路由问题要小得多. BGP是互联网的域间路由协议,在处理互联网的发展方面已经取得了显著的成功. 

尽管已经采取了许多步骤来扩展IPv4,但很显然,不久将需要一种新的ㄡ更长的地址格式. 这需要一个新的IP数据报格式和一个新版本的协议. 最初称为下一代IP (IPng) ,现在称为IPv6,它提供一个128位的地址 (主要是) 类似CIDR的地址和路由. 尽管IPv6已经拥有许多新功能,但是它的主要优势仍然是支持大量可寻址设备的能力. 

最后,互联网也需要在功能和大小上发展. 在这方面,我们看了三个增强到原来的IP数据报模型. 第一种是多播,使同一数据能够有效地传递给接收器组. 与单播一样,多播中的许多挑战与伸缩有关,并且已经开发了许多不同的协议和多播模式来优化不同环境中的伸缩和路由. 第二个增强是MPLS,它把虚拟电路网络的一些方面引入到IP中,并被广泛用于扩展IP的能力. MPLS的应用范围从流量工程到互联网上的虚拟专用网的支持. 最后,随着更多的网络设备,包括主机和路由器,都变成了移动的,移动性支持变得日益重要. 

## 进一步阅读

我们的第一个选择,Bradner和Mankin的RFC,提供了关于快速增长的Internet如何强调原始体系结构的可伸缩性的信息概述,最终产生了IPv6. Paxson的论文描述了路由器如何在互联网上运行的研究. 尽管已经有15多年的历史了,它仍然被高度引用,并且是研究人员如何研究互联网动态行为的一个好例子. 最后讨论了组播,给出了MBOX最初使用的组播方法. 

-   布拉德纳ㄡ美国和A. Mankin. 对下一代IP协议的推荐. *征求意见*1752,1995年1月. 

-   Paxson,V.端到端的路由行为在互联网上. *西格康96*第25页- 38页,1996年8月. 

-   迪灵ㄡS和D·切里顿. 数据报互联网络和扩展LAN中的组播路由. *计算机系统的ACM事务*8 (2) : 85ℴ110,1990年5月. 
