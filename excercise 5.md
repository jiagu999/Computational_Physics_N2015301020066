## Excercise 5:The cannon
### Problem
- Caculate the trajectory of our cannon shell including both air drag and the reduced air density at high altitude so that you can reproduce the results in Figure 2.5.Preform your calculation for different firing angles and determine the value of the angle that give the maximum range.
- 空气阻力对炮弹的影响：![](http://latex.codecogs.com/gif.latex?F_{drag}=-B_2v^2)
- 海拔高度改变空气密度而影响炮弹![](http://latex.codecogs.com/gif.latex?F_{drag}^*=\frac{\rho&space;}{\rho&space;_0}F_{drag}(y=0)=(1-\frac{ay}{T_0})F_{drag}(y=0))
-再利用欧勒法微分递推出炮弹轨迹，取![](http://latex.codecogs.com/gif.latex?30^{\circ}\sim&space;60^{\circ})发射炮弹，再用pylab得到图像如下
- [代码](https://github.com/jiagu999/Computational_Physics_N2015301020066/blob/master/excercise%205_code)
- 运行结果![](https://note.youdao.com/web/#/file/recent/image/WEBf2f57cf15b5157796c4edc8a91a8ec1b/)
-图片链接  https://note.youdao.com/web/#/file/recent/image/WEBf2f57cf15b5157796c4edc8a91a8ec1b/