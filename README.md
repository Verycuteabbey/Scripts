# Description

[简体中文](https://github.com/Verycuteabbey/Scripts/blob/main/README_CN.md)

### Warning

**All script compiled by Fallen_VCA#6890 | Copyright © 2022 The Mystery Team**

### How to use?

First, you need goto the script content and have a look, there are have comments for uses (If you don't know)

And, use `loadstring()` to load the script like this:
```lua
loadstring(game:HttpGet("https://raw.example.com/114514"))();
```
If nothing happens, you can use this to catch errors like this:
```lua
local Lua = loadstring(game:HttpGet("https://raw.example.com/114514"));
local IsSuccessed, ReturnInfo = pcall(Lua);

if (Lua) then
    print("Script injected!");
else
    warn(ReturnInfo);
end;
```
After it if caught any errors not about the HTTP, welcome you take a screenshot report to my email:

1. mengmengyujie@hotmail.com

2. 487313236@qq.com (Not recommended)
