## Uvod

## Shell komande

**NOTE:** Pogledati tutorijal o komandnoj liniji

Terminal se sastoji od dve stvari:

1. Gui aplikacija (terminal emulator)
2. Shell - Interaktivni program (interpreter) koji je pokrenut u repl (read-evaluate-print-loop) rezimu
   Primeri: `bash`, `zsh`, `fish`

Svaka komanda u terminalu je ili:

1. Ugradjena komanda terminala (cd, ...)
2. Program - Ime programa (git, awk, grep, nvim)

Svaka komanda se sastoji od:

```
Ime komande/programa i argumenata

git arg1 arg2
ls -l
^    ^
|    |
|   argument
ime
```

## Git

Git je sistem za kontrolu verzija, koristi se za laksu kolaboraciju

```
git # Alat (program) komandne linije
```

## Git komande

```sh
git init .  # Inicijalizuje git repositorijum u trenutnom folderu
```

## Instaliranje bootstrap-a.

```sh
mkdir bootstrap 
cd bootstrap
npm install bootstrap
```


Lista svih bootstrap varijabli se nalazi u:


```sh
node_modules/bootstrap/scss/_variables.scss
```

Mogu se override-ovati, upisivanjem u sekciju 2. u `custom.scss`

Pored varijabli, mogu se override-ovati i Sass mape koje se odnose na boje i drugo

## Kompajliranje sass stila

Potrebno instalirati sass

```sh
sass custom.scss ./assets/custom-bootstrap.css
```
