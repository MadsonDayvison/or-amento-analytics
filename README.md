<p align="center">
  <img src="images/Capa.png" width="100%" />
</p>

## >> Painel de Gestão Orçamentária – Power BI

Este projeto apresenta um dashboard completo para acompanhamento do **Orçado x Realizado**, permitindo avaliar performance, consumo de orçamento, desempenho por setor e evolução mês a mês.  
Embora os dados sejam fictícios, a modelagem, as técnicas e o pensamento analítico utilizados refletem práticas reais adotadas em áreas financeiras e controladoria.

---

## >> Objetivo do Projeto

Apoiar o processo de gestão orçamentária respondendo perguntas essenciais:

- O orçamento está sendo executado dentro do esperado?
- Quais setores já consumiram mais recursos?
- Em quais meses o realizado ficou acima ou abaixo do orçado?
- Quanto do orçamento ainda está disponível (saldo)?
- Qual é a tendência mensal do consumo?
- Estamos performando dentro da meta?

---

## >> Como interpretar os Indicadores do Dashboard

Cada indicador do dashboard foi construído com o objetivo de **guiar decisões**, e acompanhar a performance do orçamento.

### ⚫  1. **Orçado (R$ 2,94 Mi)**
Mostra o total previsto para o período.  
➡ Ajuda gestores a entender **qual o limite financeiro** estabelecido para o ano.

---

### ⚫  2. **Realizado (R$ 2,77 Mi)**
Total efetivamente gasto.  
➡ Indica **o ritmo de consumo** e se estamos gastando como planejado.

---

### ⚫  3. **Saldo (R$ 168 mil)**
Cálculo:  
`Saldo = Orçado – Realizado`  
➡ Essencial para prever riscos de estouro de orçamento.

---

### ⚫  4. **Performance (Meta x Realizado)**
Mostra se o gasto está **acima ou abaixo da meta projetada**.

Exemplo da imagem:  
✔ Meta: R$ 266,55 mil  
✔ Realizado: R$ 249,99 mil  
✔ Variação: +6,21%

➡ Ajuda na tomada de decisão preventiva: cortar gastos, replanejar, justificar excedentes.

---

### ⚫  5. **Orçado x Realizado por Setor**
Permite identificar:

- Setores que gastam consistentemente acima da média  
- Áreas críticas que precisam de revisão de processos  
- Possíveis alocações indevidas  

➡ É uma visão central para **priorização de auditorias internas**.

---

### ⚫  6. **Ranking Realizado**
Classifica os setores pelo maior gasto.  
➡ Ideal para reuniões com diretores e gestores.

---

### ⚫ 7. **Consumo do Orçamento (%)**
Compara:

- % já gasto  
- % ainda disponível  

➡ Permite saber rapidamente se a área está saudável ou crítica.

---

### ⚫ 8. **Evolução do Orçado x Realizado (Mês a Mês)**
Mostra tendência e sazonalidade.  
➡ Fundamental para prever meses de maior risco (ex.: bonificações, compras grandes, etc).

---

## 🏗️ Estrutura do Modelo de Dados

Boas práticas de modelagem de dados baseado nas etapas do projeto


✔ Definição das tabelas fato e dimensão   
✔ Tabela **Calendário** com relacionamentos corretos  
✔ Tratamento de tipos, limpeza, renomeação via Power Query 
✔ Medidas DAX organizadas em pastas  
✔ Página de “Rascunho” para testar DAX
✔ Otimização ocultando colunas não utilizadas

###  Esse projeto foi desenvolvido usando os dados fornecidos pelo professor André Rosa, no curso de Power BI Profissional disponível em: https://www.udemy.com/course/formacao-power-bi-pro/
