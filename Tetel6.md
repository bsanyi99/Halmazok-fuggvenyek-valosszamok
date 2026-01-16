## 6.tétel

### 1. Halmazok ekvivalenciája és a számosság fogalma
*   **Egyenlő számosság:** Két halmaz, $A$ és $B$ **egyenlő számosságú (ekvivalens)**, ha létezik közöttük **bijektív leképezés** (bijekció), azaz egy kölcsönösen egyértelmű megfeleltetés. Jelölése: $cardA = cardB$ vagy $A \sim B$.
*   **Számosságok összehasonlítása:** Az $A$ halmaz számossága **kisebb vagy egyenlő**, mint $B$ számossága ($cardA \le cardB$), ha létezik **$A$-ból $B$-be vezető injektív leképezés**.
*   **Szigorúan kisebb számosság:** $cardA < cardB$ akkor teljesül, ha $cardA \le cardB$ fennáll, de a két halmaz nem egyenlő számosságú.
*   **Ekvivalencia-reláció:** A halmazok ekvivalenciája ($\sim$) a halmazok egy tetszőleges családján ekvivalencia-reláció, mivel reflexív, szimmetrikus és tranzitív.

### 2. Schröder–Bernstein-tétel
A tétel a számosságok közötti $\le$ reláció antiszimmetriáját mondja ki, ami alapvető a számosságok rendezéséhez.
*   **Állítás:** Ha az $A$ és $B$ halmazokra teljesül, hogy **$cardA \le cardB$ és $cardB \le cardA$**, akkor a két halmaz **egyenlő számosságú**, azaz **$cardA = cardB$**.
*   **Jelentősége:** Ez lehetővé teszi annak igazolását, hogy két halmaz ekvivalens, anélkül, hogy közvetlenül megadnánk közöttük egy bijekciót; elegendő két kölcsönös injekciót találni.
*   **Bizonyítási alapgondolat:** A források szerint a tétel bizonyítható a **Tarski-féle fixponttétel** segítségével, egy olyan monoton növekvő leképezést definiálva a hatványhalmazon, amelynek fixpontja kijelöli a megfelelő részeket a bijekció felépítéséhez.

### 3. Cantor-tétel
Ez a tétel bizonyítja, hogy nem létezik "legnagyobb" számosság, mivel minden halmaznál van nagyobb.
*   **Állítás:** Tetszőleges $X$ halmaz esetén a halmaz számossága **szigorúan kisebb a hatványhalmazának számosságánál**: **$cardX < cardP(X)$**.
*   **Bizonyítás (indirekt):** Tegyük fel, hogy létezik $\psi: X \to P(X)$ bijekció. Tekintsük az **$A = \{x \in X \mid x \notin \psi(x)\}$** halmazt. Mivel $\psi$ szürjektív, kell lennie egy olyan $a \in X$ elemnek, amelyre $\psi(a) = A$. Ekkor azonban ellentmondáshoz jutunk: $a \in A \iff a \notin \psi(a) = A$.
*   **Következmény:** Mivel $cardX < cardP(X) < cardP(P(X)) \dots$, a számosságok sora végtelen.

### 4. Nevezetes számossági osztályok
*   **Véges halmaz:** Olyan halmaz, amely ekvivalens egy $N_n = \{1, 2, \dots, n\}$ alakú halmazzal vagy üres.
*   **Megszámlálhatóan végtelen halmaz:** A **természetes számok halmazával ($\mathbb{N}$)** ekvivalens halmaz. Ilyen például az egész számok ($\mathbb{Z}$) és a racionális számok ($\mathbb{Q}$) halmaza is.
*   **Megszámlálható halmaz:** Amely véges vagy megszámlálhatóan végtelen.
*   **Kontinuum számosság:** A **valós számok halmazának ($\mathbb{R}$)** számossága. Cantor tétele és az exponenciális leképezés alapján ez megegyezik a természetes számok hatványhalmazának számosságával: $card\mathbb{R} = cardP(\mathbb{N})$. A források igazolják, hogy a valós számok halmaza **nem megszámlálható**.
