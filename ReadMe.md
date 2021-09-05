## pyinstaller 是一款可以打包.py为.exe 的实用工具
### 这里给大家介绍一些常用的功能
### 首先，安装pyinstaller插件：

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
在生成的dist文件夹中即可看到生成的exe文件

## 2、其他命令
### 如果想要更改生成的exe文件的图标也是可以的，
### 首先你需要找到一些.ico格式的图片（后期我会在这里更新）
### 然后将它复制到.py同目录文件夹下
### 在终端中输入

```
pyinstaller -F -i ico_name.ico name.py
```
#### ico_name是你的ico图片的名称

#### 如果你的爬虫程序没有交互功能，你不想看到运行后的黑框框，你可以在终端中输入
```
pyinstaller -F -W name.py
```
## 以上，
### 喜欢的请给我点个star，谢谢咯~
