Análise de Desempenho de Campanhas Publicitárias

Este projeto realiza a análise de dados de campanhas publicitárias com base em um dataset no formato JSON. Ele inclui o cálculo de métricas-chave e a geração de visualizações para auxiliar no monitoramento e na avaliação de campanhas.

Introdução

Este projeto foi desenvolvido para facilitar a análise de campanhas publicitárias, permitindo:

    Identificar métricas de desempenho como CTR (Taxa de Cliques) e CPC (Custo por Clique).
    Monitorar gastos e conversões por campanha.
    Gerar gráficos para avaliar tendências e comportamento das métricas ao longo do tempo.

Funcionalidades

    Carregamento do Dataset:
        Suporta arquivos JSON.
        Trata erros no carregamento e valida o dataset.

    Análise Estatística:
        Exibe estatísticas descritivas para métricas importantes (gastos, cliques, impressões, etc.).
        Verifica valores ausentes e duplicados.

    Cálculo de Métricas de Desempenho:


Exemplo de Visualizações
    1. Gráfico de Linha - Gastos por Mês/Ano
    2. Gráfico de Linha - Impressões por Mês/Ano
        CTR: (Cliques / Impressões) * 100.
        CPC: Gasto Total / Cliques.
        Resumo agrupado por campanha e por período (mês/ano).

    Visualizações:
        Gráficos de linha para gastos totais e impressões por mês/ano.

Pré-requisitos

Certifique-se de que os seguintes itens estão instalados:

    Python 3.7+
    Bibliotecas Python:
        pandas
        matplotlib
    Instale as dependências com:

      pip install pandas matplotlib
