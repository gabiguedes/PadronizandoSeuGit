## ✅️ Helpando - Git

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

> Helpando Git, é indicado para quem já tem uma base de versionamento usando a ferramenta _GIT_

> Aqui vai um lembrete, por favor não commite na branch master!

###  🎩 Sugestão para nomeclatura de branchs

##### 🎩 Features | Evolutivas
- **feature_78348-cheque-especial.**

##### 🎩  Bugfix | Corretivas
- **fix_876767-cheque-especial-teladelistar**

Faça o que bem entender no seu ambiente local, por exemplo: crie branchs de backup quando for fazer um rebase/merge. Na remote tente manter o padrão de nomeclatura, todos na equipe vai agradece!

> https://git-school.github.io/visualizing-git/ - para visualizar e _brincar_ como os ramos/branches/linhas de desenvolvimento diferentes funcionam!

Exemplo abaixo:

![](/visualbranches.png)

---

#### Sobre commit
- Se você manda bem no inglês e sua equipe também, então mandem ver, commita tudo em inglês.
- Se você não entende muito bem e faz isso aqui: **fix correcao do button que deu msg of error**. Por favor, faça os commits em português.

#### commit
- Não foi marcada pra commitar, ou seja não foi feito o **add**:
```git checkout -- arquivo```
---
- Desfazer uma alteração que foi marcada para commitar, ou seja foi feito o **add**
```git reset HEAD arquivo```
---
- Desfazer uma alteração que foi marcada para commitar e foi commitada!
```git log``` para ver o hash do commit, depois:
```git revert 49ghg434hghg434398sdhs``` isso irá criar um novo commit, desfazendo o revert
---
- Stash
  * para salvar as modificações em um local temporário, run command: ```git stash```
  * listar os stashs salvos, run command: ```git stash list```
  * retomar um stash salvo específico, run command: ```git stash apply INDICE_DO_STASH```
  * deletar stash, run command: ```git stash drop```
  * apply e remove stash, run command: ```git stash pop```
  
### Viagem no tempo - commit
> Vamos iniciar com o, run command: ```git log --oneline```

Veja que temos vários commits e temos uma hash única para cada commit, para mudar sua aplicação para um commit específico, run command: ```git checkout HASH_DO_COMMIT```

##### Muito melhor realizar um commit bem descritivo que você e sua equipe entenda, do que um inglês que pode ser legal, mas você não faz a mínima ideia do que escreveu.

> Sinta-se tranquilo quando der um **git log**
###### https://devhints.io/git-log
> Tenha orgulho da mensagem do seu commit 

---

#### Quer deixar alguma ideia? Por gentileza, faça um pull request <3
