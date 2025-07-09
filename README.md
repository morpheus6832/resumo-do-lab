# resumo-do-lab
"Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO".
Aqui está um resumo conciso dos fundamentos para aprender Microsoft Azure:

1. O que é o Azure?
- Plataforma de Nuvem Pública: Conjunto de serviços de computação, armazenamento, rede, IA e análise oferecidos pela Microsoft via internet.
- Modelo de Responsabilidade Compartilhada: A Microsoft gerencia infraestrutura física/segurança; você gerencia dados/aplicações.

2. Conceitos Essenciais
- Assinatura: Unidade básica de faturamento e gestão de recursos.
- Regiões: Data centers globais (ex: "Brasil Sul"). Escolha conforme compliance e latência.
- Grupos de Recursos: Contêineres lógicos para organizar serviços relacionados (ex: um grupo para um app + banco de dados).
- Azure Resource Manager (ARM): Ferramenta para implantar/gerenciar recursos via templates (JSON).

3. Serviços Principais
- Computação:
  - Máquinas Virtuais (VMs): IaaS (infra como serviço).
  - Azure App Service: PaaS (plataforma como serviço) para apps web/mobile.
  - Azure Functions: Serverless (execução por evento).
- Armazenamento:
  - Blob Storage: Arquivos não estruturados (imagens, vídeos).
  - Azure SQL Database: Banco de dados relacional gerenciado.
  - Cosmos DB: Banco de dados NoSQL multi-modelo.
- Rede:
  - Virtual Network (VNet): Rede isolada na nuvem.
  - Load Balancer/Aplication Gateway: Distribuição de tráfego.
  - VPN Gateway: Conexão segura com redes locais.

4. Ferramentas de Gerenciamento
- Portal Azure: Interface web para gerenciar recursos.
- Azure CLI/PowerShell: Automação via linha de comando.
- Azure Monitor: Coleta e analisa telemetria (logs, métricas).

5. Segurança Básica
- Azure Active Directory (AD): Gerenciamento de identidade e acesso.
- Network Security Groups (NSGs): Firewall para redes/VMs.
- Azure Policy: Garantir conformidade de recursos.

6. Custos
- Modelo Pay-as-you-go: Pago apenas pelo que usar.
- Azure Pricing Calculator: Estime custos antes de implantar.
- Tags: Organize recursos para otimizar faturamento.

7. Como Começar?
1. Crie uma Conta Gratuita: US$200 em créditos + serviços populares grátis por 12 meses.
2. Treinamentos Oficiais:
   - Microsoft Learn: Cursos gratuitos (módulos interativos).
   - Certificação AZ-900: Exame de fundamentos (recomendado para iniciantes).
3. Hands-on: Experimente criar VMs, bancos de dados e apps simples.

