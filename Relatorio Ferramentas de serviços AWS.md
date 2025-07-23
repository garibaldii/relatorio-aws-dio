# RELATORIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 23/07/2025

Empresa: Abstergo Pharmaceutical Industries

Responsável: Matheus Garibaldi Rodrigues

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Pharmaceutical Industries, realizado por Matheus Garibaldi Rodrigues. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Processamento Econômico de Dados

* __Ferramenta__: __AWS Lambda__
* __Foco__: Eliminar servidores ociosos com computação sob demanda
* __Descrição de uso__: Com o AWS Lambda, a empresa pode executar códigos para tarefas como geração de relatórios, automação de backups e integração de sistemas sem manter servidores em funcionamento contínuo. Isso resulta em economia significativa, pois o custo é baseado apenas no tempo real de execução. Ideal para tarefas recorrentes de curta duração e eventos automatizados.

### Etapa 2: Banco de Dados com Custos Otimizados

* __Ferramenta__: __Amazon RDS (Relational Database Service)__
* __Foco__: Reduzir custos com manutenção e escalar de acordo com a demanda.
* __Descrição de uso__: O Amazon RDS permite que a empresa utilize bancos relacionais como PostgreSQL ou MySQL de forma gerenciada, com backups automáticos e escalabilidade. A equipe de TI não precisa mais realizar manutenção manual de servidores de banco de dados, o que reduz custos de pessoal e falhas operacionais. Permite o uso de instâncias sob demanda ou reservadas, dependendo da necessidade.

### Etapa 3: Hospedagem Escalável com Economia

* __Ferramenta__: __Amazon EC2 com Auto Scaling + Spot Instances__
* __Foco__:  Reduzir custos com infraestrutura de servidores.
* __Descrição__: A empresa pode hospedar aplicações web, sistemas internos ou APIs em instâncias EC2 que são escaladas automaticamente conforme o uso. Durante horários de menor demanda, o sistema reduz o número de instâncias, e, para tarefas não críticas, pode-se usar Spot Instances, que oferecem descontos de até 90% em comparação às instâncias padrão.

## Conclusão

As ferramentas da AWS escolhidas neste projeto têm como principal objetivo reduzir os custos da empresa Abstergo Pharmaceutical Industries. Usando o AWS Lambda, a empresa consegue rodar tarefas rápidas sem pagar por um servidor ligado o tempo todo. Com o Amazon RDS, ela usa um banco de dados pronto, sem precisar cuidar da manutenção. E com o Amazon EC2 com Auto Scaling e Spot Instances, consegue rodar sistemas pagando menos por servidores, ajustando conforme a necessidade. Com essas mudanças, a empresa gasta menos, mas continua com bom desempenho. É importante continuar usando essas ferramentas e estudar outras opções da AWS que também podem ajudar a economizar mais.

## Anexos

Abaixo, segue a documentação referente a cada ferramenta a ser utilizada, junto de seus guias ténicos e instruções de implementação.

### AWS Lambda

Mostra como criar funções que rodam na nuvem, sem precisar de servidor. Ensina como configurar, testar e automatizar tarefas.


https://docs.aws.amazon.com/lambda/

### Amazon RDS 

Explica como criar, configurar e usar bancos de dados prontos na nuvem, como MySQL e PostgreSQL. 

https://docs.aws.amazon.com/rds

### Amazon EC2 - Auto Scaling & Spot Instances

Ensina a criar servidores EC2, configurar o Auto Scaling para aumentar ou reduzir automaticamente o número de máquinas, e usar Spot Instances para economizar.

https://docs.aws.amazon.com/autoscaling/
https://docs.aws.amazon.com/ec2-spot/


###
------
###

### Assinatura do Responsável pelo Projeto:

### Matheus Garibaldi Rodrigues