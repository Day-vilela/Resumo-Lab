# 📘 Resumo de Aula – Computação em Nuvem e Microsoft Azure

## 👨‍🎓 Sobre o Documento
Este documento tem como objetivo registrar os principais aprendizados obtidos durante as aulas sobre **Computação em Nuvem** e a utilização da plataforma **Microsoft Azure**, abordando conceitos, modelos de serviço, benefícios, além das funcionalidades práticas do Azure Portal.

---

## ☁️ O que é Computação em Nuvem?

Computação em Nuvem é um modelo de entrega de recursos de TI como **servidores**, **armazenamento**, **redes**, **software** e **inteligência artificial** via internet. O principal objetivo é oferecer **acesso sob demanda**, **escalabilidade** e **pagamento conforme o uso**, eliminando a necessidade de manter infraestrutura física local.

---

## 🧰 Modelos de Serviço na Nuvem

| Modelo | Descrição | Responsabilidade do Usuário | Exemplo |
|--------|-----------|------------------------------|---------|
| **IaaS** | Infraestrutura como serviço | Sistema operacional, apps, dados | Máquinas Virtuais (Azure VM) |
| **PaaS** | Plataforma como serviço | Apenas o código e os dados | Azure App Service |
| **SaaS** | Software como serviço | Apenas o uso do app | Microsoft 365 |

---

## 🏗️ Modelos de Implantação

- **Nuvem Pública**: Infraestrutura compartilhada (ex: Azure, AWS).
- **Nuvem Privada**: Infraestrutura exclusiva para uma organização.
- **Nuvem Híbrida**: Combina os dois modelos para maior flexibilidade.

---

## ✅ Vantagens da Computação em Nuvem

- **Escalabilidade automática**
- **Redução de custos operacionais**
- **Alta disponibilidade**
- **Facilidade de backup e recuperação**
- **Acesso remoto de qualquer lugar**

---

## 🔷 Microsoft Azure – Introdução

O **Microsoft Azure** é uma plataforma de computação em nuvem da Microsoft que oferece mais de 200 produtos e serviços em nuvem, como:
- Máquinas Virtuais
- Bancos de Dados SQL
- Serviços de Web e APIs
- Monitoramento e Segurança
- IA e Machine Learning

---

## 🧭 Recursos do Azure Portal

### 🖥️ Dashboard Personalizável
- Painel inicial com blocos informativos
- Pode ser customizado por projeto ou equipe

### 🧱 Grupos de Recursos
- Organização lógica dos serviços utilizados em conjunto

### 🛒 Azure Marketplace
- Catálogo de soluções prontas (ex: WordPress, MongoDB, Ubuntu)

### 💻 Azure Cloud Shell
- Terminal embutido no navegador (Bash ou PowerShell)
- Executa comandos e scripts via CLI sem sair do portal

### 📊 Azure Monitor
- Coleta métricas e logs
- Permite criar alertas e painéis de performance

### 🔐 Controle de Acesso (IAM)
- Permissões baseadas em papéis (RBAC)
- Segurança na gestão de usuários e equipes

### 💡 Azure Advisor
- Dicas automáticas para melhorar performance, segurança e custo

### 💰 Billing & Cost Management
- Visualização de gastos por recurso
- Alertas e orçamentos configuráveis

---

## 📚 Conclusão

A computação em nuvem representa uma evolução na forma como os sistemas são construídos, escalados e mantidos. O uso do **Microsoft Azure** facilita essa jornada com uma interface amigável e uma grande variedade de ferramentas para desenvolvedores, empresas e estudantes.

---

## 📝 Glossário

- **IaaS**: Infrastructure as a Service
- **PaaS**: Platform as a Service
- **SaaS**: Software as a Service
- **RBAC**: Role-Based Access Control
- **CLI**: Command Line Interface

---

# Comparação de Serviços de Nuvem ☁️

## 📚 Introdução
Com a crescente adoção de computação em nuvem, é essencial entender as diferenças entre os principais provedores — **AWS**, **Microsoft Azure** e **Google Cloud Platform (GCP)** — além dos modelos de serviço oferecidos: **IaaS**, **PaaS** e **SaaS**. Também é importante conhecer o modelo de **responsabilidade compartilhada** adotado pelos provedores.

---

## ☁️ Modelos de Serviço em Nuvem

### 🔧 IaaS (Infrastructure as a Service)
- **O que é**: Infraestrutura básica fornecida como serviço (rede, servidores, VMs).
- **Responsabilidade do cliente**: Sistema operacional, middleware, dados, runtime e aplicações.
- **Exemplos**: Amazon EC2, Azure Virtual Machines, Google Compute Engine.

### 🧱 PaaS (Platform as a Service)
- **O que é**: Plataforma completa para desenvolvimento e hospedagem de aplicações.
- **Responsabilidade do cliente**: Somente o código da aplicação e dados.
- **Exemplos**: AWS Elastic Beanstalk, Azure App Service, Google App Engine.

### 💻 SaaS (Software as a Service)
- **O que é**: Software pronto para uso, acessado via navegador ou app.
- **Responsabilidade do cliente**: Uso da aplicação.
- **Exemplos**: Google Workspace, Microsoft 365, Salesforce.

---

## 🛡️ Modelo de Responsabilidade Compartilhada

> Na computação em nuvem, a **segurança e conformidade** são uma **responsabilidade compartilhada** entre o **provedor** e o **cliente**.

| Elemento                          | Responsável no IaaS | Responsável no PaaS | Responsável no SaaS |
|----------------------------------|----------------------|----------------------|----------------------|
| Físico (rede, datacenter, disco) | Provedor             | Provedor             | Provedor             |
| Virtualização/Sistema Operacional| Cliente              | Provedor             | Provedor             |
| Aplicações e Dados               | Cliente              | Cliente              | Provedor (com uso do cliente) |
| Configurações de segurança       | Cliente              | Parcialmente Cliente | Geralmente Cliente (usuário final) |

🔐 **Resumo**:
- Quanto mais "as a Service", **menos responsabilidade técnica** para o cliente.
- O cliente **ainda é responsável** por configurar acessos, usar senhas fortes, proteger seus dados, etc.

---

## 🔍 Principais Provedores e Comparação

| Critério                 | AWS                         | Azure                          | GCP                            |
|--------------------------|-----------------------------|--------------------------------|--------------------------------|
| **Início**               | 2006                        | 2010                           | 2008                           |
| **Popularidade**         | Mais utilizado              | Forte em empresas Microsoft    | Forte em dados e IA            |
| **Facilidade de uso**    | Curva de aprendizado média  | Integração nativa com Windows  | Interface amigável e intuitiva |
| **Serviços Notáveis**    | EC2, S3, Lambda              | VMs, Blob Storage, Azure ML    | Compute Engine, BigQuery       |
| **Preços**               | Modelo pay-as-you-go        | Similar ao AWS                 | Competitivo e flexível         |
| **Suporte e Comunidade** | Comunidade ampla e ativa    | Suporte corporativo forte      | Crescendo rapidamente          |

---

## 🧪 Casos de Uso

- **AWS**: Projetos escaláveis e globais, com grande variedade de serviços.
- **Azure**: Empresas que já utilizam Windows Server, Active Directory, etc.
- **GCP**: Projetos focados em análise de dados, machine learning e escalabilidade.

---

## ✅ Conclusão

Não existe um "melhor" provedor — a escolha depende do **caso de uso**, **custo**, **facilidade de integração** e **preferência da equipe**. Em muitos casos, empresas optam por uma **estratégia multi-cloud** para aproveitar o melhor de cada plataforma.

---

## 📎 Referências
- [AWS Overview](https://aws.amazon.com/)
- [Microsoft Azure](https://azure.microsoft.com/)
- [Google Cloud](https://cloud.google.com/)
- [Shared Responsibility Model – AWS](https://aws.amazon.com/compliance/shared-responsibility-model/)



## ✍️ Autor

**Nome:** Daiane Vilela  
**Disciplina:** Computação em Nuvem - Dio - Java Cloud Native
**Data:** Maio de 2025

