# allinone run script<br>
使用门槛路由器本身能扶墙或者上一级路由能扶墙<br>
本脚本用于软路由iStoreOS系统(x86_64、arm64)<br>
执行这个脚本可以快速安装各类装机必备插件。<br>


<pre>

 █████╗ ██╗     ██╗         ██╗███╗   ██╗     ██████╗ ███╗   ██╗███████╗    ██╗  ██╗ █████╗  ██████╗ 
██╔══██╗██║     ██║         ██║████╗  ██║    ██╔═══██╗████╗  ██║██╔════╝    ╚██╗██╔╝██╔══██╗██╔════╝ 
███████║██║     ██║         ██║██╔██╗ ██║    ██║   ██║██╔██╗ ██║█████╗       ╚███╔╝ ╚█████╔╝███████╗ 
██╔══██║██║     ██║         ██║██║╚██╗██║    ██║   ██║██║╚██╗██║██╔══╝       ██╔██╗ ██╔══██╗██╔═══██╗
██║  ██║███████╗███████╗    ██║██║ ╚████║    ╚██████╔╝██║ ╚████║███████╗    ██╔╝ ██╗╚█████╔╝╚██████╔╝
╚═╝  ╚═╝╚══════╝╚══════╝    ╚═╝╚═╝  ╚═══╝     ╚═════╝ ╚═╝  ╚═══╝╚══════╝    ╚═╝  ╚═╝ ╚════╝  ╚═════╝ 
                                                                                                     
 </pre>                                                      
                                                       
# Features<br>
* 设置好自定义域名劫持(主机名映射)，防止Android原生TV首次连接不到Wifi的情况。<br>
* 设置Emotn Store的域名代理，防止出现打不开Emotn Store的问题<br>
* 安装好软路由关机、定时设置等必备插件<br>
* 批量下载安装三大插件（OPS）<br>
* 自动识别软路由架构
* 其他等功能

# 提示：如何使用ssh ？参考如下图文
https://github.com/wukongdaily/HowToUseSSH

# How to Use
 ![Static Badge](https://img.shields.io/badge/all%20in%20one%20script-8A2BE2?logo=black&logoColor=black&label=%E7%BB%88%E7%AB%AF)
<p>
 <h3> 方式一:   在软路由终端执行下列命令即可(不区分CPU架构)</h3>
</p>
<p>

```
wget -O /tmp/all.run https://cdn.jsdelivr.net/gh/wukongdaily/allinonescript@main/all/all.run && chmod +x /tmp/all.run  && /tmp/all.run

```

</p>

<p>
 这个版本可以自动识别ARM或者x86平台,只需要执行上述命令,不需要担心架构问题。目前只适配了iStoreOS固件。其他固件后续看情况哈。
</p>


 <h3>方式二:   下载release中的run文件。打开iStore商店，手动安装即可。</h3><br>
 <img alt="Static Badge" src="https://img.shields.io/badge/xxx.run-FF4500?logo=black&logoColor=black&label=iStore%E5%95%86%E5%BA%97%E7%A6%BB%E7%BA%BF%E5%AE%89%E8%A3%85%E5%8C%85"> 
 下载地址：https://github.com/wukongdaily/allinonescript/releases <br>
 
</p>
<br>

![image](https://github.com/wukongdaily/allinonescript/assets/143675923/885169e1-68b6-4edf-8ece-ca6881d22faf)
<br>





# 其他OpenWrt系统的通用脚本(非iStoreOS系统)
https://github.com/wukongdaily/commonscript<br>

# 便携路由器 GL-iNet MT-3000/MT2500
https://github.com/wukongdaily/gl-inet-onescript

# Refers to
https://github.com/linkease/istore<br>
https://op.dllkids.xyz/packages<br>



