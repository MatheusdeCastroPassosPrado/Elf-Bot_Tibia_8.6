##ACTIONS

*VENDENDO INTENS*

{ npcsay 'hi' | npcsay 'trade' | wait 500 | end }

{ wait 500 | countitems 3414 I | wait 500 }     /*Conta quantos tem depois vende*/
{ sellitems 3414 $count | end }

{ wait 500 | countitems 3366 | wait 500 }
{ sellitems 3366 $count | end }
.
.
.
_ou_
say hi
npcsay trade
countitems 3366
wait 300
sellitems 3366 $count
wait 300

*CHECAR ESTAMINA*

if[$stamina <41*60] {gotolabel Termal} //MULTIPLICA POR 60 POR CAUSA DE HRS MIN SEG
if[$stamina == 42*60] {gotolabel DP}

*CHECAR CAPACIDADE*

caphigher 200 gotolabel start //ACIMA  DE TAL VALOR CONTINUA NO LOOP SE NAO ELE SAI 

*CONTINUUDADE DO ATAQUE*

_Parar_targeting_: stopattack | settargeting off

_ligar_targeting_: settargeting on

*GERENCIAMENTO DO ARMAZENAMENTO*

wait 500
closeallwindows //FECHA TUDO ..... AVA
wait 300
openbpitem // ABRE A BACKPACK DO LUGAR DE INTEM
wait 5000
.
.
.
_UMA_UM_POUCO_MAIS_COMPLEXO_""

openbeltitem // abre a que esta lu lugar das flechas
wait 1000

openitemnew 2854 1 'Backpack'

wait 1000

Vou explicar melhor...

O 2854 sera o ID da Backpack , bag, etc...

O NUMERO AO LADO DELA "1" será a quantidade de backpack... ex: se tiver 2 backpack 
com o mesmo ID.. no caso, 2 yellow backpack e voce queria colocar abrir essas duas backpack.. 
voce coloca a action " openitemnew ID "2" (Backpack) isso irá fazer com que abra a segunda backpack 
do mesmo ID , sem fexar a primeira. (nao sei se deu pra intender.)

Entre '' tera que ser o nome EXATO da backpack, no caso a MAIN BACKPACK... 
vamo supor que voce tem uma backpack of holding.. entao neste campo voce terá que 
colocar backpack of holding.

*SEGUE UM NPC*

wait 500
follow NomeDoNpc
wait 500
