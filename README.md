# TelecomX - Análise de Churn em Telecomunicações
Linguagem: Python 

Bibliotecas: pandas, matplotlib, seaborn, numpy, plotly(gráficos interativos não aparecem no github, por este motivo no notebook inclui imagens estáticas dos mesmos)

## 📌 Sobre o Projeto
O TelecomX é um projeto de análise de dados focado em entender e reduzir a taxa de churn (evasão de clientes) em uma empresa de telecomunicações. Utilizando técnicas de análise exploratória de dados (EDA), identificamos padrões e insights que podem ajudar a empresa a reter mais clientes e melhorar sua estratégia de negócios.

### 🔍 Principais Descobertas:
- 1869 clientes optaram pelo churn (número significativo, mas ainda uma minoria no total).
- Homens e mulheres têm taxas de evasão praticamente iguais (diferença de apenas 0,4%).
- 74,5% dos clientes que deixam a empresa têm mais de 60 anos.
- Pagamento eletrônico (electronic check) é o método com maior evasão.
- Contratos mensais têm a maior taxa de churn, enquanto clientes com contratos de longo prazo tendem a ficar.
- Clientes com serviço de telefone e fibra óptica são os que mais cancelam, indicando possíveis problemas nesses serviços.
- Gastos mais altos estão associados a uma maior taxa de evasão.

### 📊 Insights para Reduzir o Churn

1. **Melhorar a Experiência de Clientes Idosos (60+ anos)**
Oferecer planos personalizados para essa faixa etária. 
Implementar atendimento preferencial e suporte técnico mais acessível.

2. **Revisar o Modelo de Pagamento Eletrônico**
Investigar por que o electronic check tem maior evasão.
Oferecer descontos ou benefícios para quem usa pagamento automático (como cartão de crédito).

3. **Incentivar Contratos de Longo Prazo**
Promover fidelização com descontos em planos anuais.
Oferecer benefícios exclusivos (como upgrades grátis) para clientes fiéis.

4. **Otimizar Serviços de Telefonia e Fibra Óptica**
Verificar problemas técnicos que levam à insatisfação.
Melhorar a qualidade do serviço e oferecer suporte proativo.

5. **Reduzir a Evasão de Clientes com Gastos Altos**
Criar programas de retenção para clientes de alto valor.
Oferecer benefícios premium (como atendimento 24/7 ou bônus em serviços).

### 📈 Visualizações Principais
O projeto inclui gráficos como:

- Distribuição de churn por idade
- Evasão por tipo de pagamento
- Taxa de evasão por tipo de contrato
- Distribuição de evasão por serviço de telefone e internet
- Relação entre gastos mensais e churn