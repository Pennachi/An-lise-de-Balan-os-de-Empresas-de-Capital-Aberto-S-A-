# Analise-de-Balancos-de-Empresas-de-Capital-Aberto-S-A-
Este projeto teve como objetivo automatizar a obtenção e processamento dos balanços das empresas de capital aberto (S/A), 
Descrição do Projeto
Este projeto teve como objetivo automatizar a obtenção e processamento dos balanços das empresas de capital aberto (S/A), realizar o tratamento dos dados e apresentar os resultados em um dashboard interativo. O foco foi permitir uma análise eficiente do progresso financeiro das empresas e atribuir uma nota de risco, otimizando a tomada de decisão baseada em dados.
Minha Função no Projeto
Atuei na extração, tratamento e análise dos balanços financeiros, automatizando todo o processo desde o download dos arquivos até a geração dos dashboards interativos. Um dos principais desafios foi identificar o nível de progresso das empresas e desenvolver um modelo de nota de risco, permitindo uma classificação mais precisa das condições financeiras das empresas analisadas.
Ferramentas e Tecnologias Utilizadas
•	Power BI - Para visualização e análise interativa dos balanços.
•	Python - Para automação da obtenção, tratamento e organização dos dados.
•	Excel - Para organização e verificação dos balanços processados.
________________________________________
Processo de Desenvolvimento
1º Passo - Obtenção Automática dos Balanços
Desenvolvi um código em Python para baixar automaticamente cerca de 700 balanços financeiros diretamente da fonte, eliminando a necessidade de downloads manuais.
2º Passo - Descompactação Automatizada
Os arquivos vinham compactados, exigindo um processo de extração manual demorado. Para resolver isso, criei um script em Python que descompactou todos os arquivos automaticamente.
3º Passo - Padronização e Renomeação dos Arquivos
Implementei um processo de renomeação automática para que os arquivos fossem identificados pelos nomes das empresas, tanto para os arquivos Excel quanto para os PDFs, facilitando sua organização e uso posterior.
4º Passo - Tratamento dos Dados
Realizei um processamento e limpeza dos balanços em Excel, modificando os dados conforme necessário e excluindo informações irrelevantes, garantindo a padronização e usabilidade.
5º Passo - Consolidação dos Dados
Os dados foram organizados em quatro arquivos principais:
•	Ativo_Consolidado
•	Passivo_Consolidado
•	DRE_Consolidado
•	FluxoCaixa_Consolidado
Todos esses passos foram totalmente automatizados via Python, o que reduziu drasticamente o tempo de processamento.
6º Passo - Criação do Dashboard Interativo
Utilizando Power BI, desenvolvi um dashboard que exibe:
•	Principais indicadores financeiros das empresas em uma tabela interativa.
•	Gráficos da Receita Líquida e Lucro Líquido das empresas.
•	Nota de Risco Financeiro, baseada em um modelo de classificação desenvolvido no projeto.
•	Tendência de Progresso, que categoriza as empresas em crescimento, estabilidade ou declínio.
________________________________________
Resultados e Impacto
✅ Automatização completa do processo de obtenção e processamento de balanços financeiros. ✅ Criação de um dashboard interativo para análise financeira e tomada de decisão estratégica. ✅ Identificação do nível de risco das empresas, facilitando a análise de investimentos. ✅ Economia de tempo e eficiência, reduzindo tarefas manuais e possibilitando uma análise mais rápida e precisa.
________________________________________
Imagens e Demonstração
(Inserir capturas de tela dos dashboards criados e trechos do código utilizado no projeto)
