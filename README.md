# NRP_Projekt_2026_2RII_VS-

# Izgubljeno & Najdeno Kampus

Aplikacija za hiter "matching" izgubljenih in najdenih predmetov v študentskih kampusih univerz.

## Problem

Študenti in osebje univerze pogosto izgubijo predmete (ključe, študentske izkaznice, prenosnike, dežnike, knjige) na kampusu, a ni centraliziranega in učinkovitega sistema za ujemanje izgubljenih in najdenih predmetov. Študenti se trenutno zanašajo na:
- Facebook skupin (razpršene informacije, težko iskati)
- Fizične "lost & found" točke (omejene ure, slaba vidnost)
- E-mailske verižice (počasno, neindeksirano)
- Priporočila iz ust v usta

Posledica:
- Izgubljeni predmeti se redko nahajajo
- Podvojeni oglasi in iskanja
- Izguba časa pri brskanju skozi neurejene kanale
- Razočaranje in stres

## Rešitev

**Izgubljeno & Najdeno Kampus** je spletna aplikacija, ki centralizira izgubljene in najdene predmete znotraj univerzitetnega kampusa (MVP se osredotoča na Univerzo v Ljubljani). Uporabniki lahko:

1. **Naročijo Najdene Predmete**
   - Naložijo foto, opišejo predmet, izberejo kategorijo (ključi, dokumenti, elektronika, oblačila, itd.)
   - Označijo lokacijo (stavba, nadstropje, natančno prostor če je mogoče)
   - Čas se zabeleži avtomatsko

2. **Prijavijo Izgubljene Predmete**
   - Opišejo kaj so izgubili
   - Označijo približni čas in lokacijo
   - Izberejo kategorijo in nujnost

3. **Pametni Sistem Ujemanja** (Unikatna Funkcionalnost - spodaj)
   - Aplikacija avtomatsko predlaga ujemanja, kadar imajo izgubljeni in najdeni predmeti visoko podobnost
   - Prikaže odstotek verjetnosti ujemanja
   - Obvesti uporabnike o potencialnih ujemanji

4. **Brskanje & Iskanje**
   - Filtriraj po kategoriji, stavbi, časovnem razponu
   - Išči po ključnih besedah (npr. "rdeči denarnica", "MacBook")
   - Poglej najnovejše objave

5. **Neposredno Sporočanje**
   - Sporočaj se z iskačem/izgubljačem direktno prek aplikacije
   - Ni potrebe da deljenje telefonskih številk javno

6. **QR Kode na Fizičnih Lokacijah**
   - Tiskljive QR kode za knjižnico, glavno halo, domove študentov
   - Hiter dostop do aplikacije s fizičnih oglasnih tabel

## Unikatna Funkcionalnost: Pametni Ujemač Bližine

**"Inteligentni Predlagalnik Ujemanj"** - Za razliko od osnovnih lost & found platform, aplikacija avtomatsko predlaga ujemanja na podlagi:

- **Časovna bližina**: Predmet najden ob 14:45, izgubljen ob 14:30? Visoka verjetnost ujemanja
- **Prostorska bližina**: Najden v stavbi A nadstropje 2, izgubljen v stavbi A nadstropje 1? Verjetno isti predmet
- **Podobnost kategorije in opisa**: Uporablja enostavno ujemanje ključnih besed (npr. "modri nahrbtnik" vs "mornariško modra torba")
- **Ocenjevanje zanesljivosti**: Prikaže verjetnost ujemanja (70%, 85%, 95%), da uporabniki vedo kako zanesljiv je predlog

Uporabniki dobijo **obvestila**, ko je zaznano potencialno ujemanje, kar drastično pospeši vrnitev predmeta.

Primer:
> "Tvoj prenosnik (izgubljen danes 13:00, stavba C) ima 91% ujemanje z najdenim predmetom (najden 14:15, stavba C, elektronika)"

## Ciljna Skupina

- **Primarna**: Študenti in osebje Univerze v Ljubljani (15.000+)
- **Sekundarna**: Druge univerze v Sloveniji (enostavna ekspanzija)
- **Primer uporabe**: Kdorkoli na kampusu, ki pogosto izgubi ali najde stvari
