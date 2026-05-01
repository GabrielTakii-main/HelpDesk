# HelpDesk
Plataforma corporativa de gestão de chamados com SLA, dashboards e notificações. Backend Django + DRF, Frontend React, PostgreSQL, Docker, CI/CD, monitoramento e logs. 

O HelpDesk é um sistema robusto para ambientes corporativos, permitindo **controle avançado de chamados**, workflow inteligente, métricas de SLA, dashboards interativos, notificações automáticas e segurança reforçada.

---

## Tecnologias Utilizadas

- **Backend:** Django + Django REST Framework  
- **Frontend:** React  
- **Banco de dados:** PostgreSQL  
- **Containerização:** Docker + Docker Compose  
- **CI/CD:** GitHub Actions (build, testes, deploy)  
- **Monitoramento:** Prometheus e Grafana  
- **Segurança:** JWT, OAuth2, proteção CSRF, XSS e SQL Injection
 
---

## Funcionalidades

- CRUD completo de **chamados** e **usuários**  
- Workflow avançado com status, prioridade e cálculo automático de SLA  
- Dashboard com métricas: chamados abertos/fechados, SLA, MTTR, prioridades  
- Notificações automáticas por email e SMS  
- Logs estruturados e monitoramento com alertas em tempo real  
- Testes automatizados: unitários, integração e end-to-end (E2E)  
- CI/CD completo para build, testes e deploy  
- Arquitetura modular/microservices para escalabilidade futura

---

## Como Executar

### Pré-requisitos:
- Docker e Docker Compose  
- Git

 ---

## Rodando o projeto localmente

### Clonar o repositório:
git clone https://github.com/GabrielTakii-Main/HelpDesk.git
cd HelpDesk

### Subir containers:
docker-compose up --build

Backend: http://localhost:8000

Frontend: http://localhost:3000


### Executando Testes:
```bash
Backend
cd backend
pytest

Frontend
cd frontend
npm install
npm test
```
> Todos os testes devem passar antes de merge na branch main.

---

## Roadmap & Evolução Concluída

Microservices: chamados, usuários, notificações

Dashboards avançados com SLA, MTTR e gráficos por prioridade

Observabilidade completa: logs estruturados, métricas, alertas

Notificações automáticas por email e SMS

Segurança robusta implementada: JWT, OAuth2, CSRF, XSS, SQL Injection

CI/CD completo com build, testes e deploy automático

---

## Contribuição

Pull requests são bem-vindos. Para mudanças significativas, abra uma issue primeiro para discutir.

---

## License

Este projeto está licenciado sob a licença MIT.
