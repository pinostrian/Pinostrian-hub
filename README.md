# Pinostrian-hub
## Features
•Key System

•Loading Screen

And many more! 

# Getting Started
this one handles the codes for building and adding
```
loadstring(game:HttpGet(""))()
```
## For the main body

```lua
local Window = Pinostrian:CreateWindow({
    Name = "Pinostrian Hub",
    Loading = true,
    LoadingTitle = "Pinostrian Initializing...",
    KeySystem = false,

    FloatingIcon = {
        Enabled = true,
        Image = "rbxassetid://124558441880674",
        Size = 64,
        Position = UDim2.fromScale(0.03, 0.55)
    }
})
```

## Adding Tabs

```Lua
local Main = Window:CreateTab("Main")
```

## Adding Buttons, Toggle! 

## Buttons

```lua
Main:AddButton("Test Button", function()
    print("Works")
end)
```

## Toggle

```lua
Main:AddToggle("Test Toggle", false, function(v)
    print("Toggle:", v)
end)
```

# Credits

**@pinostrian**
