# Desafio_Bix

O desafio Bix consiste de uma das etapas para a admissão como cientisa de dados da empresa [Bix Tecnologia](https://www.linkedin.com/company/bixtecnologia/).
Nela é apresentado um problema, nesse caso como reduzir o custo de manutenção de uma empresa que possui uma frota de caminhões, e vê seu custo aumentar anualmente.
Para a solução do problema utilizei o algorítimo XGBoost variando o threshold de escolha de classe, para chegar a um custo mínimo.

### Scripts

Esse repositório conta com 3 Scripts.

1)Main: Conta com o programa principal para realizar as predições. Realiza a limpeza de dados; encontra o threshold ótimo a partir dos dados de treino; realiza predições nos dados de teste utilizando threshold ótimo de treino; encontra threshold ótimo real para os dados de teste e valor mínimo possível utilizando o método; plota as 10 features mais importantes e a distribuição das 5 mais importantes; plota as features que não foram utilizadas pelo modelo.

2)Plots: Possui os plots utilizados para a confecção dos slides; as funções utilizadas para plotar feature importance e as que não foram utilizadas pelo modelo.

3)Functions: A implementação de todas as funções utilizadas no script principal, da limpeza de dados a implementação do modelo.






