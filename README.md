# 云平台异构实例的实现

本Repository是毕设《天地一体化网络节点仿真关键技术研究》实现的关键代码，其主要功能是利用x86架构的云平台生成arm、ppc等架构的异构实例，其利用Qemu-system、Qemu-user、Docker等技术，并对Openstack的底层代码进行二次开发实现的。

需要注意，本代码是基于M版本实现的，容器集群的管理是基于开源项目nova-docker。

本平台至少需要一个控制节点，一个装有qemu-system的计算节点和一个配置了nova-docker以及qemu-user的计算节点。
