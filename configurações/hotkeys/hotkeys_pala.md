Hotkeys

*Ataca um mosntro com um poder que vc queira diferencia se tem ou não player no local*

auto 1 {listas 'exori gran con ~ I.A.S ™ + 8' | setcolor 200 200 200 } | if [$noplayer != 1 && $playersaround.10 == 0 && $semue == 1000 && $mp >= 100 && $monstersaround.1 >= 2 && $stopue != 1 && $player == 0 && $self.skull != 3 && $target.isshootable] {say 'exori gran con'} else if [$target.isshootable && $target.hppc >= 1] {isattacking say exori gran con | wait 1000}}

*Usa o utito tempo sam quando acaba*

auto 10000 if [$strengthttime <= 1200] {say 'Utito Tempo San' | wait 500}

*Vamo da uma corridinha?? haste*

auto 200 safe ifnothasted say 'Utamo Tempo San'

*Cura um amigo com UH HP 80%*

auto 500 listas 'Auto UH Friend' | uhpc 80 friend

*CURA PARALYSIA*

auto 100 listas 'Paralyze Heal' | setcolor 255 255 255 | healparalysis 'utamo tempo san'

*Magic wall em alguem kkk pq pq qurero ue*

if [$target.dir == 0] {set $dirx [$target.posx] | set $diry [$target.posy-3]} | if [$target.dir == 2] {set $dirx [$target.posx] | set $diry [$target.posy+3]} | if [$target.dir == 1] {set $dirx [$target.posx+3] | set $diry [$target.posy]} | if [$target.dir == 3] {set $dirx [$target.posx-3] | set $diry [$target.posy]} | if [$target.isonscreen && $target.isshootable] {useongroundxyz 3180 $dirx $diry $posz}

*Vamo de escudo de mana pq sim*

auto 100 listas 'Renovar Utamo' | if [$manashielded == 0 && $mp >= 50] {say 'utamo vita' | wait 500}
*
ele se cura com uma magia mas assim ...pq pot infinita viva os baika*

auto 100 listas 'BY PBOTWARS :: auto exura san' | setcolor 051 204 000 | if [$hppc < 90] say 'exura san'

*Preguiça não time !come auto*

auto 60000  listas 'BY PBOTWARS :: auto food' | setcolor 051 204 000 | if 60000 eatfood 
*anti afk*

auto 100 listas 'Anti-Afk' | if [$lastmsg.content ? 'you have been idle for'] turnn | wait 500 | turnw

*auto reconect*

auto 100 listas Reconect | ifnot $connected { reconnect | wait 3000 }*

*mana training de auto impacto*

auto 200 listas Mana Training | mphigher 250 say exevo mas san | mphigher 550 utito tempo san

*Transformar moedas*

_Observação_: Com estas Hotkeys você não vai precisar deixar o slot de flechas disponíveis. 

Basta que você identifique na hotkey o nome da backpack que você quer que faça change gold.
auto 1500 listas 'Gold to Platinum' | if [$itemcount.3031 > 100] { openitem 3031 2 'NOME-DA-BACKPACK'}
auto 1500 listas 'Platinum to Crystal' | if [$itemcount.3035 > 100] { openitem 3035 2 'NOME-DA-BACKPACK'}
auto 1500 listas 'Crystal to Ingot' | if [$itemcount.3043 >=100] { openitem 3043 1 'crown backpack'}

_Observação_: Deixe o espaço de flechas livre para que a hotkey funcione corretamente

auto 200 listas 'Gold coin - platinum coin' | stackitems | if [ $itemcount.3031 >= 100 ] equipbelt 3031 | if [$beltslot.id == 3031 && $beltslot.count == 100] useitem 3031
auto 1500 listas 'Platinum to Crystal' | if [$itemcount.3035 > 100] { openitem 3035 2 'crown backpack'} 
auto 1500 listas 'Crystal to Ingot' | if [$itemcount.3043 >= 100] { openitem 3043 2 'crown backpack'}   
