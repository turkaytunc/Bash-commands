# Bash(Bourne Again Shell)

_**alias**_ komutu ile bash kabuk programında temel komutlara yeni ad tahsis edilebilir ya da aynı ada sahip parametre seçenekleri eklenebilir. Yaratılan bütün takma adlar **_alias –p_** ile listelenebilir. Yaratılan takma adları devre dışı bırakmak için **_unalias_** komutu kullanılır.

```bash
alias dir=ls

alias tester="npm test --watch"

unalias tester dir
```

---
