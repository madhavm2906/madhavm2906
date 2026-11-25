![Anime skyline at night with a sailor, a soccer player, and a shinobi](assets/neon-anime-skyline.webp)

<h1 align="center">Madhav Mangalagiri</h1>
<p align="center"><strong>Software Engineering · Machine Learning Systems</strong></p>
<p align="center">Computer Science at Virginia Tech · Class of 2027</p>

I like building the software that takes a model from training to something people can use. Right now I’m working on model serving and learning how to evaluate and improve language models after training.

## Projects

### [NLP Inference and Model Release Platform](https://github.com/madhavm2906/nlp-model-release)

I trained a TinyBERT product ranker on Amazon ESCI and served it through a Go gateway that batches requests for ONNX Runtime. The release workflow checks ranking quality and latency and records promotions and rollbacks in PostgreSQL.

- **0.718 nDCG@10** for the trained ranker vs **0.691** for BM25 on **8,956 held out queries**
- **480 of 480 requests succeeded** in a local Kubernetes benchmark, with a median p95 of **71.4 ms** across three runs

### [GitHub Issue Triage](https://github.com/madhavm2906/issue-triage-ml)

I built a FastAPI and React app that suggests bug or feature request labels. A maintainer can accept or correct a suggestion, and a background worker applies the approved label through a GitHub App.

## Tools I use

`Go` · `Python` · `TypeScript` · `PyTorch` · `ONNX Runtime` · `PostgreSQL` · `Docker` · `Kubernetes`

## Away from the keyboard

I’m a fan of **One Piece**, **Ao Ashi**, and **Naruto**. You can spot a nod to each one in the banner.
