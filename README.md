# Documentação Mundo Místico RPG (BETA)

## Branch's
#### - Monstros
 > Definição de monstros como: nome e mapa que estarão.
#### - Level
 > Normalização do jogo para cada level ter X status agregados aos personagens e monstros.
#### - StatusM
 > Status dos [MONSTROS] definidos pelo level.
#### - StatusP
 > Status dos [PLAYERS] definidos pelo level.
#### - Menu
 > Como serão dispostos os itens dos menus.
#### - Textos
 > História do jogo e dos monstros e mapas. 
#### - Planejamento
 > Edição e atualização do readme.md
 
 ### ------ [ MAPEAMENTO ] ------

 ##### JOGADOR
 Breve história <br>
 Escolha dos personagens <br>
 Apresentação de STATUS e MAGIAS <br>
 Escolha do nome do personagem <br>
 Escolha dos mapas (1,2,3)<br>
 Escolha dos monstros<br>
 Combate <br>
 Pós combate <br> 
 Escolha dos mapas (1,2,3)
 
 ##### PROGRAMADOR
<p> PROCEDIMENTO (LevelUp) L:7 to 19 <br>
 ENQUANTO (Escolha dos personagens) L:57 to 181<br>
 > enquanto (SN L:57) > timer(L:58 to 71) > escolha (personagem L:78 to 180) <br>
 ENQUANTO (Escolha dos mapas) L:208 to 582 <br>
 > Enquanto > Escolha (mundo L:225) > escolha (monstro L:252 ) > enquanto (Mhp L:460) > escolha (personagem L:483)</p>
 
