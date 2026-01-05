# 🏢 FII Planner: Simulador de Renda Passiva

## 📖 Sobre o Projeto

Este projeto consiste em um simulador financeiro desenvolvido em **Excel**, focado na simulação de estratégias de investimento em Fundos Imobiliários (FIIs). 

O objetivo principal é demonstrar, de forma prática e visual, o poder dos juros compostos e do reinvestimento de dividendos. A ferramenta permite que o investidor desenhe cenários personalizados para alcançar suas metas de liberdade financeira, saindo do "achismo" e partindo para dados concretos.

Este repositório serve também como demonstração de competências em modelagem financeira, lógica de planilhas e documentação técnica.

---

## ⚙️ Funcionalidades e Estrutura

A planilha foi desenhada para ser intuitiva, dividida em quatro pilares lógicos:

### 1. 🏗️ Definição de Perfil do Investidor
O usuário insere seus dados base para gerar uma sugestão de aporte.
- Definição de renda mensal.
- Percentual destinado a investimentos.
- Cálculo automático do valor disponível para aporte.

### 2. 🎛️ Motor de Simulação
Configuração das variáveis do mercado e do tempo.
- **Horizonte de Tempo:** Projeção em anos (curto, médio e longo prazo).
- **Aporte Mensal:** Quanto será investido recorrentemente.
- **Yield Esperado:** Taxa de retorno mensal média da carteira.

### 3. 📊 Alocação de Ativos
Sugestão visual de diversificação da carteira baseada no perfil do investidor.
- Divisão estratégica entre FIIs de Papel, Tijolo, Híbridos, FOFs, etc.
- Gráfico de rosca para visualização rápida da exposição da carteira.

### 4. 📈 Gráfico de Resultados
Visualização clara do futuro financeiro baseado nos inputs anteriores.
- **% por tipos de FII:** Divisão percentual por investimento.
---

## 🧮 Lógica Financeira

Para garantir a precisão das projeções, foram aplicadas as seguintes fórmulas financeiras clássicas:

| Indicador | Conceito Matemático |
| :--- | :--- |
| **Valor Futuro (FV)** | Utiliza a fórmula de séries uniformes para calcular o montante acumulado com juros compostos. <br> `FV = PMT * [((1 + i)^n - 1) / i]` |
| **Projeção de Renda** | Multiplicação do montante acumulado pela taxa de *Dividend Yield* estipulada. |
| **Crescimento Mês a Mês** | Iteração que soma o saldo anterior + rendimento do mês + novo aporte. |

---

## 🛠️ Tecnologias e Ferramentas

* **Microsoft Excel:** Motor de cálculo, funções financeiras e interface de dashboard.
* **Git/GitHub:** Controle de versão e hospedagem da documentação.

---

## 🤝 Contribuição

Sugestões e melhorias são bem-vindas!
Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request* com otimizações nas fórmulas ou no layout.

---

## 🚀 Download

1. **Download:** Copie este repositório ou baixe o arquivo `DIO_Inve$t_FII.xlsx`.

<p align="center">
  Excel desenvolvido por <strong>Raquel Plantikow</strong>
</p>
