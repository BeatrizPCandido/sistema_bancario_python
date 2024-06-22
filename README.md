# sistema_bancario_python
sistema_bancario_python



“Este é um sistema simples que simula um ambiente bancário para saque, extrato e depósito, criado em Python. No entanto, não possui um sistema de autenticação de segurança.” 


**Detalhes** 


**1. Menu e Variáveis Iniciais:**
   
O código começa definindo um menu de opções (depósito, saque, extrato e sair) e inicializando algumas variáveis:

**saldo**: Armazena o saldo atual da conta (inicializado como zero).

**limite**: Define o limite máximo para saques (inicializado como 500).

**extrato**: Lista vazia para registrar as transações.

**numero_saques**: Contador para controlar o número de saques realizados.

**LIMITE_SAQUES**: Constante que define o limite diário de saques (inicializado como 3).

**2. Depósito:**
   
Se o usuário escolhe a opção **“d” (depósito)**, o código solicita o valor do depósito, atualiza o saldo e registra a transação no extrato.

**3. Saque:**
Se o usuário escolhe a opção **“s” (saque)**, o código verifica se o número de saques ainda está dentro do limite diário.

Em seguida, verifica se o saldo é suficiente para o saque desejado.

Se o saque for válido, o código subtrai o valor do saldo, incrementa o contador de saques e registra a transação no extrato.

**4. Extrato:**
Se o usuário escolhe a opção **“e” (extrato)**, o código exibe o histórico de transações (se houver) e o saldo atual.

**5. Sair:**
Se o usuário escolhe a opção **“q” (sair)**, o loop é interrompido e o programa encerra.

6. Validação de Opções Inválidas:

Se o usuário digita uma opção inválida, o código exibe uma mensagem de erro.
