
# 实体识别


# 标注工具SUTDAnnotator

https://github.com/jiesutd/YEDDA/

配置：WINDOWS10 环境python>=3.7

```
python3.9
pip install tk  -i https://pypi.doubanio.com/simple/
```

配置文件：default.config  标注的实体类型字典  可以修改为你所需的类型
```
{"a": "Artifical", "c": "Fin-Concept", "b": "Event", "e": "Organization", "d": "Location", "g": "Sector", "f": "Person", "h": "Other"}
```

运行YEDDA.py之后，导入文本数据，只需点击open。
![image](https://user-images.githubusercontent.com/36963108/209913544-9fcc43f6-6c2e-4c3b-888e-35b66f9b14c5.png)

然后鼠标选择右侧窗口内，选取文本所需标注的实体，最后按照右侧指定的实体类型按相应的字母即可：
![image](https://user-images.githubusercontent.com/36963108/209912909-95fdf3dd-d009-471e-bddd-db0281d08cc7.png)

完成标注之后，点击export导出,生成的路径你导入的数据路径

![image](https://user-images.githubusercontent.com/36963108/209913212-fe045cae-7650-4e23-83cd-712d2918f8e5.png)


生成数据如下：




![image](https://user-images.githubusercontent.com/36963108/209913486-a0bf96cb-2468-4099-8967-97714389ef5e.png)



![image](https://user-images.githubusercontent.com/36963108/209913400-eb065ae0-3d0d-45b9-8d97-3982212ba5e8.png)


![image](https://user-images.githubusercontent.com/36963108/209913436-bbb6fdf9-1385-49e7-b132-90dfd4d07c41.png)
