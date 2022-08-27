# Yun UI Library
This is the documentation for Yun's UI Library.

## Adding the UI Library
```lua
loadstring(game:HttpGet('https://raw.githubusercontent.com/1uaxx/yunv2/main/librarysource.lua'))()
```

## Adding a Window
```lua
local Library = initLibrary()
local Window = library:Load({name = "Yun UI Example", sizeX = 425, sizeY = 512, color = Color3.fromRGB(255, 255, 255)})
```

## Adding a Tab
```lua
local Tab = Window:Tab("Tab")
```

## Adding a Section
```lua
local Section = Tab:Section{name = "Section", column = 1}
```

not complete..
