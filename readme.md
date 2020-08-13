# NCLM 和 HNR 群组网络 音效包工程

**音效包中的音效可通过命令方块和`/playsound`命令用于服务器任何地方。**

**目前的应用：**
+ NCLM 轨道交通
  + 车站广播

## 上传需要的音效

[点击这里](https://github.com/Leo204-LKY/NAHGN-Sound-Pack/issues/new "创建一个新Issue") 或前往 **Issues** 标签创建新 Issue ，上传声音文件（格式要求`.ogg`）并附上以下内容：

``` json
"你的ID.声音类别.声音名":{
    "subtitle": "字幕，用于开启显示字幕功能后的文字提示",
    "sounds":[
        {
            "name":"你的ID/声音类别/声音名"
        }
    ]
}
```

注：
+ `第一行引号`和`name`两处的声音类别和声音名可以不同，声音类别可以省略;
+ `第一行引号`不能使用除`.`以外的任何符号

例：
``` json
"leo204lky.soundType.soundName":{
    "subtitle": "一段声音",
    "sounds":[
        {
            "name":"Leo204_LKY/soundtype/soundname"
        }
    ]
}
```
 
#### 你的声音文件将在下个版本可用。
#### 我会更新并在你的 **Issue** 下留言，随后关闭 **Issue**。
`/playsound`命令使用方式：
`/playsound <声音> <来源> <玩家> [x] [y] [z] [音量] [音调] [最小音量]`
其中：
+ `<声音>`是附文首行引号内的内容（即模板中的`你的ID.声音类别.声音名`，“例”中的`leo204lky.soundType.soundName`），安装资源包后可使用`Tab`自动补全；
  + 可能会与提交的不同。_（如无说明，即为无变化）_
+ 方括号为可选内容

例如，上文“例”中的声音可使用这个命令播放：`/playsound minecraft:leo204lky.soundType.soundName @a`

详见 Minecraft Wiki [命令/playsound](https://minecraft-zh.gamepedia.com/%E5%91%BD%E4%BB%A4/playsound "跳转到 Minecraft Wiki 上的相关内容")
