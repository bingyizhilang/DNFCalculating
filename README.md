# DNFCalculating

  主要框架由纸飞机实现，西瓜协助修改，python编写，pyqt5图形GUI库<br>


  ## 各职业实现
    女大枪(纸飞机提供)、男大枪(幕城提供)、剑魔(爱敏777提供)由纸飞机完成<br>
    剑豪(东总提供)、狂战(东总提供)、光枪(东总提供)、毒王(东总提供)由纸飞机完成<br>
    女机械由荔枝贝壳完成<br>
    女弹药由西瓜完成<br>
    将军由RBQ小一完成<br>

  ## 代码说明
  ### 添加一个职业的步骤
    1 创建职业.py文件,创建对应的职业素材文件夹,结构参考其他职业,在技能文件夹中添加技能图标,图片后缀为png,buff图标命名为BUFF.png<br>
    2 参考其他职业,在.py文件中完善技能数据及部分特殊的算法(如果有比较奇怪的算法需要时间,可以参考芙蕾雅.py修改技能类结构,或者修改伤害算法)<br>
    3 在main.py中引入并添加对应职业

  ### base.py
    核心算法及主体界面绘制部分<br>
    常规无需修改该部分,如需要优化程序的效率及部分算法，可尝试修改<br>
    主体核心可优化空间比较大,但由于接触PY才几个礼拜,对PY多核心运算的不熟悉,暂不打算修改,欢迎尝试优化

  ### 装备.py
    装备及套装数据部分<br>
    如需要添加修改装备.可在此处修改,注意装备的后缀数字,需要与img/装备下的文件名一致(新增需要同步添加图标)

  ### 装备函数.py
    一些计算公式部分,除非公式出现偏差,否则无需修改<br>

