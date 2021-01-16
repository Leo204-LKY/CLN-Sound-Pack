### This repository only supports Chinese. If you are not a **NCLM and HNR Group Network** member, it should not be what you need. 本项目仅支持中文。如果你不是 **NCLM 和 HNR 群组网络** 的成员，本项目不是你需要的。  
</br>

![头图](https://i.postimg.cc/dt91dzgg/Git-Hub.png)  
[![最新版本](https://img.shields.io/badge/最新版本-v._2103-green?style=for-the-badge)](https://github.com/Leo204-LKY/NAHGN-Sound-Pack/releases) [![GitHub issues](https://img.shields.io/github/issues/Leo204-LKY/NAHGN-Sound-Pack?style=for-the-badge)](https://github.com/Leo204-LKY/NAHGN-Sound-Pack/issues) [![GitHub stars](https://img.shields.io/github/stars/Leo204-LKY/NAHGN-Sound-Pack?style=for-the-badge)](https://github.com/Leo204-LKY/NAHGN-Sound-Pack/stargazers)  
本项目隶属于由 [NCLMREDTEA](https://github.com/nclmredtea "点击将重定向至NCLMREADTEA的GitHub主页。") 建立的 [NCLM and HNR Group Network（或 `NCLM 和 HNR 群组网络`，或`N.A.H.G.N.`）](https://github.com/nclmredtea/NAHGN "点击将跳转至 GitHub 上的 N.A.H.G.N. 项目主页。")。  
音效包中的音效可通过命令方块和`/playsound`命令用于服务器任何地方。  


## 0. 目录
### 点击可跳转至对应主题。  
0. [目录](#0-目录 "点击跳转。")  
1. [目前的应用](#1-目前的应用 "点击跳转。")  
2. [音效包下载与安装](#2-音效包下载与安装 "点击跳转。")  
3. [申请添加音效](#3-申请添加音效)  
4. [申请移除音效](#4-申请移除音效)
5. [在`/playsound`命令中使用](#5-在playsound命令中使用 "点击跳转。")  


## 1. 目前的应用  
+ NCLM 轨道交通  
  + 车站广播  
  + 列车广播  
+ 玩家个性化使用


## 2. 音效包下载与安装  
### 下载  
[点击这里](https://github.com/Leo204-LKY/NAHGN-Sound-Pack/releases "点击将重定向至 Release 页面。")或点击右侧（移动端在本页底部） `Release` 按钮前往 **Release** 页面获取最新版本。  
_点击最新版本发布说明下方的`Assets` 按钮，然后在展开的列表中点击`NAHGN+Sound+Pack_版本号.zip`下载文件_  
### 安装   
有多种方法可以安装音效包。  
与资源包（也被称为材质包）安装方式相同。  
详见 Minecraft Wiki [教程/加载资源包](https://minecraft-zh.gamepedia.com/%E6%95%99%E7%A8%8B/%E5%8A%A0%E8%BD%BD%E8%B5%84%E6%BA%90%E5%8C%85 "点击将重定向至 Minecraft Wiki 上的相关页面。")  


## 3. 申请添加音效  
### 上传前请仔细阅读  
[点击这里](https://github.com/Leo204-LKY/NAHGN-Sound-Pack/issues/new "点击将创建一个Issue。")或转到 **Issues** 标签，点击 **`New issue` 按钮**创建 Issue，复制以下内容，然后在`Leave a comment`输入框粘贴并补全。  
请注意，一条 Issue 仅能申请一个音频。如需上传多个音频，请分别提交 Issue 申请。  
```
类别：
时长：
随距离减弱:是/否
命名空间ID：
保存目录：
字幕文字：
文件链接：
```
### 内容说明  
#### 类别  
+ 指定播放声音所属的类别，对应于游戏选项中“音乐和声音”设置的分类。  
  + 该功能将为声音分类，方便玩家在游戏选项中控制不同类型声音的音量  
+ 必须为以下之一：`master`（主音量）、`music`（音乐）、`record`（唱片机/音符盒）、`weather`（天气）、`block`（方块）、`hostile`（地对生物）、`neutral`（友好生物）、`player`（玩家）、`ambient`（环境）或`voice`（声音/语音）。  
+ 经审核错误的声音类别将不予通过  
  + 如果你认为自己的分类正确，可在 Issue 下申诉  
+ 游戏中通过`/playsound`命令播放音频时亦需要将申请时提供的类别填入`<来源>`
  + 如管理员发现`/playsound`中的声音类别与申请时不同，将视情况进行处理  
#### 时长
+ 填入申请上传的音频的时长（单位：秒）
#### 命名空间ID
+ 这是 Minecraft Wiki 上对此类内容的非官方命名  
  + 详见 Minecraft Wiki [命名空间ID](https://minecraft-zh.gamepedia.com/%E5%91%BD%E5%90%8D%E7%A9%BA%E9%97%B4ID "点击将重定向至 Minecraft Wiki 上的相关页面。")  
+ 按此格式在冒号后补全：`userid.name`  
  + `userid`是你的 Minecraft 用户名  
  + `name`是自己对声音的描述（用于方便自己使用）  
+ 可在`userid`和`name`之间加入分类，用英文句点(`.`)分隔  
  + 可创建多个子分类，最多允许3个子分类，即整句句点（`.`）不能超过4个  
  + <details>
    <summary>展开举例</summary>
    <code>leo204lky.personal.sound</code>符合要求  </br>
    <code>leo204lky.personal.house.secondfloor.sound</code>符合要求，但不能再创建子分类  </br>
    <code>leo204.lky.personal.house.secondfloor.bedroom.sound</code>不符合要求，因为子分类数为4（句点数为5），超出3个的限制  </br>
    </details>  
+ 仅允许使用句点(`.`)和**英文**  
  + 如果你的 Minecraft 用户名包含下划线或任何其他符号，请将这些符号省略  
+ 这将用于`/playsound`命令  
  + 向下滑动至[4. 在`/playsound`命令中使用](#4-在playsound命令中使用 "点击跳转。")  了解使用方法

#### 随距离减弱  
+ Minecraft Wiki中的描述是这样的：`基于距离的音效大小衰减率。`  
  + 在原版游戏中应用于传送门、信标和潮涌核心  
+ 如果你需要玩家离开范围音效停止，请在冒号后输入`是`；反之请输入`否`  
  + 推荐为`是`  

#### 保存目录  
+ 按此格式在冒号后补全：`userid/filename`  
  + 与命令定义中的要求类似，但限制较少  
  + `userid`是你的 Minecraft 用户名  
    + 不能省略下划线  
  + `filename`是声音文件的文件名  
    + 不需要加后缀`.ogg`  
    + 可与`命令定义`使用不同的命名  
+ 可在`userid`和`name`之间加入分类，用斜杠（`/`）分隔  
  + 可创建多个子分类，最多允许3个子分类，即整句斜杠（`/`）不能超过4个  
  + 与[命令定义](#命令定义)中的例子类似，不再举例  
+ 可使用除`\`、`:`、`*`、`?`、`"`、`<`、`>`、`|`、` `（空格）以外的任何符号  
  + 但仍不建议使用
  + 空格（` `）请以下划线（`_`）代替
+ 这将用于确定`.ogg`文件的存放在音效包`.zip`文件中的位置  

#### 字幕文字  
+ `字幕功能` 指在游戏内 `选项…`->`辅助功能设置…`->`显示字幕` 功能为`开`后，游戏内的声音通过文字描述显示游戏窗口在右下角这一功能  
  + <details>
    <summary>详细了解</summary>
    一个例子：</br>
    <img src="https://gamepedia.cursecdn.com/minecraft_zh_gamepedia/a/a8/Subtitles_Simplified.png" title="图片来自 Minecraft Wiki。" alt="游戏内显示的字幕。"></br>
    详见 Minecraft Wiki <a href="https://minecraft-zh.gamepedia.com/%E5%AD%97%E5%B9%95" title="点击将重定向至 Minecraft Wiki 上的相关页面。">字幕</a>
    </details>  
+ 请用中文尽量简短表述，不超过10个字，做到[信达雅](https://baike.baidu.com/item/%E4%BF%A1%E8%BE%BE%E9%9B%85 "点击将跳转至“信”“达”“雅”的百度百科词条。这三个字用在这里其实并不严谨。")  
+ 方便有需要的玩家使用  

#### 资源链接  
+ **将音频文件压缩为`.zip`文件上传至附件**  
  + 可以通过拖放、复制粘贴进输入区，或点击输入区下方的`Attach files by dragging & dropping, selecting or pasting them.`上传文件
  + 上传完成后，会在输入框插入链接，将链接保留在最后即可  
+ _(这是最开始提供的方法。）_  
  由于 GitHub 不支持上传音频文件，你需要将其上传至资源分享网站，然后提供下载链接  
  + 推荐：[百度网盘](https://pan.baidu.com "点击将重定向至百度网盘。")、[奶牛快传](https://cowtransfer.com "点击将重定向至奶牛快传。")  
  + 请注意，除[百度网盘](https://pan.baidu.com "点击将重定向至百度网盘。")、[奶牛快传](https://cowtransfer.com/ "点击将重定向至奶牛快传。")、 [Apple iCloud](https://www.icloud.com/ "点击将重定向至 Apple iCloud。") 和 [Microsoft OneDrive](https://onedrive.live.com/ "点击将重定向至 Microsoft OneDrive。") 外，我不会在任何需要登录的网站下载文件  
+ 文件大小不能大于 512 KB / 30秒  
  + 你可以在[这里](https://www.compresss.com/cn/compress-ogg.html "点击将重定向至Compress.com")压缩`.ogg`文件的大小  

### 例子  
[点击查看](https://github.com/Leo204-LKY/NAHGN-Sound-Pack/issues/8 "点击将重定向至编号为8的例子 Issue。")样例 Issue。  

## 4. 申请移除音效  
[点击这里](https://github.com/Leo204-LKY/NAHGN-Sound-Pack/issues/new "点击将创建一个Issue。")或转到 **Issues** 标签，点击 **`New issue` 按钮**创建 Issue，复制以下内容，然后在`Leave a comment`输入框粘贴并补全。  
请注意，一条 Issue 仅能申请一个音频。如需移除多个音频，请分别提交 Issue 申请。  
```
命名空间ID：
保存目录：
移除原因：
添加申请的Issue编号：
```
### 内容说明
#### 命名空间ID
+ 需要移除的音效对应的命令定义  
+ 需要与添加申请 Issue 中`命令定义`填入的内容一致  
+ 如果忘记了这是什么，请前往添加申请 Issue 查看  
#### 保存目录置  
+ 需要移除的音效对应`.ogg`文件的保存位置  
+ 需要与添加申请 Issue 中`命令定义`填入的内容一致  
+ 如果忘记了这是什么，请前往添加申请 Issue 查看  
#### 移除原因
+ 提供移除音效的理由  
  + 例：不再需要此音效  
+ 不合理的理由将导致申请被拒绝  
#### 添加申请的Issue编号  
+ 以`#`开头  
+ 需要移除的音效对应的音效添加申请 Issue 的编号  
  + 找到音效添加申请后，有以下几种方式查找编号  
    + Issue 标题后方淡灰色、`#`开头的数字  
    + 浏览器地址栏最后的数字  
+ 如果正确，发布 Issue 后文字会变为超链接(蓝色文字、可点击)，点击会跳转至添加申请 Issue  

### 例子  
[点击查看](https://github.com/Leo204-LKY/NAHGN-Sound-Pack/issues/10 "点击将重定向至编号为10的例子 Issue。")样例 Issue。  

## 5. 在`/playsound`命令中使用  
### 详细了解`/playsound`命令： Minecraft Wiki [命令/playsound](https://minecraft-zh.gamepedia.com/%E5%91%BD%E4%BB%A4/playsound "点击将重定向至 Minecraft Wiki 上的相关页面。")  
`/playsound <声音> <来源> <玩家> [x] [y] [z] [音量] [音调] [最小音量]`  
1. `<声音>`应在添加`player.`前缀和时长后缀（`.xs`，其中`x`为时长[单位：秒]，`s`为固定内容）后，填入申请 Issue `命令定义`填入的内容  
2. `<来源>`应填入申请 Issue `声音类别` 填入的内容  
+ 以[样例 Issue](https://github.com/Leo204-LKY/NAHGN-Sound-Pack/issues/1 "点击将重定向至编号为1的例子 Issue。")为例，`<声音>`应填入`player.leo204lky.personal.sound.15s`  
  + 补全其他部分，例：`/playsound player.leo204lky.personal.sound.15s master Leo204_LKY`  
+ 中括号（`[ ]`）为可选内容  
+ 关于其它部分的使用方法，请查看 Minecraft Wiki [命令/playsound](https://minecraft-zh.gamepedia.com/%E5%91%BD%E4%BB%A4/playsound "点击将重定向至 Minecraft Wiki 上的相关页面。")    