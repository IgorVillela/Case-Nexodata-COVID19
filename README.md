# Case-Nexodata-COVID19
Case técnico de dados Nexodata - Analista de dados

## Contexto
Neste case fictício, você como o novo Analista de Dados tem uma demanda do time de epidemiologia da Nexodata de entender quais são as regiões pelo Brasil, nas granularidade de Cidade, que apresentaram o maior crescimento na taxa de mortalidade (devido a COVID-19) no primeiro trimestre de 2021 e quais as características em comum dessas cidades que justificam essa taxa de mortalidade crescente que se destaca do restante. O time que trouxe a demanda, é um time técnico em saúde, mas não em dados, então cabe a você pensar em estratégias para trabalhar os dados do dataset disponibilizado afim de solucionar o problema.

## Objetivo
Realizar a análise e manipulação dos datasets (ajustes, limpezas e tratamentos), usar uma plataforma de visualização (Power BI), fazer um relatório simples explicando o raciocínio por trás das decisões tomadas e respondendo as perguntas: Quais as cidades do Brasil que apresentam maior crescimento na taxa de mortalidade? Quais características em comum dessas cidades justificam a taxa de mortalidade crescente que se destaca do restante?

## Etapas do projeto
- 1. Entendimento dos datasets disponibilizados e suas características
- 2. Tratamento dos dados
- 3. Análise exploratória
- 4. Interpretação dos resultados

## Bibliotecas utilizadas
Para abrir os arquivos:
-os
-gzip

Para o tratamento dos dados:
-pandas

## Detalhes importantes
Para o devido funcionamento do script, os datasets devem estar compactados e na mesma pasta em que o script se encontra. Na execução completa do script, será gerado um novo arquivo 'novo_caso_full.csv.gz' que não há necessidade de descompactar.

Para a visualização dos dados no Power BI, você deve ter o Power BI Desktop instalado e depois basta executar o arquivo 'novo_caso_full - Relatório.pbix'. Caso queira manipular a tabela no Power Query Editor, selecione a Query novo_caso_full, vá em Advanced Editor e altere 'File.Contents('[CAMINHO DO ARQUIVO 'novo_caso_full.csv.gz' COMPLETO]')'.
