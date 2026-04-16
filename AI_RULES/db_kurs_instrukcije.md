# Instrukcije za generisanje lekcija
Tema: Projektovanje relacione baze podataka

---

## 1. KONTEKST KURSA

Ovo je kurs namenjen srednjoškolcima koji prvi put uče o bazama podataka.

Cilj kursa:
- da učenici razumeju kako se projektuje relacijska baza podataka
- da povežu teoriju sa realnim primerima
- da na kraju mogu samostalno da naprave jednostavan model baze

Kurs ima 27 lekcija i podeljen je u 5 celina:

### Modul 1: Uvod i osnovni pojmovi
- šta je baza podataka
- relacione baze (tabele, redovi, kolone)
- primer iz realnog sveta (škola ili online prodavnica)
- entiteti, atributi, relacije
- primarni i strani ključevi

### Modul 2: ER modelovanje
- ER dijagrami
- entiteti i atributi
- relacije (1:1, 1:N, N:M)
- kardinalnost i opcionalnost
- mini projekat

### Modul 3: Relacioni model i normalizacija
- prevođenje ER u tabele
- funkcionalne zavisnosti
- anomalije
- 1NF, 2NF, 3NF
- kada ne treba normalizovati

### Modul 4: Praktična primena
- SQL (SELECT, INSERT, UPDATE)
- CREATE TABLE
- mini projekat
- završni projekat

### Modul 5: Rad sa bazom kroz aplikaciju (ORM i Code-First pristup)
- šta je ORM i zašto se koristi
- Code-First vs Database-First pristup
- Entity Framework Core (DbContext, DbSet)
- definisanje modela (klasa → tabela)
- migracije i kreiranje baze iz koda
- rad sa podacima kroz ORM (CRUD, LINQ)
- poređenje SQL vs ORM pristupa

Tokom kursa koristi se jedan realan primer:
- škola ili online prodavnica

Svi pojmovi treba da se objašnjavaju kroz taj primer.

---

## 2. TEHNIČKA PRAVILA (HTML)

Lekcije se pišu u okrnjenom HTML-u.

### Naziv fajla
Format:
[kurs]_[lekcija].html

Primer:
projektovanje_relacione_baze_podataka_uvod.html

Pravila:
- koristiti mala slova
- razdvajati reči donjom crtom (_)
- bez razmaka i specijalnih znakova

---

### Dozvoljene HTML oznake

#### Naslov
```html
<h1>Naslov lekcije</h1>
```

#### Podnaslovi
```html
<h2>Podnaslov</h2>
```

#### Kod / višelinijski primer
```html
<xmp class="primer_ta">
SELECT * FROM Ucenik;
</xmp>
```

#### Napomena
```html
<div class="napomena">
Tekst napomene
</div>
```

#### Zadatak (OBAVEZNO NA KRAJU)
```html
<div class="zadatak">
Tekst zadatka
</div>
```

#### Tabela
```html
<table class="tabela">
  <thead>
    <tr>
      <th>Kolona</th>
      <th>Kolona</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Vrednost</td>
      <td>Vrednost</td>
    </tr>
  </tbody>
</table>
```

#### Slika
```html
<img src="putanja/do/slike.png" alt="opis slike" class="img-fluid velicina">
```

---

### OGRANIČENJA
- NE koristiti CSS
- NE koristiti inline stilove
- NE koristiti JavaScript
- NE koristiti dodatne HTML elemente
- koristiti SAMO dozvoljene klase
- izlaz mora biti čist HTML (bez markdown-a i bez objašnjenja)

---

## 3. PEDAGOŠKA PRAVILA

Lekcija mora biti prilagođena srednjoškolcima.

### Stil:
- jednostavan
- jasan
- postepen
- ne previše formalan
- fokus na razumevanju
- pisati pasuse tako da budu citljivi, dodatavati linebreak gde je neophodno 

---

### OBAVEZNA STRUKTURA LEKCIJE

#### 1. Povezivanje sa prethodnom lekcijom
Na početku kratko objasniti šta je prethodno rađeno i kako se nova lekcija nadovezuje.

#### 2. Uvođenje kroz pitanje ili problem
Postaviti pitanje ili situaciju iz realnog sveta.

#### 3. Objašnjenje
- koristiti primere
- koristiti centralni sistem (škola ili online prodavnica)
- objasniti pojmove kroz situacije

#### 4. Podsticanje razmišljanja
Postavljati pitanja kao:
- šta bi se desilo ako...
- kako bismo ovo rešili...

#### 5. Sekcija za pomoć
Koristiti:
```html
<div class="napomena">
Objasniti najčešće greške i zabune
</div>
```

#### 6. Najava sledeće lekcije
Na kraju lekcije napisati:
U narednoj lekciji ćemo...

#### 7. Zadatak
Na kraju OBAVEZNO dodati zadatak.

---

## 4. VAŽNA PRAVILA

- ne pisati suve definicije bez primera
- ne preskakati logičke korake
- svaki pojam objasniti kroz primer
- ne uvoditi previše teorije odjednom
- koristiti kratke pasuse
- koristiti prirodan jezik
- koristiti srpsku latinicu

---

## 5. FORMAT IZLAZA

Izlaz MORA biti:
- samo HTML lekcija
- bez dodatnih komentara
- bez markdown-a
- bez objašnjenja

---

## 6. ZABRANJENE GREŠKE

- pogrešno zatvoren <xmp> tag
- nedostaje zadatak na kraju
- nema uvoda ili povezivanja sa prethodnom lekcijom
- nema najave sledeće lekcije
- previše teorijski tekst bez primera
- nema primera
- korišćenje nedozvoljenih HTML tagova