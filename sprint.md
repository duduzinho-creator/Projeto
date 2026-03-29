# Sprint 01 - Greenhouse System 

> **Status:** 🔵 Em Planejamento
> **Período:** 01/03/2024 a 15/03/2024
> **Squad:** Eduardo Centenaro , Murilo Marcon e Guilherme Pinto 

---

## Objetivo da Sprint
Estabelecer a infraestrutura de **Autenticação** e o **Monitoramento Base** (Leitura de Sensores) para garantir que os dados cheguem ao sistema.

---

##  Quadro de Tarefas (Sprint Backlog)

### Eduardo (Backend & Security)
- [ ] Criar estrutura do Banco de Dados (Usuários e Logs)
- [ ] Implementar **Sistema de Login** (API)
- [ ] Configurar **Autenticação de Usuários** (JWT/Middleware)
- [ ] Endpoint para **Registro de dados dos sensores**

###  Murilo (IoT & Firmware)
- [ ] Configuração do hardware (ESP32/Arduino)
- [ ] Implementar **Monitoramento de temperatura** (Leitura física)
- [ ] Implementar **Monitoramento de umidade do ar**
- [ ] Lógica para **Cadastro de sensores** no firmware

### Guilherme (Frontend & UI)
- [ ] Desenvolver Tela de Login e Cadastro
- [ ] Criar **Dashboard de monitoramento** (Cards de leitura)
- [ ] Implementar interface para **Cadastro de atuadores**
- [ ] Lógica de **Monitoramento de umidade do solo** (Visualização)

---

## Acompanhamento de Prioridades


| Tarefa | Responsável | Prioridade | Status |
| :--- | :--- | :---: | :--- |
| Sistema de Login | Eduardo | 🔴 Alta | 📅 Backlog |
| Monitoramento Temp/Umidade | Murilo | 🔴 Alta | 📅 Backlog |
| Dashboard Principal | Guilherme | 🔴 Alta | 📅 Backlog |
| Autenticação (JWT) | Eduardo | 🔴 Alta | 📅 Backlog |
| Cadastro de Sensores | Murilo | 🔴 Alta | 📅 Backlog |
| Registro de Dados (Histórico) | Eduardo | 🟡 Média | 📅 Backlog |

---

##  Stack Tecnológica Utilizada
- **Linguagens:** [Ex: TypeScript / Python / C++]
- **Banco de Dados:** [Ex: PostgreSQL / MongoDB]
- **Hardware:** [Ex: ESP32 / DHT22]
- **Editor:** Visual Studio Code 💻

---

##  Notas de Reunião (Daily)
*   **01/03:** Definição das tecnologias e divisão de pastas do repositório.
*   **03/03:** Eduardo inicia a rota de login; Murilo testa sensores DHT.
