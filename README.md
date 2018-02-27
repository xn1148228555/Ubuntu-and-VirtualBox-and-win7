# Ubuntu-and-VirtualBox-and-win7
Ubuntu下虚拟机VirtualBox安装Win7
<h3 style="box-sizing: border-box; font-family: tahoma, 宋体; font-weight: normal; line-height: normal; color: rgb(51, 51, 51); margin-top: 0px; margin-bottom: 10px; font-size: 14px; white-space: normal; text-align: justify; background-color: rgb(250, 250, 252);">
    <span style="box-sizing: border-box; font-size: 16px;">第一步：下载VirtualBox</span>
</h3>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238); line-height: normal;">
    <span style="box-sizing: border-box; font-size: 14px;">&nbsp;&nbsp;&nbsp;&nbsp;方法一：你可以去Ubuntu软件中心去下载。<br/></span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238); line-height: normal;">
    <span style="box-sizing: border-box; font-size: 14px;">&nbsp;&nbsp;&nbsp;&nbsp;方法二：根据你的操作系统类型，32位（i386）或者64位（amd64）到下面提供的的官方下载页面下载相应的.deb 安装包:</span><a href="https://www.virtualbox.org/wiki/Linux_Downloads" target="_blank" style="box-sizing: border-box; background-color: transparent; color: rgb(179, 43, 213); text-align: justify; font-size: 14px;"><span style="box-sizing: border-box;">https://www.virtualbox.org/wiki/Linux_Downloads</span></a>
</p>
<h3 style="box-sizing: border-box; font-family: tahoma, 宋体; font-weight: normal; line-height: normal; color: rgb(51, 51, 51); margin-top: 0px; margin-bottom: 10px; font-size: 14px; white-space: normal; text-align: justify; background-color: rgb(250, 250, 252);">
    <span style="box-sizing: border-box; font-size: 16px;">第二步：根据自己需要下载对应Windows的镜像</span>
</h3>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238); line-height: normal;">
    <span style="box-sizing: border-box;">&nbsp;&nbsp;&nbsp;<span style="box-sizing: border-box; font-size: 14px;">&nbsp;<span style="box-sizing: border-box; font-weight: 700;">PS：</span>我这里用的是Win7-32位。下载地址我就不推荐了，自行百度！</span><br/></span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238); line-height: normal;">
    <span style="box-sizing: border-box; font-size: 16px;"></span>
</p>
<h3 style="box-sizing: border-box; font-family: tahoma, 宋体; font-weight: normal; line-height: normal; color: rgb(51, 51, 51); margin-top: 0px; margin-bottom: 10px; font-size: 14px; white-space: normal; text-align: justify; background-color: rgb(250, 250, 252);">
    <span style="box-sizing: border-box; font-size: 16px;">第三步：安装Windows(Win7-32位)虚拟机</span>
</h3>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 16px;">&nbsp;&nbsp;&nbsp;<span style="box-sizing: border-box; font-size: 14px;">&nbsp;安装步骤（1）：打开VirtualBox，新建-&gt;填写好名称，类型，版本。<br/></span></span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;"><span style="box-sizing: border-box; font-size: 16px;"></span>&nbsp;&nbsp;&nbsp;&nbsp;</span><img src="http://www.piaoyifa.com/uploads/image/1519568394103251.png" title="1519568394103251.png" alt="1517273546101988.png" class="img-responsive"/>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">&nbsp;&nbsp;&nbsp;&nbsp;安装步骤（2）：点击下一步，内存大小 默认512(PS：系统给我推荐的)-&gt;点击下一步，虚拟硬盘 默认“现在创建虚拟硬盘（C）”-&gt;下一步，虚拟硬盘文件类型 默认“VDI（VirtualBox磁盘映像）”-&gt;下一步，存储在物理硬盘上默认“动态分配（D）”-&gt;下一步，文件位置和大小 默认-&gt;创建，我们可以看到有test-win7了。</span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">&nbsp;&nbsp;&nbsp;&nbsp;<img src="http://www.piaoyifa.com/uploads/image/1519568495462764.png" title="1519568495462764.png" alt="1517274394120456.png" class="img-responsive"/></span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;"><br/></span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">&nbsp;&nbsp;&nbsp;&nbsp;安装步骤（3）：启动test-win7, 选择启动盘-&gt;启动</span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">&nbsp;&nbsp;&nbsp;&nbsp;<img src="http://www.piaoyifa.com/uploads/image/1519568533115221.png" title="1519568533115221.png" alt="1517276003539268.png" class="img-responsive"/></span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">&nbsp; &nbsp; 装系统的画面来了。<br/></span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">&nbsp;&nbsp;&nbsp;&nbsp;<img src="http://www.piaoyifa.com/uploads/image/1519568588112182.png" title="1519568588112182.png" alt="1517276125129635.png" class="img-responsive"/></span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">&nbsp;&nbsp;&nbsp;&nbsp;安装步骤（4）：当系统装完时， 我们在装一下VirtuaBox的增强包</span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">&nbsp;&nbsp;&nbsp;&nbsp;<img src="http://www.piaoyifa.com/uploads/image/1519568622166496.png" title="1519568622166496.png" alt="1517277751110957.png" class="img-responsive"/></span>
</p>
<p style="box-sizing: border-box; margin-top: 0px; margin-bottom: 15px; font-size: 15px; color: rgb(85, 85, 85); font-family: Georgia, &quot;Times New Roman&quot;, Times, serif; white-space: normal; background-color: rgb(238, 238, 238);">
    <span style="box-sizing: border-box; font-size: 14px;">&nbsp; &nbsp; 安装步骤（5）：由于安装完了增强包，我就不过多赘述了。</span>
</p>
<p>
    <br/>
</p>
