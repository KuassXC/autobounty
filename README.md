getgenv().Setting = {
    ["Team"] = "Pirates", -- Marines / Pirates
    ["Skip Fruit"] = {
        "Portal-Portal",
        "Buddha-Buddha"
    },
    ["Safe Health"] = {4000,6000}, -- Safe Health
    ["Auto Chat"] = "I'm AfxcaxiRoblox",
    ["Webhook"] = {
        ["Enabled"] = false,
        ["Link"] = "",
    },
    ["Weapons"] = {
        ["Melee"] = {
            ["Enable"] = true,
            ["Delay"] = 2,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 2},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["C"] = {["Enable"] = true, ["HoldTime"] = 0},
            }
        },
        ["Blox Fruit"] = {
            ["Enable"] = false,
            ["Delay"] = 1,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 3},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["C"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["V"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["F"] = {["Enable"] = false, ["HoldTime"] = 0}
            }
        },
        ["Sword"] = {
            ["Enable"] = true,
            ["Delay"] = 1.5,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 1},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0}
            } 
        },
        ["Gun"] = {
            ["Enable"] = true,          
            ["Delay"] = 1,
            ["Skills"] = {
                ["Z"] = {["Enable"] = true, ["HoldTime"] = 0},
                ["X"] = {["Enable"] = true, ["HoldTime"] = 0}
            } 
        }
    }
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/SatoruHub/Main-Script/main/Auto-Bounty"))()
