# Sistema de Recomendação de Filmes

TCC — Ciência da Computação | UNESC 2026  
Aluno: Wesley Emanuel Da Silva  
Orientador: Prof. André Faria Ruaro

**Repositório:** https://github.com/wespud/Recomenda-o-Filmes

## Sobre o projeto

Protótipo de sistema de recomendação de filmes desenvolvido como Trabalho de Conclusão de Curso. Compara dois algoritmos — Filtragem Colaborativa (SVD) e Recomendação Baseada em Conteúdo (TF-IDF) — sobre o dataset MovieLens 1M, avaliando precisão e diversidade simultaneamente.

## Como executar

```powershell
.\venv\Scripts\Activate.ps1
streamlit run app.py
```

Acesse em: http://localhost:8501

## Dataset

MovieLens 1M — baixe em https://grouplens.org/datasets/movielens/1m/ e extraia em `./ml-1m/ml-1m/`

## Dependências

```
streamlit==1.56.0
pandas==3.0.2
numpy==1.26.4
scikit-learn==1.8.0
scikit-surprise==1.1.4
altair==6.0.0
requests==2.33.1
```