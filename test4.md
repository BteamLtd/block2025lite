### @codeStart players set status bteamltdmakecode 0
### @codeStop players set status bteamltdmakecode 1

### @hideIteration true
### @explicitHints true

# F1R1

## ![](https://blocklite.20240806.xyz/temp/tw/1/f1r1) Step 1 

![](https://blocklite.20240806.xyz/temp/tw/1/f1r2)请使用小机器人检查方块并且增加变量的数字，然后提交对应的变量到答案记录板。<img src="https://blocklite.20240806.xyz/temp/tw/1/f1r1" width="48" height="48">


```ghost
    function go4 () {
        bteam.waitSeconds(5)
        agent.collectAll()
        agent.move(FORWARD, 5)
        agent.move(UP, 1)
        agent.turn(LEFT_TURN)
        agent.move(FORWARD, 7)
        agent.dropAll(FORWARD)
    }
    go4()
```


```template
    agent.move(UP, 1)
```


```package
```
