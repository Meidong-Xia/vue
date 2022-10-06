### Vue2

#### 环境准备

![image-20220918104157692](F:\vue\assets\image-20220918104157692.png)

更改端口和添加代理

![image-20220918110151925](F:\vue\assets\image-20220918110151925.png)

#### `Vue`基础知识

##### `Vue`项目结构

![image-20220918110244270](F:\vue\assets\image-20220918110244270.png)

![image-20220918112539349](F:\vue\assets\image-20220918112539349.png)

##### `Vue`组件

![image-20220918134139683](F:\vue\assets\image-20220918134139683.png)

##### 入门案例

![image-20220918135738149](F:\vue\assets\image-20220918135738149.png)

##### 文本插值

![image-20220918154654033](F:\vue\assets\image-20220918154654033.png)

##### 属性绑定

![image-20220918155857852](F:\vue\assets\image-20220918155857852.png)

![image-20220918155911852](F:\vue\assets\image-20220918155911852.png)

##### 事件绑定

![image-20220918161849057](F:\vue\assets\image-20220918161849057.png)

![image-20220918161903053](F:\vue\assets\image-20220918161903053.png)

##### 双向绑定

![image-20220918171409876](F:\vue\assets\image-20220918171409876.png)

##### 计算属性

![image-20220918172710297](F:\vue\assets\image-20220918172710297.png)

计算属性的好处在于有缓存，如果数据没有变，是不会进入函数的。

##### Axios

###### 安装和入门



![image-20220918173031301](F:\vue\assets\image-20220918173031301.png)

![image-20220918174705053](F:\vue\assets\image-20220918174705053.png)

![image-20220918174639769](F:\vue\assets\image-20220918174639769.png)

###### 发送请求

![image-20220918174905008](F:\vue\assets\image-20220918174905008.png)

![image-20220918175028046](F:\vue\assets\image-20220918175028046.png)

![image-20220918185648832](F:\vue\assets\image-20220918185648832.png)

###### 请求体格式

![image-20220918203552880](F:\vue\assets\image-20220918203552880.png)

![image-20220918203559476](F:\vue\assets\image-20220918203559476.png)

默认是`json`格式，所以服务器端收不到，前端应改为：

![image-20220918203806912](F:\vue\assets\image-20220918203806912.png)

或者：

![image-20220918203916833](F:\vue\assets\image-20220918203916833.png)

###### 默认配置

![image-20220918215617213](F:\vue\assets\image-20220918215617213.png)

![image-20220918215635101](F:\vue\assets\image-20220918215635101.png)

![image-20220918215831043](F:\vue\assets\image-20220918215831043.png)

###### 响应格式

![image-20220919100958490](F:\vue\assets\image-20220919100958490.png)

###### 拦截器

- 请求拦截器

![image-20220919162112795](F:\vue\assets\image-20220919162112795.png)

- 响应拦截器

![image-20220919162103859](F:\vue\assets\image-20220919162103859.png)

  通过代码可以抽取到一个公用文件中

###### 条件渲染

![image-20220919170750293](F:\vue\assets\image-20220919170750293.png)

![image-20220919171131856](F:\vue\assets\image-20220919171131856.png)

`mounted`属性在页面加载完成之后就会执行

![image-20220919171404568](F:\vue\assets\image-20220919171404568.png)

###### 重用组件

![image-20220919172907311](F:\vue\assets\image-20220919172907311.png)

![image-20220919173019027](F:\vue\assets\image-20220919173019027.png)

![image-20220919173037556](F:\vue\assets\image-20220919173037556.png)

