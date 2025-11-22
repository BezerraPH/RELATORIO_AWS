***

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 22/11/2025
**Empresa:** Abstergo Industries
**Responsável:** Pedro Henrique Bezerra de Oliveira

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Pedro Henrique Bezerra de Oliveira**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos, focando na otimização de armazenamento de dados de pesquisa e na capacidade computacional ociosa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1:
- **Nome da ferramenta:** Amazon S3 Intelligent-Tiering
- **Foco da ferramenta:** Otimização automática de custos de armazenamento.
- **Descrição de caso de uso:** Com o *Intelligent-Tiering*, o sistema irá gerenciar automaticamente os arquivos da Abstergo, para camadas de acesso frequente ou infrequente baseando-se no uso real, sem que a equipe de TI precise fazer isso manualmente, gerando economia imediata no armazenamento de longo prazo.

### Etapa 2:
- **Nome da ferramenta:** Amazon EC2 Auto Scaling
- **Foco da ferramenta:** Elasticidade de computação e eliminação de capacidade ociosa.
- **Descrição de caso de uso:** Durante a noite e fins de semana muitas vezes os servidores operam com "Unused Capacity" (capacidade não utilizada). Implementaremos o Auto Scaling para garantir "melhor gerenciamento de custos". O serviço ajustará a capacidade conforme a necessidade (Scale out as needed), garantindo economia de recursos e custo ao evitar o provisionamento excessivo para picos de demanda.

### Etapa 3:
- **Nome da ferramenta:** Amazon Aurora
- **Foco da ferramenta:** Redução de custos de licenciamento e operação de Banco de Dados Relacional.
- **Descrição de caso de uso:** A principal vantagem financeira é que o Aurora possui um "preço 1/10 de outros vendors", além de ser Serverless, o que reduz a sobrecarga administrativa.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a eliminação de gastos com recursos ociosos e a automação do ciclo de vida dos dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

1.  Documentação sobre Classes de Armazenamento S3: [https://aws.amazon.com/pt/s3/storage-classes/]
2.  Guia do Usuário para Escalabilidade (Auto Scaling): [https://docs.aws.amazon.com/pt_br/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html]
3.  Visão Geral do Amazon Aurora: [https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html]

**Assinatura do Responsável pelo Projeto:**

*Pedro Henrique Bezerra de Oliveira*
Analista de Sistemas / Cloud Beginner
