# 更新日志
4.28~5.6出去旅游了，暂时没办法更新
## 如果你会手打冰心，希望我复刻手打循环请找沐深要我的联系方式
	当前按键是根据https://jx3box.com/bps/76527中的
	【常规循环宏】繁音急节和心鼓弦手动来写的

# 教程
## 目录

*  [职业文件路径](#职业文件路径)  
*  [奇穴选择](#奇穴选择)  
*  [秘籍](#秘籍)  
*  [属性](#属性)  
*  [设置教程](#设置教程)
	*  载入职业
 	*  导入冰心监控
	*  进行取图/取色
	*  导入宏并设置按键
	*  保存你的取图和键位
	*  如何起手？
	*  功能按钮说明  


## 职业文件路径

	C:\mmconfig\data


## 奇穴选择

> [!TIP]
> 最求更高DPS

		青梅嗅,惊寒,新妆,芳姿畅音,枕上,广陵月,流玉,钗燕,盈袖,化冰,夜天,凝华

> [!TIP]
> 你没钱买万灵丹

		明妃,惊寒,新妆,芳姿畅音,枕上,广陵月,流玉,钗燕,盈袖,化冰,夜天,凝华


## 秘籍

  玳弦急曲 3伤害 1距离  
  剑气长江 2冷却 6%伤害 1刷新  
  江海凝光 1会心 2伤害 1距离/1会心  
  繁音急节 3减cd 1满堂效果  
  天地低昂 2减cd 1持续时间 （别点回血，回得少还会浪费满堂(会心会效）层数）  

 ## 属性  
 摘自https://jx3box.com/bps/76527
 ### 加速方面
 > [!TIP]
 > 9140上限更高，但是需要手动
 > 无论打不打ab玳弦都是9140手动更高

 > [!TIP]
 > 5089适合按宏选手，适合休闲玩家（也就是本按键）

 ### 武器方面  
 
> [!TIP]
> 小橙武免费，自带加速  
> 但是加速数值比较阴间（9114），实际上要么浪费加速属性，要么多打一个加速附魔，要么喝加速大酒

> [!TIP]
> 水特效毕业快，赛季初即可获得，但是价格不菲。
> 且水特效配装灵活，5089水特效喝酒+加速药=9140，进可喝酒吃药9140手动，退可5089按宏 

> [!TIP]
> 大橙武不说了，全是优点

！！！循环问题私聊我！！！
--
！！！不会设置可找调试！！！
--
！！！软件问题找沐深！！！
--
	（报错，异常，开启没反应，驱动问题）
## 设置教程 
### 一、载入职业

![image](https://github.com/iderfl/-cw-/blob/main/%E5%9B%BE%E7%89%87/%E9%80%89%E6%8B%A9%E8%81%8C%E4%B8%9A.png)

### 二、导入冰心监控

![image](https://github.com/iderfl/mm-bx/assets/90140812/ae3462ee-cc85-4b33-ad3a-3399b46aff20)


### 三、进行取图/取色

| 取图项 | 取图说明 | 
| :----: | :---- | 
| 化冰 | 释放心鼓弦，图标亮起后框选图标`内部任意` | 
| 橙武 | 取消隐藏，图标亮起后框选图标`内部任意` | 
| 繁音 | 繁音好的时候，取图标内`粉色的点` | 
| 心鼓弦 | 心鼓弦好的时候，取图标内`红色的点` | 
| 蓝条 | 取`蓝条20%~40%`位置的点 | 

> [!TIP]
> 关于万灵丹：
> 在本里打一次实战，看看多久会空蓝，根据战斗时间来决定蓝条取哪个位置  
> 你可以不设置万灵丹的键位，根据实战情况手动使用万灵丹，但是一定要取色


> [!TIP]
> 取图完成后在茗伊插件→目标监控里将需要隐藏的监控，把“隐藏消失的”选项勾选上。

> [!TIP] 
> 不要框选到图标外面

> [!TIP]
>   可拖动蓝条开启方法剑心插件-常用-技能增强-额外可拖动的蓝条
>   ![image](https://github.com/iderfl/mm-bx/assets/90140812/e4910717-76b3-40a6-b92f-e5914bc57206)

> [!TIP]
> 取图/取色完成后的展示  
> ![image](https://github.com/iderfl/mm-bx/assets/90140812/7ce330aa-aee3-43a8-bd59-1bc58d655d84)  
> ![image](https://github.com/iderfl/mm-bx/assets/90140812/fa6eff39-f04d-4369-a4e4-e866750eafe6)






### 四、导入宏并设置按键

宏
> [!TIP]
> 基础宏，必选

	/cast [nobuff:芳姿畅音&buff:满堂|bufftime:盈袖<2.5] 芳姿畅音
	/cast [tbuff:凝华] 剑气长江
  	/cast 江海凝光
  	/cast 玳弦急曲
  	/cast 广陵月
  	/cast [nobuff:满堂] 剑影留痕

橙武宏
> [!TIP]
>大橙武需要使用

  	/fcast [buff:钗燕＞0&tbuff:气吞长江=2] 剑影留痕
  	/cast [buff:钗燕=2&tbuff:气吞长江=1] 剑破虚空
  	/cast [tbuff:气吞长江=2&bufftime:飞霜绛露>1.3] 江海凝光
  	/cast 剑气长江


 ### 五、保存你的取图和键位
 
 给你的配置取名，并点击保存配置按钮  
![image](https://github.com/iderfl/mm-bx/assets/90140812/511042cd-b2eb-4ffa-95bb-4071b941a59b)


 ### 六、如何起手？
 

倒数3手动心鼓弦（非必需）：
 
 	按【启动】开启取色-按【总开关】开启按键  
  


 ### 七、功能按钮说明
 
 说明：
 
 	开始运行：开始运行这个职业
 
	模式键：选择【启动】开始取图取色（开始取图后再按开关才能开启和暂停，没有开启取图是不会按任何键的）
 
	总开关键：暂停/启动按键
 
