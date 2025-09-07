Priorizador de Features com RICE Score
Este repositório contém um script Python para priorizar features de produtos usando o modelo RICE (Reach, Impact, Confidence, Effort). Como Product Manager, a priorização é uma habilidade crucial, e esta ferramenta visa automatizar e otimizar esse processo, tornando as decisões mais orientadas por dados.

Sobre o Projeto
O script lê uma lista de features de um arquivo CSV, calcula o score RICE para cada uma e gera um novo arquivo CSV com as features ordenadas por prioridade, da maior para a menor.

Por que este projeto é relevante?
🚀 Tomada de Decisão Data-Driven: Reforça a capacidade de tomar decisões embasadas em dados concretos, em vez de intuição.

📋 Gestão de Roadmap e Backlog: Ferramenta prática para organizar e gerenciar o roadmap e o backlog de produtos de forma eficiente.

📈 Visão de Negócio: Estimula a análise do impacto e alcance das funcionalidades, alinhando o desenvolvimento à visão estratégica do negócio.

🤖 Automação de Tarefas: Automatiza uma tarefa central e repetitiva do dia a dia de um Product Manager, liberando tempo para atividades mais estratégicas.

Como Usar
Siga os passos abaixo para executar o projeto.

1. Pré-requisitos
Python 3.x instalado.

Instalação da biblioteca Pandas:

Bash

pip install pandas
2. Crie o arquivo de entrada features.csv
O arquivo CSV de entrada deve conter as seguintes colunas:

Feature: Nome da funcionalidade (string).

Reach: Quantos usuários serão impactados em um período (número inteiro).

Impact: Qual o impacto para o usuário? (Escala: 3=massivo, 2=alto, 1=médio, 0.5=baixo).

Confidence: Qual sua confiança na estimativa? (Porcentagem: 100, 80, 50).

Effort: Qual o esforço para desenvolver? (Use "person-months" ou outra unidade consistente).

Exemplo de features.csv:

Snippet de código

Feature,Reach,Impact,Confidence,Effort
"Novo Dashboard Analytics",200,3,80,4
"Integração com Slack",1500,2,100,3
"Exportar relatório em PDF",500,1,100,1
"Login com biometria",3000,0.5,50,2

