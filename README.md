[![](https://jitpack.io/v/lihangleo2/ChartView.svg)](https://jitpack.io/#lihangleo2/ChartView)

# ChartView
统计图组件,其中包括2个自定义控件：
* ChartLineView 折线图统计图
* ChartCircleView 饼状统计图

#### ChartView诞生了
* [ChartView诞生日](https://github.com/lihangleo2/ChartView/wiki) 

# 一、折线统计图
<strong>效果展示:</strong>

![](https://github.com/lihangleo2/ChartView/blob/master/gifs/showLine1.gif)

## 扫描二维体验效果(下载密码是：123456)
![](https://github.com/lihangleo2/ChartView/blob/master/gifs/eLth.png)

<br>

## 添加依赖

 - 项目build.gradle添加如下
   ```java
   allprojects {
		repositories {
			maven { url 'https://jitpack.io' }
		}
	}
   ```
 - app build.gradle添加如下
    ```java
   dependencies {
	        implementation 'com.github.lihangleo2:ChartView:1.0.0'
	}
   ```
   
<br>

## 1.2、折线统计图属性
在我们还未设置任何属性的时候，我们的坐标轴长这样：

<img src="https://github.com/lihangleo2/ChartView/blob/master/gifs/source1.png" alt="Sample"  width="350">

### 坐标轴相关属性
* <strong>修改坐标轴颜色</strong>  app:cl_axesColor="#ff0000"
* <strong>修改坐标轴宽度（粗细）</strong>  app:cl_axesWidth="2dp"

修改后的效果如图：
<img src="https://github.com/lihangleo2/ChartView/blob/master/gifs/axexAbout.png" alt="Sample"  width="350">



