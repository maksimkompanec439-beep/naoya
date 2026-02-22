local playerGui = player:WaitForChild("PlayerGui")
local main = playerGui:WaitForChild("Main")
local ultimate = main:WaitForChild("Ultimate")
local bar = ultimate:WaitForChild("Bar")
local fill = bar:WaitForChild("Fill")

-- Ult bar color
fill.BackgroundColor3 = Color3.fromRGB(0, 0, 0)

-- Moves
local moveset = main:WaitForChild("Moveset")
moveset["Get out"].ItemName.Text = "Placeholder"
moveset["I GOT THIS GAME"].ItemName.Text = "Placeholder"
moveset["damage punches"].ItemName.Text = "Placeholder"
moveset["IMPACT"].ItemName.Text = "Placeholder"

-- Ultimate rename
ultimate.Title.Text = "FLASH"
