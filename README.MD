# Guia do Projeto 
## Estrutura final do PDF
### EDA e Relatório de análise estatística em **1 arquivo**

- Introducão ao EDA / 0-1 PAG
- Eda / 3-4 pags
- Relatório de Análises estatísticas / 3-4 pags
- Modelo de previsão / 6-8 pags
- conclusao / 1-2 pags

### Responder as perguntas durante o processo de análise estatística
- [X] Qual filme você recomendaria para uma pessoa que você não conhece? CONCLUSÃO
- [X] Quais são os principais fatores que estão relacionados com alta expectativa de faturamento de um filme?


### Responder a Pergunta no Modelo de Previsão
- [X] Qual tipo de problema estamos resolvendo (regressão, classificação)? 
- [X] Qual medida de performance do modelo foi escolhida e por quê?
- [X] Quais insights podem ser tirados com a coluna Overview?, É possível inferir o gênero do filme a partir dessa coluna?
- [X] Qual modelo melhor se aproxima dos dados e quais seus prós e contras? 
- Teste para o modelo:
Supondo um filme com as seguintes características:

{
    'Series_Title': 'The Shawshank Redemption',
    'Released_Year': '1994',
    'Certificate': 'A',
    'Runtime': '142 min',
    'Genre': 'Drama',
    'Overview': 'Two imprisoned men bond over a number of years, finding solace and eventual redemption through acts of common decency.',
    'Meta_score': 80.0,
    'Director': 'Frank Darabont',
    'Star1': 'Tim Robbins',
    'Star2': 'Morgan Freeman',
    'Star3': 'Bob Gunton',
    'Star4': 'William Sadler',
    'No_of_Votes': 2343110,
    'Gross': '28,341,469'
 }

- Qual seria a nota do IMDB?

### Responder as perguntas durante a Conclusão
- [ ] Explique como você faria a previsão da nota do imdb a partir dos dados.

## Montar requirements.txt
### pip freeze > requirements.txt
- LEMBRA DE ESTAR NO .VENV PARA EXECUTAR O COMANDO

## Montar README.md COMPLETO
### Teste 10+ vezes antes de enviar

# ENTREGAR

## Fontes Usadas
- [Template EDA](https://www.kaggle.com/code/bextuychiev/my-6-part-powerful-eda-template)

- [Template Modelo Previsão](https://www.kaggle.com/code/evilspirit05/predictive-modeling-with-scikit-learn/notebook)

- Documentations - Seaborn, scikit-learn, matplotlib.... - for coding Help
- ChatGPT and Claude for auxiliate in thinking and coding-analysis
- Gemini and Perplexity for aux in data and search 