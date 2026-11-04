Como funcionaria
- Agente Router: identifica a intenção do usuário.
- Agente Jurídico: responde questões de legislação.
- Agente Comercial: consulta dados de vendas.
- Agente Técnico: responde sobre documentos e tecnologia.
- Agente Hub: consolida a resposta


<img width="673" height="484" alt="image" src="https://github.com/user-attachments/assets/4d39e65f-d1ac-4fc3-ac14-280f0924343a" />


RAG-MULTI-AGENTS/
│
├── app.py
├── requirements.txt
├── .env
│
├── agents/
│   ├── router.py
│   ├── hub.py
│   └── specialists.py
│
├── rag/
│   ├── ingestion.py
│   └── retriever.py
│
├── database/
│   └── db.py
│
└── data/
    ├── dados.csv
    ├── tic.csv
    └── arquivo.pdf
