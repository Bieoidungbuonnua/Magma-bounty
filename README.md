getgenv().Team = "Pirates"

getgenv().WeaponsSetting = {
    ["Melee"] = {
        ["Enable"] = true,
        ["Delay"] = 3, 
        ["SwitchNextWeaponIfCooldown"] = true,
        ["Skills"] = {
            ["Z"] = {
                ["Enable"] = true,
                ["NoPredict"] = false, -- For Dragon Tailon, Disable it 
                ["HoldTime"] = 0,
                ["TimeToNextSkill"] = 0,
            },
        [ "X"] = {
                ["Enable"] = true,
                ["HoldTime"] = 0,
                ["TimeToNextSkill"] = 0,
            },

            ["C"] = {
                ["Enable"] = true,
                ["HoldTime"] = 0,
                ["TimeToNextSkill"] = 0,
            },
        },
    },
    ["Blox Fruit"] = {
        ["Enable"] = true,
        ["Delay"] = 4,
        ["SwitchNextWeaponIfCooldown"] = true,
        ["Skills"] = {
            ["Z"] = {
                ["Enable"] = true,
                ["HoldTime"] = 2,
                ["TimeToNextSkill"] = 0,
            },
            ["X"] = {
                ["Enable"] = true,
                ["HoldTime"] = 0,
                ["TimeToNextSkill"] = 0,
            },

            ["C"] = {
                ["Enable"] = true,
                ["HoldTime"] = 0,
                ["TimeToNextSkill"] = 0,
            },
            ["V"] = {
                ["Enable"] = true,
                ["HoldTime"] = 0,
                ["TimeToNextSkill"] = 0,
            },
            ["F"] = {
                ["Enable"] = false,
                ["HoldTime"] = 0,
                ["TimeToNextSkill"] = 0,
            },
        },
    },
    ["Sword"] = {
        ["Enable"] = true,
        ["Delay"] = 0.5,
        ["Skills"] = {
            ["Z"] = {
                ["Enable"] = true,
                ["HoldTime"] = 0.1,
                ["TimeToNextSkill"] = 0,
            },
            ["X"] = {
                ["Enable"] = true,
                ["HoldTime"] = 0.2,
                ["TimeToNextSkill"] = 0,
            },
        },
    },
    ["Gun"] = {
        ["Enable"] = true,
        ["Delay"] = 0.5,
        ["Skills"] = {
            ["Z"] = {
                ["Enable"] = true,
                ["HoldTime"] = 0.1,
                ["TimeToNextSkill"] = 0,
            },
            ["X"] = {
                ["Enable"] = true,
                ["HoldTime"] = 0.1,
                ["TimeToNextSkill"] = 0,
            },
        },
    },
}
getgenv().Theme = { -- getgenv().Theme = false if you want to disable
    OldTheme = false,
    Name="oka", --"Raiden","Ayaka","Hutao","Yelan","Miko","Nahida","Ganyu","Keqing","Nilou","Barbara","Zhongli","Layla"
    Custom={
            ["Enable"] = true,
            ['char_size'] = UDim2.new(0.668, 0, 1.158, 0),
            ['char_pos'] = UDim2.new(0.463, 0, -0.105, 0),
            ['title_color'] = Color3.fromRGB(255, 221, 252),
            ['titleback_color'] = Color3.fromRGB(169, 20, 255),
            ['list_color'] = Color3.fromRGB(255, 221, 252),
            ['liststroke_color'] = Color3.fromRGB(151, 123, 207),
            ['button_color'] = Color3.fromRGB(255, 221, 252)
       }
}
loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/b6d24ef1f7dab9c7b22f259a3db6c47e.lua"))()
