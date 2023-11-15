Uma forma mais detalhada para explicar o fluxograma:

1 - Ingresso Disponível?
  - O usuário acessa o site.
  - O sistema verifica se há ingressos disponíveis.
    - Se não houver ingressos disponíveis:
      - O usuário recebe uma mensagem informando que os ingressos estão esgotados.
      - Fim do processo.
      - 
2 - Entrar na Fila Virtual:
 - Se houver ingressos disponíveis, o usuário entra na fila virtual.
 - A fila é gerenciada por ordem de chegada.
   
3 - Acesso Gradual:
 - O sistema controla o número de usuários que podem acessar simultaneamente.
 - O acesso é concedido gradualmente para evitar sobrecarga.
   
4 - Reserva Temporária:
 - Ao adicionar um ingresso ao carrinho, o sistema faz uma reserva temporária.
 - O usuário tem um tempo limitado para concluir a compra.

5 - Verificação de Disponibilidade:
 - Antes de finalizar a compra, o sistema verifica novamente a disponibilidade de ingressos.
   - Se não houver ingressos disponíveis:
    - A reserva temporária é liberada.
    - O usuário recebe uma mensagem informando que os ingressos estão esgotados.
    - Fim do processo.

6 - Conclusão da Compra:
 - Se houver ingressos disponíveis, o usuário conclui a compra.
 - O sistema confirma a transação e reserva definitivamente os ingressos.
   
7 - Mensagens Informativas:
 - Durante todo o processo, mensagens claras e informativas são exibidas ao usuário para indicar o status da fila, o número de ingressos restantes e outras instruções relevantes.
   
8 - Testes de Estresse Prévios:
 - Antes do evento, o sistema passa por testes de estresse para garantir que pode lidar com o tráfego intenso de usuários.
