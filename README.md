<div align="center">

# Abhimanyu Pratap Singh

**Backend Engineer · AI Systems · RAG Pipelines · LLM Applications**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhimanyupratapsingh2004/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:abhimanyu2004111@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-4B0082?style=flat-square&logo=read-the-docs&logoColor=white)](https://drive.google.com/file/d/1Q3R0sq-WE6g-KYXtK-zWNSSWeiJ4jEoW/view?usp=sharing)
[![LeetCode](https://img.shields.io/badge/LeetCode_450+-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://codolio.com/profile/lumenbyte)

</div>

---

## About

Pre-final year B.Tech CSE student building production-grade AI systems and backend infrastructure. My work sits at the intersection of **retrieval-augmented generation**, **agentic AI**, and **scalable backend engineering**.

I do not build demos. I build systems — with proper architecture, vector search, async APIs, and deployment pipelines.

Currently focused on: `Python` · `FastAPI` · `RAG Pipelines` · `LangChain` · `LangGraph` · `Vector Databases`

---

## Featured Project

### Codexa — AI Codebase Assistant (RAG-Based)

> Ask any question about a Python GitHub repository in plain English. Get precise, cited answers.

Codexa indexes entire GitHub repositories using syntax-aware code parsing (tree-sitter), generates embeddings for every function and class, stores them in a vector database, and retrieves grounded answers with exact file and line citations.

**This is not a chatbot wrapper. It is a retrieval system built on real engineering decisions.**

| Component | Choice | Reason |
|-----------|--------|--------|
| Code Parsing | tree-sitter | AST-aware chunking by function/class, not arbitrary splits |
| Vector DB | Qdrant | Production-grade, better than Chroma for real workloads |
| Embeddings | Gemini Embeddings | Cost-effective, high quality |
| LLM | Groq (LLaMA) | Fast inference, free tier for development |
| Backend | FastAPI (async) | Non-blocking I/O for concurrent retrieval |
| Database | PostgreSQL | Query history, user metadata |
| Deployment | Docker + Vercel | Portable, reproducible |

**What makes it hard (and worth talking about in interviews):**
- Code cannot be chunked like prose — functions must stay intact. tree-sitter parses the AST to split by logical code units, not character count.
- Cross-file context: when a function calls another, both are retrieved together, not in isolation.
- Rate-limited API calls handled via a custom token-bucket rate limiter with local embedding fallback.

[![Live Demo](https://img.shields.io/badge/Live_Demo-00C7B7?style=flat-square)](https://codexarag.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lumen-byte/Codexa--RAG-Based-Codebase-Assistant)

---

## Technical Stack

```
AI / RAG          Python · LangChain · LangGraph · RAG Pipelines
                  Qdrant · Vector Embeddings · Prompt Engineering

Backend           FastAPI · RESTful API Design · Async Python
                  PostgreSQL · SQLAlchemy · JWT Auth · Docker

Languages         C++ · Python · JavaScript (ES6+) · SQL

Prior Stack       Node.js · Express.js · React.js · MongoDB · Redis

Cloud / Tools     Microsoft Azure · Git · Postman · VS Code
```

---

## Problem Solving

700+ problems across competitive programming platforms. Strong in graphs, dynamic programming, and tree problems.

[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=LeetCode&logoColor=black)](https://leetcode.com/u/lumenbyte/)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=Codeforces&logoColor=white)](https://codeforces.com/profile/lumenbyte/)
[![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=CodeChef&logoColor=white)](https://www.codechef.com/users/lumenbyte)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-298D46?style=for-the-badge&logo=GeeksforGeeks&logoColor=white)](https://www.geeksforgeeks.org/profile/lumenbyte)

---

## Activity

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=lumen-byte&theme=react-dark&area=true&hide_border=false&color=9370DB&point=4B0082" width="100%" />
</div>

---

## What I Am Building Toward

```
Current         RAG-based codebase intelligence (Codexa)
Next            Agentic AI systems — multi-step reasoning, tool use, LangGraph
Goal            Backend + AI Engineer at a product company
                building systems that actually ship
```

---

<div align="center">
  <sub>Open to internships and entry-level roles in Backend Engineering and AI Engineering.</sub>
  <br/>
  <sub>
    <a href="mailto:abhimanyu2004111@gmail.com">abhimanyu2004111@gmail.com</a>
  </sub>
</div>
