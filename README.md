# Simulador de Investimentos em FIIs - InvestID

Este projeto é uma planilha Excel desenvolvida para simular investimentos em Fundos Imobiliários (FIIs), permitindo que usuários calculem patrimônio acumulado, dividendos e sugestões de alocação baseadas no perfil de investidor.[^1]

A ferramenta responde a perguntas comuns como "Quanto investir?", "Por quanto tempo?" e "Qual o retorno esperado?", automatizando cálculos financeiros para decisões informadas.[^1]

Inclui configurações de perfil (Conservador, Moderado, Agressivo) e cenários de projeção em 2, 5, 10, 20 e 30 anos.[^1]

## Funcionalidades Principais

- **Configurações de Perfil**: Insira salário, rendimento da carteira e perfil (ex: Conservador; Moderado; Agressivo). A partir desses dados a planilha sugere investimento mensal inicial. (ex: R\$ 500,00.[^1])
- **Simulação de Investimentos**: Calcula o aporte mensal, o patrimônio acumulado e os dividendos mensais com base em taxa de rendimento mensal configurável.[^1]
- **Cenários Projetados**: Tabelas mostram patrimônio e dividendos para horizontes de 2 a 30 anos, com gráficos de evolução.[^2][^1]
- **Distribuição de FIIs**: Sugestões por tipo (Papel; Tijolo; Híbrido; FOFs; Desenvolvimento; Hotelaria).[^1]


## Como Usar

1. Abra o arquivo `Projeto_Invest_ID.xlsx`.[^1]
2. Preencha as configurações: salário, perfil de investimento e aporte desejado por mês.
3. Insira taxa de rendimento mensal e período em anos.
4. Visualize resultados em cenários, patrimônio e sugestões de FIIs.
5. Ajuste valores para simular diferentes cenários.

Exemplo de tela de configurações e resultados: ![Captura configurações] ![Captura simulação][^3][^2]

## Fórmulas e Cálculos Utilizados

- **Patrimônio Acumulado**: Usa função de valor futuro com aportes mensais, como FV(taxa_mensal, períodos, -aporte, 0).[^1]
- **Dividendos Mensais**: Calculados como porcentagem do patrimônio (ex: 0,9% ao mês).[^1]
- **Distribuição FIIs**: Tabela de distribuição de FIIs por perfil, somando alocações a 100%.[^1]


## Estrutura da Planilha

| Aba/Seção | Conteúdo Principal |
| :-- | :-- |
| Invest ID | Configurações, simulações e gráficos       [^1] |
| Planilha1 | Tabela de perfis e alocações por tipo FII  [^1] |

## Aprendizado no Desafio DIO

Desenvolvido durante o laboratório de Excel da DIO, aplicando conceitos de fórmulas financeiras (FV, PV), tabelas dinâmicas, gráficos e lookups (ÍNDICE/CORRESP). Resolveu o desafio de simular FIIs com inputs variáveis para outputs projetados.[^1]

## Arquivos Incluídos

- `Projeto_Invest_ID.xlsx`: Planilha principal da simulação.[^1]
- `/images/Captura-de-tela-2026-01-12-010741.jpg`: Tela de configurações.[^2]
- `/images/Captura-de-tela-2026-01-12-010820.jpg`: Tela de resultados e gráficos.[^3]

Repositório público para o Desafio DIO - Simulador de Investimentos em Fundos Imobiliários. Contribuições bem-vindas!

<div align="center">⁂</div>

[^1]: Projeto_Invest_ID.xlsx

[^2]: Captura-de-tela-2026-01-12-010741.jpg

[^3]: Captura-de-tela-2026-01-12-010820.jpg

