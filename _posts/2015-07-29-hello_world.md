---
layout: post
title: Coding
category: code
comments: true
---

![github](http://github.com/unicorn.png "github")

## 感想

我们学习编程真的不能马虎，很多人比如说我就养成很不好的习惯，刷oj的时候没耐心想，总想着看题解；平时学习算法也是
不仔细，总是看着别人的模板来写，自己也就理解不透彻，其实是浪费了时间；我们必须要打好基础，数学的基础，培养成自
己的一套变成思路，比如说下面一个求多边形面积的代码，就利用了叉积，这是一个体现很基础的数学知识与编程结合的栗子：

```C++
	double polygon_area(int n)
	{
		double area=0;
		for(int i=0; i<n-1; i++)
			area += p[i].x * p[i+1].y - p[i].y * p[i+1].x;	
		area += p[n-1].x * p[0].y - p[n-1].y * p[0].x;
		return fabs(area) / 2;
	}
```

### 好处

* 扎实的基础，以后随手就可以写出各种代码，面试什么的就so easy啦！
