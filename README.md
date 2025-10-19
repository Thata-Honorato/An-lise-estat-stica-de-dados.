
# Sprint 4 – Análise Estatística de Dados Megaline

## Descrição do Projeto

Neste projeto, você atua como analista de dados para a empresa de telecomunicações **Megaline**, que oferece dois planos pré-pagos: **Surf** e **Ultimate**. O objetivo é determinar qual plano gera mais receita com base no comportamento dos clientes.

O conjunto de dados contém informações sobre **500 clientes**, incluindo chamadas, mensagens e uso de internet em 2018. A análise envolve pré-processamento de dados, análise estatística, visualização e teste de hipóteses.

---

## Objetivos

- Limpar e preparar os dados para análise.
- Analisar o comportamento dos clientes de cada plano.
- Determinar qual plano gera mais receita média.
- Criar gráficos e tabelas explicativas.
- Formular e testar hipóteses estatísticas.

---

## Descrição dos Planos

**Surf**  
- Preço mensal: \$20  
- Inclui: 500 minutos, 50 mensagens, 15 GB de dados  
- Excedentes: 1 minuto = \$0,03 | 1 mensagem = \$0,03 | 1 GB = \$10  

**Ultimate**  
- Preço mensal: \$70  
- Inclui: 3.000 minutos, 1.000 mensagens, 30 GB de dados  
- Excedentes: 1 minuto = \$0,01 | 1 mensagem = \$0,01 | 1 GB = \$7  

> Observação: a Megaline arredonda segundos para minutos e megabytes para gigabytes, conforme regras do plano.

---

## Dicionário de Dados

**users.csv** – dados dos usuários:  
- `user_id`, `first_name`, `last_name`, `age`, `reg_date`, `churn_date`, `city`, `plan`  

**calls.csv** – dados das chamadas:  
- `id`, `call_date`, `duration`, `user_id`  

**messages.csv** – dados de mensagens de texto:  
- `id`, `message_date`, `user_id`  

**internet.csv** – dados de sessões web:  
- `id`, `mb_used`, `session_date`, `user_id`  

**plans.csv** – dados dos planos:  
- `plan_name`, `usd_monthly_fee`, `minutes_included`, `messages_included`, `mb_per_month_included`, `usd_per_minute`, `usd_per_message`, `usd_per_gb`  

---

## Etapas do Projeto

1. **Abrir os arquivos de dados** e estudar informações gerais.  
2. **Preparar os dados**:  
   - Corrigir tipos de dados  
   - Tratar erros e valores ausentes  
   - Calcular para cada usuário: chamadas e minutos usados, mensagens enviadas, volume de dados e receita mensal  

3. **Análise de dados**:  
   - Comparar consumo de minutos, mensagens e dados por plano  
   - Calcular média, variância e desvio padrão  
   - Construir histogramas e interpretar distribuições  

4. **Teste de hipóteses**:  
   - Comparar receita média entre planos Surf e Ultimate  
   - Comparar receita média de usuários da região NY-NJ com outras regiões  
   - Explicar hipóteses nula e alternativa, critérios de teste e interpretação dos resultados  

5. **Conclusão geral**:  
   - Resumir resultados do projeto  
   - Destacar insights e recomendações baseadas na análise  

---

## Observações

- Todos os notebooks originais estão hospedados na plataforma TripleTen e não podem ser alterados.  
- Este repositório documenta o projeto e o aprendizado adquirido.  
- Certifique-se de adicionar explicações detalhadas em células Markdown e organizar gráficos com títulos, legendas e eixos rotulados.
EOF
