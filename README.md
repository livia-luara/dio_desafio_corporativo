# Desafio - Processamento de Dados Corporativos
Este desafio teve como objetivo realizar a integração do Power BI com o MySQL, com dados de uma empresa fictícia, a fim de gerar relatórios gráficos e realizar a transformação e análise de dados. O processo incluiu etapas de limpeza e organização da base de dados, além da criação de relatórios e gráficos eficientes para análise.

## Etapas
Banco de Dados MySQL: O banco de dados manipulado foi disponibilizado no GitHub pela professora Juliana Mascarenhas. A estrutura foi montada com tabelas relacionadas a empregados, departamentos, projetos, dependentes e alocações.

Transformações dos Dados:
* Verificação de cabeçalhos e tipos de dados: ajustes feitos para garantir a integridade dos dados.
* Conversão de valores monetários: valores de salários e outras variáveis monetárias foram ajustados para um formato mais preciso.
* Verificação de valores nulos: colaboradores sem gerente (super_ssn nulo) foram identificados como gerentes.
* Preenchimento de lacunas de dados: dados ausentes foram devidaemnte preenchidos.
* Mesclagem de dados e junções.

Criação de Novas Colunas e Agrupamento
As colunas de Nome e Sobrenome foram mescladas para criar uma coluna única, e as colunas de Departamento e Localização também foram combinadas para facilitar a análise. Além disso, os dados foram agrupados para mostrar quantos colaboradores existem por gerente (3 para Franklin, 3 para James, 2 para Jeniffer).

Eliminação de Colunas Desnecessárias
Durante a análise, colunas irrelevantes para o relatório final foram removidas, a fim de otimizar a visualização e análise dos dados.

## Relatórios Criados
Foram criados cinco relatórios gráficos no Power BI:

* Barras Clusterizado de Horas por Projeto

* Gráfico de Pizza de Distribuição de Funcionários por Sexo

* Mapa por Localização de Departamento

* Matriz de Projetos e Horas Totais por Colaborador

* Gráfico de Pizza de Dependentes por Colaboradores

Os relatórios estão disponíveis em formato PDF e PBIX para visualização das dinâmicas entre os gráficos. A base de dados útilizada também está disponível em SQL, assim como a estrutura do esquema.
