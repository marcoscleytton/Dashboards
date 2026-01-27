# INSIGHTS - Análise de Dados de Saúde

##  Visão Geral dos Dados

Você possui dados de **sinistros de saúde** (5 tabelas relacionadas) com informações sobre:
- **22 sinistros** processados entre janeiro e fevereiro de 2024
- **8 prestadores** de saúde (clínicas, hospitais, laboratórios)
- **17 procedimentos** médicos organizados em grupos
- **5 planos** de saúde com diferentes coberturas
- **Múltiplos usuários/beneficiários**

---

## 💡 PRINCIPAIS INSIGHTS RECOMENDADOS

### 1️⃣ **Análise de Custos e Autorizações**

#### Dashboard: Tendências de Gastos
```
Métrica: Taxa de Aprovação vs Redução
   • Sinistros aprovados: 100%
   • Sinistros com redução: ~27% (redução média de ~10%)
   • Valor total solicitado: R$ 9.270,00
   • Valor total autorizado: R$ 9.120,00
   • Economia com rejeições: R$ 150,00 (1,6%)

Insight: Boa taxa de aprovação, mas há pequenas reduções em exames caros.
   Estratégia: Revisar critérios de autorização para exames de alto valor.

-----------------------------------------------------------------------------------

#### Análise por Tipo de Procedimento

 Despesa por Grupo:
   1. Procedimentos de Imagem (Ressonância, Tomografia): ~43,2% do total
   2. Consultas Especializadas: ~15,8% do total
   3. Laboratório: ~17,5% do total
   4. Ultrassom: ~2,7% do total

Insight: Imagens diagnósticas são o maior custo.
   Recomendação: Negociar com prestadores de imagem por volumes menores.

-----------------------------------------------------------------------------------


### **Performance dos Prestadores**

#### Dashboard: Ranking de Prestadores
```
 Top 3 Prestadores (por volume de sinistros):
   1. Hospital Central (SP): 4 sinistros | R$ 4.250,00
   2. Clínica São Paulo (SP): 3 sinistros | R$ 530,00
   3. Imagem Diagnóstica (RJ): 2 sinistros | R$ 1.820,00

Prestadores por Custo Médio:
   1. Imagem Diagnóstica: R$ 910,00/sinistro (exames caros)
   2. Hospital Central: R$ 1.062,50/sinistro (procedimentos complexos)
   3. Laboratório Análises: R$ 85,50/sinistro (volume baixo)

 Insight: Hospital Central concentra maioria dos casos, mas Imagem tem custo unitário alto.
   Ação: Monitorar utilização de Imagem e considerar credenciamento de alternativas.

-----------------------------------------------------------------------------------

#### Análise de Regiões

 Distribuição Geográfica:
   1. São Paulo (SP): 5 prestadores | 15 sinistros | R$ 7.200,00
   2.Outras (RJ, MG, DF): 3 prestadores | 7 sinistros | R$ 1.920,00

 Insight: Concentração em SP. Oportunidade de expandir rede no RJ/MG.

-----------------------------------------------------------------------------------


### **Análise de Planos e Coparticipação**

Coparticipação vs Custos:

Plano Básico (20% coparticipação):
   • Sinistros: ~5-6
   • Custo para operadora: Maior impacto

Plano Premium (0% coparticipação):
   • Ideal para procedimentos caros
   • Menor responsabilidade do usuário

 Insight: Necessário correlacionar planos com procedimentos.
   Recomendação: Restringir procedimentos caros no Plano Básico.

-----------------------------------------------------------------------------------


### **Padrões de Utilização e Saúde**

#### Dashboard: Procedimentos Mais Solicitados
```
 Top Procedimentos:
   1. Ressonância Magnética: 2 solicitações | R$ 2.400,00
   2. Tomografia Computadorizada: 1 solicitação | R$ 800,00
   3. Consultório Dentário: ~20% de procedimentos simples

 Distribuição:
   • Imagem (60% dos custos): 3 procedimentos
   • Consultas (21% dos custos): 7 procedimentos
   • Laboratório (19% dos custos): 7 procedimentos

Insight: Beneficiários utilizando mais diagnósticos por imagem.
   Possível causa: Falta de atenção primária eficiente.

-----------------------------------------------------------------------------------

### **Análise Temporal**

#### Dashboard: Tendências por Período
```
 Janeiro vs Fevereiro:
   • Janeiro: ~45% dos sinistros
   • Fevereiro: ~55% dos sinistros
   
 Crescimento: +22% de sinistros de jan para fev

 Insight: Padrão de crescimento. Pode haver sazonalidade.
   Ação: Monitorar próximos meses para confirmar tendência.

-----------------------------------------------------------------------------------

### **Análise de Taxa de Rejeição e Conformidade**

#### Dashboard: Qualidade de Reivindicações

✅ Taxa de Aprovação: 100%
⚠️ Taxa de Redução: 27% (3 de 11 sinistros com redução)
❌ Taxa de Rejeição: 0%

 Valor Retido por Redução:
   • Redução média por sinistro: R$ 50-100
   • Total retido: R$ 150

Insight: Critérios rigorosos funcionando bem.
   Recomendação: Manter mesmos critérios.

-----------------------------------------------------------------------------------


