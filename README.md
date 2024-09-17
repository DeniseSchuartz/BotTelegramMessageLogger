# Análise e Processamento de Dados de Bot do Telegram com AWS e SQL

## Descrição

Este projeto demonstra a criação de um pipeline eficiente para capturar e analisar grandes volumes de mensagens de um grupo no Telegram, integrando essas mensagens a uma infraestrutura robusta usando serviços da AWS. Utilizando AWS Lambda, S3, Athena e EventBridge, construímos uma solução escalável para armazenamento e análise em tempo real das mensagens.

## Funcionalidades
* **Captura de Mensagens:** Recebe e armazena mensagens em tempo real.
* **Armazenamento em S3:** Armazena as mensagens de forma eficiente e escalável.
* **Processamento com Lambda:** Processa e transforma mensagens automaticamente.
* **Análise com Athena:** Permite consultas SQL avançadas para análise de dados.
* **Automação com EventBridge:** Garante o fluxo contínuo de dados e eventos.
  
## Benefícios

* **Escalabilidade:** Lida automaticamente com altos volumes de dados.
* **Análise em Tempo Real:** Mensagens prontas para consulta e análise com mínima intervenção manual.
* **Aplicações Práticas:** Monitoramento de redes sociais, análise de feedback de clientes, e estudos de comportamento e comunicação.
  

## Cenários de Uso

* **Monitoramento de Redes Sociais:** Acompanhe interações em grupos de trabalho e a eficiência da comunicação interna.
* **Análise de Feedback de Clientes:** Capture e analise feedback em grupos de suporte para melhorar produtos e serviços.
* **Estudos de Comportamento:** Identifique padrões de comportamento e comunicação, como horários de atividade e palavras mais utilizadas.

## Requisitos

* Conta na AWS
* Permissões para criar e gerenciar serviços AWS (Lambda, S3, Athena, EventBridge)
* Conhecimento básico em SQL para consultas no Athena

## Instalação
1. Clone o repositório:
`https://${GITHUB_USER}:${GITHUB_TOKEN}@github.com/DeniseSchuartz/BotTelegramMessageLogger-.git`

2. Configuração dos Serviços AWS:

* Configure AWS Lambda para processar mensagens.
* Crie um bucket no S3 para armazenamento de mensagens.
* Configure AWS Athena para consultas SQL.
* Configure o EventBridge para automatizar o fluxo de dados.

3. Deploy:

* Faça o upload do código Lambda para a AWS.
* Configure os gatilhos e permissões necessárias.
* Teste o pipeline com dados de exemplo.

## Uso

* **Consultas no Athena:** Utilize consultas SQL para analisar as mensagens e extrair insights, como picos de atividade e usuários mais ativos.
 
## Contribuição
Sinta-se à vontade para contribuir com melhorias ou correções. Para isso:
1. Faça um fork do projeto.
2. Crie uma branch para a sua feature (git checkout -b feature/nova-feature).
3. Faça o commit das suas alterações (git commit -am 'Adiciona nova feature').
4. Envie para o repositório (git push origin feature/nova-feature).
Abra um Pull Request.

## Licença
Este projeto está licenciado sob a MIT License.

## Contato
Para mais informações, entre em contato com denise.schuartz@hotmail.com.

