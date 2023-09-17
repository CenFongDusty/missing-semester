<fon size=22 face="方正舒"><center>中国海洋大学</center></fot>
<font size=26><center>**实 &ensp; 验 &ensp; 报 &ensp; 告**</center></font>


<font face="宋体" size=4
<b>
<!--文件头 第一行 需要改动!!!!!!!!-->
<div
    <span style="float: left">学生姓名: 岳一磊</span>
    <span style="float: right">指导老师: 范浩</span>
</div
<center>学号: 22020007136 </center>
<!--文件头 第二行 需要改动!!!!!!!!-->
<d
    <center>实验地点:信息南楼C102</center>
    <center>实验时间: 2023年8月25日</center>
</div
<b


#### 一、实验名称:课程概览与shell

#### 二、实验内容：
1. 了解课程开设动机和课程结构
2. 初步认识shell
#### 三、实验步骤：
使用shell进行操作
1. 新建文件夹
2. 了解使用touch新建文件
3. 使用echo输入指令到文件
4. 尝试运行文件
5. 尝试查找输出中特定内容记录到文件
6. 尝试获取电脑电量信息
#### 四、实验代码及关键结果截图分析：
新建文件
```shell
cd /tmp
mkdir missing
```
![Alt text](%7D%5D%5DC6MYPTIUASXPHYGTGN%7B0-1.png)
新建文件并输入内容
```shell
touch semester
echo '#''!'/bin/sh > semester
echo curl --head --silent https://missing.csail.mit.edu
#使用cat打印出文件内容
cat semester
```
![Alt text](<1~_1WDFL%_TZ){K3N2G7~CG-1.png>)
> 成功输入了要求的内容但是在输入的时候对于特殊的符号要注意使用引用


运行文件
```shell
./semester
```
![Alt text](<{(9G56@Q6YX]0}(I3]AORVX-1.png>)
> 需要注意权限问题

将特定内容输出到文件
```shell
./semester | grep last-modified > ~/last-modified.txt
```
![Alt text](Z6G%2561SJLG%5DDTNE%7D8%60H3RZ3-1.png)
> 这里用到了管道

获取电脑电量
```shell
find /sys -name capacity | xargs cat
```
![Alt text](73%60MH_79R(DX)P5_7CMVZ%7DO-1.png)
> 前几行是因为没有用root权限所以会有报错


#### 五、遇到的问题及如何解决：
1. 在尝试运行semester文件的时候遇到了权限问题

> 使用chmod改变文件的权限即可

```shell
chmod +rwx semester
```
2. 在使用vm虚拟机尝试获取电量信息的时候发现原本应该有capacity文件的文件夹内容为空
   
> 在使用其他的虚拟软件如WSL时才解决了问题
#### 六、心得体会：
有些东西看起来很难，shell初次见面可能对新手不是很友好，但了解以后便更让人容易接受
shell虽然是很基础的东西但初次了解也需要一定的练习，在什么也不了解的情况下想要完成课后练习是有一定的挑战性的。
</b>
</font>