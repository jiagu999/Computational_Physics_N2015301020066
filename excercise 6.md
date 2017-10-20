# Exercise 6:The spin of baseball
## Problem
- 2.19.Model the effect of backspin on the range of a batted ball.Assume an angular velocity of 2000 rpm.
## 摘要
- 棒球的运动轨迹受空气牵扯力，以及棒球自旋受到的Magnus力的影响，使得球的轨迹十分复杂。
- 本题要解决球的后自旋对球的射程范围的影响。
## 研究背景
- 棒球在受到重力，空气阻力及Magnus力的作用下运动微分方程为
- ![](http://latex.codecogs.com/gif.latex?m\frac{d^{2}\vec{r}}{dt^{2}}=m\vec{g}-B_2v^{2}\vec{v}^{0}&plus;S_0\vec{v}\times&space;\vec{w})
- 其中![](http://latex.codecogs.com/gif.latex?m)是棒球质量，![](http://latex.codecogs.com/gif.latex?g)是重力加速度，![](http://latex.codecogs.com/gif.latex?\vec{v}^{0})是速度方向的单位矢量，![](http://latex.codecogs.com/gif.latex?\vec{w})即棒球旋转角速度。上面![](http://latex.codecogs.com/gif.latex?-B_{2}v2\vec{v}^{0})即空气阻力项，而![](http://latex.codecogs.com/gif.latex?S_0\vec{v}\times&space;\vec{w})即为Magnus力。在棒球速度范围内尚可认为![](http://latex.codecogs.com/gif.latex?S_0)基本是一常量，而![](http://latex.codecogs.com/gif.latex?B_2)则显著依赖于棒球的速度，按照教科书上所给近似，可将其写为 ![](http://latex.codecogs.com/gif.latex?\frac{B_2}{m}=0.0039&plus;\frac{0.0058}{1&plus;\epsilon&space;^{\frac{v-35}{5}}})。最后再结合欧拉法写出递推运动微分公式。这是[代码](https://github.com/jiagu999/Computational_Physics_N2015301020066/blob/master/excercise%206_code)。
## 射程范围对比
|项目      |有后旋   |无后旋   |
|---------|---------|---------|
|最远距离  |113m     |119.5m  |
## 运动轨迹对比
![](https://i.loli.net/2017/10/20/59e9ebbfa2959.png)
## 小结
- 本次作业讨论了棒球的运动问题，讨论了棒球所受空气阻力和Magnus力对棒球运动的影响。其中前者的影响极为显著，将很大地减少棒球的射程，明显地改变棒球的轨迹，而后者也有不小的影响，如果棒球旋转适当，可以朝不同的方向发生偏移，因而给棒球运动带来很大的不确定性和娱乐性。
