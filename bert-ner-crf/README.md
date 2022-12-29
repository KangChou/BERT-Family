
# 实体识别


# 标注工具1:SUTDAnnotator

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

运行YEDDA.py之后，导入文本数据，只需点击opent文件test_ner.txt。
![image](https://user-images.githubusercontent.com/36963108/209913544-9fcc43f6-6c2e-4c3b-888e-35b66f9b14c5.png)

然后鼠标选择右侧窗口内，选取文本所需标注的实体，最后按照右侧指定的实体类型按相应的字母即可：
![image](https://user-images.githubusercontent.com/36963108/209912909-95fdf3dd-d009-471e-bddd-db0281d08cc7.png)

完成标注之后，点击export导出,生成的路径你导入的数据路径

![image](https://user-images.githubusercontent.com/36963108/209913212-fe045cae-7650-4e23-83cd-712d2918f8e5.png)


生成数据如下：


![image](https://user-images.githubusercontent.com/36963108/209913486-a0bf96cb-2468-4099-8967-97714389ef5e.png)


![image](https://user-images.githubusercontent.com/36963108/209913400-eb065ae0-3d0d-45b9-8d97-3982212ba5e8.png)


![image](https://user-images.githubusercontent.com/36963108/209913436-bbb6fdf9-1385-49e7-b132-90dfd4d07c41.png)


# 标注工具2:SUTDAnnotator

项目地址：https://github.com/heartexlabs/label-studio

教程参考：[https://huaweicloud.csdn.net/63803da2dacf62](https://huaweicloud.csdn.net/63803da2dacf622b8df86bb5.html?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Eactivity-1-123298406-blog-121129928.pc_relevant_vip_default&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Eactivity-1-123298406-blog-121129928.pc_relevant_vip_default&utm_relevant_index=1)

ubuntu20安装：
```
python3.8的环境
pip install -U label-studio -i https://pypi.doubanio.com/simple/
pip uninstall attr
pip install attrs
```
终端启动命令：label-studio  这里我使用的是vs code连接docker容器
![image](https://user-images.githubusercontent.com/36963108/209916873-4b154a68-4f94-438e-9250-d01511af29bd.png)

之后在终端输入命令自动打开浏览器 ,如果没有自动打开就在浏览器输入：http://localhost:8082/user/signup

![image](https://user-images.githubusercontent.com/36963108/209917022-9643a36a-0b35-4a35-bd09-255c0ed62b63.png)
注册账号成功之后，打开
![image](https://user-images.githubusercontent.com/36963108/209917109-3ea01d66-f6c1-4c5b-a96a-3fcd62fae306.png)

第一次登陆进来，这个页面应该是空白的，这些都是我自己建的项目。下面，我们开始创建自己的项目：
![image](https://user-images.githubusercontent.com/36963108/209917338-da283ec6-3990-4e20-a2cf-cea6bd2b5452.png)

导入数据选择：选择的是List of tasks


