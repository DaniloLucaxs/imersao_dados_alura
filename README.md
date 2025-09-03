📊 Dashboard de Salários na Área de Dados

Este projeto foi desenvolvido durante a Imersão de Dados da Alura, com o objetivo de explorar e analisar salários na área de dados de forma interativa.

🔗 Acesse o dashboard online:
https://imersaodadosalura-q89hynvh8mhdub9dt8egdg.streamlit.app/

🔎 Sobre o Projeto
O dashboard permite que você:

- Explore salários por ano, senioridade, tipo de contrato e tamanho da empresa
- Visualize o Top 10 cargos por salário médio
- Analise a distribuição de salários
- Compare a proporção de trabalho remoto x presencial
- Observe o salário médio por país para Cientistas de Dados
- Consulte os dados detalhados em uma tabela interativa

A ideia é permitir análises rápidas e interativas sem precisar baixar ou manipular os dados manualmente.

⚙️ Como Executar Localmente
1️⃣ Abrir o terminal

Use Git Bash ou PowerShell no Windows.

2️⃣ Clonar o repositório
git clone https://github.com/DaniloLucaxs/imersao_dados_alura.git
cd imersao_dados_alura


Isso vai criar a pasta imersao_dados_alura e entrar nela.

3️⃣ Criar e ativar o ambiente virtual

Git Bash:

python -m venv .venv
source .venv/Scripts/activate


PowerShell:

python -m venv .venv
.\.venv\Scripts\Activate.ps1


Se funcionar, você verá (.venv) no começo da linha do terminal.

4️⃣ Instalar dependências

Como o arquivo requirements.txt não existe, rode:

pip install streamlit pandas plotly

5️⃣ Executar o dashboard
python -m streamlit run aplicativo.py


O navegador abrirá automaticamente em http://localhost:8501
.
Se não abrir, copie o link que aparece no terminal e cole no navegador.

🛠 Tecnologias Utilizadas

- Python – Linguagem principal
- Pandas – Manipulação e limpeza de dados
- Plotly – Visualizações interativas
- Streamlit – Dashboard web

👤 Autor

Danilo Lucas – Estudante de Análise e Desenvolvimento de Sistemas
Participante da Imersão de Dados - Alura
