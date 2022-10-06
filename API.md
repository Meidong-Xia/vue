### API

#### 查找页面元素

![](F:\vue\assets\image-20220917122330955.png)

##### 使用`querySelector`

![image-20220917105657575](F:\vue\assets\image-20220917105657575.png)

##### 使用`querySelectorAll`

![image-20220917121619512](F:\vue\assets\image-20220917121619512.png)

##### 配合使用`querySelector`和`querySelectorAll`

![image-20220917122140506](F:\vue\assets\image-20220917122140506.png)

##### 使用`getElementById`

![image-20220917122341012](F:\vue\assets\image-20220917122341012.png)

也可以使用`querySelector`，只不过要使用`#`号而不是`.`号

![image-20220917122433655](F:\vue\assets\image-20220917122433655.png)

#### 修改页面元素的内容

![image-20220917122537785](F:\vue\assets\image-20220917122537785.png)

##### `innerHtml`

![image-20220917131546291](F:\vue\assets\image-20220917131546291.png)

![image-20220917131926268](F:\vue\assets\image-20220917131926268.png)

##### `textContent`

![image-20220917131945710](F:\vue\assets\image-20220917131945710.png)

`innerHtml`可以识别标签，`textContent`不可以

##### 利用模板

![image-20220917163344563](F:\vue\assets\image-20220917163344563.png)

![image-20220917165507182](F:\vue\assets\image-20220917165507182.png)

##### Fetch

![image-20220917200019245](F:\vue\assets\image-20220917200019245.png)

###### 同步接收结果

![image-20220917200034443](F:\vue\assets\image-20220917200034443.png)

![image-20220917203321525](F:\vue\assets\image-20220917203321525.png)

###### 异步接收结果

![image-20220917200102055](F:\vue\assets\image-20220917200102055.png)

![image-20220917203256828](F:\vue\assets\image-20220917203256828.png)

##### 跨域问题

![image-20220917210045496](F:\vue\assets\image-20220917210045496.png)

不同源就会报错，解决思路：

######  加请求头

![image-20220917205616005](F:\vue\assets\image-20220917205616005.png)

![image-20220917205755028](F:\vue\assets\image-20220917205755028.png)

###### 代理

![image-20220917211129160](F:\vue\assets\image-20220917211129160.png)

##### 导入导出

###### 导出

![image-20220917212459109](F:\vue\assets\image-20220917212459109.png)

![image-20220917212721803](F:\vue\assets\image-20220917212721803.png)

![image-20220917212819175](F:\vue\assets\image-20220917212819175.png)

###### 导入

![image-20220917212605637](F:\vue\assets\image-20220917212605637.png)

![image-20220917212955391](F:\vue\assets\image-20220917212955391.png)

![image-20220917213137001](F:\vue\assets\image-20220917213137001.png)

