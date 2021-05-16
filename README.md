
# play-plane-game

## 简介
休闲小游戏
### 在线试玩（需要挂代理访问） 
github [https://chenyouf1996.github.io/play-plane-game/](https://chenyouf1996.github.io/play-plane-game/)

![飞机大战演示图1](https://user-images.githubusercontent.com/51696131/118353493-0dbc4c80-b599-11eb-9ac0-99b481bfe199.gif)

![飞机大战演示图2](https://user-images.githubusercontent.com/51696131/118353940-262d6680-b59b-11eb-82fd-28cd71969ef0.gif)

![飞机大战演示图3](https://user-images.githubusercontent.com/51696131/118353948-304f6500-b59b-11eb-9401-fe98e938bcc5.gif)

### 游戏引擎
CocosCreate

### 玩法介绍
1. 我方: 血量200
2. 敌方:
    - 基纽队长:紫色 血量50 飞行过程左右飘 碰撞掉血50
    - 弗利沙:白色 血量100 直线飞行 发射橙色子弹伤害50速度较慢 碰撞掉血100
    - 拉迪茨: 血量150 旋转飞行 发射白色子弹伤害50速度较快 碰撞掉血100
    - 贝吉塔: 血量200 极速下坠 碰撞掉血100
    - 滑稽boss(击杀20只滑稽后出现黑悟空) 行为怪异 血量3000 尖头子弹
    - 黑悟空boss 行为怪异 血量5000 黑色子弹3连发
3. 武器道具
    - 子弹数量有限打完即哑火 吃到新子弹之前没打完的会夹杂一起 打中敌人子弹数才会减少
    - 子弹道具中随机获取一种
    - 紫色1发: 初始子弹数量70发 伤害50 道具中获得90
    - 紫色2发: 伤害100 数量80
    - 紫色3发: 伤害150 数量70
    - 滑稽子弹: 伤害200 数量60 对滑稽boss伤害翻倍
    - 蓝色漩涡弹: 伤害250 数量50
4. 大招螺旋丸
    - 开场动画 全屏螺旋丸 伤害500 可清除敌方子弹 右下角点击使用
5. 回血道具 
    - 回血+50(满血不加) 回血+100(血量低于或等于100触发) 回血+150(血量低于或等于50触发) 扣血-50(血量低于或等于50不触发) 空血包
6. 援军
    - 开场援军 援军数量为5 自下而上贯穿敌军 吃到超神水触发援军
    - 比克: 伤害100
    - 悟空: 伤害150
    - 宇智波鼬: 伤害200
7. 随机难度
    - 每次开局 子弹发射频率,敌军飞行速度,道具掉落时间,boss出现时间 有略微差异
8. 得分
    - 每秒得分+1
    - 基纽:5
    - 弗利沙:10

    - 拉迪茨:20
    - 贝吉塔:30
    - 滑稽:100
    - 黑悟空:200
