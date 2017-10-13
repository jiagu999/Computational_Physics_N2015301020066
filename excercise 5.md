## Excercise 5:The cannon
### Problem
- Caculate the trajectory of our cannon shell including both air drag and the reduced air density at high altitude so that you can reproduce the results in Figure 2.5.Preform your calculation for different firing angles and determine the value of the angle that give the maximum range.
- 空气阻力对炮弹的影响：![](http://latex.codecogs.com/gif.latex?F_{drag}=-B_2v^2)
- 海拔高度改变空气密度而影响炮弹![](http://latex.codecogs.com/gif.latex?F_{drag}^*=\frac{\rho&space;}{\rho&space;_0}F_{drag}(y=0)=(1-\frac{ay}{T_0})F_{drag}(y=0))
-再利用欧勒法微分递推出炮弹轨迹，取![](http://latex.codecogs.com/gif.latex?30^{\circ}\sim&space;60^{\circ})发射炮弹，再用pylab得到图像如下
- [代码](https://github.com/jiagu999/Computational_Physics_N2015301020066/blob/master/excercise%205_code)
- 运行结果![](https://i.loli.net/2017/10/13/59e0e19f7fb6e.png)
### 结论
- 加上空气阻力及海拔对空气阻力的改变后，炮弹发射的最全距离的角度再![](http://latex.codecogs.com/gif.latex?40^{\circ}\sim&space;45^{\circ})范围内
最后细分角度测量落点距离最大值时角度为43.4度，距离为24.53km。
