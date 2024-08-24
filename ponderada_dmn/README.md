# Atividade ponderada: Modelagem de decisão com DMN

### Enunciado

A linguagem DMN trata da possibilidade de representação de tomadas de decisão em processos. Muitas vezes, as tomadas de decisão devem levar em consideração regras de negócio. Por isso, é comum usar tabelas de decisão como um dos elementos desse modelo.

1. Elabore 5 regras de decisão do negócio da empresa do projeto que você está fazendo em linguagem natural (lembre-se de seguir um padrão de linguagem).

2. Crie um modelo em DMN para uma situação de decisão no processo que seu grupo modelou no projeto no qual um ou mais dessas regras esteja envolvida.

## Regras de negócio

Para esta atividade, defini as seguintes regras de negócio:

| Nº    | Descrição                                    | Critérios de Aplicação                                       | Ações                           | Responsável           |
|-------|----------------------------------------------|--------------------------------------------------------------|---------------------------------|-----------------------|
| FI001 | Requisição de um relatório financeiro         | As transações realizadas precisam estar armazenadas para a consulta | Enviar o relatório              | Departamento financeiro|
| FI002 | Solicitação de saída de caixa                 | A área solicitante precisa ter um orçamento disponível        | Liberar a saída de caixa         | Departamento financeiro|
| FI003 | Registro de transações de entrada no caixa    | Transações de entrada confirmadas e ocorridas                | Atualizar o saldo do caixa       | Departamento financeiro|
| FI004 | Previsão de transações de entrada             | Transações de entrada ainda não confirmadas                  | Adicionar a previsão ao caixa    | Departamento financeiro|
| FI005 | Notificação contábil após transação de entrada| Após a atualização do saldo com a entrada                    | Notificar a equipe de contabilidade | Departamento financeiro|

## Modelo DMN

Criei cinco modelos DMN, cada um para cada regra de negócio, para representar as decisões envolvidas no processo modelado nesta atividade.

### Tabelas de decisão DMN

As regras de decisão de cada um dos modelos DMN são as seguintes:

- **FI001**: Relatório financeiro - Enviar o relatório financeiro se as transações realizadas estiverem armazenadas;
- **FI002**: Verificação de orçamento para saída de caixa - Liberar a saída de caixa se a área solicitante tiver orçamento disponível;
- **FI003**: Registro de transação de entrada confirmada - Atualizar o saldo do caixa para transações de entrada confirmadas;
- **FI004**: Registro de previsão de entrada - Adicionar a previsão ao caixa para transações de entrada não confirmadas;
- **FI005**: Notificação contábil após transação de entrada - Notificar a equipe de contabilidade após a atualização do saldo com entrada confirmada.

## Instruções para execução

1. Os arquivos estão na página "diagrams";
2. Abra os arquivos DMN no Camunda Modeler;
3. Examine as regras de decisão e os critérios de aplicação;
4. Verifique se as decisões modeladas estão de acordo com o processo descrito na atividade.


