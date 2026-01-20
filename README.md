RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 20 de janeiro de 2026  
Empresa: Abstergo Industries  
Responsável: Naiane Chaves

Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Naiane Chaves. O objetivo do projeto foi aplicar três serviços da AWS com foco na redução de custos operacionais em farmácias, otimizando processos como controle de estoque, atendimento ao cliente e armazenamento de dados regulatórios.

Descrição do Projeto

O projeto foi dividido em três etapas, cada uma voltada para um aspecto crítico da operação farmacêutica. A seguir, são descritas as etapas e os serviços utilizados:

Etapa 1:
- Amazon EC2 Auto Scaling  
- Foco: Otimização de sistemas de gestão farmacêutica  
- Descrição de caso de uso: Utilização de Auto Scaling para ajustar automaticamente os servidores que rodam o sistema de gestão de estoque e vendas da farmácia. Isso garantiu desempenho adequado em horários de pico e economia nos períodos de menor movimento, reduzindo custos com infraestrutura ociosa.

Etapa 2:
- AWS Lambda  
- Foco: Automatização de tarefas administrativas e regulatórias  
- Descrição de caso de uso: Implementação de funções Lambda para automatizar tarefas como envio de alertas de validade de medicamentos, geração de relatórios para a Anvisa e integração com sistemas de prescrição eletrônica. Como o serviço é cobrado apenas por execução, houve economia significativa em comparação com servidores dedicados.

Etapa 3:
- Amazon S3 com Lifecycle Policies  
- Foco: Armazenamento econômico e seguro de documentos e receitas digitais  
- Descrição de caso de uso: Armazenamento de receitas digitalizadas, notas fiscais e documentos regulatórios em buckets S3 com políticas de ciclo de vida. Arquivos antigos foram automaticamente movidos para classes de armazenamento mais baratas (como S3 Glacier), reduzindo custos sem comprometer a conformidade com normas sanitárias.

Conclusão

A implementação dos serviços AWS na operação farmacêutica da empresa Abstergo Industries resultou em uma redução significativa de custos, maior eficiência nos processos internos e melhor aproveitamento dos recursos tecnológicos. As soluções adotadas também aumentaram a segurança e a escalabilidade dos sistemas, preparando a farmácia para futuras expansões. Recomenda-se a continuidade do uso dessas ferramentas e a avaliação de novas soluções AWS para aprimorar ainda mais os processos.

Anexos

- Manual de Auto Scaling para sistemas de farmácia  
- Scripts Lambda para automação de alertas e relatórios  
- Política de ciclo de vida do Amazon S3 para documentos regulatórios  
- Comparativo de custos antes e depois da implementação

Assinatura do Responsável pelo Projeto:  
Naiane Chaves#
