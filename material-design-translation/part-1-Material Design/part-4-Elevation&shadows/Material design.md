原文地址：[https://material.io/guidelines/material-design/elevation-shadows.html](https://material.io/guidelines/material-design/elevation-shadows.html)

# Elevation & shadows #

## Objects in material design possess similar qualities to objects in the physical world. ##
# 在 Material design 中的事物和现实世界中的事物具有相似的质量（特性）。 #

-----------------------------------------------

In the physical world, objects can be stacked or affixed to one another, but cannot pass through each other. Objects also cast shadows and reflect light.

在物理世界中，物体能被堆叠或者相互粘在仪器，但是不能穿过对方。物体也能产生阴影和反射光线。

----------------------------------------------

Material Design reflects these qualities to form a spatial model that is familiar to users and can be applied consistently across apps.

Material design 反映了这些（物理世界的）特性来形成一个用户很熟悉的并且能一致运用到不同应用程序中的空间模型。

----------------------------------------------

## Elevation ##
## 海拔（或高度） ##

Measured from the front of one surface to the front of another, an element’s elevation indicates the distance between surfaces and the depth of its shadow.

从一个表面的前面到另外一个表面的前面测量，元素的高度指明了表面之间的距离和它阴影的深度。

---------------------------------------------

## Resting elevation ##
## 静止高度（暂且这么翻译吧！！！） ##

All material elements have resting elevations. While components have consistent resting elevations across apps, they may have different resting elevations across platforms and devices.

所有的对象都有静止高度（暂且这么翻译）。当组件在不同应用程序中有静止高度，它们可能在不同平台和设备中有不同的静止高度。

---------------------------------------------------

## Dynamic elevation offsets ##
## 动态高度偏移 ##

Dynamic elevation offsets are the goal elevation that a component moves towards, relative to its resting state.

动态高度偏移是组件移动的目标高度，与其静止状态有关。
（动态高度偏移是组件相对其静止状态高度移动的目标高度）

---------------------------------------------------

# Elevation (Android) #
# Andriod 的高度 #

Elevation is the relative depth, or distance, between two surfaces along the z-axis.

高度是两个表面沿着z轴相互之间的深度，或者距离。

-----------------------------------------

**Specifications:**
- 
- Elevation is measured in the same units as the x and y axes, typically in density-independent pixels (dp). Because material elements have depth (all material is 1dp thick), elevation is measured in distance from the top of one surface to the top of another.
- A child object's elevation is relative to the parent object's elevation.

**指明：**
-
- 高度是跟x轴和y轴使用一样单位来测量的,通常是密度无关的单位中（是dp）。由于 material 对象有深度（所有的 material 是1dp的厚度），高度的计算是从一个物体的表面到另外一个物体的表面的。
- 一个子物体的高度与父物体的高度有关。

---------------------------------------------------

The images and values shown are for Android apps.

图片和数值用于安卓应用程序的说明。

![两个物体的多高度测量](https://storage.googleapis.com/material-design/publish/material_v_12/assets/0B6Okdz75tqQsTVdGcm1LX0dVeGM/whatismaterial-3d-elevation1.png)

--------------------------------------------------

## Resting elevation ##
## 静止高度 ##

All material objects, regardless of size, have a resting elevation, or default elevation that does not change. If an object changes elevation, it should return to its resting elevation as soon as possible.

material 所有的对象，不管大小，都有不改变静止高度，或者默认高度。如果一个物体改变了高度，它应该尽快回到其静止高度。

-------------------------------------------------

Desktop resting elevation is 2dp below the listed values to accommodate mouse and non-touch environments.

（这翻译是google给出的）
桌面静止高度低于其给出高度2dp,来迁就鼠标和非触摸环境。

-------------------------------------------------

**Component elevations:**
- 
- Components maintain consistent resting elevations across apps. For example, the floating action button’s elevation does not vary from one app to another.
- Components may have different resting elevations across platforms and devices, depending on the depth of the environment. For instance, TV has a greater depth than desktop as it has a larger screen and is viewed from further away. Similarly, both TV and desktop have a greater depth than mobile.

**控件高度：**

控件在不同应用程序中保持一贯的静止高度。例如：悬浮按钮的高度在不同应用程序中的高度不会改变。
控件依据环境的深度在不同平台和设备中可能有不同的静止高度。例如，电视比桌面更深，因为电视有更大的屏幕以及能从更远的地方被看到。相似的，电视和桌面都比移动设备有更深的深度。

----------------------------------------------------
possess -----具有
stacked-----堆叠
affixed-----黏贴，附加
reflects-----反映
spatial-----空间的
is familiar to-----很熟悉
depth-----深度
components-----组件
consistent-----一贯
goal-----目标
typically-----一般
density-----密度
independent-----无关
regardless-----不管
accommodate-----容纳，迁就
For instance-----例如