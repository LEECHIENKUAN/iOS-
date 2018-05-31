### 清除 已經下載的 Simulator ###
- 打開　Finder 切到 /Library/Developer/CoreSimulator/Profiles/Runtimes ，就會看到所有已下載的Simulator
```shell
  cd  /Library/Developer/CoreSimulator/Profiles/Runtimes
```
- 刪除不需要的Device

### 清除 已經不支援的 Simulator ###
xcrun simctl delete unavailable

### 可以查看目前的 Simulator 的指令
xcrun simctl --h 

### 列出目前所有的Simulator
xcrun simctl list 
