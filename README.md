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

**Comando que evidenciou o conflito:**

git status

***Apoio do ChatGPT***

**Usámos o ChatGPT para:**

Confirmar que este é o conflito “clássico” (duas alterações na mesma região do ficheiro).
Sugerir o procedimento de resolução (editar, remover marcadores, add, commit).
Sugerir mensagens de commit e texto para Pull Request.

**Resolução (linha de comandos)**

**Abrir o ficheiro e remover os marcadores do Git, escolhendo o conteúdo final:**

Treino Git init, add, commit
Linha da branch main
Linha da branch conflito-b

*Marcar como resolvido e concluir o merge*


