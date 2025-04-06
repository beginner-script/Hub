local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "일게이 허브(미완성)",
   Icon = 0,
   LoadingTitle = "로딩중...",
   LoadingSubtitle = "튜버스 게이",
   Theme = "Default",

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false,

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil,
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = false,
      Invite = "noinvitelink",
      RememberJoins = true
   },

   KeySystem = true,
   KeySettings = {
      Title = "일게이 허브 키 시스템",
      Subtitle = "키를 입력하세요",
      Note = "키: 킬러한테 물어봐",
      FileName = "BigHubKey",
      SaveKey = false,
      GrabKeyFromSite = false,
      Key = {"튜버스 게이"}
   }
})

-- 어드민 탭
local adminTab = Window:CreateTab("어드민", nil)
adminTab:CreateSection("")

adminTab:CreateButton({
   Name = "name less",
   Callback = function()
      loadstring(game:HttpGet('https://raw.githubusercontent.com/FilteringEnabled/NamelessAdmin/main/Source'))()
   end,
})

adminTab:CreateButton({
   Name = "infinity yield",
   Callback = function()
      loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
   end,
})

-- 모션핵 탭
local motionTab = Window:CreateTab("모션핵", nil)
motionTab:CreateSection("")

motionTab:CreateButton({
   Name = "마히토(사이타마)",
   Callback = function()
      loadstring(game:HttpGet('https://raw.githubusercontent.com/Kenjihin69/Kenjihin69/refs/heads/main/Mahitotsbupdate'))()
   end,
})

motionTab:CreateButton({
   Name = "스쿠나(아토믹)",
   Callback = function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/zyrask/Nexus-Base/main/atomic-blademaster%20to%20sukuna"))()
   end,
})

motionTab:CreateButton({
   Name = "소닉(가로우)",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/7V1mUBtQ"))()
   end,
})

motionTab:CreateButton({
   Name = "자동콤보(좀 구림)",
   Callback = function()
      loadstring(game:HttpGet("https://pastefy.app/XNKwIjUX/raw"))()
   end,
})

motionTab:CreateButton({
   Name = "고조(사이타마)",
   Callback = function()
      loadstring(game:HttpGet("https://raw.githubusercontent.com/skibiditoiletfan2007/BaldyToSorcerer/main/Latest.lua"))()
   end,
})

motionTab:CreateButton({
   Name = "보로스(사이타마)",
   Callback = function()
      loadstring(game:HttpGet("https://paste.ee/r/XPIH5"))()
   end,
})

-- 백도어 탭
local backdoorTab = Window:CreateTab("백도어", nil)
backdoorTab:CreateSection("")

backdoorTab:CreateButton({
   Name = "soul server side",
   Callback = function()
      local url = "https://raw.githubusercontent.com/Obunga-666/S-O-U-L/refs/heads/main/E-x-e-c-u-t-o-r"
      local scriptContent = game:HttpGet(url)
      loadstring(scriptContent)()
   end,
})
