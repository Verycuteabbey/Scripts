# Description

[简体中文](https://github.com/Verycuteabbey/Scripts/blob/main/README_CN.md)

**Warning:**

**All script compiled by Fallen_VCA#6890 | Copyright © 2022 The Mystery Team**

Here you can use `loadstring()` to load the script like this:
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
