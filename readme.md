# git clone - vezba

**Zadatak:**

povuci neciji repo sa interneta (preseliti internet code u lokalni repo na tvom kompu)

**Koraci**

ovo sto vidis je repo na github-u
mozes da povuces kod kod tebe na komp tako sto:

1. otvoris neki novi prazan folder na tvom disku
2. otvoris gitBash u tom folderu 
3. ukucas komandu:

```bash
git clone https://github.com/ljgww/Bascelik_proba_1.git
```

Git ce da ti povuce ceo repo code sa git-huba u pod-direktorijum od tvog foldera iz koraka 1. a po imenu repo imena

4. znaci treba da udjes u potfolder:

```
cd Bascelik_proba_1
```

i to ti je radni folder u kome ce se pojaviti fajlovi koji su prikazani ovde na git-hub-u

znaci u tvom lokalnom folderu treba da vidis fajlove koje je git povukao sa git-hub-a.

**Vazno:**

kad uzimas kod sa interneta putem `git clone` ne treba ti **git init** jer ce `clone` da odradi sve sto je potrebno (napravice .git local repo i ostale radnje)

`git clone` se kao i `git init` radi samo **JEDAMPUT** da bi se postavilo sve sto treba.

**U cemu je razlika?**

`git init` radis kad imas neki 
kod koji hoces da bude pokriven gitom (verzije) a jos uvek nemas nista (repo) na internetu pa u lokalu hoces da pocnes da radis sa gitom.

`git init` se takodje radi samo **jedamput**
