## Numpy 要点整理
### 1. ndarray
ndarray 是一个N维数组对象，期中所有元素必须是**相同类型**的  
看维度：`data.shape`  
看数据类型：`data.dytpe`

#### 1.1 创建
# 使用array将series转化为numpy数组
```python
# 使用array将series转化为numpy数组
[Input]  data1 = [0,1.5,2,3]
         arr1 = np.array(data1)
         arr1
[Output] array([0. , 1.5, 2. , 3. ])
```


# 设置array的数据类型
*通常会根据 series 元素类型自行调节，但也可以在*  np.array *中手动设置*


