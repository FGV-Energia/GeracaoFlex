# Análise Flexível de Geração das Principais Fontes do Sistema Interligado Nacional

## Descrição
Este repositório contém uma série de análises gráficas sobre a geração de energia no Sistema Interligado Nacional (SIN) do Brasil, bem como a análise da curva líquida de energia

## Estrutura do Repositório
```
├── data                    # Contém planilha de dados de geração agrupado de 2016 a 2023, por subsistema e/ou planilha de geração usina em base horária
├── src                     # Contém o arquivo do código da análise gráfica de flexibilidade
└── README.md               # Descrição e instruções para o projeto
```

## Configuração

Detalhamento de Seções do Notebook:

Seção 1 (Geração): 
- Gráfico de Atendimento a Carga das principais fontes de geração do SIN
- Gráfico de Geração Média Horária das principais usinas do CAG

Seção 2 (Curva Líquida):
- Gráfico da Curva Líquida, Geração Solar e Geração Eólica (Média Horária)
- Gráfico de Gerações Hidráulica, Geração Solar e Carga (Média Horária)

Seção 3 (Rampas):
- Gráfico de variabilidade horária da Curva Líquida, Geração Hidráulica, Geração Solar ou Geração Eólica por período de 1 hora de um mês e ano escolhido
- Gráfico de variabilidade horária da Curva Líquida, Geração Hidráulica, Geração Solar ou Geração Eólica por período de 3 horas de um mês e ano escolhido
- Gráfico de variabilidade horária da Curva Líquida, Geração Hidráulica, Geração Solar ou Geração Eólica por período, mês escolhido de 2016 a 2023
- Gráfico empilhado de geração das principais fontes de energia, carga e curva líquida

```
# Adicione comandos para instalar dependências, por exemplo:
pip install -r requirements.txt
```

## Uso

Instruções para rodar a Seção 1 do Notebook:
- Planilha referente a um mês ou ano específico de Geração por Usina em Base Horária (Link: https://dados.ons.org.br/dataset/geracao-usina-2) inserida dentro da pasta data;
- Inserir ano e mês de análise

Instruções para rodar as Seções 2 e 3 do Notebook:
- Planilha "Balanco_Energetico_Agrupa.xlsx" dentro da pasta 'data', que contém dados de geração de energia por subsistema de 2016 a 2023;
- Inserir ano, mês, período inicial ou período final de acordo com a necessidade de cada subseção

```
# Exemplo de como rodar um script:

Exemplo de rodagem da Seção 1 do Notebook (Gráfico de Atendimento a Carga)

- Rodar Notebook referente a seção
- Inserir ano e mês desejado de análise
- Plot do Gráfico

```

## Créditos
Agradecimentos a colaboradores, instituições ou qualquer entidade que contribuiu significativamente para o desenvolvimento do projeto.
