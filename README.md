# ibm-challenge
# Teste para Desenvolvedor

Você deve criar uma API de Caixa ATM, onde deve ser possível executar
operações de saque, depósito, transferência e produzir um relatório de fechamento, 
além de operações e controles que forem necessários.

* Para as operações estarem disponiveis, o caixa deve estar aberto, ou seja, deve ser previsto operações de abertura e fechamento de caixa.

### SAQUE
 - Para o saque, devem ser informados os dados necessários para a operação, e retornar as cédulas que serão retiradas do caixa, além de dados complementares se necessário.
 
### DEPÓSITO
 - Para o depósito, devem ser informados os dados necessários para a operação, além do tipo de depósito(DINHEIRO, CHEQUE) e retornar os dados necessários para o comprovante.

### TRANSFERÊNCIA
 - Para operações de transferência, devem ser informados os dados necessários para a operação das contas origem e destino, com cenários de validação de saldo e possibilidade de agendamento.
 
## Como entregar estes desafios
Você deve forkar este projeto e fazer o *push* no seu próprio repositório e enviar o link para _taisfg@br.ibm.com_ ou para o email do recrutador, junto com seu LinkedIn atualizado.

A implementação deve ficar na pasta correspondente ao desafio. Fique à vontade para adicionar qualquer tipo de conteúdo que julgue útil ao projeto, alterar/acrescentar um README com instruções de como executá-lo, etc.

## Critérios de Avaliação
- Clean Code
- Simplicity
- Logic
- SOC (Separation of Concerns)
- Flexibility/Extensibility
- Scalability/Performance
  
**Obs.**:
- Você não deve fazer um Pull Request para este projeto!
- Para este projeto, deve ser utilizado linguagem Java em versões 8+.

## Diferencial
- Regras de sugestão de cédulas para melhor distribuição e disponibilidade no caixa.
- Banco de dados, contendo dados de contas corrente e informações de cada operação realizada.
- Docker

### Extras

- Descreva o processo de resolução dos desafios;
- Descreva como utilizar a sua solução;
- Tratamento de erros e exceções. Fica a seu critério quais casos deseja tratar e como serão tratados;

