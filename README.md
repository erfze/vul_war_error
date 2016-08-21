###《漏洞战争：软件漏洞分析精要》勘误表

1. 前言VIII 第4段落最后一句：`专研` => `钻研`

2. P7页中多处的 `smail` => `smali`，`baksmail` ＝> `baksmali` （感谢 陈良@科恩实验室）

3. P529页第2段中，“按照`图10-12所示`的方法重新编译内核源码” => “按照`第10.3.7章节`的方法重新编译内核源码”（感谢 江小照）

4. P16页最后一行中`Thread` => `Threat`（感谢“不高兴撒”）

5. P164页第3段第3行`unsigned int（2字节）` => `unsigned int（4字节）`（感谢“55-AA”）

6. P355页最后一段中:`我们知道数组的元素大小为1014(0x3F6)长度的Vector.<Object>对象` => `我们知道ov[0]已经被赋值为长度0x3FE的Vector.<uint>对象`，`它就相当于ov[1][0x0d]` => `它就相当于ov[1][0x5]` (感谢“Cindy_晨曦-Smr02”)

7. P276页第一段第5行：`悬念指针` => `悬挂指针` （感谢“逍遥客”）
8. P228页最后一段，删除`然后按F7键跟进，`（感谢“55-AA”）

9. P228页图5-3中第5行的栈值`0000007F`=>`000003FF`,因为调试图是对应`char buff[128]`的程序，但后面笔者为方便写漏洞利用改成了`char buff[1024]`，而原有的调试图并未一起修改过来。因此同时，P229页图5-4中的`buff长度值0x7F`应修改为`buff长度值0x3FF`（感谢“55-AA”）

10. P230页表5-1中`\n`的作用`回车或换行`应改为`换行`（感谢“55-AA”）

11. P232页第2行`令ECX指向“0xCC……”字符串`改为`令ECX指向"90 90 CC CC ……"字符串`，图5-9下一行中`ECX指向“CC……”`改为`ECX指向“90 90 CC……”`（感谢“55-AA”）

12. P246第一段第3行`参考第8章`=> `参考第7章`（感谢“55-AA”）

13. P30页第2.4.1章节第一段第6行`蓝网队` => `篮网队`（感谢“55-AA”）

14. P492页第一段第1行`发现的其智能插座` => `发现的智能插座`（感谢“55-AA”）

15. P71页第2.7.5章节的上一段中，`基本与CVE-2012-3333类似`=> `基本与CVE-2010-3333类似`（感谢“肯特awp”）
 
16. P106页表3-5中第5行`0x10`=>`0x0A`，第6行`0x12`=>`0x0C`（感谢 hanfengley ）

17. P164页中`正整数最高位为1，负整数最高位为0`=>`正整数的最高位（即符号位）为0，负整数最高位为1`（感谢“期待的远行”）

18. P91页中`检查长度的高位是否存在数值` => `将长度的高位与低位进行拼接`（感谢 ench4nt3r）

19. P91页第3行中`0:015> dd ebp+0c` => `0:015> dd poi(ebp+c)`（感谢 ench4nt3r）

20. P144页第11行中`(3) CtableLayout + 0x90` => `(3) CtableLayout + 0x9C`（感谢 ench4nt3r）

21. P522页中图10-86上两处`R2`标注应应改为`R0`(感谢“杯中取月”)

22. P54页第一段第2行中`栈顶`=>`栈底`（感谢“兴华蔡27136”）

23. P78页最后一段第2行中“`buf2`与后面的空闲堆`00600bc8`进行合并” => “`heap`与后面的空闲堆`00530bb0`进行合并”（感谢“兴华蔡27136”）

24. P350页第5行`nofifyGlobalMemoryChanged` => `notifyGlobalMemoryChanged`（感谢 ench4nt3r ）

25. P284页第一段描述第2行中`第2个参数值0x0`=>`第2个参数值0x06457bc0`（感谢 ench4nt3r ）

26. P298页中`图7-17 CElement::insertBeforeHelper函数`=> `图7-17 CElement::insertBefore函数`（感谢 ench4nt3r ）

