# Checkpoint-01-An-lise-de-Dados-de-Energia-Final

Desafio Final — Análise de Dados de Energia com API Pública
Curso: Ciência da Computação
Disciplina: Soluções em Energias Renováveis e Sustentáveis

Situação-problema
Uma equipe de planejamento energético precisa analisar o comportamento da carga elétrica de uma região atendida pelo Sistema Interligado Nacional (SIN).

Os dados serão obtidos diretamente de uma API pública do Operador Nacional do Sistema Elétrico (ONS). A conexão com a API e a preparação inicial do JSON já estão fornecidas. A partir daí, sua equipe deverá construir o DataFrame, organizar os dados, criar recortes, calcular indicadores, produzir gráficos e elaborar um relatório técnico.

Todos os códigos, resultados, gráficos e respostas devem permanecer neste mesmo Notebook.


Fonte dos dados
API pública de Carga Verificada do ONS:

Portal: https://dados.ons.org.br/
Conjunto de dados: https://dados.ons.org.br/dataset/carga-energia-verificada
Dicionário de dados: Carga Verificada do ONS
Neste notebook será utilizada inicialmente a área SP — São Paulo, no período de 01/08/2025 a 07/08/2025.

Os campos usados na análise seguem a estrutura da Carga Verificada do ONS: cod_areacarga, dat_referencia, din_referenciautc, val_cargaglobal e demais componentes disponibilizados pela API.

INTEGRANTES:

Bruno Menezes Monegatto -  RM570311
Fabiana Yumi Rodrigues Nakagawa - RM571249
Iago Neiva Gorrão - RM 570234
João Pedro Amorim Albuquerque - RM 573342
Kayky Araujo Silva - RM569535
