<fon size=22 face="������"><center>�й������ѧ</center></fot>
<font size=26><center>**ʵ &ensp; �� &ensp; �� &ensp; ��**</center></font>


<font face="����" size=4
<b>
<!--�ļ�ͷ ��һ�� ��Ҫ�Ķ�!!!!!!!!-->
<div
    <span style="float: left">ѧ������: ��һ��</span>
    <span style="float: right">ָ����ʦ: ����</span>
</div
<center>ѧ��: 22020007136 </center>
<!--�ļ�ͷ �ڶ��� ��Ҫ�Ķ�!!!!!!!!-->
<d
    <center>ʵ��ص�:��Ϣ��¥C102</center>
    <center>ʵ��ʱ��: 2023��8��25��</center>
</div
<b


#### һ��ʵ������:�γ̸�����shell

#### ����ʵ�����ݣ�
1. �˽�γ̿��趯���Ϳγ̽ṹ
2. ������ʶshell
#### ����ʵ�鲽�裺
ʹ��shell���в���
1. �½��ļ���
2. �˽�ʹ��touch�½��ļ�
3. ʹ��echo����ָ��ļ�
4. ���������ļ�
5. ���Բ���������ض����ݼ�¼���ļ�
6. ���Ի�ȡ���Ե�����Ϣ
#### �ġ�ʵ����뼰�ؼ������ͼ������
�½��ļ�
```shell
cd /tmp
mkdir missing
```
![Alt text](%7D%5D%5DC6MYPTIUASXPHYGTGN%7B0-1.png)
�½��ļ�����������
```shell
touch semester
echo '#''!'/bin/sh > semester
echo curl --head --silent https://missing.csail.mit.edu
#ʹ��cat��ӡ���ļ�����
cat semester
```
![Alt text](<1~_1WDFL%_TZ){K3N2G7~CG-1.png>)
> �ɹ�������Ҫ������ݵ����������ʱ���������ķ���Ҫע��ʹ������


�����ļ�
```shell
./semester
```
![Alt text](<{(9G56@Q6YX]0}(I3]AORVX-1.png>)
> ��Ҫע��Ȩ������

���ض�����������ļ�
```shell
./semester | grep last-modified > ~/last-modified.txt
```
![Alt text](Z6G%2561SJLG%5DDTNE%7D8%60H3RZ3-1.png)
> �����õ��˹ܵ�

��ȡ���Ե���
```shell
find /sys -name capacity | xargs cat
```
![Alt text](73%60MH_79R(DX)P5_7CMVZ%7DO-1.png)
> ǰ��������Ϊû����rootȨ�����Ի��б���


#### �塢���������⼰��ν����
1. �ڳ�������semester�ļ���ʱ��������Ȩ������

> ʹ��chmod�ı��ļ���Ȩ�޼���

```shell
chmod +rwx semester
```
2. ��ʹ��vm��������Ի�ȡ������Ϣ��ʱ����ԭ��Ӧ����capacity�ļ����ļ�������Ϊ��
   
> ��ʹ�����������������WSLʱ�Ž��������
#### �����ĵ���᣺
��Щ�������������ѣ�shell���μ�����ܶ����ֲ��Ǻ��Ѻã����˽��Ժ����������׽���
shell��Ȼ�Ǻܻ����Ķ����������˽�Ҳ��Ҫһ������ϰ����ʲôҲ���˽���������Ҫ��ɿκ���ϰ����һ������ս�Եġ�
</b>
</font>