# tdd_challenge
Test a rpg design

Produto: Um jogo RPG chamado Breath of Fantasy

Estória: O esquema de batalha -> Criar o esquema de batalha para o jogo. 

Descrição: 

A batalha é baseada em turnos, a cada momento um personagem ataca e o outro recebe o ataque. O personagem tem pontos de energia e pontos de poder. Essas duas propriedades contém números inteiros. Por exemplo, se o herói (pontos de energia:60, pontos de poder:45) ataca um inimigo (pontos de energia:60, pontos de poder:45) o inimigo terá seus pontos de energia diminuídos. O dano sofrido, ou seja, os pontos de energia perdidos pelo inimigo, dependem do fator sorte. O fator sorte é um número randômico de 0 a 100 que é dado a cada turno da batalha. 

Há quatro tipos de ataques que dependem logicamente do fator sorte: 

Quando a sorte está em 0-3 então o ataque é Perdido -> não causa dano;

Quando a sorte está em 4-70 então o ataque é Normal -> causa 1/3 de seus pontos de poder de danos;

Quando a sorte está em 71-96 então o ataque é Sorte -> causa 1/3 de seus pontos de poder mais 20% desses 1/3;

E quando a sorte está em 97-100 então o ataque é Crítico -> causa o dobro de um ataque normal.

Crie testes que provem que com os personagens acima (herói e inimigo) : 

Quando houver um ataque Perdido não há dano; 

Quando houver um ataque Normal haverá um dano de 1/3 dos pontos de poder; 

Quando houver um ataque Sorte haverá um dano de 1/3 + 20% de 1/3; 

E quando houver um ataque Crítico haverá um dano de duas vezes o dano de um ataque normal.

