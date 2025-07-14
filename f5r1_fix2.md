### @codeStart players set status bteamltdmakecode 0
### @codeStop players set status bteamltdmakecode 1

### @hideIteration true
### @explicitHints true

# F5R1

## Step 1
请使用小机器人检查方块并且增加变量的数字，然后提交对应的变量到答案记录板

```ghost
    let 空缺方块的计数 = 0

    for (let index = 0; index < 5; index++) {
        基岩科技第五层第一房间.newIf(基岩科技第五层第一房间.isAirDOWN(), function () {
            bteam.changeVariableBy(空缺方块的计数, 1)
        })
        agent.move(FORWARD, 1)
    }
    player.say(空缺方块的计数)
    基岩科技第五层第一房间.subAnsOnF5R1_air_wool(空缺方块的计数)
```
```template
    let 空缺方块的计数 = 0

    for (let index = 0; index < 5; index++) {
        基岩科技第五层第一房间.newIf(基岩科技第五层第一房间.isAirDOWN(), function () {
            基岩科技第五层第一房间.changeVariableBy(空缺方块的计数, 1)
        })
        agent.move(FORWARD, 1)
    }
    player.say(空缺方块的计数)
    基岩科技第五层第一房间.subAnsOnF5R1_air_wool(空缺方块的计数)
```

```package
blocklite=github:BteamLtd/block2025lite-ts#f5r1fix
```
