# ☁️ Bootcamp Java Cloud Native – Bradesco & DIO

Este repositório documenta os principais conceitos, práticas e ferramentas abordadas durante o Bootcamp **Java Cloud Native**, promovido pelo **Bradesco** em parceria com a plataforma **DIO (Digital Innovation One)**. O programa foca no desenvolvimento de aplicações modernas, escaláveis e resilientes utilizando Java, Spring Boot, microsserviços e computação em nuvem, com ênfase em DevOps e infraestrutura no Microsoft Azure.

---

## 📘 Conteúdo Detalhado

### 1. Fundamentos de Java

- **Paradigma Orientado a Objetos (POO):** Profundo entendimento dos pilares da POO — encapsulamento, herança, polimorfismo e abstração — para modelar sistemas complexos com reutilização e baixo acoplamento.
- **Gerenciamento de Coleções e Fluxos (Streams):** Uso avançado das coleções Java (List, Set, Map) e APIs funcionais para manipulação eficiente de dados, transformações e operações paralelas via Streams.
- **Tratamento de Exceções:** Estratégias para criar um fluxo robusto de exceção, utilizando blocos try-catch-finally, exceções customizadas, e boas práticas para manter a estabilidade da aplicação.
- **Gerenciamento de Memória e Garbage Collection:** Noções de heap, stack, e como o Java gerencia a memória automaticamente para evitar vazamentos e otimizar desempenho.

---

### 2. Desenvolvimento com Spring Boot

- **Arquitetura Spring Boot:** Criação de aplicações stand-alone com configuração automática (auto-configuration), que reduz a complexidade e acelera o desenvolvimento de APIs RESTful.
- **Spring Data JPA:** Abstração da camada de persistência, facilitando a manipulação de dados em bancos relacionais através do padrão Repository, consultas via JPQL e Criteria API.
- **Segurança Aplicacional:** Uso do Spring Security para implementar autenticação (via JWT, OAuth2) e autorização baseada em roles, garantindo proteção contra vulnerabilidades comuns como CSRF e XSS.
- **Testes Unitários e de Integração:** Aplicação de frameworks como JUnit 5 e Mockito para mocks e stubs, assegurando cobertura e confiabilidade do código por meio de testes automatizados.

---

### 3. Microsserviços e Arquitetura Cloud Native

- **Desenho de Microsserviços:** Quebra de sistemas monolíticos em serviços independentes, cada um com responsabilidades específicas, comunicação assíncrona e independência de deploy.
- **Comunicação entre Serviços:** Implementação de APIs RESTful e mensageria (RabbitMQ, Kafka) para troca eficiente de mensagens, com padrões de design como API Gateway e Service Discovery (Eureka).
- **Tolerância a Falhas:** Aplicação de padrões como Circuit Breaker (Hystrix), Retry e Bulkhead para garantir resiliência e continuidade dos serviços mesmo diante de falhas.
- **Orquestração e Contêineres:** Utilização de Kubernetes/OpenShift para orquestração de contêineres Docker, facilitando escalabilidade horizontal, balanceamento de carga e rollback automático.

---

### 4. DevOps e Integração Contínua (CI/CD)

- **Controle de Versão com Git:** Gestão de branches, pull requests e resolução de conflitos para trabalho colaborativo eficiente.
- **Automação com GitHub Actions:** Construção de pipelines automatizados para testes, builds, análise estática de código e deploy contínuo, reduzindo erros humanos e acelerando o ciclo de entrega.
- **Monitoramento e Logging:** Implementação de ferramentas como Prometheus, Grafana e ELK Stack para coletar métricas, logs e traçar o comportamento das aplicações em produção.
- **Infraestrutura como Código (IaC):** Uso de ferramentas como Terraform e ARM templates para provisionamento automatizado e versionado da infraestrutura.

---

### 5. Computação em Nuvem com Azure

- **Modelos de Serviço:** Exploração detalhada dos modelos IaaS (Infraestrutura como Serviço), PaaS (Plataforma como Serviço) e SaaS (Software como Serviço) e seus casos de uso ideais.
- **Azure Virtual Machines:** Provisionamento rápido e seguro de VMs no Azure via portal, configurando sistema operacional, tamanho, rede e regras de acesso, conforme [documentação oficial](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal).

  - **Configuração da VM:**
    - Escolha da imagem (Windows Server, Linux)
    - Tamanho da instância (CPU, RAM)
    - Credenciais e autenticação segura
    - Definição de regras de firewall e portas abertas (RDP, SSH, HTTP/HTTPS)
  
  - **Acesso Remoto:** Conexão via RDP ou SSH para gerenciamento direto da VM.
  
- **Azure App Service e Functions:** Implantação de aplicações web e funções serverless, permitindo escalabilidade automática e integração com outros serviços Azure.
- **Gerenciamento de Identidade:** Uso do Azure Active Directory para controle de acesso granular e autenticação multifator.
- **Segurança e Compliance:** Ferramentas integradas para monitoramento de segurança, prevenção contra ameaças e auditoria de conformidade regulatória.

---

## 🧠 Competências Desenvolvidas

- Design e implementação de APIs RESTful robustas e seguras com Java e Spring Boot.
- Arquitetura e operação de microsserviços distribuídos com alta disponibilidade e resiliência.
- Automação completa do ciclo de vida de software via pipelines CI/CD em GitHub Actions.
- Implantação e gerenciamento de recursos em nuvem pública (Microsoft Azure), incluindo VMs, serviços PaaS e segurança.
- Práticas avançadas de monitoramento, logging e troubleshooting em ambientes produtivos.
