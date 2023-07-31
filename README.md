# Algoritmo do Banqueiro

Esta é uma implementação em Python do Algoritmo do Banqueiro ("Banker's Algorithm"), um algoritmo de prevenção de deadlocks usado em sistemas operacionais para gerenciar recursos de forma eficiente e evitar situações de deadlock.

## Utilização

1. Clone o repositório ou baixe os arquivos `banker.py` e `main.py` para o seu computador.

2. Certifique-se de que você tenha o Python 3 instalado em seu sistema.

3. Para executar o Algoritmo do Banqueiro, execute o script `main.py`:

   ```bash
   python main.py
   ```

4. O script solicitará que você insira o número de processos e o número de tipos de recursos necessários para cada processo. Em seguida, ele solicitará os dados de alocação de recursos e requisitos.

5. O script executará os cálculos do Algoritmo do Banqueiro e exibirá o estado do sistema, incluindo os recursos alocados, recursos disponíveis, recursos necessários e o status de cada processo (se está em execução ou não).

6. O algoritmo determinará se o sistema está em um estado seguro e se todos os processos serão concluídos sem causar um deadlock. Se o sistema estiver em um estado seguro, será exibida a mensagem de que os processos não entrarão em um deadlock. Caso contrário, será informado que os processos entrarão em um deadlock.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.

A Licença MIT (MIT) é uma licença de código aberto permissiva que permite usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias do software. Ela proporciona a liberdade de usar o software para qualquer finalidade, sujeito às condições e limitações da licença.