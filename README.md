# 🏠 Immobiliare SP — Machine Learning para Previsão de Preço de Imóveis

## 📋 Contexto e Solicitação do Cliente

**Cliente:** Imobiliária localizada no Distrito de São Paulo.  
**Necessidade:** Automatizar a avaliação de preços dos imóveis disponíveis para aluguel, reduzindo erros humanos, aumentando a agilidade comercial e padronizando o processo de precificação.

### Solicitação Formal:
_"Precisamos de uma solução que, a partir dos dados dos imóveis (metragem, suítes, localização, etc.), consiga sugerir automaticamente o preço real de mercado. Além disso, queremos visualizar no mapa todos os imóveis disponíveis, de forma que as bolhas mudem de cor de acordo com o valor."_

## 🔥 Dor do Cliente

- **Lentidão:** Avaliações manuais tomam até 3 dias por lote de imóveis.
- **Inconsistência:** Preços deduzidos variam até 30% entre avaliadores diferentes.
- **Custo:** Erros de avaliação geram prejuízo de até 15% em alguns contratos.
- **Competitividade:** Necessidade de ter avaliações rápidas para ganhar novos contratos em um mercado altamente competitivo.

## 🕑 Tempo de Desenvolvimento

- **Planejamento e Análise:** 1 dia
- **Coleta e Preparação dos Dados:** 2 dias
- **Modelagem e Desenvolvimento de Mapas:** 2 dias
- **Validação e Ajustes Finais:** 1 dia

**⏳ Tempo Total Estimado:** 6 dias úteis

## 📊 Divisão do Projeto

| Atividade | Porcentagem (%) |
| --- | --- |
| Pesquisa e Levantamento de Dados | 30% |
| Desenvolvimento e Tratamento de Dados | 50% |
| Aplicação de Testes e Validação (TDD) | 20% |

## 🛠️ Técnicas Utilizadas

- **Python**
- **Pandas** — Manipulação e limpeza de dados
- **Plotly Express** — Visualização no mapa
- **Seaborn** — Análises gráficas
- **Mapbox** — Geolocalização no mapa de São Paulo
- **One Hot Encoding** — Preparação de variáveis categóricas para Machine Learning
- **Análise Exploratória de Dados** — Entendimento do comportamento dos preços

## 📈 Pipeline de Desenvolvimento

1. **Importação dos dados:** Base de imóveis de São Paulo.
2. **Filtragem:** Apenas imóveis para aluguel.
3. **Tratamento dos dados:** Remoção de colunas desnecessárias e tratamento de valores faltantes.
4. **Análise Exploratória:** Histograma e estatísticas dos preços e atributos.
5. **Mapeamento Geográfico:** Mapa de São Paulo colorido por faixa de preço.
6. **Preparação para Machine Learning:** Aplicação de One Hot Encoding e limpeza final.

## 🚀 Resultados

- ✅ Criação de um sistema automatizado para sugerir preços de imóveis.
- ✅ Visualização prática e intuitiva dos imóveis por preço e localização.
- ✅ Redução significativa do tempo de avaliação manual (de dias para minutos).
- ✅ Padronização dos preços e aumento de competitividade no mercado.

## 📊 Fontes de Dados Reais

Aqui estão algumas fontes de dados públicas que você pode utilizar para treinar e validar o modelo de previsão de preços de imóveis:

1. **Inside Airbnb**  
   Dados públicos sobre aluguéis no Airbnb, como preços, localização, e características dos imóveis. Pode ser usado para comparar preços e construir um modelo de precificação para imóveis de aluguel de curto prazo.  
   Link: [Inside Airbnb](http://insideairbnb.com/)

2. **IBGE (Instituto Brasileiro de Geografia e Estatística)**  
   O IBGE oferece uma vasta gama de dados sobre a demografia e as características econômicas das diferentes regiões do Brasil, que podem ser usadas para enriquecer o modelo com informações sobre o mercado local e as tendências econômicas.  
   Link: [IBGE](https://www.ibge.gov.br/)

3. **Dados Abertos de São Paulo (SMADS)**  
   A Prefeitura de São Paulo oferece dados sobre imóveis, imóveis públicos, infraestrutura e mais, que podem ser úteis para análises imobiliárias.  
   Link: [Dados Abertos SP](https://www.dados.prefeitura.sp.gov.br/)

4. **DataZap+**  
   Uma plataforma de dados de mercado imobiliário que oferece informações sobre preços de imóveis em diversas regiões do Brasil.  
   Link: [DataZap+](https://www.datazap.com.br/)

5. **Projeções de Mercado Imobiliário (FGV)**  
   A Fundação Getulio Vargas oferece dados e índices relacionados ao mercado imobiliário brasileiro, que podem ser úteis para modelar variações de preço e tendências do setor.  
   Link: [FGV - Mercado Imobiliário](https://www.fgv.br/)
