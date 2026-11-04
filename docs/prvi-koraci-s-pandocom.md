# Prvi koraci s Pandocom

Ovdje ćete naučiti rukovati alatom Pandoc. Jednostavan je alat, te će ovo potrajati oko 20-30 minuta.

Provjereno s Pandocom 3.13 na Git Bashu, OS je Windows 11.

## Prije početka

- Obavezno je imati VS Code, terminal i README.md.

## 1. Instalirajte Pandoc

### Windows

Preuzmite Pandoc sa [GitHuba.](https://github.com/jgm/pandoc/releases/tag/3.13)

## 2. Provjerite instalaciju

```bash
pandoc --version
```

**Očekivani rezultat:** 

```pandoc 3.13
```

## 3. Pretvorite Markdown u Word

Naredba:

```pandoc README.md -o izlaz/README.docx
```

U Wordu biste trebali imati dokument formatiran isto kao i Markdown datoteka.

## 4. Pretvorite Markdown u web-stranicu

Naredba:

```pandoc README.md -s -o izlaz/README.html
```

-s znači da je datoteka samostalna, te da će se oblikovati drukčije od datoteke napravljene naredbom bez -s. Ukratko, bit će šire margine, te će pozadina vjerojatno biti tamna s bijelim tekstom, za razliku od prošle.

## Ako ne radi

| Poruka | Što znači | Što učiniti |
|---|---|---|
| `command not found` | [Unesena je kriva naredba] | [Dobro provjerite kako ste napisali naredbu.] |

## Što ste napravili

Sad znate rukovati osnovama Pandoca. Nakon ovoga, možete pretvoriti datoteke iz formata .md u .docx te .html, što znači da od Markdown datoteke imate Microsoft Word dokument i stranicu.