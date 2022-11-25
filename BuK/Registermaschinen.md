---
aliases: [Registermaschine]
tags:
- BuK
---
![[../res/ram.png]]

## Befehle
| Befehl    | Erklärung                   | b += 1? |
| --------- | --------------------------- | ------- |
| LOAD      | c(0) <- c(i)                | X       |
| INDLOAD   | c(0) <- c(c(i))             | X       |
| CLOAD     | c(0) <- i                   | X       |
| STORE     | c(0) -> c(i)                | X       |
| INDSTORE  | c(0) -> c(c(i))             | X       |
| ADD       | c(0) <- c(0) + c(i)         | X       |
| CADD      | c(0) <- c(0) + i            | X       |
| INDADD    | c(0) <- c(0) + c(c(i))      | X       |
| SUB       | c(0) <- max{0, c(0) - c(i)} | X       |
| MULT      | c(0) <- c(0) * c(i)         | X       |
| DIV       | c(0) <- c(0) / c(i)         | X       |
| GOTO      | b <- i                      |         |
| IF x GOTO | b <- i                      | (X)     |
| END       |                             |         |
