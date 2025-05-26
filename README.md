# Customer Sentiment Analysis

## Objetivo

O objetivo principal deste projeto é analisar o sentimento de tweets de clientes em relação a empresas, usando um modelo de machine learning para rotular um grande conjunto de dados e identificar padrões de sentimento ao longo do tempo e entre diferentes empresas.

## Sobre os Dados

O [dataset](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter) que vamos usar possui tweets de suporte ao cliente, mostrando os tweets dos clientes e as respostas da empresa, porém, vamos trabalhar apenas com os tweets do clientes.

## Road Map

<ul>
    <li>Visão geral do projeto</li>
    <li>Importando pacotes iniciais e Datasets</li>
    <li>Transformação dos Dados
        <ul>
            <li>Criando a coluna <code>empresa_id</code></li>
            <li>Excluindo registros com poucos exemplos</li>
            <li>Coluna <code>created_at</code></li>
            <li>Selecionando apenas textos em inglês</li>
        </ul>
    </li>
    <li>Pré-processamento
        <ul>
            <li>Substituir menções de usuários</li>
            <li>Conversão de emoticons e emojis em texto</li>
            <li>Normalização</li>
            <li>Preservando negações</li>
            <li>Removendo URLs e números isolados</li>
            <li>Removendo palavras maiores que 45 letras</li>
            <li>O que mais foi testado:
            <li>Tokenização | POS Tagging | Stopwords</li>
            <li>Lemmatização</li>
            </li>
        </ul>
    </li>
    <li>Modelagem
        <ul>
            <li>Score de Sentimento</li>
            <li>Otimização</li>
        </ul>
    </li>
    <li>Rotulando os tweets</li>
    <li>Análise
        <ul>
            <li>Empresas</li>
                <ul>
                  <li>Top 10 empresas piores e melhores avaliadas</li>
                </ul>
            <li>Dias da semana</li>
            <li>Dias do mês</li>
            <li>Horários</li>
        </ul>
    </li>
</ul>

## Referências

- [Dataset](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter)
- [Data Science Academy](https://www.datascienceacademy.com.br/)
- [Analytics Vidya](https://www.analyticsvidhya.com/blog/2021/06/rule-based-sentiment-analysis-in-python/)
