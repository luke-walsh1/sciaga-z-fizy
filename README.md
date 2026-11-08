# Ściąga: gazy doskonałe i przemiany gazowe

<!-- tab: Tab 1 -->

# Ściąga: gazy doskonałe i przemiany gazowe

2026-11-07

## 1. Stałe i jednostki

Zasada nr 1: **T zawsze w kelwinach** (T = t + 273), reszta w jednostkach SI, gdy używasz R lub k.

| Wielkość | Wartość | Uwagi |
| --- | --- | --- |
| R (stała gazowa) | 8,31 J/(mol·K) | z n (mole) |
| k (stała Boltzmanna) | 1,38·10⁻²³ J/K | z N (cząsteczki), k = R/N\_A |
| N\_A (liczba Avogadra) | 6,02·10²³ 1/mol | N = n·N\_A |
| warunki normalne | p = 101 325 Pa, T = 273 K | 1 mol gazu: V = 22,4 dm³ |
| T | T\[K\] = t\[°C\] + 273 | ΔT = Δt |

| Jednostka | Zamiana na SI |
| --- | --- |
| 1 dm³ = 1 litr | 10⁻³ m³ (dziel przez 1000) |
| 1 cm³ | 10⁻⁶ m³ (dziel przez 1 000 000) |
| 1 kPa / 1 hPa / 1 MPa | 10³ Pa / 10² Pa / 10⁶ Pa |
| 1 atm | ok. 10⁵ Pa (101 325 Pa) |
| 1 g / 1 t | 10⁻³ kg / 10³ kg |
| masa molowa μ | g/mol → kg/mol: dziel przez 1000 (28 g/mol = 0,028 kg/mol) |
| 1 kmol | 1000 mol |

W przemianach, gdzie liczysz stosunek (p₁V₁ = p₂V₂, V₁/T₁ = V₂/T₂), jednostki p i V mogą być dowolne, byle takie same po obu stronach. **T i tak zawsze w K.**

| Gaz | Wzór | μ \[g/mol\] |
| --- | --- | --- |
| wodór | H₂ | 2 |
| hel | He | 4 |
| neon | Ne | 20 |
| azot | N₂ | 28 |
| tlen | O₂ | 32 |
| dwutlenek węgla | CO₂ | 44 |
| powietrze | mieszanina | ok. 29 |

Gazy dwuatomowe (H₂, N₂, O₂): masa molowa = 2 × masa atomowa. Gazy szlachetne (He, Ne) są jednoatomowe.

## 2. Wzory podstawowe

Wybór wzoru: w zadaniu są **mole n** (albo masa m i μ) → użyj R. Są **cząsteczki N** → użyj k.

Równanie Clapeyrona:

```latex
pV = nRT \qquad\qquad pV = NkT
```

Ilość gazu:

```latex
n = \frac{m}{\mu} \qquad\qquad n = \frac{N}{N_A} \qquad\qquad N = n\cdot N_A
```

Gęstość gazu (objętość i masa znikają):

```latex
\rho = \frac{m}{V} \qquad\qquad p = \frac{\rho R T}{\mu} \qquad\qquad T = \frac{p\mu}{\rho R}
```

Przy stałej temperaturze p/ρ = const (również 5.48).

Teoria kinetyczna (rozdz. 19):

```latex
\overline{E_k} = \frac{3}{2}kT \qquad\qquad pV = \frac{2}{3}N\overline{E_k} \qquad\qquad pV = \frac{1}{3}N m_0 \overline{v^2} \qquad\qquad p = \frac{1}{3}\rho \overline{v^2}
```

Średnia prędkość (pierwiastek ze średniego kwadratu prędkości):

```latex
v = \sqrt{\frac{3kT}{m_0}} = \sqrt{\frac{3RT}{\mu}} \qquad\qquad v = \sqrt{\frac{3p}{\rho}}
```

μ w kg/mol. Gdy dwa gazy mają tę samą T, szybszy jest ten o mniejszym μ (v \~ 1/√μ).

Energia kinetyczna wszystkich cząsteczek (energia wewnętrzna gazu jednoatomowego):

```latex
E = N\cdot\frac{3}{2}kT = \frac{3}{2}pV
```

Średnia odległość między cząsteczkami (zad. 545):

```latex
\frac{V}{N} = \frac{kT}{p} \qquad\qquad d = \sqrt[3]{\frac{V}{N}}
```

## 3. Przemiany gazowe

Pierwsze pytanie w każdym zadaniu: **co się nie zmienia?** (T, p, V czy n). Od tego zależy wzór. Przy stałej ilości gazu (n = const) wszystkie poniższe wzory wynikają z jednego:

```latex
\frac{p_1 V_1}{T_1} = \frac{p_2 V_2}{T_2}
```

| Przemiana | Co stałe | Prawo | Wzór | Wykres p-V | Wykres p-T | Wykres V-T |
| --- | --- | --- | --- | --- | --- | --- |
| izotermiczna | T, n | Boyle'a-Mariotte'a | p₁V₁ = p₂V₂ (pV = const) | hiperbola | odcinek pionowy | odcinek pionowy |
| izobaryczna | p, n | Gay-Lussaca | V₁/T₁ = V₂/T₂ (V/T = const) | odcinek poziomy | odcinek poziomy | prosta przez 0 |
| izochoryczna | V, n | Charles'a | p₁/T₁ = p₂/T₂ (p/T = const) | odcinek pionowy | prosta przez 0 | odcinek poziomy |
| ogólna (n = const) | n | równanie stanu | p₁V₁/T₁ = p₂V₂/T₂ | dowolny | dowolny | dowolny |

**Jak rozpoznać przemianę na wykresie:**

- prosta przechodząca przez początek układu współrzędnych w p-T lub V-T → izochora lub izobara (p-T: V = const, V-T: p = const),
- hiperbola w p-V → izoterma, wyższa hiperbola = wyższa temperatura,
- prosta w p-V przez początek układu **nie** jest izotermą (to p = CV, zob. sekcja 7),
- na prostej przez początek układu iloraz (p/T albo V/T) jest taki sam w każdym punkcie, więc do obliczeń wybierz punkt z ładnymi liczbami.

**Porównywanie kilku prostych przez początek układu** (np. rys. 199, 203): w V-T większy ktąt nachylenia = większa stała V/T = **mniejsze ciśnienie** (p = nR/(V/T)). W p-T większy ktąt nachylenia = większa stała p/T = **mniejsza objętość** (V = nR/(p/T)).

**Wzory pomocnicze:**

- gdy zmienia się T o ΔT, a p lub V jest stałe: ΔV/V₁ = ΔT/T₁ (izobara), Δp/p₁ = ΔT/T₁ (izochora),
- wzrost o k% przy wzroście temperatury o ΔT (zad. 612): p₂/p₁ = 1 + k = T₂/T₁ → T₁ = ΔT/k,
- test sensu: ogrzewanie → rosną T oraz p (izochora) lub V (izobara); sprężanie izotermiczne → p rośnie, V maleje.

## 4. Wykresy przemian

[Embedded widget: schemat poglądowy, bez skali](node/fb27babe-6863)

Przy rysowaniu zaznacz osie, podziałki (T₁, 2T₁, 3T₁) i strzałkę kierunku przemiany.

## 5. Rurki z rtęcią i tłoki

**Rurka z kroplą lub słupkiem cieczy:** objętość V = S·l, a pole przekroju S się skraca, więc w równaniach wstawiasz same długości słupka powietrza.

```latex
p_1 l_1 = p_2 l_2 \ \ (T=\text{const}) \qquad \frac{l_1}{T_1}=\frac{l_2}{T_2} \ \ (p=\text{const})
```

| Ustawienie rurki (zamknięta z jednej strony) | Ciśnienie gazu w rurce |
| --- | --- |
| otwarty koniec do góry (pionowo) | p = p₀ + ρgh |
| otwarty koniec do dołu (pionowo) | p = p₀ − ρgh |
| poziomo | p = p₀ |
| pod kątem α do pionu | p = p₀ ± ρgh·cosα (h = długość słupka cieczy, która jest pionowym różnicą wysokości) |
| ukosem pod kątem α do poziomu (zad. 5.51c) | p = p₀ ± ρgh·sinα |

- Długość słupka powietrza = długość rurki − długość słupka cieczy.
- Gdy słupek rtęci podano w mm Hg, ciśnienie atmosferyczne też bierz w mm Hg (p₀ ≈ 760 mm Hg), wtedy nie zamieniasz na paskale.
- Zanurzona rurka zatkana u góry (5.53, 5.55): poziom cieczy w rurce niższy niż w naczyniu → p = p₀ + ρg·Δh, poziom wyższy niż w naczyniu → p = p₀ − ρg·Δh (Δh = różnica poziomów).
- Zad. z równaniem kwadratowym (5.55, 5.56) zostaw na koniec.

**Tłok z ciężkiem:** równowaga sił daje ciśnienie gazu.

```latex
p = p_0 + \frac{mg}{S} \qquad \text{(tłok z odważnikiem m na gazie, otwarty od góry)}
```

- Gdy tłok jest swobodny i ciężar się nie zmienia (p = const): ogrzewanie to izobara, więc V₁/T₁ = V₂/T₂, a przesunięcie tłoka Δh = ΔV/S.
- Gdy po dodaniu odważnika Δm tłok stoi na tej samej wysokości (V = const): p₂/p₁ = T₂/T₁, a p₂ = p₀ + (m + Δm)g/S (zad. 6.34, 6.35).
- Manometr rtęciowy: nadciśnienie = ρ\_Hg·g·Δh (ρ\_Hg = 13 600 kg/m³, g = 10 m/s² lub 9,81 m/s², zgodnie z zadaniem).

## 6. Zmiana ilości gazu, dwa gazy, zawór

Gdy gaz ucieka lub jest dopompowywany, **n się zmienia**: dla każdego stanu piszesz osobne pV = nRT i przyrównujesz to, co jest stałe.

| Sytuacja | Co stałe | Wynik |
| --- | --- | --- |
| otwarte naczynie ogrzewane, część gazu ucieka (554) | p, V | m₁T₁ = m₂T₂, czyli m₂/m₁ = T₁/T₂ |
| gaz wypuszczany lub dopuszczany, T stałe (balon, butla, 555, 564, 566) | V, T | p₁/n₁ = p₂/n₂ (ciśnienie \~ ilość gazu) |
| zmieniają się m i T, objętość stała (np. butla) | V | p₁/(m₁T₁) = p₂/(m₂T₂) |
| pompka: N cykli, T stałe (582, 590) | T | p₂V = p₁V + N·p₀Vₚ (Vₚ = objętość pompki) |

**Dwa naczynia połączone zaworem** (557, 558, 566, 571): po otwarciu zaworu ilości gazu się sumują, a ciśnienie się wyrównuje.

```latex
n = n_1 + n_2 \qquad V = V_1 + V_2 \qquad p = \frac{nRT}{V}
```

- Ta sama temperatura przed i po: p·(V₁ + V₂) = p₁V₁ + p₂V₂.
- Różne temperatury, potem wyrównane do T: p·(V₁ + V₂)/T = p₁V₁/T₁ + p₂V₂/T₂.
- Jedno naczynie próżne: gaz rozpręża się na obie objętości, p·(V₁ + V₂) = p₁V₁ (przy tej samej T).
- Mieszanina różnych gazów (558, 566): ciśnienia składowe się dodają, p = p₁ + p₂ (prawo Daltona). Masa molowa mieszaniny: μ = (m₁ + m₂)/(n₁ + n₂).

**Gaz przedzielony tłokiem** (562, 563, 567, 593):

- tłok swobodny w równowadze → ciśnienia po obu stronach równe, p₁ = p₂,
- gdy T równe, z p₁ = p₂ wynika n₁/V₁ = n₂/V₂ (stosunek objętości = stosunek ilości gazu),
- tłok nieprzewodzący ciepła przy ogrzewaniu jednej części: pisz p, V, T dla każdej części osobno, a połącz je warunkami p₁ = p₂ i V₁ + V₂ = const.

**Częste wartości pomocnicze:** 1 mol w warunkach normalnych zajmuje 22,4 dm³. Gaz o gęstości ρ w warunkach normalnych ma μ = ρ·V\_mol (np. hel: 0,178 kg/m³ · 0,0224 m³/mol ≈ 4 g/mol).

## 7. Czytanie wykresów i przemiany nietypowe

**Odczyt z wykresu:** wybierz punkt, w którym obie wartości leżą na podziałkach osi (tam, gdzie przerywane linie schodzą do osi), zamień jednostki z osi (kPa, dm³, cm³) i licz z równania stanu. Sprawdź wynik z odpowiedzią z tyłu książki.

| Co dane na wykresie | Co liczysz | Wzór |
| --- | --- | --- |
| punkt (p, V, T) na wykresie (551, 574) | n albo p | n = pV/(RT), p = nRT/V |
| punkt (p, V) bez T, dwa punkty A i B (573) | stosunek temperatur | T\_B/T\_A = p\_B V\_B / (p\_A V\_A) |
| wykres ρ(p) przy stałej T (576) | masa molowa μ | μ = ρRT/p (prosta przez początek układu, bierz dowolny punkt) |
| wykres p(T) przy stałym V (542, 551) | liczba cząsteczek lub n | z dowolnego punktu: N = pV/(kT) |
| trzy proste przez początek układu (rys. 199, 203) | porównanie p lub V | zob. sekcja 3 (nachylenie) |
| wykres z krzywą (609, 604, 605) | kierunek zmiany V lub p | iloraz p/T lub V/T w punkcie = nachylenie prostej od początku układu do tego punktu |

**Przemiany nietypowe:** wyjdź od pV = nRT i wstaw zależność z wykresu.

```latex
p = CV \ \Rightarrow \ CV^2 = nRT \ \Rightarrow \ V = \sqrt{\frac{nRT}{C}} \sim \sqrt{T}, \qquad p = CV \sim \sqrt{T}
```

- To **nie jest** izoterma ani izobara: prosta w p-V przez początek układu oznacza, że T rośnie jak V² (zad. 552).
- Prosta w p-V **nie** przez początek układu (p = p₀ + aV): T = pV/(nR), więc T zależy od V jak parabola i ma maksimum.
- W opisie zawsze dopisz, że n = const (masa gazu się nie zmienia).

**Przerysowywanie cyklu do innych układów** (621, 622, 623, 624, 6.53 do 6.56, 6.61 do 6.64):

1. Dla każdego punktu wypisz p, V, T w tabelce (brakujące z p₁V₁/T₁ = p₂V₂/T₂ lub pV = nRT).
2. Dla każdego odcinka określ, co jest stałe (T, p czy V).
3. Narysuj odcinek według tabeli z sekcji 3: izoterma = pion w p-T i V-T, izobara = poziom w p-V i p-T, izochora = pion w p-V i poziom w V-T.
4. Skala na osiach: punkty z tabelki, a nie na oko. Zaznacz strzałki kierunku i oznacz punkty cyframi 1, 2, 3.
5. Przy cyklu zaznacz T\_min i T\_max (na wykresie p-V to punkty na najniższej i najwyższej hiperboli).

## 8. Schemat rozwiązywania i typowe błędy

1. Wypisz dane i zamień jednostki (T w K, V w m³ przy R, μ w kg/mol).
2. Zapytaj: **co się nie zmienia?** (T, p, V, n).
3. Wybierz wzór: stanów jest dwa → p₁V₁/T₁ = p₂V₂/T₂ (upraszczasz o to, co stałe); stan jest jeden → pV = nRT lub pV = NkT.
4. Podstaw, policz, sprawdź sens (czy gaz się ogrzał, czy ciśnienie powinno wzrosnąć).
5. Jeśli jest wykres: odczytaj punkty z podziałek, a przy rysowaniu opisz osie i podaj kierunek przemiany.

| Typowy błąd | Jak uniknąć |
| --- | --- |
| T w °C we wzorze | zawsze T = t + 273 |
| dm³ dzielone przez 10 lub 100 | 1 dm³ = 10⁻³ m³ (sześcian), 1 cm³ = 10⁻⁶ m³ |
| masa molowa w g/mol przy R | zamień na kg/mol (28 g/mol = 0,028 kg/mol) |
| tlen jako O (16) zamiast O₂ (32) | gazy dwuatomowe: podwojona masa atomowa |
| Δt = 50 wstawione jako temperatura | do wzoru bierzesz T₁ i T₂, a różnica ΔT jest taka sama w °C i K |
| p w kPa przy R | zamień na Pa (×1000) |
| prosta w p-V przez początek układu jako izoterma | izoterma to hiperbola |
| N zamiast n | N → k, n → R |
| pominięcie ciśnienia atmosferycznego w rurce | zawsze p₀ ± ρgh |
| zapomniane „n = const” w opisie | dopisz założenie, że masa gazu się nie zmienia |

**Na ostatnią minutę przed sprawdzianem:** przeczytaj sekcję 3 (tabela przemian), sekcję 1 (T w K, jednostki) i sekcję 7 (przerysowywanie cyklu).

