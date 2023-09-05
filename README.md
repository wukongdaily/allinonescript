# allinone run script<br>
本脚本用于软路由iStoreOS系统(x86_64、arm64)<br>
执行这个脚本可以快速安装各类装机必备插件。<br>
由于许多插件存放在`raw.githubusercontent.com`服务器<br>
国内直接访问容易超时或者访问不到。<br>
因此执行这个脚本之前，最好让软路由器启用一个科学插件<br>
这样才能够保证快速安装。替换hosts的方式不能完全规避速度慢的问题。<br>

<pre>

 █████╗ ██╗     ██╗         ██╗███╗   ██╗     ██████╗ ███╗   ██╗███████╗    ██╗  ██╗ █████╗  ██████╗ 
██╔══██╗██║     ██║         ██║████╗  ██║    ██╔═══██╗████╗  ██║██╔════╝    ╚██╗██╔╝██╔══██╗██╔════╝ 
███████║██║     ██║         ██║██╔██╗ ██║    ██║   ██║██╔██╗ ██║█████╗       ╚███╔╝ ╚█████╔╝███████╗ 
██╔══██║██║     ██║         ██║██║╚██╗██║    ██║   ██║██║╚██╗██║██╔══╝       ██╔██╗ ██╔══██╗██╔═══██╗
██║  ██║███████╗███████╗    ██║██║ ╚████║    ╚██████╔╝██║ ╚████║███████╗    ██╔╝ ██╗╚█████╔╝╚██████╔╝
╚═╝  ╚═╝╚══════╝╚══════╝    ╚═╝╚═╝  ╚═══╝     ╚═════╝ ╚═╝  ╚═══╝╚══════╝    ╚═╝  ╚═╝ ╚════╝  ╚═════╝ 
                                                                                                     
 </pre>                                                      
                                                       
# Features<br>
1、设置好自定义域名劫持(主机名映射)，防止Android原生TV首次连接不到Wifi的情况。<br>
2、设置Emotn Store的域名代理，防止出现打不开Emotn Store的问题<br>
3、安装好软路由关机、定时设置等必备插件<br>
4、批量下载安装三大插件（OPS）<br>
5、自动补全各类Clash内核（dev、tun、meta）<br>
6、自动更新OpenClash到最新版本<br>

# How to Use

![Static Badge](https://img.shields.io/badge/%E4%B8%89%E5%90%88%E4%B8%80-%E7%89%88%E6%9C%AC-F31E48?logoColor=0D66E7&labelColor=0D66E7)


<p>
 <h3>方式一:   在软路由终端执行下列命令即可</h3>
</p>

<h4>x86_64软路由</h4><br>

```
wget -O /tmp/OPS.run https://raw.githubusercontent.com/wukongdaily/allinonescript/main/x86/OPS.run && chmod +x /tmp/OPS.run && /tmp/OPS.run

```

<h4>arm软路由 (R2S、R4S等)</h4><br>

```
wget -O /tmp/OPS.run https://raw.githubusercontent.com/wukongdaily/allinonescript/main/arm64/OPS.run && chmod +x /tmp/OPS.run && /tmp/OPS.run

```

<p>
 <br>
 <h3>方式二:   下载release中的run文件。打开iStore商店，手动安装即可。</h3><br>
 下载地址：https://github.com/wukongdaily/allinonescript/releases
</p>
<br>

![image](https://github.com/wukongdaily/allinonescript/assets/143675923/885169e1-68b6-4edf-8ece-ca6881d22faf)
<br>

![Static Badge](https://img.shields.io/badge/%E5%85%AD%E5%90%88%E4%B8%80-%E7%89%88%E6%9C%AC-F31E48?logoColor=8A2BE2&labelColor=8A2BE2)

<h4>x86_64软路由</h4><br>

```
wget -O /tmp/OPSPVB.run https://raw.githubusercontent.com/wukongdaily/allinonescript/main/x86/OPSPVB.run && chmod +x /tmp/OPSPVB.run && /tmp/OPSPVB.run

```

<h4>arm软路由 (R2S、R4S等)</h4><br>

```
wget -O /tmp/OPSPVB.run https://raw.githubusercontent.com/wukongdaily/allinonescript/main/arm64/OPSPVB.run && chmod +x /tmp/OPSPVB.run && /tmp/OPSPVB.run

```

</p>

<h1>带菜单版一键脚本(集合全部功能)</h1><br>

![Static Badge](https://img.shields.io/badge/%E5%B8%A6%E8%8F%9C%E5%8D%95%E7%89%88%E6%9C%AC-8A2BE2?label=%E7%BB%88%E7%AB%AF%E5%91%BD%E4%BB%A4%E8%A1%8C&labelColor=F31E48)

<p>
 <h3> 在软路由终端执行下列命令即可(不区分CPU架构)</h3>
</p>
<p>

```
wget -O /tmp/allmenu.run  https://raw.githubusercontent.com/wukongdaily/allinonescript/main/all/allmenu.run && chmod +x /tmp/allmenu.run  && /tmp/allmenu.run

```

</p>

<p>
 这个版本可以自动识别ARM或者x86平台,只需要执行上述命令,不需要担心架构问题。目前只适配了iStoreOS固件。其他固件后续看情况哈。
</p>


 
# Refers to

https://github.com/AUK9527/Are-u-ok/tree/main/x86 <br>
https://github.com/megastep/makeself


