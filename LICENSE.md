local playerGui = player:WaitForChild("PlayerGui")
local main = playerGui:WaitForChild("Main")
local ultimate = main:WaitForChild("Ultimate")
local bar = ultimate:WaitForChild("Bar")
local fill = bar:WaitForChild("Fill")

-- Ult bar color
fill.BackgroundColor3 = Color3.fromRGB(0, 0, 0)

-- Moves
local moveset = main:WaitForChild("Moveset")
moveset["Dismantle""].ItemName.Text = "Placeholder"
moveset["aura farm"].ItemName.Text = "Placeholder"
moveset["i have no idea"].ItemName.Text = "Placeholder"
moveset["super damage"].ItemName.Text = "Placeholder"

-- Ultimate rename
ultimate.Title.Text = "LOL""
