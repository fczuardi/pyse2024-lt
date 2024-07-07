# Git Worktree
Branchs como subdiretórios

---
# Stash, Switch, Pull, Rebase...

- Estou trabalhando numa feature e um hotfix ganha prioridade
- Quero testar ou revisar uma branch de um amigo
- Quero trabalhar em duas features em paralelo 

---
# Seus problemas acabaram

- git worktree (list, add, remove)
- cd ../outra-branch

---
# Setup com git --bare

- baseado em https://morgan.cugerone.com/blog/how-to-use-git-worktree-and-in-a-clean-way/

---

```
$ mkdir my-awesome-project
$ cd my-awesome-project

$ git clone --bare git@github.com:myname:my-awesome-project.git .bare

$ echo "gitdir: ./.bare" > .git
```
---
# Demo

