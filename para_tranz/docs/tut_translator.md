# 非常简单的翻译指南

## 注册并加入项目
在加入项目前，首先需要在平台创建账号。ParaTranz 平台需要使用 Github 进行登录。
- 打开 [Github](https://github.com/) ，登录您的帐号。
    - 没有账号的话，点击右上角【Signup】来注册一个。
    - 注册好后在浏览器里登录账号。
- 打开 [ParaTranz](https://paratranz.cn/) ，点击右上角的【登陆】，
  根据提示使用Github账号登录网站。
- 打开 [远行星号中文化项目申请页](https://paratranz.cn/projects/3489/applications) ，
  点击【提交申请】来申请加入。请在申请理由中**写下您加入汉化群的QQ号**，别的随便填。
- 找jn_xyp或欧瑞捷门叫他同意您的申请。

## 进行翻译
好啦，现在你就可以立刻开始翻译啦！

ParaTranz 上的翻译以**词条**为单位，每一个词条
都对应游戏csv中某个格子里的文本内容。
你可以随便挑自己喜欢的词条进行翻译，一次翻几个都可以，非常地灵活。

- 要开始翻译，首先打开项目的 [文件列表](https://paratranz.cn/projects/3489/files) ，
  这个页面会显示各个csv文件的翻译进度。
- 选择一个尚未翻译完成的文件，就可以打开翻译界面。该界面默认显示所有**未翻译**的词条
- 在译文文本框内输入译文，点击【保存】即可！

## 进行校对
根据目前的设置，每个翻译完成的词条需要经过一次校对才算翻译完成。

要参与校对工作，需要有校对者权限。请找欧瑞捷门进行申请。

- 要开始校对，在翻译界面，点击左上方搜索框右侧的漏斗状【筛选】按钮，选择筛选【已翻译】
  词条。
- 打开词条后，如果内容无误，点击译文文本框右下角的【审核】即可完成校对。

## 其它（不用看也能翻译）
### 全局搜索
- 平台提供了方便的全局搜索功能，可以搜索全部原文，译文或词条键值
- 在翻译界面按`Ctrl-F`快速进行搜索

### 词条和游戏文件的对应关系
- 平台上的每一个文件与游戏中的csv一一对应。
  - 例如`data/campaign/rules.json`对应本地的`data/campaign/rules.csv`
- 每一个词条则对应csv中需要翻译的**某一格**，词条下方的`键值`中指示了这种对应关系：
  - ![][string-kv]
  - 格式为`文件名`#`行id`$`列名`
  - 例如`industries`#`heavybatteries`$`name`意味着
    - 词条来自于`industries.csv`
    - 词条所在行的id是`heavybatteries`
    - 词条的内容来自于`name`这一列
- 因此，如果需要查询来自同一行的其它词条，可以在左上方搜索栏中输入键值的前两部分
  - 在本例中，可以搜索`industries`#`heavybatteries`
  - ![][kv-search]


[string-kv]:string-kv.png
[kv-search]:kv-search.png