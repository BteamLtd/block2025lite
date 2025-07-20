### @codeStart players set status_sub bteamltdmakecode 0
### @codeStop players set status_sub bteamltdmakecode 1

### @hideIteration true
### @explicitHints true

# F5R2

## Step 2
房间2: 加减乘除
你需要使用变量，变量赋值，变量运算。然后分别提交计算的``结果``。

```ghost
    let 被减数 = 648
    let 减数 = 200
    let 差 = 0
    
    
    差 = 被减数 - 减数

    player.say(差)
    基岩科技第五层第三房间.subAnsOnF5R2_sub(差)
```
```template
    let 被减数 = 648
    let 减数 = 200
    let 差 = 0
    
    
    差 = 被减数 - 减数

    player.say(差)
    基岩科技第五层第三房间.subAnsOnF5R2_sub(差)
```

```package
blocklite=github:BteamLtd/block2025lite-ts#master
```
