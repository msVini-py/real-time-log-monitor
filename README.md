# real-time-log-monitor
Analisador de Logs em Tempo Real com WebSocket e Regex DinÃ¢mico

## Sobre o Projeto

Este projeto Ã© uma ferramenta de monitoramento de infraestrutura desenvolvida em Java com Spring Boot, capaz de acompanhar arquivos de log em tempo real, processar eventos utilizando Regex DinÃ¢mico e transmitir informaÃ§Ãµes instantaneamente para um dashboard web atravÃ©s de WebSocket.

O objetivo Ã© simular uma soluÃ§Ã£o de observabilidade utilizada em ambientes corporativos, permitindo identificar erros, avisos e eventos crÃ­ticos de forma rÃ¡pida.

---

## Funcionalidades

- Monitoramento contÃ­nuo de arquivos de log
- AtualizaÃ§Ã£o em tempo real via WebSocket
- Filtros utilizando Regex DinÃ¢mico
- Dashboard web para visualizaÃ§Ã£o dos eventos
- Contagem de logs INFO, WARNING e ERROR
- Arquitetura modular e escalÃ¡vel
- Base para futuras integraÃ§Ãµes com bancos de dados e ferramentas de observabilidade

---

## Tecnologias Utilizadas

- Java
- Spring Boot
- WebSocket
- Maven
- Regex
- HTML
- CSS
- JavaScript

---

## Estrutura do Projeto

```text
log-monitor/
â”‚
â”œâ”€â”€ src/
â”‚   â”œâ”€â”€ model/
â”‚   â”œâ”€â”€ service/
â”‚   â”œâ”€â”€ websocket/
â”‚   â”œâ”€â”€ controller/
â”‚   â””â”€â”€ LogMonitorApplication.java
â”‚
â”œâ”€â”€ logs/
â”‚   â””â”€â”€ application.log
â”‚
â”œâ”€â”€ dashboard/
â”‚   â””â”€â”€ index.html
â”‚
â”œâ”€â”€ pom.xml
â”œâ”€â”€ README.md
â””â”€â”€ .gitignore
```

---

## Como Executar

### Clonar o RepositÃ³rio

```bash
git clone https://github.com/seu-usuario/log-monitor-websocket.git
```

### Entrar no Projeto

```bash
cd log-monitor-websocket
```

### Executar

```bash
mvn spring-boot:run
```

### Acessar

```text
http://localhost:8080
```

---

## Exemplo de Log

```text
2025-06-05 INFO AplicaÃ§Ã£o iniciada

2025-06-05 ERROR Banco indisponÃ­vel

2025-06-05 WARNING MemÃ³ria alta

2025-06-05 ERROR Timeout API
```

---

## PossÃ­veis Melhorias

- Dashboard com Chart.js
- ExportaÃ§Ã£o CSV e PDF
- Docker e Docker Compose
- PostgreSQL
- Spring Security + JWT
- IntegraÃ§Ã£o com Telegram
- IntegraÃ§Ã£o com Discord
- Elasticsearch
- Kibana
- Kafka para processamento distribuÃ­do

---

## Aprendizados

Este projeto demonstra conhecimentos em:

- Desenvolvimento Backend com Java
- Spring Boot
- WebSocket
- ManipulaÃ§Ã£o de Arquivos
- ExpressÃµes Regulares (Regex)
- ProgramaÃ§Ã£o Concorrente (Threads)
- Arquitetura de Software
- Monitoramento e Observabilidade

---

## Autor
- Vinicius Mendes 
