### pyinstaller 是一款可以打包.py为.exe 的实用工具


### 这里给大家介绍一些常用的功能
### 首先，安装pyinstaller插件：
————————————————————————————
## 1、快速体验
#### 在终端中输入
```
pip install pyinstaller
```

#### 然后切换到py文件所在的目录
#### 在终端中输入
```
pyinstaller -F name.py
```
![11](https://user-images.githubusercontent.com/79883276/132129521-12f7646f-4c51-4131-bfa5-a69e5e92fbf0.png)

在生成的dist文件夹中即可看到生成的exe文件
![2](https://user-images.githubusercontent.com/79883276/132129525-d087968e-0aa5-4396-949a-a121fb0814bf.png)

## 2、其他命令
### 如果想要更改生成的exe文件的图标也是可以的，
### 首先你需要找到一些.ico格式的图片（后期我会在这里更新）
### 然后将它复制到.py同目录文件夹下
### 在终端中输入

```
pyinstaller -F -i ico_name.ico name.py
```
#### ico_name是你的ico图片的名称
![33](https://user-images.githubusercontent.com/79883276/132129591-7f28ca36-668c-4a89-bd2c-b5d37340ac5b.png)


#### 如果你的爬虫程序没有交互功能，你不想看到运行后的黑框框，你可以在终端中输入
```
pyinstaller -F -W name.py
```
## 3、ico图标制作网站，可以看看这个：http://www.ico51.cn/
### ico图标免费下载网站：https://www.aigei.com/icon/class/

## 4、注意：
### 4.1如果是打包pygame这样的有素材包的py文件，需要将生成后的exe文件和原来的素材包文件放在同目录下才可以运行哦！
### 4.2在代码里面尽量不要用import，最好用from.....import....，因为如果是import的话，在打包的时候，会将整个包都打包到exe里面，会增大生成的exe文件的大小！

## 以上，
#### 喜欢的请给我点个star，谢谢咯~
