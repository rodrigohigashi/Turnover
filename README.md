📌 Análise de Turnover de uma Empresa
Este projeto utiliza Árvore de Decisão para classificar se um funcionário terá turnover (saída da empresa) ou não, com base em suas características.

📊 Objetivo
O objetivo é construir um modelo preditivo capaz de identificar padrões e auxiliar na tomada de decisão sobre retenção de talentos.

🔍 Análise Exploratória de Dados (AED)
Antes de treinar o modelo, o arquivo aed.py realiza uma análise exploratória automatizada, incluindo:

Pandas Profiling: Gera um relatório detalhado sobre o dataset, com estatísticas descritivas e visualizações.
Information Value (IV): Calcula a importância das variáveis independentes para prever a variável alvo (turnover).
Análise Bivariada: Examina a relação entre as variáveis independentes e a variável alvo.
Como rodar a análise exploratória:
Execute o script aed.py para obter um relatório completo de análise exploratória.

python aed.py
O script gerará um relatório do pandas profiling e outras análises no diretório de saída.
🚀 Como Rodar o Projeto
Clone este repositório:

git clone https://github.com/seuusuario/analise-turnover.git
cd analise-turnover
Crie e ative um ambiente virtual (opcional, mas recomendado):

python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
Instale as dependências:

pip install -r requirements.txt
Execute o script da AED:

python aed.py
Após a análise exploratória, execute o modelo de árvore de decisão:

python main.py
📈 Métricas Utilizadas
O modelo é avaliado por diversas métricas de classificação:

Acurácia
Precisão (Precision)
Recall (Sensibilidade)
F1-score
Matriz de Confusão
Índice de Gini
📊 Visualizações
O projeto inclui duas formas de visualização da árvore de decisão:

plot_tree (visualização padrão do sklearn)
dtreeviz (visualização mais detalhada e interpretável)
Exemplo de uma árvore gerada:

📜 Licença
Este projeto é de uso livre para fins de aprendizado e estudo.