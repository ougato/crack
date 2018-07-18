# 破解应用程序文档

## **JetBrains PyCharm 2017.3 版本**

### 下载
> * 获取途径：[百度云盘](https://pan.baidu.com/s/1v23iWM8xvsoUTh7H-pbpXg)
> * 提取密码：**pguh**
> * 解压密码：**i1wiQ2LCZG1T0bELVR5bedbknG9avCRZ**

### 安装

> * 打开`Package`文件夹，安装`Pycharm.exe`文件到指定的目录

### 汉化

#### 1：使用配置文件汉化
> * 打开安装路径下的lib文件夹 `X:\Pycharm\lib`，找到`resources_en.jar`文件
> * 重命名`resources_en.jar`为`resources_cn.jar`
> * 使用解压工具打开（注意：是打开，不是解压），找到`resources_cn.jar`中的`messages`文件夹
> * 把安装包内的`Chinesize\message` 所有`*.properties`文件拖拽到正在使用解压工具打开的`resources_cn.jar`中
> * 替换已修改好的`resources_cn.jar`到`X:\Pycharm\lib`中
> * **（注：如果出现乱码情况，关闭IDE，删除`X:\Pycharm\lib`中的`resources_cn.jar`文件，使用方法2复制到`X:\Pycharm\lib`，再设置`File->Settings->Appearance&Behavior->Appearance->Override default fonts by->选择任意字体即可`）**

#### 2：使用生成文件汉化
> * 删除`X:\Pycharm\lib`中的`resources_en.jar`文件
> * 把`Chinesize\jar\resources_cn.jar`文件，复制到`X:\Pycharm\lib`
> * **（注：也有可能出现乱码情况，使用上面步骤）**

### 破解
> * 复制`Crack\JetbrainsCrack-2.6.10-release-enc.jar`到`X:\Pycharm\lib`中
> * 修改`X:\Pycharm\bin`目录下的这两个文件`pycharm.exe.vmoptions`和`pycharm64.exe.vmoptions`，在最后一行追加`-javaagent:X:\Pycharm\lib\JetbrainsCrack-2.6.10-release-enc.jar`
> * 重启IDE
> * 选择激活方式 `Activation code->输入文字（任意字符）->OK`
