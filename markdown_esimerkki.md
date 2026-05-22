# Markdown-esimerkki

Tämä on **pääotsikko** (`#`). Sivulla käytetään vain yhtä H1-otsikkoa.

---

## Tekstimuotoilu (`##` = luvun otsikko)

Normaali teksti kirjoitetaan sellaisenaan.  
**Lihavointi** tehdään kahdella tähdellä.  
*Kursiivi* tehdään yhdellä tähdellä.  
~~Yliviivaus~~ kahdella tildellä.  
Koodisana rivillä: `print("hei")`

---

## Listat

Järjestämätön lista (luettelomerkit):

- Ensimmäinen kohta
- Toinen kohta
  - Sisennys kahdella välilyönnillä
  - Toinen alikohta

Numeroitu lista:

1. Ensimmäinen vaihe
2. Toinen vaihe
3. Kolmas vaihe

---

## Lainaus ja vaakaviiva

> Tämä on lainauslohko (`>`).  
> Käytetään esim. sitaateissa tai huomioissa.

Kolme viivaa (`---`) tekee vaakaviivan, kuten yllä.

---

## Linkit ja kuvat

[Tämä on linkki](https://www.markdownguide.org) – syntaksi: `[teksti](url)`

![Kuvan kuvaus]([https://via.placeholder.com/150](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/208px-Markdown-mark.svg.png)) – syntaksi: `![alt-teksti](kuva.png)`

---

## Koodilohko

Käytetään kun näytetään useampi rivi koodia:

```python
def tervehdi(nimi):
    print(f"Hei, {nimi}!")

tervehdi("opiskelija")
```

---

### Yhteenveto (`###` = alaluku)

| Merkintä       | Tulos         |
|----------------|---------------|
| `# Otsikko`    | H1-otsikko    |
| `**teksti**`   | **lihavoitu** |
| `*teksti*`     | *kursiivi*    |
| `- kohta`      | luetelmapiste |
| `` `koodi` ``  | koodisana     |
