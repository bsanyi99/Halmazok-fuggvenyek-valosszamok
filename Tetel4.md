## 4. Tétel
Az ekvivalencia-reláció és a halmazok osztályozása szorosan összefüggő fogalmak a halmazelméletben, amelyek gyakorlatilag ugyanazt a struktúrát írják le két különböző nézőpontból.

### 1. Az ekvivalencia-reláció fogalma
Legyen $X$ egy nemüres halmaz. Egy $\sim$ relációt **ekvivalencia-relációnak** nevezünk $X$-en, ha teljesíti az alábbi három tulajdonságot:
*   **Reflexív:** Minden $x \in X$ esetén $x \sim x$.
*   **Szimmetrikus:** Ha $x, y \in X$ és $x \sim y$, akkor $y \sim x$.
*   **Tranzitív:** Ha $x, y, z \in X$, továbbá $x \sim y$ és $y \sim z$, akkor $x \sim z$.

### 2. Az osztályozás (partíció) fogalma
Legyen $H$ egy nemüres halmaz. Egy $\mathcal{A} \subset \mathcal{P}(H) \setminus \{\emptyset\}$ halmazcsaládot a $H$ halmaz **osztályozásának** nevezünk, ha:
*   Elemei **páronként diszjunktak**, azaz két különböző osztálynak nincs közös eleme ($B, C \in \mathcal{A}, B \neq C \implies B \cap C = \emptyset$).
*   Az osztályok **egyesítése kiadja az eredeti halmazt** ($\bigcup \mathcal{A} = H$).

### 3. Kapcsolat az ekvivalencia-reláció és az osztályozás között
A források szerint a két fogalom között kölcsönösen egyértelmű megfeleltetés van:

1.  **Relációból osztályozás:** Ha $\sim$ egy ekvivalencia-reláció $X$-en, akkor az **ekvivalenciaosztályok** (azaz az egymással relációban álló elemek halmazai: $\tilde{x} = \{y \in X \mid y \sim x\}$) az $X$ halmaz egy osztályozását alkotják.
2.  **Osztályozásból reláció:** Ha adott egy $\mathcal{A}$ osztályozás $X$-en, akkor definiálható egy olyan $R$ ekvivalencia-reláció, amelyben két elem ($x$ és $y$) akkor és csak akkor áll relációban, ha **ugyanabba az osztályba tartoznak** ($x, y \in A \in \mathcal{A}$).

### 4. Példák
*   **Egyenlőség:** A halmaz elemei közötti egyenlőségi reláció egyértelmű példa ekvivalencia-relációra. Ebben az esetben minden elem egy külön osztályt alkot.
*   **Halmazok ekvivalenciája (Számosság):** Egy tetszőleges $X$ halmaz esetén a részhalmazok közötti "egyenlő számosság" ($\sim$) ekvivalencia-reláció a hatványhalmazon ($\mathcal{P}(X)$), mivel reflexív, szimmetrikus és tranzitív. Itt az egy osztályba tartozó halmazok azok, amelyek között létezik bijekció.
*   **Metrikák ekvivalenciája:** Két metrika ekvivalenciája szintén ekvivalencia-reláció az egy adott halmazon értelmezett összes metrika halmazán.
*   **Struktúrák hasonlósága:** Két jólrendezett halmaz közötti hasonlósági reláció szintén ekvivalencia-relációnak tekinthető.
