# Projeto_avaliacao
https://www.figma.com/make/qom6fkCIjSOGZOA8zq1sWr/Le-Mans-2026-Schedule?t=QFZvFbLEH7GNzjmu-1




| Campo                  | Significado                     |
| ---------------------- | ------------------------------- |
| 24 Heures du Mans      | Nome do evento                  |
| 14–15 Juin 2026        | Data da corrida                 |
| EN DIRECT              | Dados sendo atualizados ao vivo |
| Leader #7 Toyota Gazoo | Carro líder atual               |
| 383 tours              | Voltas completadas pelo líder   |
 
 
 Indicadores rápidos

Logo abaixo:

Voitures en Course

21

Quantidade de carros ainda participando.

Tours Leader

383

Número de voltas do primeiro colocado.

Dernier Tour Leader

3:27.412

Tempo da última volta do líder.

Abandons

1

Carros que abandonaram a corrida.

Au Pit Lane

3


Carros que estão atualmente nos boxes.

 Filtros de categoria

Botões:

ALL
HYPERCAR
LMP2
LMGT3

Quando o usuário clica:

ALL

Mostra todos os carros.

HYPERCAR

Mostra apenas os Hypercars.

LMP2

Mostra apenas os protótipos LMP2.

LMGT3

Mostra apenas os GT3.


 Ordenação

Botões à direita:

Position

Ordena pela classificação.

Tours

Ordena pelo número de voltas.

Arrêts Pit

Ordena pelo número de paradas.


 Tabela principal

Cada linha representa um carro.

POS

Posição na corrida.

Exemplo:

1
2
3
4
N°

Número oficial do carro.

Exemplo:

#7
#51
#8
Classe

Categoria.

Cores ajudam a identificar:

 Hypercar (Vermelho)

 LMP2 (Azul)

 LMGT3 (Verde)

Équipe / Voiture

Equipe e modelo.

Exemplo:

Toyota Gazoo Racing
Toyota GR010 Hybrid

ou

Ferrari AF Corse
Ferrari 499P
Pilotes

Pilotos do carro.

Exemplo:

M. Conway
K. Kobayashi
N. López

Como Le Mans dura 24 horas, os pilotos se revezam.

Tours

Voltas completadas.

Exemplo:

383
382
381

O líder tem mais voltas.

Écart

Diferença para o líder.

Exemplos:

+0:42.1

42 segundos atrás.

1 lap

1 volta atrás.

2 laps

2 voltas atrás.


 Arrêts

Número de pit stops.

Exemplo:

14
15
16

Quanto mais tempo nos boxes, maior o risco de perder posições.


 Dernier Tour

Última volta realizada.

Exemplo:

3:27.412
3:28.190
3:30.114

Quanto menor o tempo, mais rápida foi a volta.


 État (Estado)

Mostra a situação atual do carro.

 COURSE (Verde)

Carro correndo normalmente.

 PIT (Amarelo)

Carro nos boxes.

Exemplo:

Alpine #38
Cool Racing #37
Corvette #33
 LENT (Laranja)

Carro lento.
Pode indicar:

problema mecânico
pneu furado
economia de combustível
retorno aos boxes

Exemplo:

Isotta Fraschini #11


 Como a classificação é calculada

O sistema compara:

Primeiro

Número de voltas.

Exemplo:

Carro	Voltas
Toyota #7	383
Ferrari #51	383
Toyota #8	382

Toyota #8 fica atrás porque tem menos voltas.

Segundo

Tempo de diferença.

Entre Toyota #7 e Ferrari #51:

383 voltas

Mas:

Ferrari = +0:42.1

Então a Ferrari está 42 segundos atrás.


 Atualização em tempo real

A cada passagem pela linha de chegada o sistema:

recebe o tempo do carro
soma uma volta
recalcula posições
atualiza diferenças
atualiza estado (PIT/COURSE/LENT)
atualiza líder

Fluxo:

Carro cruza a linha
        ↓
Cronometragem recebe tempo
        ↓
Atualiza voltas
        ↓
Recalcula ranking
        ↓
Atualiza tabela
O que chama atenção na sua tela

Neste momento:

 Toyota #7 lidera

 Ferrari #51 está apenas 42 segundos atrás

 Toyota #8 está 1 volta atrás

 Alpine #38 está nos boxes

 Isotta Fraschini #11 está lenta

 O melhor LMP2 é o carro #31 da WRT

 O melhor LMGT3 é o carro #55 da Iron Dames

Ou seja, essa interface funciona como um centro de controle ao vivo da corrida, mostrando posição, estratégia de boxes, ritmo e estado de cada carro em tempo real.