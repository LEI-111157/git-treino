***Relatório da resolução de conflitos (com apoio do ChatGPT).***

**Contexto:**

Repositório: git-treino
Branch base: main
Branch de feature: conflito-b
Ficheiro em conflito: treino1.txt
Objetivo: simular alterações concorrentes no mesmo ficheiro e resolver manualmente o conflito.

**Como o conflito foi criado:**

Em main, editámos treino1.txt e fizemos commit/push.
Num ramo paralelo (conflito-b), editámos a mesma zona de treino1.txt e fizemos commit/push.
Ao testar integrar (git merge conflito-b em main), o Git assinalou conflito.
