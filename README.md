# Simulador de Investimentos em FIIs - InvestID ![logo](/images/Logo.png)

Planilha Excel para simular investimentos em Fundos Imobiliários (FIIs), permitindo calcular patrimônio acumulado, dividendos e sugestões de alocação conforme perfil do investidor.

## Funcionalidades

- **Configurações de Perfil**: salário, rendimento da carteira e perfil (Conservador, Moderado, Agressivo).
- **Simulação de Investimentos**: cálculo de aporte mensal, patrimônio acumulado e dividendos.
- **Cenários Projetados**: projeções para 2, 5, 10, 20 e 30 anos com gráficos.
- **Distribuição de FIIs**: sugestões por tipo (Papel, Tijolo, Híbrido, FOFs, Desenvolvimento, Hotelaria).

## Como Usar

1. Abra o arquivo `/Projeto_Invest_ID.xlsx`.
2. Configure salário, perfil e aporte mensal. ![config](/images/Captura_01.png)
3. Defina taxa de rendimento e período em anos. ![tela_01](/images/Captura_02.png)
4. Visualize resultados em cenários, patrimônio e sugestões de FIIs.![tela_02](/images/Captura_03.png)
5. Ajuste valores para simular diferentes cenários.

## Fórmulas Utilizadas

- **Patrimônio Acumulado**: `FV(taxa_mensal, períodos, -aporte)`
- **Dividendos Mensais**: percentual do patrimônio (ex.: 0,9% ao mês)
- **Distribuição FIIs**: tabela de alocação somando 100%

## Estrutura da Planilha

| Aba/Seção   | Conteúdo Principal |
|-------------|--------------------|
| Invest ID   | Configurações, simulações e gráficos |
| Planilha1   | Perfis e alocações por tipo de FII (oculto)|

## Aprendizado

Projeto desenvolvido em laboratório da DIO, aplicando fórmulas, tabelas, gráficos e funções de busca.

## Arquivos

- `/Projeto_Invest_ID.xlsx` – planilha principal
- `/images/Captura_01.png` – tela de configurações
- `/images/Captura_02.png` – tela de projeção do patrimonio
- `/images/Captura_03.png` – tela de distribuição dos FIIs
- `/images/Logo.png` – logo do projeto

---

✨ Repositório público para o Desafio DIO - Simulador de Investimentos em FIIs. Contribuições são bem-vindas!
