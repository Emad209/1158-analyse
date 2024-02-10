# Cycle de vie du logiciel #

## Description ##

## Implémantation ##
- codage / programmation
- test
- analyse
- conception


```mermaid
flowchart LR
A(Analyse)  
C(Conception)
D(Codage)
T(Test)
I(Integration)
A --> C
C --> D
D --> T
T --> I
```



# Source control #
La gestion du code source.
On utilise git, mais il y a d'autres systemes (subversion, mercurial).

Le flux quand on développe.
```mermaid
flowchart LR
C(code)
R(local repository)
G(github)
C --> R
R --> G
```

Mais avant, il faut initier le repository :


