# 📘 Plano de Estudos — Linguagem C

> Curso base: [Programe seu Futuro — Programação com Linguagem C (Udemy)](https://www.udemy.com/course/programe-seu-futuro-curso-de-programacao-com-a-linguagem-c/)
> Início: 13/06/2026 · Aluno: Lucas

---

## 🎯 Como eu (Claude) posso te ajudar

Sempre que estiver estudando, é só me pedir. Eu posso:

- **Explicar conceitos** com analogias e exemplos (ponteiros, structs, recursão...)
- **Revisar seu código** — apontar bugs, vazamentos de memória, más práticas
- **Corrigir erros de compilação** — cole a mensagem do GCC e eu traduzo/explico
- **Criar exercícios** no seu nível, com gabarito comentado
- **Fazer "code review didático"** — não só conserto, explico *por quê*
- **Montar quizzes** para fixar (ex: "me pergunte 5 coisas sobre laços")
- **Comparar abordagens** — qual jeito é mais idiomático em C e por quê
- **Acompanhar progresso** — atualizar este arquivo conforme você avança

> 💡 Dica: depois de cada aula, traga o código que escreveu e peça
> *"revisa isso como se fosse um professor de C"*.

---

## 🗺️ Roteiro de Aprendizado (fundamentos → avançado)

### Fase 1 — Fundamentos
- [ ] Estrutura de um programa (`#include`, `main`, `return`)
- [ ] Tipos de dados (`int`, `float`, `double`, `char`)
- [ ] Variáveis e constantes (`const`, `#define`)
- [ ] Entrada e saída (`printf`, `scanf`) e especificadores (`%d`, `%f`, `%c`, `%s`)
- [ ] Operadores (aritméticos, relacionais, lógicos)

### Fase 2 — Controle de Fluxo
- [ ] Condicionais (`if`, `else if`, `else`)
- [ ] `switch / case`
- [ ] Laços (`while`, `do-while`, `for`)
- [ ] `break` e `continue`

### Fase 3 — Estruturando o código
- [ ] Funções (parâmetros, retorno, escopo)
- [ ] Recursão
- [ ] Arrays (vetores e matrizes)
- [ ] Strings (arrays de `char`, `<string.h>`)

### Fase 4 — O coração do C
- [ ] **Ponteiros** (o assunto mais importante e mais temido)
- [ ] Passagem por valor vs. por referência
- [ ] Ponteiros + arrays
- [ ] Alocação dinâmica (`malloc`, `calloc`, `free`)

### Fase 5 — Dados compostos e arquivos
- [ ] `struct`, `typedef`, `union`, `enum`
- [ ] Manipulação de arquivos (`fopen`, `fprintf`, `fscanf`, `fclose`)
- [ ] Organização em múltiplos arquivos (`.h` / `.c`)

### Fase 6 — Projetos práticos
- [ ] Calculadora completa
- [ ] Sistema de cadastro (CRUD em memória)
- [ ] Jogo simples (adivinhação / forca no terminal)
- [ ] Cadastro persistido em arquivo

---

## 🛠️ Rotina de estudo sugerida

| Dia | Atividade |
|-----|-----------|
| Estudo | Assistir 2–3 aulas + anotar o conceito-chave |
| Prática | Reescrever o exemplo da aula **sem olhar** |
| Desafio | Resolver 1 exercício novo do tema |
| Revisão | Pedir code review e anotar o que errou |

**Regra de ouro:** não avance de fase enquanto não conseguir escrever o
código da fase anterior do zero, sem copiar.

---

## ✅ Checklist de boas práticas em C

- [ ] Sempre inicializar variáveis antes de usar
- [ ] Verificar retorno de `scanf` e `malloc`
- [ ] Todo `malloc` tem um `free` correspondente
- [ ] Indentar e nomear variáveis com clareza
- [ ] Compilar com avisos ligados: `gcc -Wall -Wextra arquivo.c -o programa`
- [ ] Ler a mensagem de erro com calma antes de pedir ajuda

---

## 🐛 Erros comuns (e o que significam)

| Erro | Causa provável |
|------|----------------|
| `segmentation fault` | Acessou memória inválida (ponteiro/índice errado) |
| `undefined reference to main` | Faltou a função `main` ou erro no nome |
| `expected ';'` | Esqueceu o ponto e vírgula na linha anterior |
| `implicit declaration of function` | Usou função sem incluir o header (`#include`) |
| Lê valor errado no `scanf` | Esqueceu o `&` antes da variável |

---

## 📒 Diário de progresso

> Vá registrando aqui (ou me peça para atualizar):

| Data | Aula / Tema | O que aprendi | Dúvida pendente |
|------|-------------|---------------|-----------------|
| 13/06 | aula 2-8 — maior de 3 números | `if/else if` + operador `&&` | — |
|  |  |  |  |

---

## 🔗 Recursos complementares

- **Compilador online** (testar rápido): [godbolt.org](https://godbolt.org) · [onlinegdb.com](https://www.onlinegdb.com)
- **Referência rápida**: [cppreference (seção C)](https://en.cppreference.com/w/c)
- **Apostila** que você já tem: `Apostila_Linguagem_C.pdf` na pasta do Desktop

---

*Documento vivo — me peça para atualizar conforme avança no curso.* 🚀
