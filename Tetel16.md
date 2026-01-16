A megadott források alapján a komplex számok elméletét az alábbiak szerint foglalhatjuk össze:

### 1. Definíció és algebrai alak
*   **Definíció:** A komplex számok halmaza ($\mathbb{C}$) a valós számpárok halmaza ($\mathbb{R} \times \mathbb{R}$), amelyen két műveletet, az összeadást és a szorzást értelmezzük:
    *   $(a, b) + (c, d) := (a + c, b + d)$
    *   $(a, b) \cdot (c, d) := (ac - bd, ad + bc)$,.
*   **Képzetes egység:** A $(0, 1)$ párt képzetes egységnek nevezzük és $i$-vel jelöljük. Erre teljesül, hogy $i^2 = -1$,.
*   **Algebrai alak:** Minden $z = (a, b)$ komplex szám egyértelműen felírható $z = a + bi$ alakban, ahol $a, b \in \mathbb{R}$,.
*   **Test tulajdonság:** A komplex számok halmaza a fenti műveletekkel **testet alkot**. A valós számok ($\mathbb{R}$) beágyazhatók ebbe a testbe az $a \mapsto (a, 0)$ megfeleltetéssel, így $\mathbb{R} \subset \mathbb{C}$,.

### 2. Alapfogalmak és tulajdonságok
Legyen $z = a + bi$ egy komplex szám.
*   **Valós és képzetes rész:** $Re(z) := a$ (valós rész) és $Im(z) := b$ (képzetes rész),.
*   **Konjugált:** A $z$ szám konjugáltja $\bar{z} := a - bi$.
    *   Tulajdonságok: $\overline{z + w} = \bar{z} + \bar{w}$, $\overline{zw} = \bar{z}\bar{w}$, és $z\bar{z} = |z|^2$,.
    *   Összefüggés a részekkel: $Re(z) = \frac{z + \bar{z}}{2}$, $Im(z) = \frac{z - \bar{z}}{2i}$,.
*   **Abszolút érték (modulus):** A $z$ szám abszolút értéke $|z| := \sqrt{a^2 + b^2}$.
    *   Tulajdonságok: $|z| \ge 0$, $|z| = 0 \iff z = 0$, $|zw| = |z||w|$,.
    *   **Háromszög-egyenlőtlenség:** $|z + w| \le |z| + |w|$,.
    *   Továbbá érvényes: $||z| - |w|| \le |z - w|$.

### 3. Metrikus tulajdonságok és sorozatok
*   **Metrikus tér:** A komplex számok halmaza metrikus tér a $d(z_1, z_2) := |z_1 - z_2|$ távolságfüggvénnyel (amely az euklideszi távolságnak felel meg $\mathbb{R}^2$-en),.
*   **Teljesség:** A $\mathbb{C}$ (az euklideszi metrikával) **teljes metrikus tér**, ami azt jelenti, hogy benne minden Cauchy-sorozat konvergens,.
*   **Sorozatok konvergenciája:** A $(z_n)$ komplex sorozat akkor és csak akkor konvergens, ha a valós részek $(x_n)$ és képzetes részek $(y_n)$ sorozata is konvergens (ahol $z_n = x_n + i y_n$). Ha $x_n \to x$ és $y_n \to y$, akkor $z_n \to x + iy$,.
*   **Bővített komplex sík:** Bevezethető a $\mathbb{C}_b = \mathbb{C} \cup \{\infty\}$ (vagy $\{+\infty\}$) halmaz. Egy sorozat akkor tart a $\infty$-be, ha $|z_n| \to +\infty$,,. Értelmezhető rajta metrika (Riemann-gömb) is.

### 4. Sorok és elemi függvények
A komplex analízisben a függvényeket gyakran hatványsorokkal definiáljuk, amelyek a konvergenciakörükön belül (vagy az egész síkon) értelmezettek.
*   **Sorok konvergenciája:** A $\sum z_n$ sor konvergens, ha a részletösszegek sorozata konvergens. Ha $\sum |z_n|$ konvergens (abszolút konvergencia), akkor $\sum z_n$ is konvergens,.
*   **Exponenciális függvény:** $exp(z) := \sum_{n=0}^{\infty} \frac{z^n}{n!}$. Ez a sor minden $z \in \mathbb{C}$ esetén konvergens.
    *   Addíciós tétel: $exp(x+y) = exp(x) \cdot exp(y)$,.
*   **Trigonometrikus és hiperbolikus függvények:** Hasonlóan hatványsorokkal definiálhatók a $\mathbb{C}$-n a $sin(z), cos(z), sh(z), ch(z)$ függvények,.
*   **Euler-összefüggés:** Kapcsolat az exponenciális és trigonometrikus függvények között:
    $exp(ix) = \cos(x) + i \sin(x)$,.

### 5. Számosság
*   A komplex számok halmaza **kontinuum számosságú** (számossága megegyezik a valós számokéval), mivel $\mathbb{R} \times \mathbb{R}$ ekvivalens $\mathbb{R}$-rel,,.
