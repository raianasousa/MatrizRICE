🚀 Como Usar

💡 Dica: Se preferir, você pode executar este projeto facilmente no Google Colab, sem precisar instalar nada no seu computador!

✅ 1. Pré-requisitos
Python 3.x instalado.

Instalação da biblioteca Pandas:

Bash

pip install pandas
📄 2. Crie o arquivo de entrada features.csv
O arquivo CSV de entrada deve conter as seguintes colunas:

📝 Feature: O nome da funcionalidade (texto).

👥 Reach: Quantos usuários serão impactados em um período (número inteiro).

💥 Impact: O impacto para o usuário (Escala: 3=massivo, 2=alto, 1=médio, 0.5=baixo).

🤔 Confidence: Sua confiança nas estimativas (Porcentagem: 100, 80, 50).

💪 Effort: O esforço necessário para desenvolver (Use "person-months" ou outra unidade).

Exemplo de features.csv: 👇

Snippet de código

Feature,Reach,Impact,Confidence,Effort
"Novo Dashboard Analytics",200,3,80,4
"Integração com Slack",1500,2,100,3
"Exportar relatório em PDF",500,1,100,1
"Login com biometria",3000,0.5,50,2
