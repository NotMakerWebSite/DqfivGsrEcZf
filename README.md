## 中国象棋网页游戏

> [点我下载源码或在线试用](https://www.notmaker.com/detail/d3b62feb108c40ba94c0932d8d1002b6/ghbnew) 

> 支持定制、讲解、修改、远程调试

[查看视频](https://store.ptcc9.top/manual_upload/中国象棋.mp4)

### 一、相关技术
- 前端：`HTML` / `CSS` / `Javascript` 等。

### 二、相关软件（列出的软件其一均可运行）
- `IDEA`
- `Eclipse`
- `Visual Studio Code(VScode)`
- 等

本程序是一个基于Html/css/javascrip的网页端象棋APP，其中引入JQuery来简便开发。
在程序中，使用一个Map二维数组来表示棋盘，通过给棋子设置不同的横坐标与纵坐标来放置他们的位置。
在棋手准备移动棋子时，程序会根据中国象棋已有的规则，来判断对应棋子的可行进方向和步长。
例如“兵”棋，在己方地界时，只能向前移动，且每次只能移动一位。在敌方地界时，仅能向前和两边的地界移动，且每次只能移动一位。
当两棋子的位置重叠时，当前正在移动的棋子拥有优先权，占据棋盘对应位置，而原有的棋子被剔除。

![image.png](https://store.ptcc9.top/notmaker/user_upload/ba15bc64d0b24c178659372c9c4386bd/2024-02-26%2020:28:55_image.png)

![image.png](https://store.ptcc9.top/notmaker/user_upload/ba15bc64d0b24c178659372c9c4386bd/2024-02-26%2020:29:00_image.png)
