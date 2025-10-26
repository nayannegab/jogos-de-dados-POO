# jogos-de-dados-POO
jogo de dados da matéria de POO, construção em conjunto.
Projeto Jogo de Dados Web
Visão Geral do Sistema
O projeto Jogo de Dados Web tem como objetivo desenvolver uma aplicação para simular um jogo de apostas com dois dados, aplicando na prática os conceitos de Programação Orientada a Objetos (POO).
O sistema utiliza dois dados e uma quantidade variável de jogadores, que deve ser informada no início da partida.
Lógica da Partida:
- Os jogadores informam seus nomes e apostas.
- O sistema realiza o lançamento dos dois dados.
- O sistema calcula a soma das faces dos dados.
- Caso o resultado seja igual a algum valor apostado, o sistema informa o(s) jogador(es) vencedor(es).
- Caso contrário, o sistema informa que o computador venceu.

Levantamento de Requisitos
  O sistema deve atender a requisitos funcionais específicos que representam as principais interações entre o jogador e o sistema.

Requisitos Funcionais
  CSU01 – Inserir Jogadores:
O sistema solicita e registra a quantidade e o nome de cada jogador.

CSU02 – Escolher Valor para Apostar:
O sistema solicita o valor da aposta de cada jogador.

CSU03 – Lançar Dados e Apresentar Resultado:
O jogador solicita o lançamento dos dados (iniciar o jogo); o sistema executa o lançamento e exibe o resultado da soma das faces.

CSU04 – Informar Vencedor:
O sistema verifica o resultado e informa o nome do jogador vencedor ou a vitória do computador.

Regras de Negócio
  As seguintes restrições devem ser observadas no desenvolvimento do sistema:
- O valor escolhido para a aposta deve estar obrigatoriamente entre 2 e 12, pois esta é a faixa de resultados possíveis (soma mínima 1+1=2 e soma máxima 6+6=12).
- É permitido que mais de um jogador escolha o mesmo valor para a aposta, o que pode resultar em divisão do prêmio caso aquele valor seja sorteado.

Diagrama de classes
<img width="942" height="293" alt="image" src="https://github.com/user-attachments/assets/7b05c73c-7848-4b66-873f-f8b45b452a13" />

Diagrama de casos de uso
<img width="705" height="509" alt="image" src="https://github.com/user-attachments/assets/07a1ca4f-82e2-42df-8eef-1b33b1341b76" />


