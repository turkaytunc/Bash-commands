# Bash(Bourne Again Shell)

_alias_ komutu ile bash kabuk programında temel komutlara yeni ad tahsis edilebilir ya da aynı ada sahip parametre seçenekleri eklenebilir. Yaratılan bütün takma adlar _alias –p_ ile listelenebilir. Yaratılan takma adları devre dışı bırakmak için _unalias_ komutu kullanılır.

```bash
alias dir=ls
```

```bash
alias tester="npm test --watch"
```

```bash
unalias tester dir
```

---
