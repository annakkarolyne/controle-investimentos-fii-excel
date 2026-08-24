# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

Ferramenta em Excel para simular investimentos em Fundos de Investimento Imobiliário (FIIs), calculando o valor total investido, o patrimônio acumulado e os dividendos mensais ao longo do tempo.

## 📌 Sobre o projeto

A planilha simula um aporte único inicial em um FII, com **reinvestimento automático dos dividendos** recebidos todo mês na compra de novas cotas. O retorno é calculado considerando dois fatores:

- **Valorização da cota** ao longo do tempo
- **Dividendos mensais**, que são reinvestidos automaticamente

O objetivo é ajudar investidores iniciantes a entender, de forma simples e visual, o impacto do reinvestimento de dividendos e da valorização no patrimônio total ao longo dos meses.

## ⚙️ Como funciona

O usuário preenche apenas 5 células de entrada (destacadas em amarelo):

| Parâmetro | Descrição |
|---|---|
| Valor do aporte inicial | Quanto será investido no mês 0 |
| Preço da cota no mês 0 | Cotação inicial do FII |
| Valorização mensal esperada | Taxa de valorização média da cota (%) |
| Dividend yield mensal esperado | Percentual de dividendo pago sobre a cota (%) |
| Número de meses da simulação | Período a projetar (até 60 meses) |

A partir disso, a planilha calcula automaticamente, mês a mês:
- Preço da cota
- Número de cotas acumuladas
- Patrimônio total
- Dividendos recebidos e reinvestidos
- Rentabilidade acumulada

Um painel de resumo e um gráfico comparando **patrimônio x valor investido** são gerados automaticamente.

## 🗂️ Arquivos do projeto

- `simulador_investimentos_fii.xlsx` — planilha interativa (recomendado para uso e edição)
- `simulador_investimentos_fii.pdf` — versão em PDF para visualização rápida

## 🛠️ Tecnologias

- Microsoft Excel (fórmulas nativas, sem macros)

## 🚀 Possíveis expansões futuras

- Simulação de aportes mensais recorrentes (além do aporte único)
- Comparação entre múltiplos FIIs simultaneamente
- Ajuste por inflação (retorno real vs. nominal)

## 👩‍💻 Autor

Projeto desenvolvido como parte do curso **"Criando uma Ferramenta de Controle de Investimentos com Excel"** da [DIO](https://www.dio.me/).
