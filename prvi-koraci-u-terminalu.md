# Prvi koraci u terminalu

U ovom tutorijalu, čitatelj će naučiti koristiti se terminalom u Visual Studio Codeu. Cijeli proces trebao bi trajati 30-45 minuta.

## Prije početka

- Ovdje je terminal Git Bash na sustavu Windows 11.
- Visual Studio Code je pokrenut, a u njemu je otvorena mapa Documents.

## 1. Otvorite terminal

U izborniku **Terminal** odaberite **New Terminal**.

**Očekivani rezultat:** 

```emper@DESKTOP-M720KVL UCRT64 ~/Documents
$
```

## 2. Provjerite gdje se nalazite

```bash
pwd
```

**Očekivani rezultat:** 

```/c/Users/[Ime]/Documents
```

## 3. Napravite mapu i uđite u nju

```bash
mkdir proba-terminala
cd proba-terminala
pwd
```

**Očekivani rezultat:** 
```/c/Users/[Ime]/Documents/proba-terminala
```

## 4. Napravite datoteku i upišite u nju tekst

```bash
echo "# Moje bilješke" > biljeske.md
cat biljeske.md
```

**Očekivani rezultat:**

```# Moje bilješke
```

## 5. Dodajte još jedan redak

```bash
echo "- Naredba pwd ispisuje gdje se nalazim." >> biljeske.md
cat biljeske.md
```

**Očekivani rezultat:** 

```# Moje bilješke
- Naredba pwd ispisuje gdje se nalazim.
```

Jedan znak `>` prepisuje cijelu datoteku, dok `>>` samo dodaje tekst na kraj.

## 6. Kopirajte, preimenujte i izbrišite datoteku

```bash
cp biljeske.md kopija.md
mv kopija.md stara.md
rm stara.md
ls
```

**Očekivani rezultat:** 

```biljeske.md
```

Naredba `rm` trajno briše datoteku, te morate paziti da ne izbrišete nešto što će vam trebati kasnije.

## Ako ne radi

| Poruka | Što znači | Što učiniti |
|---|---|---|
| `No such file or directory` | [Objasnite.] | [Objasnite.] |
| [Druga poruka koju ste vidjeli na vježbama] | [Objasnite.] | [Objasnite.] |

## Što dalje

Više možete saznati u priručniku Srca *Uvod u Linux*, poglavlja 2 i 3.
