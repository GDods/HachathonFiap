# HachathonFiap

Intro / Resultado:
Hackathon do MBA de Inteligencia Artifical e Machine Learing da FIAP, com data de apresentação no dia 25/04/2021.
A proposta é para reduzir as horas extras operacionais ("SO") da empresa Vivante.
Dentre as 2 turmas do MBA de IA e ML, este ficou em 1º lugar.

Desenvolvimento:
Nossa hipótese inicial foi entender que o funcionário que faz “SO” está cobrindo o atraso/falta de outro turno, 
uma vez que a maior parte das funções dos funcionários se encontra na base da Pirâmide de Maslow.

Essa hipótese foi confirmada ao vermos o gráfico Horas Extras SO x Atraso.
Com isso encontramos o funcionário que causa o SO e definimos que o Atraso é a varável resposta.

Identificando os funcionários que atrasam, procuramos soluções externas que se aplicariam para diminuir esses valores,
e encontramos um estudo que comprova que funcionários motivados atrasam cerca de 50% menos, estudo que fundamenta o 
Índice de Felicidade aplicada na ONU.

Dentre as variáveis disponibilizada pela empresa, e um processo de feature engineering,desenvolvemos clusters por DBScan 
(Agrupamento por densidade) e focamos no grupo que mais atrasa em valores absolutos. 

Analisando apenas o grupo, fizemos uma regressão por Random Forest (Árvores de decisão Aleatórias), assim conseguimos 
prever o atraso com erro médio de 15 minutos, dentro do tempo de tolerância da empresa e com o peso de cada variável 
criamos o índice de motivação/felicidade deste grupo.

Além desse modelo, propusemos a empresa a colocar em uma ferramenta de BI para auxiliar no gerenciamento, técnicas de 
gamification para projetos/campanhas motivacionais para os colaboradores.

Membros do Hackathon:
Gabriel O'Donnell;
Rafael Rosseti;
Ricardo Pereira.

