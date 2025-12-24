![Capa](https://github.com/DaDosValle/Imagens/blob/main/Capa%20Banner%20Likdin.png)



# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
## Cloud como estratégia de redução de custos e aumento de margem

**Data:** 23/12/2025  
**Empresa:** Abstergo Industries  
**Responsável:** Fernando do Valle  


## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Fernando do Valle.  
O objetivo do projeto é elencar 3 serviços AWS com a finalidade de realizar diminuição de custos imediatos.

Atualmente, a farmácia toma decisões com dados fragmentados, históricos limitados e alto esforço operacional. Esse cenário, por si só, já gera custos adicionais e diminuiçãao de rendimento por parte dos funcionários.

---

## Descrição do Projeto

Este projeto de implementação consiste em definir as principais ferramentas dos serviços AWS para o contexto atual da Abstergo, detalhando sua utilização, foco e descrição de caso de uso de cada ferramenta.

A implementação dos serviços AWS sugeridos deve ser gradual, dividida em 3 etapas, cada uma com seus objetivos específicos.  
Antes da descrição das etapas, é importante compreender onde a farmácia pode estar perdendo dinheiro neste exato momento.

### Custos invisíveis comuns em farmácias

- Compras acima ou abaixo da demanda real  
- Produtos vencidos ou encalhados  
- Ruptura de estoque (perda de venda)  
- Descontos concedidos sem base em dados  
- Horas de trabalho gastas em esforços manuais  
- Decisões atrasadas por falta de informação  
- Falta de controle adequado e seguro dos dados  

---

## Etapas da Implementação

### Etapa 1: Parar de perder dinheiro por falta de visibilidade

**Nome da ferramenta:** [Amazon S3](https://aws.amazon.com/pt/s3/)  

**Foco da ferramenta:** Centralização de dados e redução de desperdícios  

**Descrição de caso de uso:**  
Centralizar todos os dados da empresa (vendas B2C, pedidos B2B, compras, estoque, planilhas legadas e relatórios) em um único local de baixo custo.  
Isso permite manter um histórico completo de dados, identificar perdas por vencimento, produtos encalhados e compras acima da demanda real.

**Impacto direto:**  
Menos desperdício de estoque e menos dinheiro parado.

**Por que começar por aqui?**  
Porque é barato, simples e já gera economia apenas por oferecer visibilidade.

---

### Etapa 2: Parar de gastar dinheiro com processos manuais

**Nome da ferramenta:** [AWS Lambda](https://aws.amazon.com/pt/pm/lambda/?trk=eb8e67b6-648e-435d-827b-0320e72800e4&sc_channel=ps&trk=eb8e67b6-648e-435d-827b-0320e72800e4&sc_channel=ps&ef_id=CjwKCAiAmKnKBhBrEiwAaqAnZ8AtujhO0RlZJyIwsOzcAJS56zJG0mNSCsrLkYyC-rGlRwnv6KcKTxoCPOQQAvD_BwE:G:s&s_kwcid=AL!4422!3!780600535884!e!!g!!aws%20lambda&gad_campaignid=23183029123&gbraid=0AAAAADjHtp9vDk9GeCd0jY3qHlUl1kToM&gclid=CjwKCAiAmKnKBhBrEiwAaqAnZ8AtujhO0RlZJyIwsOzcAJS56zJG0mNSCsrLkYyC-rGlRwnv6KcKTxoCPOQQAvD_BwE)  

**Foco da ferramenta:** Automação e redução de custo operacional  

**Descrição de caso de uso:**  
Automatizar a coleta, tratamento e atualização diária dos dados armazenados no Amazon S3, eliminando processos manuais e retrabalho.  
O AWS Lambda executa apenas quando necessário, sem a necessidade de manter servidores ligados continuamente, reduzindo custos operacionais e dependência de tarefas manuais.

**Impacto direto:**  
Menos horas de trabalho desperdiçadas e decisões mais rápidas.

**Por que agora?**  
Porque tempo também é dinheiro, e a automação reduz custos operacionais silenciosos.

---

### Etapa 3: Usar dados para vender melhor e lucrar com B2B

**Nome da ferramenta:** [Amazon DynamoDB](https://aws.amazon.com/pt/dynamodb/?trk=ff977fff-9e97-47bf-974b-6546e42362bb&sc_channel=ps&trk=ff977fff-9e97-47bf-974b-6546e42362bb&sc_channel=ps&ef_id=CjwKCAiAmKnKBhBrEiwAaqAnZ1Q-WfJpD1-7dvpm7wuUNr7p8dKSx8T2MYgBlumlBaDbIGka4O5B1RoCDIAQAvD_BwE:G:s&s_kwcid=AL!4422!3!780600732438!e!!g!!amazon%20dynamodb&gad_campaignid=23173424571&gbraid=0AAAAADjHtp8vUPrmkEKhBXemAmHOv4FTr&gclid=CjwKCAiAmKnKBhBrEiwAaqAnZ1Q-WfJpD1-7dvpm7wuUNr7p8dKSx8T2MYgBlumlBaDbIGka4O5B1RoCDIAQAvD_BwE)  

**Foco da ferramenta:** Análise rápida para decisões de negócio e B2B  

**Descrição de caso de uso:**  
Armazenar dados consolidados e tratados (clientes, produtos, pedidos, margens e frequência de compra) para consultas rápidas e geração de relatórios.  
Essa estrutura permite identificar clientes B2B lucrativos versus clientes que geram prejuízo, apoiar reajustes de preços, renegociação de contratos e criação de ofertas B2B mais inteligentes.

**Impacto direto:**  
Interrupção do subsídio a clientes não lucrativos e foco em clientes que geram margem.

**Por que finalizar com esta etapa?**  
Porque aqui a empresa deixa de apenas economizar e passa a ganhar margem, especialmente no B2B.

---

## Resumo Simplificado

Primeiro, cortam-se desperdícios de dinheiro e tempo.  
Em seguida, otimiza-se a operação.  
Por fim, utilizam-se dados para aumentar a margem de lucro.

---

## Conclusão

A implementação das ferramentas propostas na empresa Abstergo tem como resultado esperado a redução de custos financeiros por meio da diminuição de desperdícios de produtos e de horas gastas em trabalhos manuais, da centralização e proteção dos dados estratégicos, do ganho de agilidade em processos tecnológicos e da criação de uma base de dados sólida para ampliação da margem de lucro.

Essas ações tendem a aumentar a eficiência e a produtividade da empresa.  
Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam aprimorar ainda mais os processos organizacionais.

---

## Anexos

- [Baixar relatório complementar em PDF](https://github.com/DaDosValle/relatorio_implementacao_cloud_aws/blob/relatorio-aws/Relatorio_Implementacao_AWS_Abstergo(ficticio).pdf)


-------

**Assinatura do Responsável pelo Projeto:**  

Fernando do Valle

[Meu Linkedin](https://www.linkedin.com/in/fernando-do-valle/)



