# Movimento_24Fev2026
Exercício de teste da disciplina de Programação 3:
Pontos Importantes para a Disciplina
Programação para Jogos Digitais III (Unity)

Atividade 1 — Movimentação básica com input
Crie um script que permita mover um GameObject usando as teclas:
W → mover para frente, S → mover para trás, A → mover para esquerda, D → mover para direita

Atividade 2 — Rotação baseada em direção do movimento
GameObject sempre rotacione na direção em que está se movendo.

Atividade 3 — Uso de Rigidbody para movimentação
Adicione Chão À cena e crie um script que mova um GameObject utilizando um componente Rigidbody ao invés de modificar diretamente o Transform.

Atividade 4 — Sistema de pulo
Adicione a funcionalidade de pulo ao GameObject usando a tecla espaço. (Só pode pular se estiver no chão)

Atividade 5 — Sistema de vida com variável
Crie um script que represente a vida de um personagem.
Variável health  iniciando em 100;
Tecla H reduz 10 de vida;
Mostrar no Console o valor atual;
Quando chegar em 0, mostrar "Personagem morreu";

Atividade 6 — Uso de arrays
Crie um array contendo 3 GameObjects. (Ao pressionar a Tecla T, todos os GameObjects rotacionam 45º)

Atividade 7 — Criação de classe 
Crie uma classe chamada "Enemy" com as variáveis: "health", "speed" e "damage";
Deve ter um método TakeDamage(int amount);

Atividade 8 — Comunicação entre Scripts
Player deve causar dano no Enemy ao pressionar tecla K por meio de GetComponent
Enemy deve reduzir a vida e informar de algum modo ao jogador (console, UI, partícula, o que for)
Crie um script C# para Unity com uma classe da vida de um personagem inimigo composto por health iniciando em 100, por speed e por damage igual a 10. Crie outro script para Unity referenciando o anterior com método TakeDamage(int amount) que subtraia damage de health ao pressionar a tecla K por meio do GetComponent;

Atividade 9 - Interface gráfica básica (UI)
Crie um sistema de UI que mostre a vida do jogador usando um Text ou TMP_Text.
