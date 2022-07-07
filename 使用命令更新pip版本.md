# 使用命令更新pip版本

## 命令行定位到 Scripts 目录

进入命令行（Windows系统使用cmd命令行为例），使用命令定位到 Python 安装目录。如Python 安装路径是 ‪D:\Python\Python310，则先定位到 D 盘，在命令行中输入以下命令：
```
d:
```
按下 Enter 键，完成后再输入如下命令进入 Python 的 Scripts 目录：
```
cd ‪Python/Python310/Scripts
```
按下 Enter 键完成。

## 更新 pip 版本

定位到 Scripts 目录后，直接输入以下命令更新 pip 版本：
```
python -m pip install --upgrade pip
```
按下 Enter 键，等待安装完成即可。

## 查看 pip 版本

安装完成后，可以使用以下命令查看 pip 版本：
```
pip list
```