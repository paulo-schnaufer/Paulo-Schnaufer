**English** · [Português](https://github.com/paulo-schnaufer/paulo-schnaufer/blob/main/README.pt-BR.md)

# Paulo Schnaufer

**Software Developer · Backend (Python, PostgreSQL, Odoo)**  
Computer Science student at UEM (expected graduation: December 2027)

I'm interested in how implementation decisions change a system's behavior: performance, concurrency, and scalability.

---

### Currently

- **Have Consultoria:** developing Python systems on Odoo and PostgreSQL (remote)
- **Undergraduate research (PIBIC/CNPq and Fundação Araucária):** working with data from more than 2,000 public schools and converting real timetabling data to the XHSTT XML standard

---

### Featured projects

#### [job-queue-api](https://github.com/paulo-schnaufer/job-queue-api) · [live demo](https://job-queue-api-wcex.onrender.com)

Job queue API built with **FastAPI, PostgreSQL, and Docker**, with a worker running in a separate process.

- API key authentication, with `client_id` derived only from the authenticated client
- Per-client data isolation in all queries
- Transactional logging: each job state transition is recorded in the same transaction as its `UPDATE`
- Direct SQL (psycopg2), without an ORM, for explicit transaction control

**Next steps:** rate limiting, retries for stuck jobs, automated tests, and CI/CD.

#### School timetabling data pipeline

Automated pipeline that converts real data from the SIGAH-UEM system to the XHSTT XML standard.

- Generated 3,421 instances with no manual intervention
- Validated 3,106 instances (90.8%) with HSEval
- Traced the 315 rejected instances to source data issues

---

### Stack

- **Backend:** Python · FastAPI · PostgreSQL · REST APIs · Odoo
- **Infrastructure and tools:** Docker · Git · Linux · Bash · DBeaver
- **Fundamentals:** data structures and algorithms · complexity (Big-O)
- **Languages:** Portuguese (native) · English (fluent)

---

### Contact

[LinkedIn](https://www.linkedin.com/in/paulo-schnaufer) · pauloschnaufer@gmail.com
