## 几何体
1. 圆柱几何体
```
CylinderGeometry(radiusTop : Float, radiusBottom : Float, height : Float, radialSegments : Integer, heightSegments : Integer, openEnded : Boolean, thetaStart : Float, thetaLength : Float)
radiusTop — 圆柱的顶部半径，默认值是1。
radiusBottom — 圆柱的底部半径，默认值是1。
height — 圆柱的高度，默认值是1。
radialSegments — 圆柱侧面周围的分段数，默认为8。
heightSegments — 圆柱侧面沿着其高度的分段数，默认值为1。
openEnded — 一个Boolean值，指明该圆锥的底面是开放的还是封顶的。默认值为false，即其底面默认是封顶的。
thetaStart — 第一个分段的起始角度，默认为0。（three o'clock position）
thetaLength — 圆柱底面圆扇区的中心角，通常被称为“θ”（西塔）。默认值是2*Pi，这使其成为一个完整的圆柱。
```
2. 球体
```
SphereGeometry(radius : Float, widthSegments : Integer, heightSegments : Integer, phiStart : Float, phiLength : Float, thetaStart : Float, thetaLength : Float)
radius — 球体半径，默认为1。
widthSegments — 水平分段数（沿着经线分段），最小值为3，默认值为8。
heightSegments — 垂直分段数（沿着纬线分段），最小值为2，默认值为6。
phiStart — 指定水平（经线）起始角度，默认值为0。。
phiLength — 指定水平（经线）扫描角度的大小，默认值为 Math.PI * 2。
thetaStart — 指定垂直（纬线）起始角度，默认值为0。
thetaLength — 指定垂直（纬线）扫描角度大小，默认值为 Math.PI。
```
3. 圆锥几何体
```
ConeGeometry(radius : Float, height : Float, radialSegments : Integer, heightSegments : Integer, openEnded : Boolean, thetaStart : Float, thetaLength : Float)
radius — 圆锥底部的半径，默认值为1。
height — 圆锥的高度，默认值为1。
radialSegments — 圆锥侧面周围的分段数，默认为8。
heightSegments — 圆锥侧面沿着其高度的分段数，默认值为1。
openEnded — 一个Boolean值，指明该圆锥的底面是开放的还是封顶的。默认值为false，即其底面默认是封顶的。
thetaStart — 第一个分段的起始角度，默认为0。（three o'clock position）
thetaLength — 圆锥底面圆扇区的中心角，通常被称为“θ”（西塔）。默认值是2*Pi，这使其成为一个完整的圆锥。
```
4. 正十二面几何体
```
DodecahedronGeometry(radius : Float, detail : Integer)
radius — 十二面体的半径，默认值为1。
detail — 默认值为0。将这个值设为一个大于0的数将会为它增加一些顶点，使其不再是一个十二面体。
```

## 材质
1. 基础网格材质(MeshBasicMaterial)

```
一个以简单着色（平面或线框）方式来绘制几何体的材质。
这种材质不受光照的影响。
```
2. Lambert网格材质(MeshLambertMaterial)
```
一种非光泽表面的材质，没有镜面高光。
这可以很好地模拟一些表面（例如未经处理的木材或石材），但不能模拟具有镜面高光的光泽表面（例如涂漆木材）。
```
3. Phong网格材质(MeshPhongMaterial)
```
该材质可以模拟具有镜面高光的光泽表面（例如涂漆木材）
```

## 贴图


## 光照

## 辅助线
## 投影
## 层级模型、树结构
## 相机





相机位置？
1. OrthographicCamera( left : Number, right : Number, top : Number, bottom : Number, near : Number, far : Number )
left — 摄像机视锥体左侧面。
right — 摄像机视锥体右侧面。
top — 摄像机视锥体上侧面。
bottom — 摄像机视锥体下侧面。
near — 摄像机视锥体近端面。
far — 摄像机视锥体远端面。
相机辅助线？

网格材质对象
2. MeshLambertMaterial

光照类型


渲染
setClearColor(背景色，透明度)


