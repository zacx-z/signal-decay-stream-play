## Downloads

### Twitch

 - [Windows](https://github.com/zacx-z/signal-decay-streamplay/releases/download/1.0/sd-twitch-win.exe)
 - [MacOS](https://github.com/zacx-z/signal-decay-streamplay/releases/download/1.0/sd-twitch-macos)
 - [Linux](https://github.com/zacx-z/signal-decay-streamplay/releases/download/1.0/sd-twitch-linux)

### Bilibili

 - [Windows](https://github.com/zacx-z/signal-decay-streamplay/releases/download/1.0/bplay-win.exe)
 - [MacOS](https://github.com/zacx-z/signal-decay-streamplay/releases/download/1.0/bplay-macos)
 - [Linux](https://github.com/zacx-z/signal-decay-streamplay/releases/download/1.0/bplay-linux)

## Instructions

### Twitch

Add `channel.txt` file in the same directory of the executable with the channel name (in lowercase) as its content. And run with Signal Decay with streaming-play option on.

在可执行文件同一目录下加入 `channel.txt` 文件，内容是频道名称（小写)。《拯救世界特别小队》开启直播游玩选项的同时运行。

### Bilibili

Add `roomid.txt` file in the same directory of the executable with the room id (number) as its content. And run with Signal Decay with streaming-play option on.

在可执行文件同一目录下加入 `roomid.txt` 文件，内容是房间号（数字）。《拯救世界特别小队》开启直播游玩选项的同时运行。

## How to Enable Stream-Play in Signal Decay

On _Steam_, right click _Signal Decay_, select _Properties..._, press _Set Launch Options_ button, and input `--stream-play`. (Currently only works on beta branch)

在 _Steam_ 上，右键《拯救世界特别小队》，选择“属性...”，按“设置启动选项”按钮，输入 `--stream-play`。（目前仅在beta分支上有效）

## How Stream-Play works

Once you set up stream-play, every door in _Signal Decay_ will has a text with a unique number on it. All the spectators on Twitch, etc. can put commands in chat (formatted like "d10", "d1") to control the states of doors to mess with the game. There's a 2 seconds cooldown for each command, and a command is randomly picked and executed when cooldown is over.

当你设置好直播游玩功能后，每一个《拯救世界特别小队》的门都会出现唯一数字标识。每一个直播平台的观看者都可以在聊天窗口中下达指令（格式比如d10, d1），控制门的状态，扰乱游戏。每个指令有两秒冷却，冷却结束在这期间的所有指令中会随机抽选一个执行。
