---
title: "Hulajnoga TAWA - budowa terenowej hulajnogi elektrycznej"
type: page
ShowReadingTime: true
author: ["Borys Palacz"]
ShowToc: false
---
<span style="color: #e74c3c;">
To jest historia o tym, jak z kilku surowych rur stalowych, części rowerowych i odrobiny uporu powstała ta oto hulajnoga. Bez schematów z internetu, bez gotowych zestawów — tylko pomysł w głowie i godziny pracy w warsztacie.
</span>

---

## Faza 1: Pomysł i szkic

Wszystko zaczęło się od prostego pytania: *„A co gdyby zrobić hulajnogę, która składa się w większości z części rowerowych, jest elektryczna i poradzi sobie w ciężkim terenie”*

![Szkic koncepcyjny / Pierwsze notatki](/images/t1.webp)

Nie miałem gotowego planu. Zacząłem od szkiców na kartce — rozstawu kół, położenia baterii, kąta główki ramy. Wiedziałem, że chcę:

- **Duże koła** — lepsza stabilność niż w standardowych hulajnogach
- **Amortyzator z przodu** — komfort na nierównościach
- **Baterię centralnie** — niski środek ciężkości
- **Napęd na tylne koło** — klasyczna konstrukcja

---

## Faza 2: Materiały i części

Zanim przystąpiłem do cięcia metalu, musiałem zebrać wszystko, co potrzebne:

| Element | Źródło | Uwagi |
|---------|--------|-------|
| Rama stalowa | Rura gięta na zamówienie | Główna rama |
| Widelec z amortyzatorem | Stary rower dirt | Duży ze skokiem 150mm |
| Koła 26" i 24" | Rowery górski | Przód i tył |
| Motor hub (250-500W) | AliExpress MXUS | Napęd |
| Bateria Li-ion | AliExpress | Zamontowana na ramie napięcie 48V |
| Kontroler i manetka | Komplet z motorem | Elektronika |
| Platforma do stania | Cięta laserem i spawana | Własna konstrukcja |

![Rama](/images/t2.webp)
![Zestaw części ciętych wodą](/images/t3.webp)

---

## Faza 3: Rama — klucz do hulajnogi

To był najtrudniejszy etap. Rama musiała być sztywna, ale lekka. Wykonałem ją z rury ze stali S355 spawanej metodą TIG. 

### Krok po kroku:

1. **Pomiar i cięcie** — dokładne wygięcie rury wg modelu 3D w specjalistycznej firmie 
2. **Szlifowanie krawędzi** — przygotowanie do spawania
3. **Spawanie w przyrządzie** — zapewnienie symetrii i prostych kątów
4. **Obróbka wykończeniowa** — szlifowanie i czyszczenie spoin

![Wygięta rura](/images/t4.webp)
![Spawanie wzmocnień](/images/t5.webp)
![Tylny trójkąt](/images/t6.webp)
![Spawanie platformy](/images/t7.webp)

💡 **Wskazówka:** Cienka stal jest wymagająca przy spawaniu. Czystość krawędzi i odpowiednie parametry to klucz do trwałej spoiny.

---

## Faza 4: Montaż zawieszenia i kół

Gdy rama była gotowa, przyszedł czas na pozostałe detale. Próbny montaż z kołami przed dalszymi etapami. Szybka przymiarka czy idę dobrą drogą.

![Koła na ramie](/images/t8.webp)

Rozstaw osi i geometria były krytyczne. Zbyt pionowa główka = nerwowe prowadzenie. Zbyt leżąca = ociężałe skręty. Po drobnych korektach udało się trafić w złoty środek.

---

## Faza 5: Elektryka — dusza projektu

Bez elektryki to tylko zwykła hulajnoga. Zainstalowałem:

- **Motor w piaście tylnego koła** — bezobsługowy, cichy
- **Baterię 48V / 10Ah** — umieszczoną centralnie na ramie
- **Kontroler** — schowany pod platformą
- **Manetkę gazu** — na kierownicy
- **Wyświetlacz LCD** — prędkość i poziom naładowania

Próbna jazda!

![Pierwsza jazda](/images/t9.webp)

Potem przyszła pola na mniejsze i większe drobiazgi jak np. mocowanie baterii. 

![Mocowanie bateri](/images/t10.webp)

---

## Faza 6: Wykończenie i detale

Surowa stal wygląda fajnie, ale szybko zardzewieje więc konieczne było malowanie:
Docelowo planuję pomalować ramę proszkowo jednak pierwszy prototyp malowany sprayem na działce :)

![Malowanie](/images/t11.webp)

Hulajnoga po montażu z widocznym kontrolerem.

![Kontroler](/images/t12.webp)

---

## Faza 7: Pierwsza jazda

Moment prawdy. Napięcie, klucz włączający, delikatny ruch manetką... i śmigamy!

![Cytadela](/images/t13.webp)

Hulajnoga po pierwszym 1000 km. Najdziwniejszy pojazd na stojaku!
![Stojak](/images/t14.webp)

Pozostał czas na napis! TAWA wydrukowana została na 3D i doprasowana do krzywizny ramy. 
![TAWA napis 3d](/images/t15.webp)

Napis na boku ramy wyśmienicie pasuje do żółtego potwora!
![Tawa na ramie](/images/t16.webp)

Pierwsze wrażenia z jazdy? **Zaskakująco stabilna.** Duże koła robią robotę, a centralna bateria utrzymuje w dobrym miejscu środek ciężkości. Przyspieszenie jest płynne, a zasięg wystarczający na codzienne dojazdy - około 50km zasięgu.

---

## Specyfikacja techniczna

| Parametr | Wartość |
|----------|---------|
| Rama | Stal S355, spawana TIG |
| Koła | 26 i 24 cali (MTB) |
| Amortyzacja | Widelec z przodu |
| Motor | Hub motor 250-500W MXUS |
| Bateria | 48V / 10Ah (360Wh) |
| Zasięg | ~50 km (zależnie od trybu) |
| Maksymalna prędkość | 40-45 km/h |
| Waga | ~22 kg |
| Hamulce | Tarczowe (póki co tylko tylny) |

---

## Co bym zmienił?

Każdy projekt uczy czegoś nowego. Gdybym miał budować jeszcze raz:

1. **Lżejsza bateria** — rozważyłbym ogniwa lżejsze o wyższej jakości
2. **Tarczowe hamulce** — dołożenie przedniego hamulca, tylny to za mało
3. **Oświetlenie LED** — fabrycznie zintegrowane z baterią

---

## Podsumowanie

To była kilkumiesięczna przygoda pełna wyzwań, popełnionych błędów i małych zwycięstw. Efekt? Hulajnoga, której nikt inny nie ma. Nie kupisz jej w sklepie. Nie ma drugiej takiej.


> *„Własnoręcznie zbudowane rzeczy mają duszę. Tę swoją zostawiłem w każdej spawanej spoinie.”*

---

**Masz pytania o budowę? Chętnie podzielę się szczegółami jak do mnie napiszesz** 👇
info@borilab.pl

---
