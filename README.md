# jogos-de-dados-POO
jogo de dados da matéria de POO, construção em conjunto.
Projeto Jogo de Dados Web
1. Visão Geral do Sistema
Este projeto consiste no desenvolvimento de uma aplicação para um Jogo de Dados, com o objetivo primário de aplicar os conceitos de Programação Orientada a Objetos (POO).
O sistema utiliza 2 dados e uma quantidade X de jogadores, que deve ser informada no início da partida.
Lógica da Partida
1. Os jogadores informam suas apostas.
2. Os dados são lançados, e o sistema calcula a soma do valor das faces dos dados para obter o resultado.
3. Se o resultado for igual ao valor apostado por um ou mais jogadores, o sistema informa o(s) jogador(es) vencedor(es).
4. Caso a soma não coincida com nenhuma das apostas, o sistema informa que o computador (Máquina) venceu.
2. Requisitos e Regras de Negócio
O sistema deve atender a requisitos funcionais específicos e seguir regras de negócio estritas.
2.1 Requisitos Funcionais (Casos de Uso)
As funcionalidades chave que o sistema deve implementar são:
1. CSU01 Inserir Jogadores: O sistema solicita e registra a quantidade e o nome de cada jogador.
2. CSU02 Escolher Valor para Apostar: O sistema solicita o valor da aposta de cada jogador.
3. CSU03 Lançar Dados e Apresentar Resultado: O jogador solicita o lançamento dos dados (Inicia o Jogo), o sistema executa o lançamento e exibe o resultado da soma das faces.
4. CSU04 Informar Vencedor: O sistema verifica o resultado e informa o nome do jogador vencedor ou a vitória do computador.
2.2 Regras de Negócio
As seguintes restrições devem ser implementadas no projeto:
• O máximo de jogadores permitido é 11.
• O valor da aposta deve estar obrigatoriamente entre 2 e 12, pois esta é a faixa de resultados possíveis (soma mínima 1+1=2; soma máxima 6+6=12).
• É permitido que mais de um jogador escolha o mesmo valor para a aposta, resultando em uma potencial divisão do prêmio se aquele valor for sorteado.

