# Análise de Desigualdades no Saneamento Básico no Brasil

Este repositório contém uma análise detalhada das desigualdades no acesso ao saneamento básico entre os municípios brasileiros, com ênfase nas disparidades enfrentadas pela população negra. Utilizando dados do Censo 2022, realizamos um processo completo de Extração, Transformação e Carga (ETL), seguido de testes estatísticos e técnicas de clusterização para identificar padrões e fornecer insights relevantes.

## Objetivo

O principal objetivo deste projeto é identificar e evidenciar as desigualdades no acesso ao saneamento básico, especialmente entre a população negra, e fornecer uma base sólida para a formulação de políticas públicas mais eficazes.

## Metodologia

1. **Coleta de Dados:** Utilizamos dados do Censo 2022, incluindo informações sobre domicílios, população e a malha censitária.

2. **Processo ETL:** Realizamos a extração, transformação e carga dos dados para garantir sua integridade e adequação às análises subsequentes.

3. **Análise Estatística:** Aplicamos testes estatísticos para verificar se há diferenças significativas entre a média de pessoas negras sem acesso ao esgotamento sanitário e a média geral.

4. **Visualização Georreferenciada:** Desenvolvemos mapas interativos que destacam as disparidades no acesso ao saneamento básico, filtrando os indicadores por raça.

5. **Clusterização:** Aplicamos algoritmos de clusterização, como K-means, K-medoids e DBSCAN, para agrupar municípios com perfis de saneamento semelhantes, identificando padrões de desigualdade racial e territorial.

## Resultados

- **Testes Estatísticos:** Os resultados indicaram diferenças significativas entre a média de pessoas negras sem acesso ao esgotamento sanitário e a média geral, evidenciando disparidades raciais no acesso a serviços básicos.

- **Mapas Interativos:** As visualizações georreferenciadas permitiram identificar regiões onde a população negra enfrenta condições mais críticas de saneamento.

- **Clusterização:** A aplicação do algoritmo K-means foi a mais eficaz, agrupando municípios com perfis de saneamento semelhantes e destacando os desafios enfrentados pela população negra.

## Conclusão

Esta análise fornece uma compreensão aprofundada das desigualdades no acesso ao saneamento básico no Brasil, especialmente entre a população negra. Os insights obtidos podem auxiliar na formulação de políticas públicas mais direcionadas e eficazes para mitigar essas disparidades.

## Requisitos

- Python 3.8 ou superior
- Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn, geopandas

## Como Executar

1. **Clone este repositório:**

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git

2. **Navegue até o diretório do projeto:**

   ```bash
     cd seu-repositorio
3. **Instale as dependências:**

   ```bash
     pip install -r requirements.txt


