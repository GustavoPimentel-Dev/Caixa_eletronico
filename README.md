Simulador de Caixa Eletrônico (ATM) 🏦

Este é um projeto simples desenvolvido em linguagem C que simula o funcionamento básico de um caixa eletrônico (ATM). O programa permite aos usuários consultar o saldo e realizar saques, calculando automaticamente a menor quantidade de notas a serem entregues.

🛠️ Funcionalidades

O sistema apresenta um menu interativo com as seguintes opções:

Consultar Saldo: Exibe o saldo atual da conta (o saldo inicial é predefinido em R$ 10.000 para fins de teste).

Sacar Dinheiro:

Permite saques apenas em valores múltiplos de R$ 5.

Valida se o valor solicitado é maior que zero e se há saldo suficiente na conta.

Calcula e exibe a quantidade exata de cédulas entregues, priorizando notas de maior valor (R$ 100, R$ 50, R$ 20, R$ 10 e R$ 5).

Sair: Encerra a execução do programa.

💻 Como executar o projeto

Pré-requisitos

Para compilar e executar este projeto, você precisará de um compilador C instalado na sua máquina (como o gcc).

Passo a passo

Faça o clone deste repositório ou baixe o arquivo Caixa_eletronico_Final.c.

Abra o terminal e navegue até o diretório onde o arquivo está salvo.

Compile o código usando o gcc com o seguinte comando:

gcc Caixa_eletronico_Final.c -o caixa_eletronico


Execute o programa recém-compilado:

No Linux/macOS:

./caixa_eletronico


No Windows:

caixa_eletronico.exe


📝 Estrutura do Código

O código utiliza estruturas de repetição (do-while) para manter o menu ativo, estruturas de decisão (switch-case, if-else) para gerenciar as opções e validações, e operadores matemáticos (como divisão e módulo %) para calcular a distribuição das notas no saque.

Desenvolvido como projeto de estudo em programação C.# Caixa_eletronico
Projeto de criação de um sistema basíco de caixa eletrônico
