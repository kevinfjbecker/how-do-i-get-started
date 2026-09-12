# Python Primer

Hei Arianna! ❤️

Siden du skal begynne med programmering som valgfag i 9. klasse, tenkte jeg du kunne teste litt Python før første time. Du trenger ikke kunne noe fra før.

Dette tar ca. 20–30 min, og målet er bare å se om du klarer å få datamaskinen til å gjøre det du vil 😎

Åpne denne på PC/Mac: <https://www.programiz.com/python-programming/online-compiler/>

Du skriver koden og trykker Run.

## 🐍 LEVEL 1 – ditt første program

Skriv:

``` python
print("Hei!")
```

Trykk Run.

Hvis det står Hei!, har du laget ditt første program 🎉

Oppdrag: Få programmet til å skrive tre forskjellige linjer om deg.

## 🧠 LEVEL 2 – få datamaskinen til å huske

Prøv:

``` python
navn = "Arianna"
alder = 14 

print("Hei", navn)
print("Neste år er du", alder + 1, "år.")
```

navn og alder kalles variabler. Tenk på dem som huskelapper datamaskinen kan bruke senere.

Oppdrag: Lag også en variabel som heter favorittmat og få programmet til å skrive:

Arianna er 14 år og liker _____

## 💬 LEVEL 3 – snakk med programmet

Prøv:

``` python
navn = input("Hva heter du? ")
favoritt = input("Hva er favorittmaten din? ")

print(navn, "liker", favoritt)
```

Nå kan den som bruker programmet skrive inn svar.

Oppdrag: Få programmet til å stille tre spørsmål og skrive en liten presentasjon av personen etterpå.

## 🤔 LEVEL 4 – få datamaskinen til å bestemme

Prøv:

``` python
alder = int(input("Hvor gammel er du? "))
if alder >= 13:
    print("Du er tenåring!")
else:
    print("Du er ikke tenåring ennå.")
```

if betyr hvis.

Altså:

HVIS noe er sant → gjør dette
ELLERS → gjør noe annet.

⚠️ Mellomrommene foran print er viktige i Python!

Oppdrag: Lag et program som spør hvor mange poeng du fikk.

Hvis svaret er 10 eller mer:

🏆 Du vant!

Hvis ikke:

Prøv igjen!

## 🔁 LEVEL 5 – datamaskinens superkraft

Hvis du vil skrive «Hei» fem ganger, trenger du ikke gjøre dette:

``` python
print("Hei")
print("Hei")
print("Hei")
print("Hei")
print("Hei")
```

Du kan skrive:

``` python
for i in range(5):
    print("Hei")
```

Dette kalles en løkke.

Oppdrag: Få Python til å skrive tallene fra 0 til 9.

Hint: ```for i in range(10):```

🔥 Bonus: Klarer du å få den til å skrive:

``` text
2
4
6
8
10
```

uten å skrive fem print-linjer?

## 🎮 FINAL LEVEL – lag et spill

Kopier dette:

``` python
hemmelig_tall = 7 
gjett = int(input("Gjett et tall mellom 1 og 10: ")) 
if gjett == hemmelig_tall:
    print("🎉 Riktig!")
else:
    print("❌ Feil! Tallet var", hemmelig_tall)
```

Nå har du laget et lite spill.

Legg merke til:

```=``` betyr gi en variabel en verdi

```==``` betyr er disse to like?

## FINAL CHALLENGE 🏆

Kan du endre spillet slik at det sier:

📈 For lavt!

eller

📉 For høyt!

i stedet for bare «feil»?

Du kommer til å trenge:

python if ...     ... elif ...     ... else:     ...

Jeg gir deg ikke resten 😈

## 👾 BONUS LEVEL

Hvis du klarer alt over, prøv denne:

``` python
import random

hemmelig_tall = random.randint(1, 20)
gjett = int(input("Jeg tenker på et tall mellom 1 og 20. Gjett: "))
if gjett == hemmelig_tall:
    print("🎉 RIKTIG!")
elif gjett < hemmelig_tall:
    print("📈 For lavt!")
else:
    print("📉 For høyt!")
print("Tallet mitt var", hemmelig_tall)
```

Nå velger datamaskinen et nytt tilfeldig tall hver gang.

Og hvis du kommer hit, har du allerede brukt:

* ✅ variabler
* ✅ input
* ✅ if / else
* ✅ løkker
* ✅ sammenligninger
* ✅ tilfeldige tall
* ✅ feilsøking

Det er faktisk ganske mye programmering. 😎🐍

Viktigste regel: Hvis du får masse rød tekst og ingenting virker, betyr det ikke at du er dårlig til å programmere. Det betyr at du programmerer 😂

Prøv å finne feilen først. Hvis du står helt fast, kan du sende koden til ChatGPT og skrive:

«Ikke gi meg svaret. Gi meg ett hint om hva som er feil.»

Lykke til ❤️
