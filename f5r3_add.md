### @codeStart players set status_add bteamltdmakecode 0
### @codeStop players set status_add bteamltdmakecode 1

### @hideIteration true
### @explicitHints true

# F5R2

## Step 1
房间3: 加减乘除
你需要使用变量，变量赋值，变量运算。然后分别提交计算的``结果``。

```ghost
    let 加数1 = 648
    let 加数2 = 200
    let 结果 = 0
    
    结果 = bteam_math.add(加数1,加数2)

    player.say(结果)
    基岩科技第五层第三房间.subAnsOnF5R3_add(结果)
```
```template

    let 加数1 = 648
    let 加数2 = 200
    let 结果 = 0
    
    结果 = bteam_math.add(加数1,加数2)

    player.say(结果)
    基岩科技第五层第三房间.subAnsOnF5R3_add(结果)
```

```package
blocklite=github:BteamLtd/block2025lite-ts#f5r3_2
```
