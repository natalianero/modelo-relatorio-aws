# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 17/03/2024
Empresa: Abstergo Industries 
Responsável: Natália Cristina Claudino da Silva

## Introdução
Este relatório detalha o processo de implementação de ferramentas da Amazon Web Services (AWS) na Abstergo Industries, conduzido pelo especialista em AWS, Natália Cristina Claudino da Silva. O objetivo principal deste projeto foi identificar e implementar três serviços da AWS com o intuito de otimizar a infraestrutura tecnológica da empresa, reduzir custos operacionais e melhorar a eficiência geral dos processos.

## Descrição do Projeto
O projeto de implementação de ferramentas AWS foi elaborado com base em uma análise abrangente das necessidades da Abstergo Industries e das oportunidades oferecidas pelos serviços da AWS. O processo foi dividido em três etapas distintas, cada uma com seus objetivos específicos e metodologia de implementação.

Etapa 1: Amazon S3 (Simple Storage Service)
- Objetivo: Implementar um repositório centralizado para armazenamento seguro e escalável de dados.
- Metodologia: Inicialmente, foi realizada uma análise detalhada dos requisitos de armazenamento de dados da empresa, incluindo tipos de dados, volumes e requisitos de segurança. Em seguida, foi configurado um bucket do Amazon S3 de acordo com as melhores práticas de segurança e acesso, garantindo a conformidade com regulamentações da indústria farmacêutica.
- Caso de Uso: O Amazon S3 foi utilizado para armazenar documentos regulatórios, dados de pesquisa e desenvolvimento, backups de sistemas críticos e arquivos de produção. A integração com outras ferramentas da AWS, como o AWS Lambda e o AWS Glue, permitiu automatizar processos de ETL (Extract, Transform, Load) e garantir a integridade dos dados armazenados.

Etapa 2: Amazon EC2 (Elastic Compute Cloud) 
- Objetivo: Configurar instâncias virtualizadas para execução de aplicativos farmacêuticos, garantindo escalabilidade e otimização de recursos.
- Metodologia: Após uma análise detalhada das cargas de trabalho e requisitos de desempenho dos aplicativos farmacêuticos, foram configuradas instâncias EC2 com base em instâncias otimizadas para CPU e memória. Foram implementados Auto Scaling Groups para ajustar automaticamente a capacidade de computação conforme a demanda, garantindo alta disponibilidade e eficiência na utilização dos recursos.
- Caso de Uso: As instâncias EC2 foram utilizadas para executar aplicativos de simulação molecular, análise de dados genômicos e modelagem farmacocinética. A flexibilidade e escalabilidade oferecidas pelo EC2 permitiram que a Abstergo Industries atendesse às demandas variáveis de computação, mantendo baixos custos operacionais.

Etapa 3: Amazon RDS (Relational Database Service)
- Objetivo: Migração dos sistemas de gerenciamento de banco de dados para a AWS, proporcionando maior segurança, desempenho e flexibilidade.
- Metodologia: Inicialmente, foi realizada uma avaliação detalhada dos sistemas de gerenciamento de banco de dados existentes, identificando os principais desafios e requisitos de migração. Em seguida, foi planejada e executada a migração para o Amazon RDS, com foco na minimização do tempo de inatividade e na maximização da integridade dos dados.
- Caso de Uso: O Amazon RDS foi utilizado para hospedar bancos de dados relacionais, incluindo dados de pacientes, históricos médicos e registros de ensaios clínicos. A alta disponibilidade, a escalabilidade automática e os backups automatizados oferecidos pelo RDS garantiram a continuidade operacional e a segurança dos dados críticos da empresa.



## Conclusão
A implementação das ferramentas AWS na Abstergo Industries representou um marco significativo na modernização e na otimização da infraestrutura tecnológica da empresa. A integração dessas ferramentas permitiu reduzir custos operacionais, aumentar a eficiência e a escalabilidade dos processos, e garantir a conformidade com regulamentações da indústria farmacêutica. Recomenda-se a continuidade da utilização das ferramentas implementadas e a exploração de novas tecnologias e serviços da AWS que possam aprimorar ainda mais os processos e a competitividade da Abstergo Industries no mercado farmacêutico. Este projeto exemplifica o compromisso da Abstergo Industries com a inovação e a excelência operacional, posicionando-a como uma líder na adoção de tecnologias de nuvem para impulsionar o crescimento e o sucesso sustentável.

## Anexos

Assinatura do Responsável pelo Projeto:

[Natália Cristina Claudino da Silva]