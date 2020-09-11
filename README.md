# Processo de seleção de estágio no Laboratório de Computação Científica
# Descrição da tarefa
Dois arquivos (base_ecg.csv e labels_ecg.csv); o primeiro é uma base de dados com 1000 sinais de eletrocardiograma (ECG) e o segundo representa a classe correta a qual o sinal foi atribuído (1, 2, 3, 4, ..., 17). Note que, base_ecg possui uma matriz de 1000x1025 e labels_ecg possui um vetor de 1000x1, de forma que haja correspondência, isto é, o sinal da primeira linha de base_ecg tem como classe a primeira linha de labels_ecg, o sinal da segunda linha de base_ecg tem como classe a segunda linha de labels_ecg, e assim por diante. A base de dados deve ser fracionada em 70% (treino) e 30% (teste) para experimentos com algoritmos de classificação de forma a obter as acurácias de treino e teste.

A atividade prática consiste em classificar os conjuntos de treino e teste com a maior acurácia que conseguirem obter. O envio deve ser realizado para o e-mail do LCC (lcc@unifesspa.edu.br), com o título "Edital 02/2020 - Etapa 2 - Resposta", contendo os seguintes anexos:

- Código utilizados para solução da atividade, com arquivo readme de como executá-los;
- Breve relatório contendo a metodologia aplicada para solução e os resultados obtidos (máximo 2 páginas).

Podem ser usados diferentes classificadores aliados a geradores de novos exemplos/sinais (esses últimos se julgarem necessários por conta do desbalanceamento da base de dados). O prazo para entrega é até às 19h do dia de hoje (20/04/2020).

Para mais informações, verificar o artigo em anexo a este e-mail.
