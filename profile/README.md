# PADRÃO OFICIAL DE NOMENCLATURA
## Organização de Repositórios e Pastas

## Visite
- [CARTILHA OFICIAL DE PADRONIZAÇÃO](https://docs.google.com/document/d/1MvAodf3p_3Hgvu8PxlhIikTfy5Lyx7aN6j_QO4G6Xgc/edit?usp=sharing)

##  Finalidade
Este documento estabelece as **regras obrigatórias de nomenclatura** para o uso de:

- Repositórios  
- Pastas principais  
- Estruturas internas de projetos  

##  Objetivo

Garantir:

- Padronização  
- Organização institucional  
- Escalabilidade  
- Facilidade de busca  
- Governança adequada dos projetos  

# Estrutura Oficial de Nomeação

Todos os repositórios devem seguir obrigatoriamente o seguinte padrão:

#  Definição de Cada Campo

##  [nome] (Obrigatório)

Nome principal do projeto ou iniciativa.

### Regras:
- Apenas letras minúsculas  
- Sem espaços  
- Sem acentos  
- Pode ser palavra composta, mas sem separação por espaço  

### Exemplos válidos:
-mascots
-insightboard

##  [uf] (Obrigatório)

Sigla do estado com **2 letras minúsculas**.

### Exemplos:
pe
sp
ba


## {t[turma]e[equipe]-} (Opcional)

Bloco utilizado apenas quando houver identificação de turma e equipe.

###  Formato obrigatório:
t[numero]e[numero]
### Exemplos válidos:
t9e1
t7e4
t10e2
⚠ Caso não exista turma/equipe, remover completamente este bloco (inclusive o hífen).



## [projeto] (Obrigatório)

Código ou nome reduzido do projeto.

### Regras:
- Sem espaços  
- Sem caracteres especiais  
- Sem hífen interno  
- Sem acentos  

###  Exemplos válidos:
bfd
fap

##  [ano] (Obrigatório)

Ano do projeto em dois ou quatro dígitos.

###  Exemplos:
24
2024
##  [fase] (Opcional)

Identificador da fase do projeto.

###  Identificadores permitidos:

| Código | Significado |
|--------|------------|
| `pi` | Projeto Integrador |
| `pm` | Projeto Mensal |
| `re` | Residência |

### ✅ Exemplos válidos:
pi
pm
re
#  Exemplos Estruturais (Modelo)

##  Com turma e equipe

[nome]-[uf]-t9e1-[projeto]25pm


### Exemplo:


mascots-pe-t9e1-fap25pm
[nome]-[uf]-[projeto]25re


### Exemplo:


insightboard-pe-BFD25re


---

#  Regras Gerais Obrigatórias

- Utilizar apenas hífen (-) como separador  
- Não utilizar espaços  
- Não utilizar underline (_)  
- Não utilizar caracteres especiais  
- Não alterar a ordem da estrutura  
- Validar antes da criação do repositório  
- Não alterar o nome após criação sem autorização formal  


 Este padrão é obrigatório para todos os membros da organização.


