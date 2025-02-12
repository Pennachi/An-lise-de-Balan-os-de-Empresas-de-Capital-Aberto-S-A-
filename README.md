# Automação de Processamento de Balanços Financeiros de Empresas de Capital Aberto

## Descrição do Projeto

Este projeto tem como objetivo automatizar a obtenção e o processamento dos balanços financeiros de empresas de capital aberto (S/A), permitindo uma análise eficiente do progresso financeiro das empresas e a atribuição de uma nota de risco. A automação visa otimizar a tomada de decisão com base em dados financeiros.

## Minha Função no Projeto

Atuei na extração, tratamento e análise dos balanços financeiros, automatizando o processo desde o download dos arquivos até a geração dos dashboards interativos. Um dos principais desafios foi identificar o nível de progresso das empresas e desenvolver um modelo de nota de risco, permitindo uma classificação precisa das condições financeiras.

## Ferramentas e Tecnologias Utilizadas

- **Power BI**: Para visualização e análise interativa dos balanços financeiros.
- **Python**: Para automação da obtenção, tratamento e organização dos dados.
- **Excel**: Para organização e verificação dos balanços processados.

## Processo de Desenvolvimento

### 1º Passo - Obtenção Automática dos Balanços
Desenvolvi um código em Python para baixar automaticamente cerca de 700 balanços financeiros diretamente da fonte, eliminando a necessidade de downloads manuais.

![Python_Passo1](https://github.com/user-attachments/assets/8af07188-3286-44c8-8669-52e5d571df0c)

### 2º Passo - Descompactação Automatizada
Os arquivos vinham compactados, exigindo um processo de extração manual demorado. Criei um script em Python que descompactou todos os arquivos automaticamente.

![Python_Passo2_Parte1](https://github.com/user-attachments/assets/b3c3a91f-1420-4325-a65f-1155bef280c7)
![Python_Passo2_Parte2](https://github.com/user-attachments/assets/8150aa04-1592-482a-98c7-f521521b3f3e)

### 3º Passo - Padronização e Renomeação dos Arquivos
Implementei um processo de renomeação automática para que os arquivos fossem identificados pelos nomes das empresas, tanto para os arquivos Excel quanto para os PDFs, facilitando sua organização e uso posterior.

![Python_Passo3_Parte1](https://github.com/user-attachments/assets/e5138b77-16de-4421-bdc2-4a38e4eb0b15)
![Python_Passo3_Parte2](https://github.com/user-attachments/assets/a80c9fb9-5ced-4676-8c0b-36e49c52be4c)

### 4º Passo - Tratamento dos Dados
Realizei um processamento e limpeza dos balanços em Excel, modificando os dados conforme necessário e excluindo informações irrelevantes, garantindo a padronização e usabilidade dos dados.

![Python_Passo4_Parte1](https://github.com/user-attachments/assets/be164c78-0262-41e2-a1f5-de775d99a76d)
![Python_Passo4_Parte2](https://github.com/user-attachments/assets/40b545a9-3b89-4802-a016-8a1815b29523)

### 5º Passo - Consolidação dos Dados
Os dados foram organizados em quatro arquivos principais:
- **Ativo_Consolidado**
- **Passivo_Consolidado**
- **DRE_Consolidado**
- **FluxoCaixa_Consolidado**

![Python_Passo5_Parte1](https://github.com/user-attachments/assets/b57d712f-640b-4d9d-8a9a-34ea2283c564)
![Python_Passo5_Parte2](https://github.com/user-attachments/assets/dc7cabf3-dee4-4d1e-bd9c-2c512d8ba1c8)

Todos esses passos foram automatizados via Python, conforme imagens disponibilizadas reduzindo drasticamente o tempo de processamento.

### 6º Passo - Criação do Dashboard Interativo
Utilizando Power BI, desenvolvi um dashboard interativo, que exibe:
- Principais indicadores financeiros das empresas.
- Gráficos da Receita Líquida e Lucro Líquido.
- Nota de Risco Financeiro, baseada em um modelo de classificação.
- Tendência de Progresso, categorizando as empresas em crescimento, estabilidade ou declínio.

![Passo 6](https://github.com/user-attachments/assets/ed01735a-08b2-4c76-b3ef-2a69446b81cd)

## Resultados e Impacto

- ✅ Automatização completa do processo de obtenção e processamento de balanços financeiros.
- ✅ Criação de um dashboard interativo para análise financeira e tomada de decisão estratégica.
- ✅ Identificação do nível de risco das empresas, facilitando a análise de investimentos.
- ✅ Economia de tempo e eficiência, permitindo uma análise mais rápida e precisa.














