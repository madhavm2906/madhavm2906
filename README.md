![Illustration of a desk lamp and a mountain view at dusk](assets/studio-at-blue-hour.webp)

<h1 align="center">Madhav Mangalagiri</h1>
<p align="center"><strong>Software Engineering · Machine Learning Systems · LLM Post Training</strong></p>
<p align="center">Computer Science at Virginia Tech · May 2027 · <a href="https://www.linkedin.com/in/madhav-mangalagiri-ab5676294/">LinkedIn</a></p>

I like building the software around ML models, from preparing data and training to serving and releasing a new version. I also work on the systems underneath, like Go request queues and C++ networking. Lately I’ve been testing how language models choose tools and how fine tuning changes their mistakes.

## Featured projects

### [NLP Model Release Platform](https://github.com/madhavm2906/nlp-model-release)

I trained a TinyBERT product ranker on Amazon ESCI and served it through a Go batching gateway and ONNX Runtime. The ranker scored **0.718 nDCG@10** on 8,956 held out queries, up from **0.691** with BM25. I added quality and latency checks before promotion, rollback through PostgreSQL, and a repeatable Kubernetes benchmark.

### [LLM Tool Calling and Post Training](https://github.com/madhavm2906/llm-tool-calling-lab)

I built an evaluation harness and fine tuned Qwen2.5 0.5B with LoRA. Tool selection improved from **68 to 79 of 122** on held out ToolACE cases, while exact matches fell from **36 to 29**. I used a fixed BFCL V4 subset and error analysis to see where tool choice, arguments, and decisions to skip a call broke down.

### [Collective Communication Library](https://github.com/madhavm2906/collective-communication)

I implemented ring all reduce in C++17 over TCP using nonblocking I/O, validated message frames, and deadlines. In an 8 KiB benchmark across eight local processes, I reduced median latency from **1.78 ms to 0.38 ms**.

### [GitHub Issue Triage](https://github.com/madhavm2906/issue-triage-ml)

I built a FastAPI and React app that suggests issue labels for maintainers to review. A PostgreSQL outbox keeps review decisions and label updates in sync, and a background worker retries delivery through a GitHub App.

## More work

- [Adaptive ML Inference Service](https://github.com/madhavm2906/adaptive-ml-inference) serves CPU inference with bounded queues, adaptive batching, request deadlines, and reproducible benchmarks.
- [Network Performance and Regression Framework](https://github.com/madhavm2906/network-performance-framework) measures TCP latency and checks for regressions in GitHub Actions.
- [CASCADE](https://github.com/madhavm2906/cascade) is a collaborative disaster response simulator with React, FastAPI, NetworkX, and Gemini.
- **Virginia Tech coursework** includes a Unix shell, a fork join thread pool, a memory allocator, and experiments with text classifiers and LLM prompts.

## Tools I use

- **Languages** · Go, Python, C, C++17, Java, TypeScript, JavaScript, SQL, Bash
- **ML and NLP** · PyTorch, Hugging Face Transformers, scikit-learn, NumPy, pandas, DuckDB, ONNX Runtime
- **LLM post training and evaluation** · PEFT, LoRA, ToolACE, BFCL V4, JSON Schema
- **Web and data** · FastAPI, React, Vite, PostgreSQL, SQLAlchemy, Alembic, GitHub Apps and REST API
- **Systems and infrastructure** · Linux, WSL, TCP sockets, CMake, Docker, Docker Compose, Kubernetes, kind, Nginx, Git, GitHub Actions
- **Testing and performance** · pytest, Python unittest, Go test, JUnit, CTest, Helgrind, latency and throughput benchmarking

<details>
<summary>More tools from projects and coursework</summary>

- **Language model work** · Gemini API, Groq, OpenAI Evals
- **Data and text libraries** · SciPy, Gensim, NLTK, NetworkX
- **Web and databases** · HTML, CSS, Node.js, Express, MongoDB Atlas, Django, Pydantic, HTTPX, Uvicorn, Psycopg, Mongoose, Prisma, Drizzle, tRPC
- **Hosting and developer tools** · AWS Lambda, SST, Render, Vercel, kubectl, GitHub CLI, npm
- **Coursework languages and testing** · Haskell, Scala, Prolog, Racket, PIT mutation testing

</details>

Away from the keyboard, I’m a fan of **One Piece**, **Ao Ashi**, and **Naruto**.
