# Paulo Schnaufer

**Desenvolvedor de Sistemas · Backend (Python, PostgreSQL, Odoo)**
Ciência da Computação na UEM (6º de 8 períodos)

Me interesso por entender como decisões de implementação mudam o comportamento de um sistema: desempenho, concorrência e escalabilidade.

---

### Atualmente

- **Have Consultoria**: desenvolvimento em Python sobre Odoo e PostgreSQL (remoto)
- **Iniciação científica (PIBIC/CNPq e Fundação Araucária)**: extração e transformação de dados em SQL sobre mais de 2.000 escolas públicas, com saída padronizada em XML para análise

---

### Projeto em destaque

#### [job-queue-api](https://github.com/paulo-schnaufer/job-queue-api) · [deploy](https://job-queue-api-wcex.onrender.com)

API de fila de jobs em **FastAPI + PostgreSQL + Docker**, com worker em processo separado.

- Autenticação por API key, com `client_id` vindo apenas do cliente autenticado
- Isolamento de dados por cliente em todas as consultas
- Log transacional: cada transição de estado do job é registrada na mesma transação do `UPDATE`
- SQL direto (psycopg2), sem ORM, para controle explícito de transações

**Próximos passos:** rate limiting, retry de jobs travados, testes automatizados e CI/CD.

---

### Stack

**Backend:** Python · FastAPI · PostgreSQL · Odoo
**Infra e ferramentas:** Docker · Git · Linux · Bash · DBeaver
**Fundamentos:** estruturas de dados e algoritmos · complexidade (big-O)
**Idiomas:** português (nativo) · inglês (fluente)

---

### Contato

[LinkedIn](https://www.linkedin.com/in/paulo-schnaufer) · pauloschnaufer@gmail.com
