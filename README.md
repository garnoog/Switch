if not game:IsLoaded() then repeat game.Loaded:Wait() until game:IsLoaded() end

_G.Switch_Hub_Series_X = true -- เปิดใช้งาน Series x

_G.Quest = {
    ['RGB'] = true
}

_G.RAM = {
    ['Enabled'] = true, -- เปิดใช้งาน Description Roblox Account Manager
    ['Send Log Sheet'] = true, -- ปุ่มส่ง Sheet best ในโปรแกรม Roblox Account Manager
    ['Send Log RAM'] = true, -- ปุ่มส่ง RAM Description ในโปรแกรม Roblox Account Manager
    ['Delay'] = 600 -- 10นาที
}

_G.BestSheet = {
    ['Url'] = 'https://sheet.best/api/sheets/9d4b2976-2391-4caf-ade3-018fdbfaf97c' -- ลิ้ง Sheet Best
}

_G.Main = {
    ['FPS Booster'] = false, -- ปรับภาพต่ำช่วยลด CPU + RAM
    ['White Screen'] = false, -- จอขาวช่วยลด CPU + RAM
    ['Close Ui'] = true, -- ปิดหน้าต่าง Ui
    ['AFK Check'] = 150, -- เช็คถ้ายืนนิ่งครบ 150วิจะทำการ Hop Server
    ['Lock Fruit'] = 1000000, -- ไม่ใช้ผลราคา 1ล้านขึ้นไปลงดัน
    ['Rejoin'] = true, -- รีจอยเมื่อโดนเตะ
    ['Bring Fruit'] = true, -- ดึงผล
    ['Kill Boss'] = true -- ฟาร์มบอส
}

_G.Melee = { -- เลือกหมัดที่ต้องการให้ทำ
    ['Superhuman'] = true,
    ['Death Step'] = true,
    ['Sharkman Karate'] = true,
    ['Electric Claw'] = true,
    ['Dragon Talon'] = true,
    ['Godhuman'] = true
}
_G.Fruit_Main = { -- เลือกผลหลักและเควสโมจิตื่น
    ['Main'] = {'Dough-Dough','Portal-Portal','Leopard-Leopard'}, -- ผลหลักถ้าเจอผลนี้ต่อไห้มีผลในตัวก็จะทำการกินผลนี้เหมือนเดิม
    ['Quest Dough Awaken'] = true, -- ทำเควสโมจิตื่นเมื่อได้รับแก้วน้ำ God's Chalice
    ['Fast Dough Awaken'] = false -- ใช้ผลปีศาจ 2ช1ล้าน+ในการลงดันโมจิ จะทำให้โมจิตื่นเร็วขึ้น
}

_G.Fruit = { -- เลือกผลที่ต้องการให้กิน
    'Dark-Dark','Human-Human: Buddha','Sand-Sand','Magma-Magma'
}
--ผลทั้งหมดในเกมส์'Dark-Dark','Ice-Ice','Sand-Sand','Magma-Magma','Light-Light','Quake-Quake','Kilo-Kilo','Spin-Spin','Chop-Chop','Spring-Spring','Bomb-Bomb','Smoke-Smoke','Spike-Spike','Flame-Flame','Bird-Bird: Falcon','Revive-Revive','Diamond-Diamond','Love-Love','Rubber-Rubber','Barrier-Barrier','Human-Human: Buddha','String-String','Bird-Bird: Phoenix','Portal-Portal','Rumble-Rumble','Paw-Paw','Blizzard-Blizzard','Gravity-Gravity','Dough-Dough','Shadow-Shadow','Venom-Venom','Control-Control','Spirit-Spirit','Dragon-Dragon','Leopard-Leopard'

_G.Sword = { -- เลือกดาบที่ต้องการให้ทำ
    ['Saber'] = true,
    ['Midnight Blade'] = true,
    ['Shisui'] = true,
    ['Saddi'] = true,
    ['Wando'] = true,
    ['Yama'] = true,
    ['Koko'] = false,
    ['Rengoku'] = true,
    ['Canvander'] = true,
    ['Buddy Sword'] = true,
    ['Twin Hooks'] = true,
    ['SpikeyTrident'] = true,
    ['Hallow Scryte'] = true,
    ['Dark Dagger'] = true,
    ['Tushita'] = true,
    ['True Triple Katana'] = true,
    ['Cursed Dual Katana'] = true
}

_G.Gun = { -- เลือกปืนที่ต้องการให้ทำ
    ['Kabucha'] = true,
    ['Acidum Rifle'] = true,
    ['Soul Guitar'] = true,
    ['Serpent Bow'] = true
}

_G.Mastery = { -- เลือกมาสเตอรี่ที่ต้องการฟาร์ม
    ['Melee'] = true,
    ['Fruit'] = true,
    ['Sword'] = true,
    ['Setting Sword'] = { -- ตั้งค่าดาบที่ต้องการให้ฟาร์มมาสเตอรี่
        [1] = "Tushita",
        [2] = "Hallow Scythe",
        [3] = "Spikey Trident",
        [4] = "Dark Dagger",
        [5] = "Buddy Sword",
        [6] = "Yama",
        [7] = "Shisui",
        [8] = "Saddi",
        [9] = "Wando",
        [10] = "True Triple Katana",
        [11] = "Cursed Dual Katana",
        [12] = "Midnight Blade",
        [13] = "Rengoku",
        [14] = "Saber",
        [15] = "Canvander"
    },
    ['Gun'] = true,
    ['Setting Gun'] = { -- ตั้งค่าปืนที่ต้องการให้ฟาร์มมาสเตอรี่
        [1] = 'Soul Guitar',
        [2] = 'Kabucha',
        [3] = 'Acidum Rifle',
        [4] = 'Serpent Bow'
    }
}
