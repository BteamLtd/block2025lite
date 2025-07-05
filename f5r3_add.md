### @codeStart players set status bteamltdmakecode 0
### @codeStop players set status bteamltdmakecode 1

### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# F5R2

## Step 1
房间3: 加减乘除
你需要使用变量，变量赋值，变量运算。然后分别提交他们的值，还有它们的总和。

```ghost
    let 第一季度射出箭数 = 648
    let 第二季度射出箭数 = 0
    let 第三季度射出箭数 = 0
    let 三个季度射出总箭数 = 0
    
    bteam.changeVariableBy(三个季度射出总箭数, 第一季度射出箭数)
    bteam.changeVariableBy(三个季度射出总箭数, 第二季度射出箭数)

    player.say(三个季度射出总箭数)
    基岩科技第五层第二房间.subAnsOnF5R1_arrow_1(第一季度射出箭数)
    基岩科技第五层第二房间.subAnsOnF5R1_arrow_2(第二季度射出箭数)
    基岩科技第五层第二房间.subAnsOnF5R1_arrow_3(第三季度射出箭数)
    基岩科技第五层第二房间.subAnsOnF5R1_arrow_sum(第三季度射出箭数)
```
```template
    let 第一季度射出箭数 = 648
    let 第二季度射出箭数 = 0
    let 第三季度射出箭数 = 0
    let 三个季度射出总箭数 = 0
    
    bteam.changeVariableBy(三个季度射出总箭数, 第一季度射出箭数)
    bteam.changeVariableBy(三个季度射出总箭数, 第二季度射出箭数)

    player.say(三个季度射出总箭数)
    基岩科技第五层第二房间.subAnsOnF5R1_arrow_1(第一季度射出箭数)
    基岩科技第五层第二房间.subAnsOnF5R1_arrow_2(第二季度射出箭数)
    基岩科技第五层第二房间.subAnsOnF5R1_arrow_3(第三季度射出箭数)
    基岩科技第五层第二房间.subAnsOnF5R1_arrow_sum(第三季度射出箭数)
```

```package
blocklite=github:BteamLtd/block2025lite-ts#master
```
