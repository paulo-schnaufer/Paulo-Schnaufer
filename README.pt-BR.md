[English](https://github.com/paulo-schnaufer) · **Português**

# Paulo Schnaufer

**Desenvolvedor de Sistemas · Backend (Python, PostgreSQL, Odoo)**  
Estudante de Ciência da Computação na UEM (previsão de conclusão: dezembro de 2027)

Tenho interesse em entender como decisões de implementação mudam o comportamento de um sistema: desempenho, concorrência e escalabilidade.

---

### Atualmente

- **Have Consultoria:** desenvolvimento de sistemas em Python sobre Odoo e PostgreSQL (remoto)
- **Iniciação científica (PIBIC/CNPq e Fundação Araucária):** trabalho com dados de mais de 2.000 escolas públicas e conversão de dados reais de horários para o padrão XML XHSTT

---

### Projetos em destaque

#### [job-queue-api](https://github.com/paulo-schnaufer/job-queue-api) · [demo](https://job-queue-api-wcex.onrender.com)

API de fila de jobs em **FastAPI, PostgreSQL e Docker**, com worker em processo separado.

- Autenticação por API key, com `client_id` derivado apenas do cliente autenticado
- Isolamento de dados por cliente em todas as consultas
- Log transacional: cada transição de estado do job é registrada na mesma transação do `UPDATE`
- SQL direto (psycopg2), sem ORM, para controle explícito de transações

**Próximos passos:** rate limiting, retry de jobs travados, testes automatizados e CI/CD.

#### Pipeline de dados para horários escolares

Pipeline automatizado que converte dados reais do sistema SIGAH-UEM para o padrão XML XHSTT.

- Geração de 3.421 instâncias sem intervenção manual
- Validação de 3.106 instâncias (90,8%) com o HSEval
- Identificação de problemas nos dados de origem como causa das 315 instâncias rejeitadas

---

### Stack

- **Backend:** Python · FastAPI · PostgreSQL · APIs REST · Odoo
- **Infraestrutura e ferramentas:** Docker · Git · Linux · Bash · DBeaver
- **Fundamentos:** estruturas de dados e algoritmos · complexidade (Big-O)
- **Idiomas:** português (nativo) · inglês (fluente)

---

### Contato

[LinkedIn](https://www.linkedin.com/in/paulo-schnaufer) · pauloschnaufer@gmail.com
