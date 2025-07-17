### @codeStart players set status_mul bteamltdmakecode 0
### @codeStop players set status_mul bteamltdmakecode 1

### @hideIteration true
### @explicitHints true

# F5R3

## Step 3
房间3: 加减乘除
你需要使用变量，变量赋值，变量运算。然后分别提交计算的``结果``。

```ghost
    let 因数1 = 648
    let 因数2 = 200
    let 积 = 0
    
    积 = 因数1 * 因数2

    player.say(积)
    基岩科技第五层第三房间.subAnsOnF5R3_add(积)
```
```template
    let 因数1 = 648
    let 因数2 = 200
    let 积 = 0
    
    积 = 因数1 * 因数2

    player.say(积)
    基岩科技第五层第三房间.subAnsOnF5R3_add(积)
```

```package
blocklite=github:BteamLtd/block2025lite-ts#f5r3_2
```
