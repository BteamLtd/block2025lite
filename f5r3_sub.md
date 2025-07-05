### @codeStart players set status_sub bteamltdmakecode 0
### @codeStop players set status_sub bteamltdmakecode 1

### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# F5R3

## Step 2
房间3: 加减乘除
你需要使用变量，变量赋值，变量运算。然后分别提交计算的``结果``。

```ghost
    let 被减数 = 648
    let 减数 = 200
    let 差 = 0
    
    
    差 = bteam_math.sub(加数1,加数2)

    player.say(差)
    基岩科技第五层第三房间.subAnsOnF5R3_add(差)
```
```template
    let 被减数 = 648
    let 减数 = 200
    let 差 = 0
    
    
    差 = bteam_math.sub(加数1,加数2)

    player.say(差)
    基岩科技第五层第三房间.subAnsOnF5R3_add(差)
```

```package
blocklite=github:BteamLtd/block2025lite-ts#f5r3_2
```
