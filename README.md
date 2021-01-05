# AttributeTree
Minecraft Bukkit plugin Skill AttributeTree
一个基于SkillAPI和VexView的属性加点插件，高度自定义性的界面，是Sk自带属性加点界面的完美替代品。创造属于你自己的属性加点界面吧！插件小巧轻量，开源安全，功能较为强大。看腻了Skill自带的属性加点界面(class attr)？不妨来试试这款插件！

## 功能：
· 自定义加点GUI
· 自定义加点属性
· 自定义消耗属性点

## 配置文件config.yml(演示案例 仅供参考)

/*:
 * #############################################################################
 * #  config.yml
 * #  启梦团队
 * #
 * #
 * #
 * #
 * #
 * #  加点属性：定义在SkillAPI目录下的 attributes.yml里面的属性
 * #  图片路径和vv的写法一样 参考vv教程
 * #############################################################################
 * picture:
 *   # 图片路径 和vv路径填写一样
 *   url: "[local]tf/UI_StatusFrame00_TEX.png"
 *   # 显示x坐标
 *   x: 45
 *   # 显示y坐标
 *   y: 10
 *   # 图片宽度
 *   width: 500
 *   # 图片高度
 *   height: 300
 * # 按钮设置
 * buttonSettings:
 *   # 通用设置
 *   currency:
 *     # url - 按钮贴图链接
 *     # url2 - 按钮被选中贴图链接
 *     url: "[local]tf/加点按钮.png"
 *     url2: "[local]tf/选中加点按钮.png"
 *   goldFox:
 *     x: 325
 *     y: 200
 *     # 图片宽度
 *     w: 30
 *     # 图片高度
 *     h: 30
 *     # 加点属性列表(只能加一点 若要加多个点 请重复键入)
 *     addAttr:
 *       - '烈魂'
 *       - '战斗本能'
 *     # 消耗属性点
 *     point: 2
 *   star:
 *     x: 170
 *     y: 200
 *     w: 30
 *     h: 30
 *     addAttr:
 *       - '物语'
 *       - '海语'
 *     point: 2
 *   starLight:
 *     x: 247
 *     y: 200
 *     w: 30
 *     h: 30
 *     addAttr:
 *       - '物语'
 *       - '能源虹吸'
 *     point: 2
 *   sunLight:
 *     x: 404
 *     y: 200
 *     w: 30
 *     h: 30
 *     addAttr:
 *       - '烈魂'
 *       - '战斗本能'
 *     point: 2
 *   dragonSpirit:
 *     x: 90
 *     y: 200
 *     w: 30
 *     h: 30
 *     addAttr:
 *       - '烈魂'
 *       - '战斗本能'
 *     point: 2
 * # 属性点显示坐标
 * attributePoints:
 *   x: 500
 *   y: 300
 */

## 注意事项：
1. 本插件基于SkillAPI和VexView插件，无两插件中任意一个，都无法正常运行
2. 本插件仅在1.12.X测试过 ，但并不代表其他版本无法使用
3. addAttr下面的属性 均需在SkillAPI配置目录下attributes.yml中有此属性的配置 无则报错
4. 路径和xywd 均与vv写法相同
5. 一定要配置好config(重要)

## 原创声明：
1. 本插件所用所有代码均为原创,不存在借用/抄袭等行为
2. 转载请经允许
3. 版权归 麒麟-启梦团队 所有
