local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "일게이 허브(미완성)",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "로딩중...",
   LoadingSubtitle = "레노 게이",
   Theme = "Default", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"Hello"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local mainTab = Window:CreateTab("어드민", nil) -- title, Image
local mainSection = mainTab:CreateSection("")

local Button = mainTab:CreateButton({
   Name = "name less",
   Callback = function()
     loadstring(game:HttpGet('https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source'))()
   end,
})

local Button = mainTab:CreateButton({
   Name = "infinity yield",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
  end,
})


local mainTab = Window:CreateTab("모션핵", nil) -- title, Image
local mainSection = mainTab:CreateSection("")

local Button = mainTab:CreateButton({
   Name = "마히토(사이타마)",
   Callback = function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/Kenjihin69/Kenjihin69/refs/heads/main/Mahitotsbupdate'))()
  end,
})

local Button = mainTab:CreateButton({
   Name = "스쿠나(아토믹)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/zyrask/Nexus-Base/main/atomic-blademaster%20to%20sukuna"))()
  end,
})

local Button = mainTab:CreateButton({
   Name = "소닉(가로우)",
   Callback = function()
loadstring(game:HttpGet("https://pastebin.com/raw/7V1mUBtQ"))()
  end,
})

local Button = mainTab:CreateButton({
   Name = "자동콤보(좀 구림)",
   Callback = function()
loadstring(game:HttpGet("https://pastefy.app/XNKwIjUX/raw"))()
  end,
})

local Button = mainTab:CreateButton({
   Name = "고조(사이타마)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/skibiditoiletfan2007/BaldyToSorcerer/main/Latest.lua"))()
  end,
})

local Button = mainTab:CreateButton({
   Name = "보로스(사이타마)",
   Callback = function()
loadstring(game:HttpGet"https://paste.ee/r/XPIH5")()
  end,
})

local Button = mainTab:CreateButton({
   Name = "카이가 만든고죠(사이타마)",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/RuMinGay/gojo/deb59f6926f3ed6fb613ab2601e01f26528e5e90/gojo"))()
  end,
})

local mainTab = Window:CreateTab("백도어", nil) -- title, Image
local mainSection = mainTab:CreateSection("")

local Button = mainTab:CreateButton({
   Name = "soul server side",
   Callback = function()
local SOUL = "SOUL - ServerSide Executor"
local url = "https://raw.githubusercontent.com/Obunga-666/S-O-U-L/refs/heads/main/E-x-e-c-u-t-o-r"
local scriptContent = game:HttpGet(url)
local loadstring = loadstring(scriptContent)()
   end,
})


local mainTab = Window:CreateTab("다른 허브", nil) -- title, Image
local mainSection = mainTab:CreateSection("")

local Button = mainTab:CreateButton({
   Name = "노무허브",
   Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/RuMinGay/nomu-hub523/refs/heads/main/nomu%20hub523"))()
  end,
})
