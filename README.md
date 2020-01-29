# 模拟快递分拣
Version: Build 0.2

### 简介
还记得几年前那个用机器人分拣快递的新闻吗，当时我正在学习C++基础，对自己模拟一个快递分拣十分感兴趣。但是由于技术有限(懒得做)一直拖到现在，用了一些时间终于做出来。  
本项目主要使用JavaScript编写控制程序，用HTML的Canvas显示。  
这个玩意目前十分简陋，我也只是个初二的学生，闲来无事以此为乐，代码写得很粗糙，见笑了。  
代码注释之后会不断完善。

### 使用
1.用浏览器(推荐GoogleChrome或Firefox)打开main.html，但是绝对不要使用InternetExplorer，本项目没有对IE做任何兼容。  
2.最好打开开发者工具中的JS控制台。  
  
没有任何可操作项，只能看。  
其中黑色小方块代表机器人。其中间白色字代表机器人编号；其右下角数字代表即将前往的地点，数字为白色代表投掷区编号，数字为蓝色代表基地编号。蓝色大方块代表基地(从左到右从上到下四个分别为1号、2号、3号、4号)。白色大方块代表投掷区，其中间黑色数字代表投掷区编号。JS控制台中会显示信息。  

### 贡献
如果你在使用过程中发现任何问题，可以 [提交 issue](https://github.com/Headog/-Simulation-express-sorting/issues/new) 或自行 fork 修改后提交 pull request。

如果你要提交 pull request，请确保你的代码风格和项目已有的代码保持一致，变量命名清晰，有适当的注释。

### TODO
主线任务:BFS()预判避让  
支线任务:让基地块编号显示  
支线任务:整理代码(考虑分文件)  
支线任务:在生成地图时跳过已选择的块减少去重时间  
支线任务:添加多图层canvas  
支线任务:显示基地编号  
支线任务:使BFS合理选择dir  
支线任务:详细说明plan  
支线任务:取消lib  
支线任务:不在BFS()中使用try...except...句型  
支线任务:将HOSTS的下标改为从1开始  

已知BUG:投掷区数字只有在两位时才能显示正常  
