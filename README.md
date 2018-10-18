# 说明

这是一个demo。对接公司SDK。

Cocos2dx 3.6.5版本。地址：<http://www.cocos2d-lua.org/download/index.md>

配置：cd Quick-Cocos2dx-Community文件夹中，bash setup_mac.sh 

清理缓存：rm ~/.quick_player.lua 

创建项目：Quick-Cocos2dx-Community/quick/player/player3.app 

其中解决的问题：

```
//这句在APP中会报错
system(command.c_str());
//使用popen方法
popen(command.c_str(), "r");
```

XSocks文件夹是SDK，当然demo里没有喽~~~
