github链接

[neo2358/laplace](https://github.com/neo2358/laplace)



在区域
$$
(x-0.5+y^2)^2+y^2\leq 1
$$
内使用积分方法计算laplace函数的狄里克莱边值问题，其中数值积分使用fmm包中的相关函数计算。

主函数：cal_function.m 输入一个函数句柄,输出误差的对数的图像以及L2误差

示例：

```matlab
cal_function(@(X,Y)(X.^2-Y.^2))
```






fdm_5points.m中使用五点差分格式计算，计算精度与时间复杂度均远高于fmm



