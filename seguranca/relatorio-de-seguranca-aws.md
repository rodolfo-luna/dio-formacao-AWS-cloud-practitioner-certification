RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 07/07/2023 Empresa: Abstergo Industries Responsável: Rodolfo Ferreira

Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Rodolfo Ferreira. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: - Controle de Acesso:

Autenticação de múltiplos fatores (MFA): O objetivo é configurar a autenticação de múltiplos fatores para contas de usuário da AWS, o que adiciona uma camada adicional de segurança exigindo um segundo fator de autenticação, como um token de segurança ou um aplicativo de autenticação no celular.

Gerenciamento de identidade e acesso (IAM): Configuração do IAM para criar políticas de acesso granulares e atribuir permissões aos usuários, grupos e funções. Isso permite controlar quem pode acessar seus recursos da AWS e quais ações eles podem executar.

Regras de firewall: Configuração de grupos de segurança do Amazon EC2 para controlar o tráfego de rede para nossas instâncias. Restroção das portas e os protocolos abertos somente ao necessário e limite o acesso às fontes confiáveis.

Medida 2: - Monitoramento e Detecção de Anomalias:

Amazon CloudWatch: Utilização do CloudWatch para monitorar as instâncias, serviços e recursos da AWS. Configuração de alarmes para ser notificado sobre atividades suspeitas ou comportamento anormal.

AWS CloudTrail: Ativar o CloudTrail para registrar todas as ações da API na conta da AWS. Isso fornece um registro detalhado de todas as atividades, permitindo a auditoria e rastreamento de eventos para identificar possíveis ameaças ou ações não autorizadas.

Amazon GuardDuty: Implementação do GuardDuty, um serviço de detecção de ameaças gerenciado pela AWS. Ele utiliza aprendizado de máquina e análise de comportamento para identificar atividades maliciosas ou suspeitas em nossa conta da AWS.

Medida 3: - Criptografia e Proteção de Dados:

Criptografia de dados em trânsito: Utilização de comunicações seguras usando SSL/TLS (HTTPS) para criptografar o tráfego entre os usuários e nossos aplicativos, bem como entre os serviços da AWS.

Criptografia de dados em repouso: Utilização de serviços como o Amazon S3 e o Amazon EBS para criptografar nossos dados em repouso. Utilizaremos chaves gerenciadas pela AWS (AWS KMS) ou chaves gerenciadas pela empresa (BYOK) para controlar o acesso às chaves de criptografia.

Backup e recuperação de dados: Implementação de uma estratégia de backup adequada para proteger os dados da empresa contra perda ou corrupção. Utilizaremos os serviços como o Amazon S3 e o Amazon Glacier para armazenar backups seguros e de longo prazo.

Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado a segurança dos dados, evitando que pessoas não autorizadas, tenham acesso e o controle de acesso pelos usuários da empresa, bem como auditoria de utilização dos serviços, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Anexos

https://docs.aws.amazon.com/pt_br/outposts/latest/userguide/identity-access-management.html

https://aws.amazon.com/pt/cloudwatch/

https://aws.amazon.com/pt/cloudtrail/

https://aws.amazon.com/pt/guardduty/

https://aws.amazon.com/pt/kms/

Assinatura do Responsável pelo Projeto:

Rodolfo Ferreira
