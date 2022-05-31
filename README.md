#成都中小学教师继续教育自动学习

1、需要调用ddddocr验证码识别库
2、需要安装火狐浏览器及下载对应版本的geckodriver到项目文件夹下

# 使用方法
## 安装依赖
 自动安装selenium和ddddocr
 
 pip install -r requirements.txt
## 安装火狐浏览器
下载对应火狐浏览器的webdriver即geckodriver，放到项目文件夹下
下载地址：https://github.com/mozilla/geckodriver

## 配置登录账号和密码
打开项目文件夹下jxjy.txt  第一行写入用户，第二行写入密码

## 开始学习
开始自动学习前需要先自己选择课程，并且填写完毕所有学习记录

python  auto_learn_jxjy_last.py

#已知bug
有一定概率出现学习失败，重新打开学习即可
