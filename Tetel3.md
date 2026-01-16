## 3. tétel

### 1. A függvény fogalma és megadása
*   **Fogalma:** Legyenek $X$ és $Y$ adott halmazok. Az $f \subset X \times Y$ relációt **függvénynek** (más néven leképezésnek vagy hozzárendelésnek) nevezzük, ha bármely $x \in X$ esetén **legfeljebb egy** olyan $y \in Y$ létezik, amelyre $(x, y) \in f$,. 
*   **Megadása:** 
    *   Jelölése: **$f: X \to Y$**, ami azt jelenti, hogy $f$ az $X$ halmazt az $Y$ halmazba képezi,.
    *   Hozzárendelési szabállyal: **$x \mapsto f(x)$**, ahol $f(x)$ jelöli az $x$ elemhez rendelt pontosan egy $y$ értéket,.
    *   Gráffal: A függvény megadható az elempárok halmazaként is: **$f = \{(x, f(x)) \mid x \in D_f\}$**.
    *   *Példa:* Az $f: \mathbb{R} \to \mathbb{R}, f(x) = x^2$ hozzárendelés egy függvény, amely minden valós számhoz annak négyzetét rendeli.

### 2. Értelmezési tartomány és értékkészlet
*   **Értelmezési tartomány ($D_f$):** Azon $A$-beli elemek halmaza, amelyekhez a függvény rendel valamilyen értéket. Ha $f: X \to Y$ típusú leképezésről beszélünk, akkor $D_f = X$,.
*   **Értékkészlet ($R_f$):** Azon $B$-beli elemek halmaza, amelyeket a függvény legalább egy $x \in X$ elemhez hozzárendel: **$R_f = \{y \in Y \mid \exists x \in X, (x, y) \in f\}$**,.
    *   *Példa:* Az $f: \mathbb{R} \to \mathbb{R}, f(x) = x^2$ függvény értelmezési tartománya a valós számok halmaza ($\mathbb{R}$), értékkészlete pedig a nemnegatív valós számok halmaza ($\mathbb{R}_0^+$),.

### 3. Függvények kompozíciója (összetett függvény)
*   **Definíció:** Legyenek $f: X \to Y$ és $g: Y \to Z$ függvények. Ezek **kompozícióján** (összetételén) azt a $g \circ f: X \to Z$ függvényt értjük, amelyre minden $x \in X$ esetén **$(g \circ f)(x) = g(f(x))$** teljesül,.
*   **Feltétel:** Az összetett függvény akkor létezik, ha az $f$ értékkészlete és a $g$ értelmezési tartománya között van közös rész ($R_f \cap D_g \neq \emptyset$).
    *   *Példa:* Ha $f(x) = x + 1$ (belső függvény) és $g(x) = x^2$ (külső függvény), akkor $(g \circ f)(x) = (x + 1)^2$.

### 4. Halmaz függvény általi képe és ősképe
*   **Kép:** Ha $f: X \to Y$ és $A \subset X$, akkor az $A$ halmaz $f$ általi **képe** az $f(A) = \{f(x) \mid x \in A\}$ halmaz,.
    *   **Kapcsolat a műveletekkel:** Az unió képére igaz, hogy **$f(\bigcup A_i) = \bigcup f(A_i)$**,.
    *   Metszet és különbség esetén általában csak a tartalmazás áll fenn: $f(A \cap B) \subset f(A) \cap f(B)$ és $f(A) \setminus f(B) \subset f(A \setminus B)$,.
*   **Őskép:** Ha $B \subset Y$, akkor a $B$ halmaz $f$ általi **ősképe** az **$f^{-1}(B) = \{x \in X \mid f(x) \in B\}$** halmaz,.
    *   **Kapcsolat a műveletekkel:** Az őskép "jól viselkedik" minden művelettel:
        *   $f^{-1}(B \cup C) = f^{-1}(B) \cup f^{-1}(C)$.
        *   $f^{-1}(B \cap C) = f^{-1}(B) \cap f^{-1}(C)$,.
        *   $f^{-1}(B \setminus C) = f^{-1}(B) \setminus f^{-1}(C)$,.

### 5. Injektív, szürjektív és bijektív függvények
*   **Injektív (egy-egyértelmű):** Ha különböző $X$-beli elemekhez különböző $Y$-beli értékeket rendel, azaz $x_1 \neq x_2 \implies f(x_1) \neq f(x_2)$,,.
    *   *Példa:* Az $f(x) = 2x$ függvény injektív $\mathbb{R}$-en.
*   **Szürjektív (ráképezés):** Ha az értékkészlet megegyezik a fogadó halmazzal, azaz **$f(X) = Y$** (minden $y \in Y$ elemnek van ősképe),,.
    *   *Példa:* Az $f(x) = x^3$ függvény szürjektív $\mathbb{R}$-re nézve.
*   **Bijektív (kölcsönösen egyértelmű):** Ha a függvény **egyszerre injektív és szürjektív**,,. 
    *   **Invertálhatóság:** Egy függvény akkor és csak akkor invertálható, ha injektív,. Ha bijektív, akkor az inverze ($f^{-1}: Y \to X$) is bijektív.
    *   *Példa:* Az identikus függvény ($id_A(x) = x$) mindig bijektív,.
