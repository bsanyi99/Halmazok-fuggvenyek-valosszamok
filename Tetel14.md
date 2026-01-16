# 14.tétel

### 1. A számosság fogalma
Két halmaz, $A$ és $B$ **egyenlő számosságú** (ekvivalens), ha létezik közöttük bijektív leképezés (kölcsönösen egyértelmű megfeleltetés),,. Ennek jelölése $cardA = cardB$ vagy $A \sim B$,.
*   Ha létezik injektív leképezés $A$-ból $B$-be, akkor $A$ számossága kisebb vagy egyenlő $B$ számosságánál ($cardA \le cardB$),.
*   A **Schröder–Bernstein-tétel** kimondja, hogy ha $cardA \le cardB$ és $cardB \le cardA$, akkor a két halmaz egyenlő számosságú,.

### 2. Véges halmazok
Egy $A$ halmazt **végesnek** nevezünk, ha az üres halmaz, vagy ha létezik olyan $n \in \mathbb{N}$ természetes szám, hogy $A$ ekvivalens az $N_n = \{1, 2, \dots, n\}$ halmazzal,,.
*   Véges halmaz minden részhalmaza véges.
*   Véges sok véges halmaz egyesítése is véges.

### 3. Megszámlálható halmazok
Egy halmazt **megszámlálhatóan végtelennek** nevezünk, ha egyenlő számosságú a természetes számok halmazával ($\mathbb{N}$), azaz létezik elemei és a természetes számok között bijekció (sorozatba rendezhető),.
Egy halmazt **megszámlálhatónak** mondunk, ha véges vagy megszámlálhatóan végtelen,.

**Nevezetes megszámlálható számhalmazok:**
*   **Természetes számok ($\mathbb{N}$):** Definíció szerint megszámlálhatóan végtelen.
*   **Egész számok ($\mathbb{Z}$):** Megszámlálható, mivel előállítható $\mathbb{N} \cup \{0\} \cup (-\mathbb{N})$ uniójaként, illetve bijekció létesíthető $\mathbb{Z}$ és $\mathbb{N}$ között (pl. $0 \to 1, 1 \to 2, -1 \to 3, \dots$),,.
*   **Racionális számok ($\mathbb{Q}$):** Megszámlálhatóan végtelen,. A bizonyítás alapja, hogy $\mathbb{Q}$ előállítható megszámlálható sok megszámlálható halmaz egyesítéseként, vagy visszavezethető $\mathbb{Z} \times \mathbb{N}$ megszámlálhatóságára,.

**Fontos tulajdonságok:**
*   Megszámlálható sok megszámlálható halmaz egyesítése is megszámlálható,,.
*   Két megszámlálható halmaz Descartes-szorzata is megszámlálható (pl. $\mathbb{N} \times \mathbb{N} \sim \mathbb{N}$),.
*   Minden végtelen halmaznak van megszámlálhatóan végtelen részhalmaza, tehát a megszámlálhatóan végtelen számosság a "legkisebb" végtelen számosság,.

### 4. Kontinuum számosság
A valós számok halmazát ($\mathbb{R}$) és a vele ekvivalens halmazokat **kontinuum számosságúnak** nevezzük.
*   **Nem megszámlálható:** A valós számok halmaza nem megszámlálható, számossága szigorúan nagyobb a természetes számokénál ($card\mathbb{N} < card\mathbb{R}$),,.
    *   Ez bizonyítható például a Cantor-féle átlós eljárással vagy egymásba skatulyázott intervallumokkal, illetve a $p$-adikus (pl. diadikus) törtbefejtéssel,.
    *   Cantor tétele szerint egy halmaz számossága mindig kisebb a hatványhalmazának számosságánál ($cardX < cardP(X)$), és igazolható, hogy $\mathbb{R}$ ekvivalens $\mathbb{N}$ hatványhalmazával ($P(\mathbb{N})$),.

**Példák kontinuum számosságú halmazokra:**
*   **Valós számok ($\mathbb{R}$):**,.
*   **Irracionális számok ($\mathbb{R} \setminus \mathbb{Q}$):** Mivel $\mathbb{R} = \mathbb{Q} \cup (\mathbb{R} \setminus \mathbb{Q})$, és $\mathbb{Q}$ megszámlálható, az irracionálisoknak kontinuum számosságúnak kell lenniük (különben $\mathbb{R}$ is megszámlálható lenne),.
*   **Intervallumok:** Bármely nyílt intervallum ($]a, b[$ vagy $]0, 1[$) ekvivalens a teljes valós számegyenessel, így kontinuum számosságú,,.
*   **Komplex számok ($\mathbb{C}$):** A komplex számok halmaza is kontinuum számosságú, mivel $\mathbb{R} \times \mathbb{R}$ ekvivalens $\mathbb{R}$-rel,.
*   **$\mathbb{R}^n$:** Bármely $n \in \mathbb{N}$ esetén kontinuum számosságú.
