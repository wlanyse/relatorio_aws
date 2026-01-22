
Redução dos Custos em Farmácias com AWS


\**RELATORIO DE IMPLEMENTACAO DE SERVICOS AWS**



Data: 20/01/2026

Empresa: Abstergo Industries 

Responsável: Wlanyse Pantoja Beckman





** Introdução**

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Wlanyse Pantoja Beckman. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar a diminuição de custos imediatos.





** Descrição do Projeto**

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:


**Etapa 1:** 

\- **Amazon Elastic Compute Cloud - EC2**

\- é um serviço da AWS que oferece capacidade computacional escalável na nuvem. Ele permite que você crie e execute instâncias virtuais (servidores) que podem ser configuradas para atender às necessidades de seus aplicativos, seja para ambientes de desenvolvimento, teste ou produção.O EC2 elimina a necessidade de investimento em hardware físico, oferecendo flexibilidade para aumentar ou reduzir a capacidade computacional de acordo com a demanda, cobrando apenas pelo que for utilizado. As instâncias EC2 suportam diversos sistemas operacionais, como Linux e Windows, e podem ser integradas a outros serviços da AWS, como o Elastic Block Store (EBS) para armazenamento persistente. Esse serviço é amplamente utilizado por empresas para executar desde pequenas aplicações até grandes sistemas, devido à sua segurança, confiabilidade e capacidade de se ajustar a diferentes tipos de workload​s.

\- Hospedagem de Aplicações Web e Empresariais: Hospede blogs, sites de e-commerce e sistemas corporativos, aproveitando a escalabilidade e alta performance.
Ambientes de Desenvolvimento e Teste (Dev/Test): Provisione e destrua ambientes rapidamente para desenvolvedores, pagando apenas pelo uso.
Machine Learning (ML) e Inteligência Artificial (IA): Use instâncias com GPU para treinar modelos complexos e rodar cargas de trabalho de IA, com opções como os EC2 Capacity Blocks para ML.
Computação de Alto Desempenho (HPC): Execute modelagem científica, simulações e análise de grandes conjuntos de dados de forma econômica.
Processamento em Lote (Batch Processing): Processamento de grandes volumes de dados, transcodificação de mídia e tarefas de análise que não precisam de execução em tempo real.
Servidores Dedicados para Jogos: Hospede servidores para jogos online, escalando conforme a demanda de jogadores.
Desenvolvimento Apple: Crie e teste aplicativos para macOS sob demanda com as instâncias Mac do EC2.
Big Data e Análise: Fornece poder computacional para processar grandes volumes de dados, muitas vezes integrado com serviços como EMR ou Redshift. 



**Etapa 2:** 

\- **Amazon Redshift**

\- é um serviço de data warehouse totalmente gerenciado na nuvem, projetado para processar grandes volumes de dados com alta performance e escalabilidade.O Redshift oferece uma relação custo-benefício excepcional, com performance até 3 vezes melhor e throughput 7 vezes maior em comparação com outros data warehouses na nuvem.

\- O Redshift permite consultas em dados armazenados no Amazon S3 sem necessidade de transferências, suportando formatos abertos com alta performance. Ele também integra dados de fontes como Amazon Aurora, RDS e DynamoDB, além de serviços de streaming como Amazon Kinesis e MSK, para análises quase em tempo real.

\- A integração com o Amazon SageMaker possibilita análises avançadas e machine learning diretamente no Redshift. Além disso, o Amazon Q simplifica a criação de consultas SQL usando linguagem natural, aumentando a produtividade dos usuários.O Amazon Redshift é uma solução poderosa para empresas que buscam análises escaláveis, seguras e de alta performance. Ele combina flexibilidade, integração com o ecossistema AWS e facilidade de uso, tornando-se uma escolha estratégica para organizações que desejam extrair valor de seus dados.



**Etapa 3:** 

\- **Amazon Elastic Block Store - EBS**

\- O Amazon EBS permite que você crie volumes de armazenamento e os anexe a instâncias do Amazon EC2. Depois de conectado, é possível criar um sistema de arquivos sobre esses volumes, executar um banco de dados ou utilizá-los como se fossem armazenamento em bloco. Os volumes do Amazon EBS são inseridos em uma zona de disponibilidade específica, na qual são replicados automaticamente para protegê-los de falhas em um único componente. Todos os tipos de volumes do EBS oferecem recursos de snapshots(backups) duráveis e são projetados para alta disponibilidade. 

\- Sistemas Operacionais (Volumes de Inicialização): Anexar volumes EBS para hospedar o sistema operacional de instâncias EC2, permitindo que persistam mesmo após a instância ser terminada.
Bancos de Dados: Hospedar bancos de dados como MySQL, PostgreSQL, SQL Server, Oracle, SAP HANA e Cassandra, aproveitando os tipos de volume otimizados para IOPS ou throughput.
Aplicações de Alto Desempenho: Suportar aplicações que exigem acesso rápido e frequente a dados, como sistemas ERP e CRM.
Volumes de Dados: Usar como disco rígido local para armazenar arquivos de aplicações, logs ou qualquer dado que precise de armazenamento persistente fora da instância.
Backups e Recuperação de Desastres: Criar snapshots (cópias pontuais) de volumes EBS para backups, migração de dados e recuperação de desastres, com armazenamento incremental no S3.
Desenvolvimento e Testes: Capturar estados de volumes de produção para criar ambientes de teste e desenvolvimento seguros. 






** Conclusão**

A implementação de ferramentas na empresa Abstergo Industries tem como esperado: escalabilidade, flexibilidade, alta performance, segurança e com um custo-benefício excepcional, o que aumentara¡ a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.



Assinatura do Responsável pelo Projeto: 
<br>Wlanyse Pantoja Beckman</br>

