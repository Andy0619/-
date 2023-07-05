## 介绍

最近大家都在刷最新的密评题库，题量之多一锅炖不下 啊，太难了，但是在 PDF、Excel 或者 word 里面看太难受了，而且没办法检验自己是否记忆。于是乎想着弄个简单的答题工具，网上其实也有很多小工具，但是都不合心意，所以想着用 GPT 写一个，本来也没想它能写出来一个能用的，主要自己对 Web 开发知之甚少。

该系统主要功能就是从本地读取 excel 中的数据然后出题，然后作答，主要是增加了随机作答和顺序作答，还有题型选择，这样大家可以一边记忆一边测试。

当你记忆了100—200 道题，那么你可以选择 从 100 道开始，出 100 道题测试一下自己记忆效果。

可能有些人会先看判断题，把所有判断题看完，再看单选或者多选，那么你可以看完判断题，在答题系统只选择判断题来检测自己的学习成果。

系统功能很简单，主要是方便大家检验自己的记忆成果，巩固学习使用。

## 主要功能页面

### 选择题库、题型、出题方式页面

![](pic/Pasted%20image%2020230705114226.png)

### 答题页面
每个题昨晚都可以提交判断是否正确，如果错误大家可以在自己的小本本上标记对应的题目，最后我们只看这些错题即可。

![](pic/Pasted%20image%2020230705114415.png)

![](pic/Pasted%20image%2020230705114546.png)

## 使用方法

该项目是基于python+Flask 实现的，需要有 Python 环境，并安装对应的 python 模块

1、确保自己有 python 环境，py3

2、安装模块

```bash
pip install -r requirements.txt
```

3、运行系统

```bash
python app.py
```

4、随便一个浏览器输入 “http://127.0.0.1:5000/” 打开网页就可以使用了

5、如果需要改答案，可以在文件夹下的“测试题库.xlsx”里面修正，该 excel 文件的列不能删减，名称不能改动。

## 特别鸣谢

感谢笛卡尔盾的老师们帮大家整理所有题目答案，现在答案已更新到 2000 题，需要的可以关注“笛卡尔盾”公众号，第一时间获取答案。还要感谢群里各位老师不断的纠正错误，使得答案正确率更高。

## 最后

本系统代码已开源，大家可以自行下载，代码中包含了笛卡尔盾老师公开的前 2000 道题的答案，本答案并非官方标准答案，如有错漏请谅解。也可加入老师们的大军一起纠错。

开源地址：https://github.com/Andy0619/Commercial-Cryptography-Evaluation

也可以本公众号回复“密评题库”，通过网盘地址下载。