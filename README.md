缝合了大量成品方案，并做了大量的注释和引导。个人英语很菜（高考没及格的那种），这个赶忙上传好多东西还没搞，目前是给群友分享较多。谢谢理解。

特别鸣谢https://github.com/Mintimate/oh-my-rime

基于这个作者的框架开始的这个项目，后续会继续做整合和新手引导，尽量做到让大家上手即用。

dict为字典文件夹

icons为图标文件夹

lua为插件脚本文件夹

opencc主要为emoji文件夹

default为rime层设置，特性是多平台适配兼容。主要包含	

	1. 候选方案列表
 
	2. 主要键位
 
	3. 方案切换相关包括快捷键
 
	4. 候选词默认个数和标签
 
	5. 标点符号输入习惯由symbols引入，此处不包含
 
	6. 常规快捷键
 
	7. 定义识别码
 
		a. 正则表达式
  
		b. 通过识别你之前输入过的内容来进行自动标点，比如你上一个输入的是数字，下一个就是“句号”就是半角，可当小数点
  
  8．西文模式快捷键
  
weasel为小狼毫的配置，里边主要包含外观配色信息

v_family.schema.yaml是真正的输入方案的配置，内涵大量设置且会覆盖default里的相同类型选项

v_family.dict.yaml是字典索引，你当然也可以直接在里边加词，但我还是更推荐你加到dicts里边的第一个用户词典里

radical_pinyin的两个是另一个输入方案“偏旁部首拆字输入”的配置文件和字典（本体），你也可以做一个一样的索引然后把本体扔dicts文件夹里边但是没必要

将上述文件一股脑直接扔到Rime的用户文件夹即可（本教程因为作者菜+时间赶，更多是给群友看的，他们多少有点使用基础）后续会快速频繁更新以至完善



