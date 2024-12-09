local ReplicatedStorage = game:GetService("ReplicatedStorage")
local CommF_ = ReplicatedStorage.Remotes["CommF_"]
local function checkInventoryAndExecute()
    local inventory = CommF_:InvokeServer("getInventory")
    for _, item in pairs(inventory) do
        if item.Name == "Zebra Cap" then
            spawn(function()
                loadstring(game:HttpGet("https://raw.githubusercontent.com/Manhtuan24112001/autogat/refs/heads/main/autogatan.md"))()
            end)
            return true  -- Thông báo là "Zebra Cap" đã được tìm thấy
        else
            spawn(function()
                loadstring(game:HttpGet("https://raw.githubusercontent.com/Manhtuan24112001/autogat/refs/heads/main/auto%20cy%20wazure"))()
            end)
        end
    end
    return false  -- Thông báo là "Zebra Cap" không được tìm thấy
end
