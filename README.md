# MAI5017-Visualização da Informação

# Estudo de Audiência Compartilhada no YouTube

Repositório do projeto desenvolvido para a disciplina **MAI5017 — Visualização da Informação**, do ICMC-USP, com foco na análise de sobreposição de audiência entre canais brasileiros de jornalismo no YouTube.

O estudo utiliza dados públicos de transmissões ao vivo e de chats do YouTube para investigar padrões de engajamento, recorrência, circulação de público, vocabulário, temas, emoções e relações entre canais.

## Acesso ao site

A versão publicada do projeto pode ser acessada em:

**https://wsoaresjr.github.io/MAI5017-Visualizacao-da-Informacao/**

## Sobre o projeto

A proposta do projeto é investigar uma camada pouco explorada da audiência no YouTube: o **chat ao vivo**. Diferentemente de métricas tradicionais como visualizações, inscritos e tempo de exibição, o chat permite observar sinais públicos de participação ativa, identificando usuários que interagem em uma ou mais transmissões.

A análise parte da seguinte questão central:

> Como os usuários que participam dos chats ao vivo se distribuem entre canais brasileiros de jornalismo, e em que medida existe audiência ativa compartilhada entre eles?

O recorte analisado considera transmissões públicas realizadas entre **20/05/2026 e 20/06/2026**, contemplando **12 canais monitorados**, **2.133 transmissões**, aproximadamente **1,86 milhão de mensagens de chat** e cerca de **99 mil autores únicos**.

## Canais monitorados

* CNN Brasil
* Jovem Pan News
* SBT News
* Band Jornalismo
* TV Cultura
* TV 247
* UOL
* Metrópoles TV
* ICL Notícias
* Gazeta do Povo
* Revista Oeste
* Poder360

## Estrutura analítica

O projeto foi organizado em três eixos, alinhados aos conteúdos da disciplina.

### Eixo A — Visualização de Dados Multivariados

Investiga diferenças e semelhanças entre canais a partir de múltiplas métricas de audiência e engajamento.

Visualizações incluídas:

* Scatter plot: participantes únicos × volume de chat
* Heatmap z-score por canal
* Coordenadas paralelas
* PCA para agrupamento multivariado

### Eixo B — Visualização de Documentos e Textos

Analisa o conteúdo discursivo dos chats e das transcrições das lives, buscando padrões temáticos, vocabulário recorrente e sinais emocionais.

Visualizações incluídas:

* Nuvem de palavras por canal
* Heatmap temático
* Timeline de termos
* t-SNE de tópicos das lives
* Comparação fala × chat
* Distribuição de emojis

### Eixo C — Visualização de Árvores e Grafos

Mapeia a sobreposição de audiência ativa entre canais, considerando usuários que comentaram em mais de um canal.

Visualizações incluídas:

* Matriz de similaridade Jaccard
* Grafo de sobreposição
* Diagrama de cordas
* Sankey de migração de público
* Dendrograma hierárquico

## Insights exploratórios adicionais

Além dos três eixos principais, o site também apresenta visualizações complementares geradas a partir das análises exploratórias dos notebooks, incluindo:

* Curva média de audiência simultânea
* Relação entre audiência e engajamento
* Heatmap de lives por dia e horário
* Super Chats por canal
* Retenção intra-live
* Episódios de spam ou raids
* Sentimento do chat
* Evolução temática semanal
* Matriz absoluta de autores compartilhados
* Correlação entre likes e pico de audiência
* Funil de engajamento
* Distribuição de duração das lives

## Principais conclusões

O projeto evidencia quatro achados principais:

1. **Audiências majoritariamente segmentadas**
   A maior parte dos pares de canais apresenta baixa sobreposição de público ativo.

2. **Circulação relevante entre canais**
   Embora a audiência seja segmentada, uma parcela dos autores comenta em mais de um canal, indicando circulação cross-editorial.

3. **Perfis multivariados distintos**
   Os canais apresentam diferentes combinações de alcance, engajamento, recorrência, volume de chat e intensidade temporal.

4. **Assinaturas temáticas e emocionais**
   O vocabulário, os temas e os emojis revelam diferenças relevantes entre comunidades de chat.

## Estrutura do repositório

```text
MAI5017-Visualizacao-da-Informacao/
├── index.html
├── README.md
├── Base_Dados/
│   └── Link_Base_de_Dados.txt
├── apresentacao/
│   └── Apresentacao.pdf
├── artigo/
│   └── Artigo.pdf
├── graficos/
│   ├── eixo_a/
│   ├── eixo_b/
│   ├── eixo_c/
│   ├── exploratoria/
│   └── fotos/
└── jupyter-notebooks/
    ├── analise_lives_youtube_n1.ipynb
    ├── analise_lives_youtube_n2.ipynb
    └── analise_lives_youtube_n3.ipynb
```

## Tecnologias utilizadas

O site é estático e foi construído com:

* HTML5
* CSS3
* JavaScript
* GitHub Pages

As visualizações foram exportadas como imagens PNG a partir de análises realizadas com ferramentas como:

* Python
* Pandas
* Plotly
* Matplotlib
* NetworkX
* scikit-learn
* WordCloud


## Privacidade e ética

O estudo considera apenas dados públicos disponíveis em transmissões e chats do YouTube. Os identificadores reais dos usuários não são apresentados publicamente. A proposta do projeto é analisar padrões agregados de audiência, circulação e engajamento, preservando a identidade individual dos participantes.

## Equipe

* Janderson Pereira
* Walter Soares A. Junior
* Junior Fernandes Marques

Disciplina: **MAI5017 — Visualização da Informação**
Professor: **Afonso Paiva Neto**
Instituição: **USP-ICMC-MECAI**
Ano: **2026**

## Licença

Este repositório foi desenvolvido para fins acadêmicos. Caso deseje reutilizar o conteúdo, os gráficos ou a metodologia, recomenda-se citar o projeto e seus autores.

