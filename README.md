# Projeto para preparação e análise da base de IPTU

## Análise do cenário imobiliário da cidade de Recife

Para este problema de negócio, o(a) candidato(a) deverá trabalhar com as bases fornecidas e descritas na seção `Dataset` abaixo, realizando os tratamentos que julgar necessários a fim de garantir as respostas às perguntas propostas.

Você é um(a) Analista de Dados na equipe responsável por apresentar um **Panorama geral do inventário imobiliário** da cidade a um grupo de investidores que pode ter múltiplos interesses. Na divisão de tarefas, você ficou responsável por realizar a preparação da base e apresentar algumas premissas básicas:

1. **Volume**: Qual o total de imóveis e como o inventário está distribuído fisicamente (tipo, bairro etc.)?
2. **Idade**: Como o inventário está distribuído em termos de idade de construção?
3. **Valor (R$)**: Quais os bairros com imóveis mais valiosos? Há relação direta entre idade e valor?
4. **Evolução**: Quais bairros apresentam maior evolução em número de imóveis? E em relação a valor?

## Análise do cenário imobiliário da cidade de Recife

Disponibilização de dashboard(painél), em ferramenta a sua escolha (Excel, Power BI, QuickSight, Redash...), que permita:

1. **Visualização**: das análises do item acima
2. **Interatividade**: Possibilidade de filtros simples, destaques etc. que permitam ao usuário focar em determinados pontos nas análises (ex.: por bairro)

## Artefato mínimo esperado ao fim do projeto:

1. Um Jupyter Notebook legível, contendo as etapas de preparação da base.

2. Um dashboard (link compartilhável), em ferramenta a sua escolha, contendo as respostas aos itens acima.

3. Queries e outros materiais de apoio que você considere interessantes para a avaliação.

## Diferenciais

Para este desafio prático, esperamos que todos os materiais entregues sejam legíveis e mantenham um padrão de lógica. Porém, para aumento da sua avaliação, considere as seguintes oportunidades (obs: os itens não estão em ordem de prioridade):
- Layout funcional e com comunicação objetiva
- Uso de ferramentas que permitam automação e escalabilidade de tarefas e processos (ex.: Airflow)
- Análises cruzadas com dados adicionais às bases para melhoria da decisão no contexto do desafio (ex.: dados microeconômicos, dados de portais de anúncios...)

### Datasets
- As bases disponibilizadas são referentes a 05 (cinco) anos de IPTU da cidade de Recife, todas contendo 32 colunas.

- De 2020 a 2023, as bases possuíam um formato e encontram-se na pasta [../iptu_20_23](https://github.com/Neurolake/challenge-data-engineer/tree/main/iptu_20_23)

- No ano de 2024, houve uma mudança no formato do arquivo, que encontra-se na pasta [../iptu_24](https://github.com/Neurolake/challenge-data-engineer/tree/main/iptu_24)
