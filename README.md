# Previsão Score de Crédito

Esse estudo tem como objetivo prever score de crédito de clientes a partir de informações fornecidas por eles, como profissão, renda mensal, tempo de relacionamento e dívidas.

Um score "Poor" significa que o cliente tem baixas chances de pagar um empréstimo alto ou uma fatura alta. Já o score "Standard" esse risco é menor, e esses clientes podem ter um limite maior, porém ainda conservador. Já os clientes com score "Good", o banco pode ser mais arrojado, pois eles tem condições de arcar com maiores valores. 

Linguagem utilizada: Phyton
Bibliotecas utilizadas: Pandas e Scikitlearn

Para resolver esse desafio, foi utilizada uma base com dados de 100 mil clientes com score de crédito previamente definido. 

Desses 100 mil, 70 mil observações foram usados para treinar dois modelos - Random Forest e KNN.

Depois, 30 mil foram usados para testar os modelos e definir qual é mais preciso para essa aplicação. 

Com 82,4% de acurácia, o modelo mais efetivo é o Random Forest (Árvore de Decisão).

Com o modelo treinado e validado, foi feita a previsão de score de crédito de 3 clientes - sendo útil para definir quanto o cliente pode pegar em empréstimo e ter de limite de cartão.
