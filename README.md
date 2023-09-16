local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
    Name = "meow",
    LoadingTitle = "co owner liam owner marius",
    LoadingSubtitle = "by Marius and liamisthebest",
    ConfigurationSaving = {
       Enabled = true,
       FolderName = true, -- Create a custom folder for your hub/game
       FileName = "Big Hub"
    },
    Discord = {
       Enabled = true,
       Invite = "https://discord.gg/TyTAD78g", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
       RememberJoins = true -- Set this to false to make them join the discord every time they load it up
    },
    KeySystem = true, -- Set this to true to use our key system
    KeySettings = {
       Title = "i love kat",
       Subtitle = "i love kat",
       Note = "join discord",
       FileName = "i love kat", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
       SaveKey = false, -- The user's key will be saved, but if you change the key, they will be unable to use your script
       GrabKeyFromSite = true, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
       Key = {"https://pastebin.com/raw/d5inkVPB"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
    }
 })

 local katTab = Window:CreateTab("kat", 4483362458) -- Title, Image
 local katSection = katTab:CreateSection("kat")

 local Button = katTab:CreateButton({
   Name = "kat silent aim",
   Callback = function()
      loadstring(game:HttpGet('https://pastebin.com/raw/5pZwFLYB'))()
   end,
})

local button = katTab:CreateButton({
   Name = "Esp",
   Callback = function()
      loadstring(game:HttpGet('https://pastebin.com/raw/JY7yqAbx'))()
   end,
})

local Button = katTab:CreateButton({
   Name = "Tracers",
   Callback = function()
      loadstring(game:HttpGet('https://pastebin.com/raw/2pKnJADw'))()
   end,
})

local Button = katTab:CreateButton({
   Name = "Name over Players",
   Callback = function()
      loadstring(game:HttpGet('https://pastebin.com/raw/2vmJYxz7'))()
   end,
})

local CreditsTab = Window:CreateTab("Credits", 4483362458) -- Title, Image
local Section = CreditsTab:CreateSection("Credits")

local Input = CreditsTab:CreateInput({
   Name = "Owner",
   PlaceholderText = "Marius",
   RemoveTextAfterFocusLost = false,
   Callback = function(Text)
   -- The function that takes place when the input is changed
   -- The variable (Text) is a string for the value in the text box
   end,
})

local Input = CreditsTab:CreateInput({
   Name = "CO OWNER",
   PlaceholderText = "liamisthebest",
   RemoveTextAfterFocusLost = false,
   Callback = function(Text)
   -- The function that takes place when the input is changed
   -- The variable (Text) is a string for the value in the text box
   end,
})

 
