# 欺骗防御
- https://github.com/paralax/awesome-honeypots    //优秀蜜罐，相关技术手段收集。goodjob。G:/OWASP/Honeypot-Project;P:/SDN网络微隔离;--
- https://www.freebuf.com/articles/paper/207739.html    //intro。开源蜜罐测评报告
- https://github.com/Cymmetria    //欺骗防御公司。Struts2、weblogic、telnet、Cisco ASA、Micros等仿真蜜罐，honeycomb低交互蜜罐框架
- https://www.freebuf.com/sectool/204652.html    //基于EVE-NG平台上构建企业内网攻防环境
- https://github.com/BinaryDefense/artillery    //Py。端点蜜罐防护。
## 攻击反制
- https://tom0li.github.io/反制攻击队和防守人员/    //
- https://github.com/WyAtu/CVE-2018-20250    //Py。WinRAR压缩包代码执行复现与利用
- https://www.bamsoftware.com/hacks/zipbomb/    //ZIPBOMB压缩包炸弹
- https://www.freebuf.com/articles/terminal/175862.html    //Intro。从OpenVPN配置文件中创建反弹Shell实现用户系统控制。
- https://www.exploit-db.com/exploits/38847    //CVE-2015-4027。Acunetix WVS 10 - Local Privilege Escalation本地提权漏洞。如何优雅的反击扫描你网站的黑客。
- https://www.exploit-db.com/exploits/39755    //Acunetix WVS 10 - Remote Command Execution远程命令执行
- https://www.secpulse.com/archives/18940.html    //Intro。Web Vulnerability Scanner 8 远程命令执行漏洞。本地使用wscript.shell组件执行命令。
- https://bbs.pediy.com/thread-195431.htm    //Intro。Pwn the n00bs - Acunetix 0day。awvs溢出攻击
- https://www.anquanke.com/post/id/176379    //Intro。蚁剑菜刀RCE。蚁剑客户端RCE挖掘过程及源码分析。Electron APP漏洞。
### 攻击反制利用
- https://blog.csdn.net/ls1120704214/article/details/88174003    //Go。反击mysql蜜罐。利用MySQL LOCAL INFILE读取客户端文件漏洞分析并使用Golang编写简易蜜罐;从MySQL出发的反击之路;Github:/MysqlT，支持大文件无损传输，支持用户验证，支持自定义的 Mysql 版本，随机的盐加密，加上用户验证，让攻击者毫无察觉;Github:/Rogue-MySql-Server;--
- https://github.com/gh0stkey/ahrid    //py。利用jsonp等漏洞通过分析模块对黑客画像溯源
## 虚拟化
- http://www.linux-kvm.org    //Linux内核虚拟化工具，支持unix/win等多种系统。
- https://www.qemu.org    //纯软件实现的虚拟化环境仿真，硬件设备的环境模拟仿真。qemu-kvm为虚拟机管理工具
- https://www.busybox.net/    //集成了三百多个最常用Linux命令和工具的软件，良好支持嵌入式。
- https://www.virtualbox.org    //跨平台多系统支持，社区版。
- https://www.vmware.com    //跨平台多系统支持。ESXI虚拟化平台管理工具，vsphere集群。商业版。
- https://www.proxmox.com/    //ProxmoxVE类virtualbox架构，开源虚拟化平台，自带防火墙、邮件网关。
- http://www.eve-ng.net    //UnifiedNetworking Lab统一网络实验室。基于Ubuntu深度定制。商业版。
### 虚拟化云平台
- https://github.com/zstackio/zstack    //Java。类似openstack基于kvm与vmware的虚拟化云管理框架。商业版。
### 虚拟化容器
- https://github.com/moby/moby    //Go。Linux下虚拟容器dockerCE。54k。
- https://github.com/containers/libpod    //Go。podman.io虚拟容器。3k。
- https://github.com/hashicorp/vagrant    //Ruby。管理虚拟机。19k。
- https://www.cnblogs.com/ryanyangcs/p/12558727.html/    //两个奇技淫巧，将 Docker 镜像体积减小 99%。多阶段构建，系统精简。
### 主动反制面包屑
- https://www.cnblogs.com/k8gege/p/12390265.html    //看我如何模拟Cobalt Strike上线欺骗入侵者
- https://www.freebuf.com/articles/ics-articles/230402.html    //一种工控蜜罐识别与反识别技术研究与应用实践
- https://www.freebuf.com/articles/system/232669.html    //内网Kerberos用户蜜罐。主动防御
### 虚拟化沙盒
- https://github.com/cuckoosandbox/cuckoo    //PY/JS。自动恶意软件分析系统，恶意样本分析沙盒检测。
- https://github.com/euphrat1ca/Panda-Sandbox    //Py。钟馗沙箱是基于cuckoo的适配国内软件环境的恶意软件检测
- https://www.sandboxie.com/DownloadSandboxie    //基于转换存储的沙盒。代码社区开源。
- https://github.com/felicitychou/MalAnalyzer    //Py3。基于docker虚拟化的恶意代码沙箱
## 蜜罐服务
- https://github.com/phage-nz/malware-hunting    //Py。利用蜜罐进行恶意文件捕获。包含众多蜜罐使用说明
- https://github.com/threatstream/mhn    //Py。现代蜜网，集成了多种蜜罐的安装脚本，可以快速部署、使用，也能够快速的从节点收集数据
- https://github.com/dtag-dev-sec/tpotce    //T-POT.里面使用docker技术实现多个蜜罐组合，配合ELK进行研究与数据捕获
- https://github.com/n3uz/t-pot-autoinstall    //Bash。将fork的T-POT蜜罐的一键安装脚本替换为国内加速镜像
- https://www.freebuf.com/sectool/190840.html    //Intro。T-Pot多蜜罐平台使用心法
- https://github.com/honeytrap/honeytrap    //Go。可扩展高交互蜜罐框架，侦听所有端口，监管蜜罐运行状态。
- https://github.com/honeynet/beeswarm    //Py。使用agent探针与蜜罐进行实时交互来引诱攻击者
### Web服务蜜罐
- https://github.com/p1r06u3/opencanary_web    //Py。基于TORNADO的低交互蜜罐。支持自动化安装，目前支持常见的16种协议，采用探针/蜜罐-管理的架构。可以考虑二次开发为探针-沙盒-管理的架构
- https://gitlab.com/SecurityBender/webhoneypot-framework    //Py3。基于docker和docker-compose，现支持wordpress/drupal
- https://github.com/mushorg/snare    //Py3。web安全蜜罐，可克隆指定Web页面
- https://github.com/netxfly/x-proxy    //Go。代理蜜罐的开发与应用实战。simple
### 数据库蜜罐
- https://gitlab.com/bontchev/elasticpot    //py。Elasticsearch数据库蜜罐
- https://github.com/hacklcs/HFish    //Go。redis\MYSQL\SSH etc 低交护蜜罐。goodjob。
- https://github.com/codeplutos/MySQL-JDBC-Deserialization-Payload    //MySQL JDBC Deserialization Payload / MySQL客户端jdbc反序列化漏洞
### 供应链蜜罐
- http://www.imooc.com/article/26398    //NodeJS 应用仓库钓鱼。同理可应用于python库\apache module 后门等，相关诱饵名称可设置为加解密模块等，或者直接dns劫持。
### PC服务蜜罐
- https://github.com/micheloosterhof/cowrie    //Py3。使用ELK（ElasticSearch，LogStash，Kibana）进行数据分析，目前支持ssh，telnet，sftp等协议蜜罐。
- https://github.com/desaster/kippo    //Py。蜜罐系统HoneyDrive下的图形化SSH蜜罐。1k。
- https://github.com/thinkst/opencanary    //Py3。SNMP\RDP\SAMBA蜜罐
- https://github.com/gosecure/pyrdp    //Py3。RDP MITM蜜罐
- https://gosecure.net/2018/12/19/rdp-man-in-the-middle-smile-youre-on-camera/    //Intro。基于PYRDP,打造可记录图像和按键的RDP蜜罐
- https://github.com/leeberg/BlueHive    //PS。利用Active Directory生成用户账户蜜罐
### 摄像头蜜罐
- https://github.com/alexbredo/honeypot-camera    //Py。摄像头蜜罐。tornado模拟WEB服务，图片代替视频，可以考虑后期多加点图片和按钮
- https://github.com/EasyDarwin/EasyIPCamera    //C。RTSP服务器组件用以构建摄像头蜜罐
### 工控蜜罐
- https://www.freebuf.com/articles/ics-articles/230402.html    //一种工控蜜罐识别与反识别技术研究与应用实践
- https://github.com/sjhilt/GasPot    //模拟油电燃气工控系统
- https://github.com/djformby/GRFICS    //IoT工业仿真系统模拟框架，采用MODBUS协议对PLC虚拟机监视和控制
- https://github.com/RabitW/IoTSecurityNAT    //IoT测试系统，方便快速接入各种设备，进行安全测试
- https://github.com/mushorg/conpot    //针对ICS/SCADA的低交互工控蜜罐，模拟Modbus和S7comm
- https://github.com/trombastic/PyScada/    //Py3。基于Django的SCADA操作管理系统