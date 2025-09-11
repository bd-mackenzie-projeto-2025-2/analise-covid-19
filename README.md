# 📊 Análise COVID-19  

Este repositório contém bases de dados públicas da Organização Mundial da Saúde (OMS / WHO) sobre a pandemia de COVID-19. Os arquivos disponíveis incluem informações sobre casos, mortes, hospitalizações, admissões em UTI e vacinação. O objetivo é facilitar análises exploratórias, estudos de políticas de vacinação, impactos por faixa etária e acompanhamento de tendências globais.  

Na pasta **data/** estão incluídos os seguintes arquivos:  

- **WHO-COVID-19-global-data.csv**: base semanal com casos e mortes de COVID-19 reportados por data. É atualizada semanalmente e pode incluir correções retrospectivas.  
- **WHO-COVID-19-global-monthly-death-by-age-data.csv**: base mensal com mortes por COVID-19 detalhadas por faixa etária. Pode não cobrir todos os países e os totais por idade podem diferir dos totais gerais.  
- **WHO-COVID-19-global-hosp-icu-data.csv**: base semanal com hospitalizações e admissões em UTI por COVID-19. Também é atualizada semanalmente e inclui correções retrospectivas.  
- **COV_VAC_UPTAKE_2024.csv**: base trimestral com dados de vacinação em 2024, detalhados por grupos-alvo (profissionais de saúde, idosos, gestantes etc.) e por sexo. Os dados vão até o terceiro trimestre de 2024 e a frequência e completude variam por país.  
- **COV_VAC_POLICY_2024.csv**: base trimestral com informações sobre políticas de vacinação em 2024, por país e grupos-alvo. Assim como a anterior, cobre até o terceiro trimestre de 2024, com frequência e completude variáveis por país.  
- **COV_VAC_UPTAKE_2021_2023.csv**: base mensal arquivada com dados de vacinação total por país entre janeiro de 2021 e dezembro de 2023. Não é mais atualizada.  
- **COV_VAC_PROD.csv**: base arquivada com informações sobre a introdução inicial de produtos de vacina por país, cobrindo o período de novembro de 2020 a fevereiro de 2022. Não é mais atualizada.  

Esses conjuntos de dados permitem análises como evolução global de casos e mortes, impacto da vacinação em diferentes grupos populacionais, comparação de políticas de vacinação entre países, distribuição etária das mortes ao longo da pandemia e relação entre hospitalizações/UTI e políticas públicas de saúde.  

Todos os dados foram obtidos diretamente da **OMS (WHO)** e estão disponíveis no [painel oficial da COVID-19](https://data.who.int/dashboards/covid19/data).  

Para começar a usar, basta clonar o repositório, acessar a pasta `data/` e carregar os arquivos no Python, R ou Excel para realizar suas próprias análises.  
