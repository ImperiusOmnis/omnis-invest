# OMNIS INVEST

Simulador de investimentos em Fundos Imobiliários desenvolvido em Microsoft Excel.

![Preview do OMNIS INVEST](images/omnis-invest-preview.png)

## Sobre o projeto

O **OMNIS INVEST** é um simulador de investimentos em Fundos Imobiliários (FIIs) desenvolvido em Microsoft Excel.

A ferramenta permite configurar parâmetros como salário, percentual destinado a investimentos, aporte mensal, período de investimento e taxa de rendimento. A partir dessas informações, a planilha calcula automaticamente o patrimônio acumulado, o total aportado, o ganho acumulado e uma estimativa de dividendos mensais.

O projeto também permite selecionar um perfil de investidor e apresenta uma sugestão de distribuição do aporte entre diferentes tipos de FIIs, acompanhada de uma visualização gráfica.

## Funcionalidades

- Simulação de investimentos a partir de aporte mensal, período e taxa de rendimento
- Cálculo automático do patrimônio acumulado
- Comparação entre total aportado e ganho acumulado
- Estimativa de dividendos mensais
- Projeção de patrimônio e dividendos para diferentes períodos
- Seleção do perfil de investidor: Conservador, Moderado ou Agressivo
- Sugestão automática de distribuição do aporte entre diferentes tipos de FIIs
- Visualização gráfica da distribuição sugerida do investimento

## Tecnologias e recursos utilizados

O projeto foi desenvolvido no **Microsoft Excel**, utilizando recursos como:

- Fórmulas e cálculos automatizados
- Função financeira `FV` para projeção do patrimônio
- `VLOOKUP (PROCV)` para busca de dados na tabela auxiliar
- Intervalos nomeados para organização e leitura das fórmulas
- Referências absolutas para construção dos cenários de investimento
- Validação de dados para seleção de parâmetros e perfil de investidor
- Formatação condicional para feedback visual do perfil selecionado
- Gráfico de rosca para visualização da distribuição sugerida do aporte

## Como utilizar

1. Baixe o arquivo `omnis-invest.xlsx` disponível neste repositório.
2. Abra o arquivo no Microsoft Excel.
3. Na seção **Configurações**, informe o salário e escolha o percentual que deseja destinar aos investimentos.
4. Na seção **Investimento Mensal**, defina o aporte, o período de investimento e a taxa de rendimento mensal.
5. Consulte os resultados calculados automaticamente, como patrimônio acumulado, total aportado, ganho acumulado e dividendos mensais.
6. Selecione seu perfil de investidor para visualizar a sugestão de distribuição do aporte entre os diferentes tipos de FIIs.
7. Consulte o gráfico para visualizar a composição sugerida do aporte mensal.
