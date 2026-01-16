# 15.tétel

### 1. Bernoulli-egyenlőtlenség
Ez az egyenlőtlenség a hatványozás és a szorzás kapcsolatát becsüli meg.
*   **Állítás:** Ha $n \in \mathbb{N}$ és $x \in \mathbb{R}$ olyan, hogy $x \ge -1$, akkor:
    $$(1+x)^n \ge 1+nx$$
   ,.
*   **Egyenlőség feltétele:** Az egyenlőség akkor és csak akkor teljesül, ha $n=1$ vagy $x=0$,.
*   **Bizonyítás:** A tétel teljes indukcióval igazolható,.

### 2. A számtani és mértani közepek közötti egyenlőtlenség (Cauchy-tétel)
Ez az egyenlőtlenség a pozitív valós számok különböző középértékeit hasonlítja össze.
*   **Definíciók:** Legyenek $x_1, \dots, x_n$ pozitív valós számok.
    *   **Számtani közép ($A_n$):** $\frac{x_1 + \dots + x_n}{n}$.
    *   **Mértani közép ($G_n$):** $\sqrt[n]{x_1 \dots x_n}$.
    *   **Harmonikus közép ($H_n$):** $\frac{n}{\frac{1}{x_1} + \dots + \frac{1}{x_n}}$.
*   **Állítás:** Bármely $n \in \mathbb{N}$ és pozitív $x_i$ számok esetén:
    $$H_n \le G_n \le A_n$$
    A források a $G_n \le A_n$ egyenlőtlenséget emelik ki Cauchy tételeként, illetve a Páles-féle jegyzet a harmonikus közepet is bevonja az összehasonlításba ($M_{-1} \le M_0 \le M_1$).
*   **Egyenlőség feltétele:** Egyenlőség akkor és csak akkor áll fenn, ha a számok mind egyenlőek ($x_1 = x_2 = \dots = x_n$),.

### 3. Hatványközepek közötti egyenlőtlenség
A közepek fogalma általánosítható tetszőleges $p \in \mathbb{Q}$ kitevőre.
*   **Definíció:** Az $x_1, \dots, x_n$ pozitív számok $p$-edik hatványközépértéke ($p \ne 0$):
    $$M_p(x_1, \dots, x_n) = \left( \frac{x_1^p + \dots + x_n^p}{n} \right)^{\frac{1}{p}}$$
    Míg $M_0$ a mértani közép.
*   **Állítás:** A hatványközepek a minimum és maximum közé esnek:
    $$\min\{x_i\} \le M_p(x_1, \dots, x_n) \le \max\{x_i\}$$
   .

### 4. Cauchy-Bunyakovszkij-Schwarz-egyenlőtlenség (CBS)
Ez az egyenlőtlenség alapvető szerepet játszik az euklideszi terek elméletében és a skaláris szorzat becslésében.
*   **Állítás:** Legyenek $x_1, \dots, x_n$ és $y_1, \dots, y_n$ valós számok. Ekkor:
    $$\left( \sum_{i=1}^n x_i y_i \right)^2 \le \left( \sum_{i=1}^n x_i^2 \right) \left( \sum_{i=1}^n y_i^2 \right)$$
   ,.
*   **Egyenlőség feltétele:** Egyenlőség akkor és csak akkor teljesül, ha léteznek olyan $\lambda, \mu$ nem mind nulla számok, hogy $\lambda x_i = \mu y_i$ minden $i$-re (azaz a vektorok arányosak/párhuzamosak).
*   **Bizonyítás:** A bizonyítás történhet egy másodfokú segédfüggvény ($f(t) = \sum (x_i t + y_i)^2$) diszkriminánsának vizsgálatával.

### 5. Minkowski-egyenlőtlenség
Ez az egyenlőtlenség a háromszög-egyenlőtlenség általánosítása $n$-dimenziós terekre.
*   **Állítás:** Legyenek $x_1, \dots, x_n$ és $y_1, \dots, y_n$ valós számok. Ekkor:
    $$\sqrt{\sum_{i=1}^n (x_i + y_i)^2} \le \sqrt{\sum_{i=1}^n x_i^2} + \sqrt{\sum_{i=1}^n y_i^2}$$
   ,.
*   **Jelentősége:** Ez biztosítja, hogy az euklideszi norma (vektor hossza) teljesíti a metrika (távolság) tulajdonságait,.

### 6. Háromszög-egyenlőtlenség (Abszolút értékre)
A valós és komplex számok abszolút értékére vonatkozó alapvető összefüggés.
*   **Állítás:** Bármely $x, y$ valós (vagy komplex) számra:
    $$|x + y| \le |x| + |y|$$
   ,,.
*   **Következmény:** $||x| - |y|| \le |x - y|$,.

### 7. Hölder-egyenlőtlenség
A források a feladatok között említik a Hölder-egyenlőtlenséget, amely a Cauchy-Bunyakovszkij-Schwarz-egyenlőtlenség általánosítása $p, q > 1$ konjugált kitevőkre ($1/p + 1/q = 1$):
*   $$\sum_{i=1}^n x_i y_i \le \left( \sum_{i=1}^n x_i^p \right)^{1/p} \left( \sum_{i=1}^n y_i^q \right)^{1/q}$$
   .
