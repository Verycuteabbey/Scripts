# 说明

[English](https://github.com/Verycuteabbey/Scripts/blob/main/README.md)

### 提醒

**所有脚本为 Fallen_VCA#6890 所编写 | 版权为 © 2022 The Mystery Team 所有**

### 我该如何使用？

首先，你需要到脚本内容去查看，那里有使用说明（在不知道如何用的情况下）

然后使用 `loadstring()` 来读取脚本，就像下面这样:
```lua
loadstring(game:HttpGet("https://raw.example.com/114514"))();
```
如果你发现什么动静都没有，那你可以像下面这样来捕获错误:
```lua
local Lua = loadstring(game:HttpGet("https://raw.example.com/114514"));
local IsSuccessed, ReturnInfo = pcall(Lua);

if (Lua) then
    print("Script injected!");
else
    warn(ReturnInfo);
end;
```
执行后如果发现与 HTTP 无关的报错，欢迎你截图发送到我的 QQ 或者是邮箱:

QQ: 487313236

邮箱：

1. mengmengyujie@hotmail.com

2. 487313236@qq.com (不推荐)
