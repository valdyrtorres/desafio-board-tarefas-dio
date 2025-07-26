Tarefa: Projeto de board para gerenciamento de tarefas

* Escreva um código que irá criar um board customizável para acompanhamento de tarefas

* Requisitos
* * 1 - O código deve iniciar disponibilizando um menu com as seguintes opções: Criar novo board, Selecionar board, Excluir boards, Consultar um board, Mostrar vários cards, Sair;
* * 2 - O código deve salvar o board com suas informações no banco de dados MySQL;

* Regras dos boards
* * 1 - Um board deve ter um nome e ser composto por pelo menos 3 colunas [ coluna onde o card é colocado inicialmente, coluna para cards cancelados, a nomenclatura é de escolha livre);
* * 2 - As colunas tem seu respectivo nome, ordem que aparece no board seu tipo (Inicial, cancelamento, final e pendente);
* * 3 - Cada board só pode ter 1 coluna do tipo inicial, cancelamento e final, colunas do tipo pendente podem ter quantas foram necessárias, obrigatoriamente a coluna inicial deve ser a primeira coluna do board, a final deve ser a penúltima e a de cancelamento deve ser a última
* * 4 - As colunas podem ter 0 ou N csrds, cada card tem o seu título, descrição, data de criação e se está bloqueado;
* * 5 - Um card deve navegar nas colunas seguindo a ordem delas no board, sem pular nenhuma etapa, exceto pela coluna de cards cancelados que pode receber cards diretamente de qualque coluna que não for a coluna final;
* * 6 - Se um card estiver marcado como bloqueado ele não pode ser movido até ser desbloqueado
* * 7 - Para bloquar um card deve-se informar o motivo de seu bloqueio e para desbloqueá-lo deve-se informar o motivo

* Menu de manipulação de board selecionado

* * 1 - O menu deve permitir mover o card para a próxima coluna, cancelar um card, criar um card, bloquea-lo, desbloqueá-lo e fechar board;

* Requisitos opcionais:

* * 1 - Um card deve armazenar a data e hora em que foi colocado em uma coluna e a data e hora que foi movido para a próxima coluna;
* * 2 - O código deve gerar um relatório do board selecionado com o tempo que cada tarefa demorou para ser concluída com inromações do tempo que levou em cada coluna
* * 3 - O código deve gerar um relatório do board selecionado com os bloqueios dos cards, com o tempo que ficaram bloqueados e com a justificativa dos bloqueios e desbloqueios.
