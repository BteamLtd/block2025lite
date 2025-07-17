### @codeStart players set status_div bteamltdmakecode 0
### @codeStop players set status_div bteamltdmakecode 1

### @hideIteration true
### @explicitHints true

# F5R3

## Step 4
房间3: 加减乘除
你需要使用变量，变量赋值，变量运算。然后分别提交计算的``结果``。

```ghost
    let 被除数 = 648
    let 除数 = 200
    let 商 = 0
    
    商 = 被除数 / 除数

    player.say(商)
    基岩科技第五层第三房间.subAnsOnF5R3_add(商)
```
```template
    let 被除数 = 648
    let 除数 = 200
    let 商 = 0
    
    商 = 被除数 / 除数

    player.say(商)
    基岩科技第五层第三房间.subAnsOnF5R3_add(商)
```

```package
blocklite=github:BteamLtd/block2025lite-ts#f5r3_2
```
