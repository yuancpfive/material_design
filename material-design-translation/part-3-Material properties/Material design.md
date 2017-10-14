原文地址：[https://material.io/guidelines/material-design/material-properties.html#](https://material.io/guidelines/material-design/material-properties.html#)

# Material properties # 
Material 属性

## Material has certain immutable characteristics and inherent behaviors. ##
Material 拥有某些不变的特性和固定的行为.

## Understanding these qualities of material will help you manipulate material in a way that’s consistent with the vision of material design. ##
理解Material的这些特性可以帮助你以符合Material design的愿景来操纵Material

## Material characteristics ##

- Solid
- Occupies unique points in space
- Impenetrable
- Mutable shape
- Changes in size only along its plane
- Unbendable
- Can join to other material
- Can separate, split, and heal
- Can be created or destroyed
- Moves along any axis


Material 特性

- 固体(坚实),不能穿透的
- 在空间上使用独特的点
- 费解的
- 易变的形状
- 只在对应的水平面上改变尺寸
- 不能弯曲的
- 可以添加到其他 material 中
- 能分割,分离,和还原
- 能被创造或者毁灭
- 能独自在任何轴上移动


## Physical properties ##
物理特性

Material has **varying x & y dimensions **(measured in dp) and a **uniform thickness** (1dp).

Do.
The height and width of material can vary.

Don’t.
Material is always 1dp thick.

Material 拥有变化的x和y尺寸(单位是dp),和均匀的厚度(1dp)

下面是两种说法:

正确的说法:

material 的宽高是可变的

正确的说法:(因为这里是有对应着视频的,所以Don't 是指视频演示的内容不正确)
Material 总是1dp厚

----------------------------

Material casts shadows.

Shadows result naturally from the relative elevation (z-position) between material elements.

Do.
Shadows depict the relative elevation between material elements.

Don’t.
Shadows are never approximated by coloring material.

Material产生阴影

相互有关系material对象的高度会自然的产生阴影.

----------------------------------

下面是两种说法:

正确的说法:
阴影可以表明 material 对象间的高度关系.

正确的说法:(因为这里是有对应着视频的,所以Don't 是指视频演示的内容不正确)
*有颜色的 material 产生的阴影一点都不相似*(*这个翻译有问题!!!!*).

-------------------------------------
Content is displayed on material, in any shape and color. Content does not add thickness to material.

Do.
Material can display any shape and color.

任何形状和颜色的 material 上都能显示内容,内容不会增加 material 的厚度.

正确的说法:
material 能表现出任何的形状和颜色.

-------------------------------------

Content can behave independently of the material, but is limited within the bounds of the material.

Do.
Content behavior can be independent of the behavior of material.

内容独立于 material 而行动, 但是受限于 material 的界限(即只能在 material 的界限内行动).

正确的说法:
内容的行为是独立于 material 的行为的.

------------------------------------

Material is solid.

Input events cannot pass through material.

Do.
Input events only affect the foreground material.

Don’t.
Input events cannot pass through material.

Material 是坚固的

输入事件不能穿透 material.(这个说法感觉不正确:事件有传递性)

正确的说法:
输入事件只能影响前景的 material

正确的说法:(因为这里是有对应着视频的,所以Don't 是指视频演示的内容不正确)
输入事件不能穿透 material.()

----------------------------------

Multiple material elements cannot occupy the same point in space simultaneously.

Do.
Using elevation to separate material elements is one method of preventing multiple material elements from occupying the same point in space simultaneously.

Don’t.
Multiple material elements cannot occupy the same point in space simultaneously.

多个 material 对象不能同时占据空间上相同的点(这点跟现实世界也是一致的.)

正确的说法:
使用海拔来分割 material 对象是一种阻止多个 material 对象同时占据相同空间点的方法.

正确的说法:(因为这里是有对应着视频的,所以Don't 是指视频演示的内容不正确)
多个 material 对象不能同时占据空间相同的点.(这是什么意思???怎么又作为don't 的呢??)

-----------------------------------

Material cannot pass through other material.

For example, one sheet of material cannot pass through another sheet of material when changing elevation.

Don’t.
Material cannot pass through other material.

Material 不能穿透其他的 material.

举个栗子,当改变高度的时候,一片 material不能穿透另外一片material.

错误的说法:
Material 不能穿透其他的 material.

----------------------------------

## Transforming material ##

Material can change shape.

## 转换 material ##
material 能转换形状.

--------------------------------

Material grows and shrinks only along its plane.

Do.
Material grows and shrinks only along its plane.

material 只能在他所在的平面拉伸和收缩.

----------------------------------------

Material never bends or folds.

Don’t.
Material never bends or folds.

material 不能弯曲和褶皱.

-----------------------------------------

Sheets of material can join together to become a single sheet of material.

一片的material 能相互结合变成新的一片 material.

------------------------------------------

When split, material can heal. For example, if you remove a portion of material from a sheet of material, the sheet of material will become a whole sheet again.

当被分隔后, material 能恢复.例如,如果你从一片 material 移除了一部分, 被移除的部分又会变成一个完整的一片 material.

----------------------------------------

## Movement of material ##
Material can be spontaneously generated or destroyed anywhere in the environment.

## material 的移动 ##
在material 所在的环境中, material 能自发的产生或者毁灭. 

----------------------------------------

Material can move along any axis.

material 能在任何的轴上移动.

----------------------------------------

Z-axis motion is typically a result of user interaction with material.

Z轴运动通常是用户与 material 交互的结果。

-----------------------------------------------
certain-----某些
immutable ----- 一成不变
inherent -----固有
qualities -----质量
manipulate -----操作
consistent -----一贯
vision -----视力
consistent with the vision----符合愿景
Solid-----固体,坚实
Occupies-----占用
unique-----独特的
Impenetrable-----费解的
Mutable-----易变得
plane-----水平面
Unbendable-----不能弯曲的
vary-----变化
uniform -----制服,匀净的
elevation-----海拔
depict-----描绘
approximated-----近似
independent-----独立
bounds-----界限
simultaneously-----同时
occupy-----占据
shrinks-----收缩
bends-----弯曲
folds-----褶皱
portion-----一部分
spontaneously-----自发
spontaneously generated----- 自发产生
motion-----运动
typically-----一般
interaction with-----互动