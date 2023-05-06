## Atividade Regressão Linear

Crie um notebook no serviço em nuvem Google Colaboratory para reproduzir o exemplo apresentado em sala de aula e, em seguida, responda:

a) Trata-se de um tipo de regressão logística binominal ou multinomial? Por quê?

Resp.: **É binomial**. Pois possuimos apenas 2 classes para predizer os valores: `mnist.data` e `mnist.target`; conforme visto no `train_test_split` (que eu coloquei como *tts*)

b) Repita as etapas de treino e testes modificando o algoritmo de otimização para: ‘liblinear’, ‘newton-cg’, ‘newton-cholesky’, ‘sag’, ‘saga’. Houve alguma diferença nos resultados?

Resp.: Pelo código abaixo, podemos conferir as alterações ocorridas ao substituir o otimizador (Farei uma tabela para comparar os resultados)

| Otimizador | Score Treino | Score Teste |
|------------|--------------|-------------|
| lbfgs | 0.9362 | 0.9186 |
| liblinear | - | - |
| newton-cg | - | - |
| newton-cholesky | 0.9356 | 0.9093 |
| sag | 0.9421 | 0.9151 |
| saga | 0.9412 | 0.9159 |

Sim, pode-se notar uma leve diferença nos dados de Treino e Teste (dependendo do otmizador)
