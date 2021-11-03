# study_plan
学习计划

#2021/11/2
##每天抽出3-4个小时去补充自己基础知识和完成每周分下来的算法题，并相对应的有所产出

#2021/11/3

##创建对象的三重方法

1，直接创建
let obj = {name:'小明',age:'20'};

2，构造函数创建
let obj = new Objeck()
obj.name = '小明';
obj.age = 20

3,objeck.create()创建

这种创建方法是创建到原型上的__proto__上的

let obj = objeck.create({
name:'小明',
age:20
})


