原文地址：[https://material.io/guidelines/material-design/environment.html](https://material.io/guidelines/material-design/environment.html)

# Environment #

# Material design is a three-dimensional environment containing light, material, and cast shadows. #

All material objects have x, y, and z dimensions.

All material objects have a single z-axis position.

Key lights create directional shadows, and ambient light creates soft shadows.

# Material design 是一个包含光线、材质、投影的三维环境。 #

所有的材质都有x，y和z轴的尺寸。

所有的材质都有一个单独的z轴位置。

（物体周围是有不同的光源的，包含主光源和周围光源）主光源投影到物体上产生了直接的阴影，周围的光源则产生了柔和的阴影。


## Material thickness ##
1dp

物体的厚度为1dp

## Shadows ##
Shadows are created by the elevation difference between overlapping material.

阴影是由不同的重叠物的海拔创造的。（**修正**：阴影是由不同重叠物的高度差产生的。）

![](https://storage.googleapis.com/material-design/publish/material_v_12/assets/0B7WCemMG6e0VVFpiZ041SmhwY2c/what-is-material-environment.png)

# 3D world #
The material environment is a 3D space, which means all objects have x, y, and z dimensions. The z-axis is perpendicularly aligned to the plane of the display, with the positive z-axis extending towards the viewer. Every sheet of material occupies a single position along the z-axis and has a standard 1dp thickness, equivalent to one pixel of thickness on screens with a pixel density of 160.

material的环境是一个3维空间，这意味着在里面的所有物体都有x，y和z轴。这里所指的z轴是垂直于显示器的，z轴正方向像观察者延伸。每片材料都占据了一个单一的z轴位置并且拥有标准的1dp厚度（理解的意思是：不管物体有多薄，最小占据单位是1dp），相当于像素密度为160的屏幕上的一个像素厚度。

![3D space with x, y, and z axes](https://storage.googleapis.com/material-design/publish/material_v_12/assets/0Bx4BSt6jniD7UXpQYWltVjNPWXc/whatismaterial-environment-3d.png)

## Light and Shadow ##
Within the material environment, virtual lights illuminate the scene. Key lights create directional shadows, while ambient light creates soft shadows from all angles.

在material环境中，虚拟的灯光照亮了场景。周围灯光从各个角度创造柔和的灯光时，主灯光创造了直接(主要)的阴影。


Shadows in the material environment are cast by these two light sources. In Android development, shadows occur when light sources are blocked by sheets of material at various positions along the z-axis. On the web, shadows are depicted by manipulating the y-axis only. The following example shows the card with a height of 6dp.

在material环境中的阴影是由这两种光源（主光源和周围光源)产生的。在安卓开发中，当光源被不同位置的材料块阻挡会在z轴产生阴影。在网络上（在平面上？），阴影只能通过操纵描绘y轴来产生。接下来的例子会展示出6dp高度的卡片。

![Shadow cast by key light](https://storage.googleapis.com/material-design/publish/material_v_12/assets/0B6Okdz75tqQsSFZUZ01GTk13T28/whatismaterial-environment-shadow1.png)

![Shadow cast by ambient light](https://storage.googleapis.com/material-design/publish/material_v_12/assets/0B6Okdz75tqQsdDhaaTMwMTFVLTA/whatismaterial-environment-shadow2.png)

![Combined shadow from key and ambient lights](https://storage.googleapis.com/material-design/publish/material_v_12/assets/0B6Okdz75tqQsNnVmbTNMUF9DR0U/whatismaterial-environment-shadow3.png)


--------------------------------------------------------
cast shadowns-----投影
dimension-----尺寸
ambient-----周围
thickness-----厚度
elevation-----海拔
overlapping----重叠
perpendicularly-----垂直
sheet-----片
occupies-----占据
equivalent-----当量
illuminate-----照亮
cast-----投
blocked-----受阻
depicted-----描绘
manipulating-----操纵