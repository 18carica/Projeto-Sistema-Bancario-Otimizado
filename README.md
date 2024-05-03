# Projeto-Sistema-Bancario-Otimizado

Para otimizar o Sistema Bancário, o código foi refatorado para separar as operações em funções específicas, tornando o código mais modular e reutilizável. As principais mudanças incluem:

  1. Divisão em Funções Específicas: As operações principais, como depósito, saque e exibição do extrato, foram separadas em funções individuais, como depositar, sacar e exibir_extrato, respectivamente. Isso facilita a compreensão do código e permite reutilizar essas operações em diferentes partes do programa.
  2. Uso de Parâmetros Nomeados: Em vez de passar uma série de argumentos posicionais para as funções, as operações de saque e depósito agora aceitam um único dicionário de parâmetros nomeados. Isso torna mais claro quais são os parâmetros esperados e simplifica a chamada das funções.
  3. Melhorias no Tratamento de Exceções: Foram adicionados blocos try-except para lidar com exceções de entrada do usuário ao solicitar valores numéricos para depósito e saque. Isso melhora a robustez do programa, evitando falhas inesperadas devido a entradas inválidas.
  4. Melhor Feedback para o Usuário: Mensagens de feedback foram aprimoradas para fornecer informações mais úteis ao usuário, como notificar sobre operações bem-sucedidas ou fornecer orientações sobre como corrigir entradas inválidas.
  5. Otimização do Fluxo de Controle: O menu principal foi ajustado para permitir que o usuário veja as opções novamente após realizar uma operação, melhorando a experiência geral do usuário e facilitando o uso do sistema.

Essas mudanças tornam o Sistema Bancário mais organizado, fácil de entender e mais robusto, contribuindo para uma melhor experiência de desenvolvimento e manutenção.
