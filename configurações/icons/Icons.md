[Icons]
Name: Floor Spy
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: spydown
RightCommand: spyup

State: Inactive
IconType: Normal
IconIds: 3487 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 10
AlignY: Top
PositionY: 20
Text: Spy
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3487 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 10
AlignY: Top
PositionY: 20
Text: Spy
TextColor: 65535
HoverColor: 16776960

Name: Exiva
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 6000 dontlist | exivatarget
RightCommand: auto 6000 dontlist | exivalast

State: Inactive
IconType: Normal
IconIds: 3487 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 20
Text: Find
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3487 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 20
Text: Finding
TextColor: 65280
HoverColor: 16776960

Name: Haste
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 200 safe ifnothasted say 'Utamo Tempo San'
RightCommand: dash

State: Inactive
IconType: Normal
IconIds: 3079 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 420
Text: Haste
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3079 0 0 0
BkgType: Normal
BkgIds: 9018 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 420
Text: Haste
TextColor: 65280
HoverColor: 16776960

Name: Runes Of War Lable
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 0
AlignY: Top
PositionY: 50
Text: --Runes Of War--
TextColor: 12632256
HoverColor: 0

State: Active
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 0
AlignY: Absolute
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: D-Field
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: useoncreature 3148 self
RightCommand: crosshair 3148

State: Inactive
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 100
Text: D-Field
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 100
Text: D-Field
TextColor: 65280
HoverColor: 16776960

Name: Magic Wall
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 2000 dontlist | keepmagwall
RightCommand: auto 100 listas 'MW Target' | safe {set $y $target.posy | set $x $target.posx | if [$target.posx > $posx] inc $x | if [$target.posx < $posx] dec $x | if [$target.posy > $posy] inc $y | if [$target.posy < $posy] dec $y | {useongroundxyz [3180] [$x] [$y] [$target.posz]}}

State: Inactive
IconType: Normal
IconIds: 3180 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 150
Text: M-Wall
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3180 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 150
Text: M-Wall
TextColor: 65280
HoverColor: 16776960

Name: Fire Bomb
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: useoncreature 3192 self
RightCommand: crosshair 3192

State: Inactive
IconType: Normal
IconIds: 3192 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 100
Text: F-Bomb
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3192 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 100
Text: F-Bomb
TextColor: 65280
HoverColor: 16776960

Name: Sudden Death
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 100 | dontlist | if [$target.hppc < 25] {sd target | wait 300}
RightCommand: crosshair 3155

State: Inactive
IconType: Normal
IconIds: 3155 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 235
Text: -SD-
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3155 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 235
Text: -SD-
TextColor: 65280
HoverColor: 16776960

Name: Ultimate Healing Rune
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 100 safe | listas 'Heal Friends' | if [$self.hppc >= 80] | sio 80 anyfriend
RightCommand: crosshair 3160

State: Inactive
IconType: Normal
IconIds: 3160 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 195
Text: UH
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3160 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 195
Text: UH
TextColor: 65280
HoverColor: 16776960

Name: Tracking Lable
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: -20
Text: ---Tracking---
TextColor: 12632256
HoverColor: 16777215

State: Active
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 0
AlignY: Top
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: ---Rings/Amys---
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 0
AlignY: Top
PositionY: 260
Text: ---Rings/Amys---
TextColor: 12632256
HoverColor: 16777215

State: Active
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 0
AlignY: Absolute
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: Aol
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 10 | dontlist | if [$amuletslot.id != 3057 && $winitemcount.3057 >= 1] {equipammy 3057 | if [$amuletslot.id == 3057] statusmessage 'SSA Equipped!' | end} | if [$winitemcount.3057 == 0 && $winitemcount.3057 >= 1] {openitem 3057 1 1 | statusmessage 'Opening next SSA backpack!' | end}
RightCommand: say '!aol

State: Inactive
IconType: Normal
IconIds: 3057 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 300
Text:   Use
TextColor: 65535
HoverColor: 43176

State: Active
IconType: Normal
IconIds: 3057 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 300
Text: Using
TextColor: 65280
HoverColor: 35840

Name: Elven Amulet
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 100 | dontlist | equipamy 3082
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3082 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 330
Text:  Use
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3082 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 330
Text: Using
TextColor: 65408
HoverColor: 16776960

Name: Stone Skin Amulet
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 10 | dontlist | if [$amuletslot.id != 3081 && $winitemcount.3081 >= 1] {equipammy 3081 | if [$amuletslot.id == 3081] statusmessage 'SSA Equipped!' | end} | if [$winitemcount.3081 == 0 && $winitemcount.2870 >= 1] {openitem 2870 1 1 | statusmessage 'Opening next SSA backpack!' | end}
RightCommand: auto 100 | listas 'Equip ML Ammy' | if [$amuletslot.id = 3081] equipammy 10457

State: Inactive
IconType: Normal
IconIds: 3081 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 360
Text:  Use
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3081 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 360
Text: Using
TextColor: 65280
HoverColor: 16776960

Name: Time Ring
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 100 | dontlist | equipring 3053
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3053 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 50
AlignY: Top
PositionY: 360
Text:  Use
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3053 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Right
PositionX: 50
AlignY: Top
PositionY: 360
Text: Using
TextColor: 65535
HoverColor: 16776960

Name: Might Ring
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 10 | dontlist | if [$rigslot.id != 3048 && $winitemcount.3048 >= 1] {equipring 3048 | if [$amuletslot.id == 3048] statusmessage 'Might Ring Equipped!' | end} | if [$winitemcount.3048 == 0 && $winitemcount.2871 >= 1] {openitem 2871 1 1 | statusmessage 'Opening next might ring backpack!' | end}
RightCommand: auto 100 | listas 'Equip Donar Ring' | if [$ringslot.id == '3048'] equipring 406

State: Inactive
IconType: Normal
IconIds: 3048 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 50
AlignY: Top
PositionY: 330
Text:  Use
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3048 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Right
PositionX: 50
AlignY: Top
PositionY: 330
Text: Using
TextColor: 65280
HoverColor: 16776960

Name: Energy Ring
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 200 | listas 'Energy Ring Full' | equipring 3051
RightCommand: auto 100 | listas 'Energy Ring Low' | if [$self.hppc <= 75 && $mppc >= 40 && $paralyzed == 1] {equipring 3051 | statusmessage '***Energy Ring Equipped!***'} | wait 100 | if [$self.hppc >= 80 || $mppc <= 40] {equipring 406}

State: Inactive
IconType: Normal
IconIds: 3051 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 50
AlignY: Top
PositionY: 300
Text:  Use
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3088 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 50
AlignY: Top
PositionY: 300
Text: Using
TextColor: 65280
HoverColor: 16776960

Name: Drunk Ring
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 100 | dontlist | if [$drunk == 1] {equipring 3097 | wait 10000 | end} | if [$drunk == 0] {equipring 3007 | wait 100 | end}
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 2894 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 90
AlignY: Top
PositionY: 302
Text:   Use
TextColor: 4227327
HoverColor: 0

State: Active
IconType: Normal
IconIds: 3097 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 90
AlignY: Top
PositionY: 301
Text: Using
TextColor: 65280
HoverColor: 6528840

Name: Shovel
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: 
RightCommand: crosshair 3457

State: Inactive
IconType: Normal
IconIds: 3457 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Left
PositionX: 32
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 3457 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Left
PositionX: 32
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: Rope
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: say 'Exani Tera'
RightCommand: crosshair 3003

State: Inactive
IconType: Normal
IconIds: 3003 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Left
PositionX: 96
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 3003 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Left
PositionX: 96
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: Pick
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: 
RightCommand: crosshair 3456

State: Inactive
IconType: Normal
IconIds: 3456 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Left
PositionX: 64
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 3456 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Left
PositionX: 64
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: mechette
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: 
RightCommand: crosshair 3308

State: Inactive
IconType: Normal
IconIds: 3308 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Left
PositionX: 0
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 3308 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Left
PositionX: 0
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: Food
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 20000 | dontlist | eatfood
RightCommand: eatfood

State: Inactive
IconType: Normal
IconIds: 3725 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Left
PositionX: 288
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 3725 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Left
PositionX: 288
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: Blessed Stake
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: 
RightCommand: crosshair 5942

State: Inactive
IconType: Normal
IconIds: 5942 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Left
PositionX: 160
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 5942 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Left
PositionX: 160
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: Obsidian Knife
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: 
RightCommand: crosshair 5908

State: Inactive
IconType: Normal
IconIds: 5908 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Left
PositionX: 128
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 5908 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Left
PositionX: 128
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: GP to Plats
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 1500 listas 'Gold to Platinum' | if [$itemcount.3031 >= 100] { openitem 3031 1 'backpack'}
RightCommand: auto 200 listas 'Gold coin - platinum coin' | stackitems | if [ $itemcount.3031 >= 100 ] equipbelt 3031 | if [$beltslot.id == 3031 && $beltslot.count == 100] useitem 3031

State: Inactive
IconType: Normal
IconIds: 3031 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Left
PositionX: 192
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 3035 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Left
PositionX: 192
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: Plats to Crystals
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 1500 listas 'Platinum to Crystal' | if [$itemcount.3035 >= 100] { openitem 3035 2 'backpack'}
RightCommand: auto 1000 dontlist | stackitems | if [ $itemcount.3035 >= 100 ] equipbelt 3035 | if [$beltslot.id == 3035 && $beltslot.count == 100] useitem 3035

State: Inactive
IconType: Normal
IconIds: 3035 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Left
PositionX: 224
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 3043 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Left
PositionX: 224
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: Crystals to ingot
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 1500 listas 'Crystal to Ingot' | if [$itemcount.3043 >=100] { openitem 3043 2 'backpack'}
RightCommand: auto 200 listas 'Gold coin - platinum coin' | stackitems | if [ $itemcount.3043 >= 100 ] equipbelt 3043 | if [$beltslot.id == 3043 && $beltslot.count == 100] useitem 3043

State: Inactive
IconType: Normal
IconIds: 3043 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Left
PositionX: 256
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 9058 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Left
PositionX: 256
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: Other Lable
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 0
AlignY: Top
PositionY: 380
Text: -----Other----
TextColor: 12632256
HoverColor: 16777215

State: Active
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 0
AlignY: Absolute
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: Softs
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 100 listas 'Paralyze Heal' | setcolor 255 255 255 | healparalysis 'utamo tempo san'
RightCommand: auto 200 | listas 'Fire Walkers' | if [$bootsslot.id == '9020'] unequip 'boots' | wait 1000 | useoninventoryitem 676 9020 | wait 1000 | equipboots 9019

State: Inactive
IconType: Normal
IconIds: 6530 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 420
Text: Boots
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3549 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 420
Text: Boots
TextColor: 65280
HoverColor: 16776960

Name: Blessing
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 100 | dontlist | ifnot $connected {reconnect | wait 3000 | say '!bless'}
RightCommand: say '!bless'

State: Inactive
IconType: Normal
IconIds: 6561 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 455
Text: Blessing
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 6561 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 455
Text: Blessing
TextColor: 65280
HoverColor: 16776960

Name: Toggle Bot
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: if [$targetingon || $caveboton] {statusmessage 'ElfBot NG - CaveBot Paused' | stopattack | settargeting off | setcavebot off | wait 400 | end} | if [$targetingon == 0 || $caveboton == 0] {statusmessage 'ElfBot NG - CaveBot Resumed' | settargeting on | setcavebot on | wait 400}
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 7360 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 455
Text: On/Off
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 6499 0 0 0
BkgType: Normal
BkgIds: 7359 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 455
Text: On/Off
TextColor: 65280
HoverColor: 16776960

Name: Hold Target speed atl
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 100 if $attacked set $holdd $attacked | if [$attacked != $holdd && $holdd.hppc != 0] attack $holdd.id | ifnot [$holdd.hppc] clear $holdd | setpos [$screenleft+2] [$screentop] | setcolor 206 206 206 | if $holdd displaytext 'Hold target: [$holdd.name]' | ifnot $holdd displaytext 'Hold 
RightCommand: Auto 1 attack target

State: Inactive
IconType: Normal
IconIds: 8082 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 535
Text: Target
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 8082 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 535
Text: Target
TextColor: 65280
HoverColor: 16776960

Name: Training
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 200 listas Mana Training | mphigher 250 say exevo mas san | mphigher 550 utito tempo san
RightCommand: auto 500 | listas 'Magic Level Training' | say 'Utana Vid' wait 5000

State: Inactive
IconType: Normal
IconIds: 238 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 495
Text: Train
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 238 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 495
Text: Train
TextColor: 65280
HoverColor: 16776960

Name: Dance of Dead
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 500 | listas 'Dance' | turne | wait 500 | turns | wait 500 | turnw | wait 500 | turnn | wait 500 | turne
RightCommand: auto 1 turnw | wait 1 | turns | wait 1 | turne | wait 1 | turnn | wait 1 

State: Inactive
IconType: Normal
IconIds: 3219 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 495
Text:  DoD
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3219 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 495
Text:  DoD
TextColor: 65280
HoverColor: 16776960

Name: N
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: useoncreature 3188 $target.name | moveitemonground $target.posx $target.posy $target.posz $target.posx [$target.posy-1] $target.posz
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 150
AlignY: Bottom
PositionY: -105
Text:    N
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 150
AlignY: Bottom
PositionY: -105
Text: N
TextColor: 65280
HoverColor: 16776960

Name: NE
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: useoncreature 3188 $target.name | moveitemonground $target.posx $target.posy $target.posz [$target.posx+1] [$target.posy-1] $target.posz
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -105
Text:   NE
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -105
Text: NE
TextColor: 65280
HoverColor: 16776960

Name: NW
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: useoncreature 3188 $target.name | moveitemonground $target.posx $target.posy $target.posz [$target.posx-1] [$target.posy-1] $target.posz
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -105
Text:   NW
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -105
Text: NW
TextColor: 65280
HoverColor: 16776960

Name: E
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: useoncreature 3188 $target.name | moveitemonground $target.posx $target.posy $target.posz [$target.posx+1] $target.posy $target.posz
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -70
Text:     E
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -70
Text: E
TextColor: 65280
HoverColor: 16776960

Name: W
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: useoncreature 3188 $target.name | moveitemonground $target.posx $target.posy $target.posz [$target.posx-1] $target.posy $target.posz
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -70
Text:    W
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -70
Text: W
TextColor: 65280
HoverColor: 16776960

Name: S
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: useoncreature 3188 $target.name | moveitemonground $target.posx $target.posy $target.posz $target.posx [$target.posy+1] $target.posz
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 150
AlignY: Bottom
PositionY: -35
Text:     S
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 150
AlignY: Bottom
PositionY: -35
Text: S
TextColor: 65280
HoverColor: 16776960

Name: SW
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: useoncreature 3188 $target.name | moveitemonground $target.posx $target.posy $target.posz [$target.posx-1] [$target.posy+1] $target.posz
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -35
Text:   SW
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -35
Text: SW
TextColor: 65280
HoverColor: 16776960

Name: SE
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: useoncreature 3188 $target.name | moveitemonground $target.posx $target.posy $target.posz [$target.posx+1] [$target.posy+1] $target.posz
RightCommand: useoncreature 3188 $target.name | moveitemonground $target.posx $target.posy $target.posz [$target.posx-1] [$target.posy+1] $target.posz

State: Inactive
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -35
Text:   SE
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -35
Text: SE
TextColor: 65280
HoverColor: 16776960

Name: PUSH
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 100 listas 'Push All' | moveitemonground $posx [$posy-1] $posz $posx $posy $posz|moveitemonground $posx [$posy+1] $posz $posx $posy $posz|moveitemonground [$posx-1] [$posy-1] $posz $posx $posy $posz|moveitemonground [$posx-1] $posy $posz $posx $posy $posz|moveitemonground [$posx-1] [$posy+1] $posz $posx $posy $posz| moveitemonground [$posx+1] [$posy-1] $posz $posx $posy $posz|moveitemonground [$posx+1] $posy $posz $posx $posy $posz|moveitemonground [$posx+1] [$posy+1] $posz $posx $posy $posz
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 150
AlignY: Bottom
PositionY: -180
Text: PUSH
TextColor: 65535
HoverColor: 0

State: Active
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 150
AlignY: Bottom
PositionY: -180
Text: PUSH
TextColor: 65280
HoverColor: 0

Name: Push Target SW
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: moveitemonground $target.posx $target.posy $target.posz [$target.posx-1] [$target.posy+1] $target.posz | moveitemonground $target.posx $target.posy $target.posz [$target.posx-1] [$target.posy+1] $target.posz
RightCommand: {useongroundxyz 3148 [$target.posx-1] [$target.posy+1] $target.posz | set $a 1}

State: Inactive
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -140
Text:   Sw
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -140
Text: SW
TextColor: 65280
HoverColor: 16776960

Name: Push Target SE
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: moveitemonground $target.posx $target.posy $target.posz [$target.posx+1] [$target.posy+1] $target.posz | moveitemonground $target.posx $target.posy $target.posz [$target.posx+1] [$target.posy+1] $target.posz
RightCommand: {useongroundxyz 3148 [$target.posx+1] [$target.posy+1] $target.posz | set $g 1}

State: Inactive
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -140
Text:   SE
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -140
Text: SE
TextColor: 65280
HoverColor: 16776960

Name: Push Target S
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: moveitemonground $target.posx $target.posy $target.posz $target.posx [$target.posy+1] $target.posz
RightCommand: {useongroundxyz 3148 $target.posx [$target.posy+1] $target.posz | set $h 1}

State: Inactive
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 150
AlignY: Bottom
PositionY: -140
Text:     S
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 150
AlignY: Bottom
PositionY: -140
Text: S
TextColor: 65280
HoverColor: 16776960

Name: Push Target W
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: moveitemonground $target.posx $target.posy $target.posz [$target.posx-1] $target.posy $target.posz | moveitemonground $target.posx $target.posy $target.posz [$target.posx-1] $target.posy $target.posz
RightCommand: {useongroundxyz 3148 [$target.posx-1] $target.posy $target.posz | set $b 1}

State: Inactive
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -170
Text:    W
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -170
Text: W
TextColor: 65280
HoverColor: 16776960

Name: Push Target E
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: moveitemonground $target.posx $target.posy $target.posz [$target.posx+1] $target.posy $target.posz | moveitemonground $target.posx $target.posy $target.posz [$target.posx+1] $target.posy $target.posz
RightCommand: {useongroundxyz 3148 [$target.posx+1] $target.posy $target.posz | set $f 1}

State: Inactive
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -170
Text:     E
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -170
Text: E
TextColor: 65280
HoverColor: 16776960

Name: Push Target NW
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: moveitemonground $target.posx $target.posy $target.posz [$target.posx+1] [$target.posy+1] $target.posz | moveitemonground $target.posx $target.posy $target.posz [$target.posx+1] [$target.posy+1] $target.posz
RightCommand: {useongroundxyz 3148 [$target.posx-1] [$target.posy-1] $target.posz | set $c 1}

State: Inactive
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -205
Text:   NW
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 120
AlignY: Bottom
PositionY: -205
Text: NW
TextColor: 65280
HoverColor: 16776960

Name: Push Target NE
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: {useongroundxyz 3148 $target.posx [$target.posy-1] $target.posz | set $d 1}
RightCommand: {useongroundxyz 3148 [$target.posx+1] [$target.posy-1] $target.posz | set $e 1}

State: Inactive
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -205
Text:    NE
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 180
AlignY: Bottom
PositionY: -205
Text: NE
TextColor: 65280
HoverColor: 16776960

Name: Push Target N
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: moveitemonground $target.posx $target.posy $target.posz $target.posx [$target.posy-1] $target.posz | moveitemonground $target.posx $target.posy $target.posz $target.posx [$target.posy-1] $target.posz
RightCommand: {useongroundxyz 3148 $target.posx [$target.posy-1] $target.posz | set $d 1}

State: Inactive
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 150
AlignY: Bottom
PositionY: -205
Text:    N
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3148 0 0 0
BkgType: Normal
BkgIds: 9019 0 0 0
AlignX: Absolute
PositionX: 150
AlignY: Bottom
PositionY: -205
Text: N
TextColor: 65280
HoverColor: 16776960

Name: Anti push
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 100 listas 'Anti Push: ON' | dropitems 283 284 285 | ifnot [$topitem.$posx.$posy.$posz ==3031] ifnot [$topitem.$posx.$posy.$posz ==3492] dropitemsxyzamount $posx $posy $posz 3031 1 | ifnot [$topitem.$posx.$posy.$posz == 3492] dropitemsxyzamount $posx $posy $posz 3492 1 |
RightCommand: auto 5000 listas 'Anti Push 2: ON' | dropitemsxyzamount $posx $posy $posz 3725 1 |

State: Inactive
IconType: Normal
IconIds: 3031 0 0 0
BkgType: Normal
BkgIds: 2118 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 534
Text: Anti
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3031 0 0 0
BkgType: Normal
BkgIds: 7359 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 534
Text: Anti
TextColor: 65280
HoverColor: 16776960

Name: Magic Wall Target
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 200 listas 'Magic Wall: ON' | safe {set $y $target.posy | set $x $target.posx | if [$target.posx > $posx] inc $x | if [$target.posx < $posx] dec $x | if [$target.posy > $posy] inc $y | if [$target.posy < $posy] dec $y | {useongroundxyz [3180] [$x] [$y] [$target.posz]}}
RightCommand: auto 100 listas 'Keep Magic Wall' | keepmagwall

State: Inactive
IconType: Normal
IconIds: 3180 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 110
AlignY: Top
PositionY: 150
Text: M-W 
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3180 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 110
AlignY: Top
PositionY: 150
Text: M-W: ON
TextColor: 65280
HoverColor: 16776960

Name: Shield-FIRE
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 100 isattacking {if [$attacked.outfit == 0] {say 'exevo mas san' | wait 200}}
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 8081 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Right
PositionX: -373
AlignY: Bottom
PositionY: 0
Text:   tna
TextColor: 12632256
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 8078 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Right
PositionX: -373
AlignY: Bottom
PositionY: 0
Text: vtp
TextColor: 255
HoverColor: 11750824

Name: Shield - Energy-UTAMO
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 100 listas '' | if [$manashielded == 0 && $mp >= 50] {say 'utamo vita' | wait 500}
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 8080 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Right
PositionX: -405
AlignY: Bottom
PositionY: 0
Text:    HP
TextColor: 255
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 8077 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Right
PositionX: -405
AlignY: Bottom
PositionY: 0
Text:    MP
TextColor: 16711680
HoverColor: 16776960

Name: Potion no amigo
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 100 set $potionid 266 | set $perc 60 | set $dist 2 | clear $best | set $lowest 100 | foreach 'screenplayers' $fr {if [$fr.distance <= $dist && $fr.hppc < $perc && $fr.hppc < $lowest && ($fr.isfriend || $fr.issubfriend)] {set $lowest $fr.hppc | set $best $fr}} | if [$hppc <= $perc] set $best $self | if $best {dashchase $best.id | useoncreature $potionid $best.id | wait 300}
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 284 0 0 0
BkgType: Normal
BkgIds: 410 0 0 0
AlignX: Right
PositionX: -244
AlignY: Bottom
PositionY: 0
Text: H/M
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 7643 0 0 0
BkgType: Normal
BkgIds: 409 0 0 0
AlignX: Right
PositionX: -244
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: ANTI -AKF
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 100 listas 'Anti-Afk' | if [$lastmsg.content ? 'you have been idle for'] turnn | wait 500 | turnw
RightCommand: 

State: Inactive
IconType: Left
IconIds: 400 0 0 0
BkgType: Left
BkgIds: 410 0 0 0
AlignX: Absolute
PositionX: 866
AlignY: Bottom
PositionY: 0
Text: AFK
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Left
IconIds: 400 0 0 0
BkgType: Left
BkgIds: 409 0 0 0
AlignX: Absolute
PositionX: 866
AlignY: Bottom
PositionY: 0
Text: AFK
TextColor: 65280
HoverColor: 16776960

Name: Botcheck - alarm
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 1 | dontlist | if [$curmsg.content ? 'CHECKED' && $curmsg.isstatus] playsound playerattacking.wav
RightCommand: 

State: Inactive
IconType: Left
IconIds: 5786 0 0 0
BkgType: Left
BkgIds: 410 0 0 0
AlignX: Absolute
PositionX: 898
AlignY: Bottom
PositionY: 0
Text: B.C.
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Left
IconIds: 5786 0 0 0
BkgType: Left
BkgIds: 409 0 0 0
AlignX: Absolute
PositionX: 898
AlignY: Bottom
PositionY: 0
Text: B.C.
TextColor: 65280
HoverColor: 16776960

Name: Disconnect - alarm
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 100 listas Reconect | ifnot $connected { reconnect | wait 3000 }
RightCommand: auto 100 | dontlist | ifnot $connected {playsound playerattacking.wav}

State: Inactive
IconType: Left
IconIds: 5786 0 0 0
BkgType: Left
BkgIds: 410 0 0 0
AlignX: Absolute
PositionX: 930
AlignY: Bottom
PositionY: 0
Text: D/C
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Left
IconIds: 5786 0 0 0
BkgType: Left
BkgIds: 409 0 0 0
AlignX: Absolute
PositionX: 930
AlignY: Bottom
PositionY: 0
Text: D/C
TextColor: 65280
HoverColor: 16776960

Name: PMS
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 100 listas 'PMs' | listboxsetup 1 [$screenleft+6] [$screenbottom-12] 6 4500000 'up' | if [$fileisline.'friends.txt'.'$curmsg.sender' && $curmsg.isprivate] {listboxaddline 1 250 0 30 '$systime [$curmsg.sender]: [$cutstr.'$curmsg.content'.0.40]'} | ifnot [$fileisline.'friends.txt'.'$curmsg.sender'] {if [$curmsg.isprivate] {listboxaddline 1 0 237 242 '$systime [$curmsg.sender]: [$cutstr.'$curmsg.content'.0.40]'}}
RightCommand: 

State: Inactive
IconType: Left
IconIds: 3236 0 0 0
BkgType: Left
BkgIds: 410 0 0 0
AlignX: Absolute
PositionX: 834
AlignY: Bottom
PositionY: 0
Text: PMS
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Left
IconIds: 3236 0 0 0
BkgType: Left
BkgIds: 409 0 0 0
AlignX: Absolute
PositionX: 834
AlignY: Bottom
PositionY: 0
Text: PMS
TextColor: 65280
HoverColor: 16776960

Name: Skills
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: auto 2000 | dontlist | setcaption '$name     Level: $level          $formatnum.$exptnl Exp/hr ---  $formattime.$timetnl Time TNL         Magic Level: $formatnum.$skillpc.mlevel % --- $formattime.$skilltime.mlevel                      Sword Level: $formatnum.$skillpc.sword % --- $formattime.$skilltime.sword                    Shielding Level: $formatnum.$skillpc.shielding % --- $formattime.$skilltime.shielding'
RightCommand: auto 1 | listas 'BOTBUGADO' | if [$standtime >= 30000] {movenw | wait 1000} | if [$standtime >= 31000] {moven | wait 1000} | if [$standtime >= 32000] {movene | wait 1000} | if [$standtime >= 33000] {movee | wait 1000} | if [$standtime >= 34000] {movese | wait 1000} | if [$standtime >= 35000] {moves | wait 1000} | if [$standtime >= 36000] {movesw | wait 1000} | if [$standtime >= 37000] {movew | wait 1000}

State: Inactive
IconType: Left
IconIds: 8176 0 0 0
BkgType: Left
BkgIds: 410 0 0 0
AlignX: Absolute
PositionX: 802
AlignY: Bottom
PositionY: 0
Text: Info
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Left
IconIds: 8176 0 0 0
BkgType: Left
BkgIds: 409 0 0 0
AlignX: Absolute
PositionX: 802
AlignY: Bottom
PositionY: 0
Text: Info
TextColor: 65280
HoverColor: 16776960

Name: Exana flam
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: say 'exana flam'
RightCommand: 

State: Inactive
IconType: Left
IconIds: 2123 0 0 0
BkgType: Left
BkgIds: 410 0 0 0
AlignX: Absolute
PositionX: 706
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Left
IconIds: 2123 0 0 0
BkgType: Left
BkgIds: 409 0 0 0
AlignX: Absolute
PositionX: 706
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 65280
HoverColor: 16776960

Name: Exana pox
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: say 'exana pox'
RightCommand: 

State: Inactive
IconType: Left
IconIds: 2121 0 0 0
BkgType: Left
BkgIds: 410 0 0 0
AlignX: Absolute
PositionX: 674
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Left
IconIds: 2121 0 0 0
BkgType: Left
BkgIds: 409 0 0 0
AlignX: Absolute
PositionX: 674
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 65280
HoverColor: 16776960

Name: Exana vis
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: say 'exana vis'
RightCommand: 

State: Inactive
IconType: Left
IconIds: 2122 0 0 0
BkgType: Left
BkgIds: 410 0 0 0
AlignX: Absolute
PositionX: 642
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Left
IconIds: 2122 0 0 0
BkgType: Left
BkgIds: 409 0 0 0
AlignX: Absolute
PositionX: 642
AlignY: Bottom
PositionY: 0
Text: 
TextColor: 65280
HoverColor: 16776960

Name: Fire Field Rune
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: 
RightCommand: crosshair 3188

State: Inactive
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 195
Text: F-Field
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3188 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 195
Text: F-Field
TextColor: 65280
HoverColor: 16776960

Name: Wild Groth Rune
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3156 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 150
Text: T-Wall
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3156 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 55
AlignY: Top
PositionY: 150
Text: T-Wall
TextColor: 65280
HoverColor: 16776960

Name: Paralyze Rune
Enabled: yes
DrawAsBackground: yes
Size: Small
LeftCommand: paralyze target
RightCommand: crosshair 3165

State: Inactive
IconType: Normal
IconIds: 3165 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 235
Text: Para
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 3165 0 0 0
BkgType: Normal
BkgIds: 111 0 0 0
AlignX: Right
PositionX: 5
AlignY: Top
PositionY: 235
Text: Para
TextColor: 65280
HoverColor: 16776960

Name: ---Poderes---
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 2
AlignY: Absolute
PositionY: 20
Text: ---------Poderes----------
TextColor: 12632256
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 0
AlignY: Absolute
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: ----Knight----
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 0
AlignY: Absolute
PositionY: 39
Text:  ---Knight---
TextColor: 6184703
HoverColor: 16711808

State: Active
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 0
AlignY: Absolute
PositionY: 39
Text:  ---Knight---
TextColor: 6184703
HoverColor: 16711808

Name: Exori
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 100 listas 'BY PBOTWARS :: auto mas exori e exori hur' | setcolor 051 204 000 | if [$playersaround.8 == 0 && $monstersaround.1 >= 1] {say 'mas exori'} | if [$playersaround.8 >= 1] {say 'exori hur'}
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 7453 0 0 0
BkgType: Normal
BkgIds: 2133 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 77
Text: Exori
TextColor: 6776679
HoverColor: 0

State: Active
IconType: Normal
IconIds: 3320 0 0 0
BkgType: Normal
BkgIds: 2131 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 77
Text: Exori
TextColor: 8421631
HoverColor: 0

Name: kinapoder
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 7402 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 77
Text: kp
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 7402 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 77
Text: 
TextColor: 0
HoverColor: 0

Name: kina poder1
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 7402 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 113
Text: kp1
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 7402 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 113
Text: 
TextColor: 0
HoverColor: 0

Name: kina poder2
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 7402 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 113
Text: kp2
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 7402 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 113
Text: kp2
TextColor: 0
HoverColor: 0

Name: kina poder3
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 7402 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 149
Text: kp3
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 7402 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 149
Text: kp3
TextColor: 0
HoverColor: 0

Name: kins poder4
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 7402 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 149
Text: kp4
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 7402 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 149
Text: kp4
TextColor: 0
HoverColor: 0

Name: ----Paladin----
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 100
AlignY: Absolute
PositionY: 39
Text:  ---Paladin---
TextColor: 10944511
HoverColor: 0

State: Active
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 0
AlignY: Absolute
PositionY: 0
Text: 
TextColor: 0
HoverColor: 0

Name: Exori Gran Con auto
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 1 {listas '' | setcolor 200 200 200 } | if [$noplayer != 1 && $playersaround.10 == 0 && $semue == 1000 && $mp >= 100 && $monstersaround.1 >= 2 && $stopue != 1 && $player == 0 && $self.skull != 3 && $target.isshootable] {say 'exori gran con'} else if [$target.isshootable && $target.hppc >= 1] {isattacking say exori gran con | wait 1000}}
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3277 0 0 0
BkgType: Normal
BkgIds: 2136 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 77
Text:   EGC
TextColor: 65535
HoverColor: 16776960

State: Active
IconType: Normal
IconIds: 7367 0 0 0
BkgType: Normal
BkgIds: 2135 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 77
Text:   EGC
TextColor: 65408
HoverColor: 16776960

Name: Exevo Mas San
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 100 listas 'BY PBOTWARS :: auto mas exori e exori hur' | setcolor 051 204 000 | if [$playersaround.8 == 0 && $monstersaround.1 >= 1] {say 'exevo mas san'} | if [$playersaround.8 >= 1] {say 'exori con'} 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3214 0 0 0
BkgType: Left
BkgIds: 2133 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 77
Text: EMS
TextColor: 16777215
HoverColor: 8421504

State: Active
IconType: Normal
IconIds: 6561 0 0 0
BkgType: Normal
BkgIds: 2131 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 77
Text: EMS
TextColor: 9699327
HoverColor: 50886

Name: Utito Tempo San
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 10000 if [$strengthttime <= 1200] {say 'Utito Tempo San' | wait 500}
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 9035 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 113
Text:   UTS
TextColor: 65535
HoverColor: 0

State: Active
IconType: Normal
IconIds: 9034 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 113
Text:   UTS
TextColor: 255
HoverColor: 0

Name: pala1
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 10000 if [$defensetime <= 1200] {say 'utamo mas sio' | wait 500}
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3277 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 149
Text: pa1
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 1135 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 149
Text: p77
TextColor: 0
HoverColor: 0

Name: pala2
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: auto 100 | listas 'Sio party: ON' | foreach 'allplayers' $l {if [$l.party >= 2 && $l.hppc < 75] {say 'exura sio "$l.name'}
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3277 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 113
Text: pa2
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 3277 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 113
Text: o
TextColor: 0
HoverColor: 0

Name: pala3
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 3277 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 149
Text: pa3
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 3277 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 149
Text: pa3
TextColor: 0
HoverColor: 0

Name: ---Druid---
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 0
AlignY: Absolute
PositionY: 168
Text:  ----Druid---
TextColor: 30976
HoverColor: 47452

State: Active
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 0
AlignY: Absolute
PositionY: 168
Text:  ----Druid---
TextColor: 30976
HoverColor: 47452

Name: MAGIA ALEATORIA1
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 207
Text: ma1
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 207
Text: D
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA2
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: q
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 243
Text: ma2
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 243
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA3
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 279
Text: ma3
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 279
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA4
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 315
Text: ma4
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 3
AlignY: Absolute
PositionY: 315
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA5
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 207
Text: ma5
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 207
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA6
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 243
Text: ma6
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 243
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA7
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 279
Text: ma7
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 279
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA8
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 315
Text: ma8
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 54
AlignY: Absolute
PositionY: 315
Text: 
TextColor: 0
HoverColor: 0

Name:  ---Sorc---
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 100
AlignY: Absolute
PositionY: 168
Text:  ---- Sorc ----
TextColor: 11734528
HoverColor: 15466496

State: Active
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 100
AlignY: Absolute
PositionY: 168
Text:  ---- Sorc ----
TextColor: 11734528
HoverColor: 15466496

Name: MAGIA ALEATORIA9
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 207
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 207
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA10
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 243
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 243
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA11
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 279
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 279
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA12
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 315
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 103
AlignY: Absolute
PositionY: 315
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA13
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 207
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 207
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA14
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 243
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 243
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA15
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 279
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 279
Text: 
TextColor: 0
HoverColor: 0

Name: MAGIA ALEATORIA16
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: say"exana pox
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 10217 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 315
Text: 
TextColor: 0
HoverColor: 0

State: Active
IconType: Normal
IconIds: 8090 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 158
AlignY: Absolute
PositionY: 315
Text: 
TextColor: 0
HoverColor: 0

Name: Extras
Enabled: yes
DrawAsBackground: no
Size: Small
LeftCommand: 
RightCommand: 

State: Inactive
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 0
AlignY: Absolute
PositionY: 326
Text: ----------Extras----------
TextColor: 12632256
HoverColor: 33023

State: Active
IconType: Normal
IconIds: 0 0 0 0
BkgType: Normal
BkgIds: 0 0 0 0
AlignX: Absolute
PositionX: 0
AlignY: Absolute
PositionY: 326
Text: ----------Extras----------
TextColor: 12632256
HoverColor: 33023
