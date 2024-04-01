# Summary

## 和我一步步部署 kubernetes 集群

* [00.组件版本和配置策略](00. Component Versions and Configuration Policies.md)
* [01.初始化系统和全局变量](01.Initialize System and Global Variables.md)
* [02.创建CA根证书和秘钥](02.Create CA Root Certificate and Key.md)			
* [03.部署kubectl命令行工具](03.kubectl.md)			
* [04.部署etcd集群](04.etcd cluster.md)				
* [05-1.部署master节点.md](05-1.master node.md)
    * [05-2.apiserver集群](05-2.apiserver cluster.md)
    * [05-3.controller-manager集群](05-3.controller-manager cluster.md)	
    * [05-4.scheduler集群](05-4.scheduler cluster.md)
* [06-1.部署woker节点](06-1.worker node.md)			
    * [06-2.apiserver高可用之nginx代理](06-2.apiserver high availability.md)
    * [06-3.containerd](06-3.containerd.md)					
    * [06-4.kubelet](06-4.kubelet.md)				
    * [06-5.kube-proxy](06-5.kube-proxy.md)
    * [06-6.部署calico网络](06-6.calico.md)	
* [07.验证集群功能](07. Verify cluster functionality.md)			
* [08-1.部署集群插件](08-1. Deploy cluster plugin.md)
    * [08-2.coredns插件](08-2.coredns plug-in.md)
    * [08-3.dashboard插件](08-3.dashboard plug-in.md)
    * [08-4.kube-prometheus插件](08-4.kube-prometheus plug-in.md)
	* [08-5.EFK插件](08-5.EFK plug-in.md)			
* [09.部署Docker-Registry](09.Registry.md)	
* [10.清理集群](10. Clean up the cluster.md)	
* [A.浏览器访问apiserver安全端口](A. Browser access kube-apiserver secure port.md)
* [B.校验TLS证书](B. Verify TLS certificate.md)
* [C.部署metrics-server插件](C.metrics-server plug-in.md)
* [D.部署Harbor-Registry](D. Deploy Harbor-Registry.md)	
* [E.部署flannel网络](E. Deploy flannel network.md)	
* [F.部署docker](F. Deploy docker.md.md)	

## 标签集合

* [标签](tags.md)
