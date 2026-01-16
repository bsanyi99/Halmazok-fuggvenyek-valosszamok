## 8.tétel

### 1. Az abszolút érték fogalma és tulajdonságai

A valós számok körében egy tetszőleges $x \in \mathbb{R}$ szám **abszolút értékén** az $|x| := \max\{-x, x\}$ nemnegatív számot értjük. Ez a definíció explicit módon a következő esetekre bontható:
*   $|x| = x$, ha $x \geq 0$ (pozitív szám vagy nulla esetén önmaga),
*   $|x| = -x$, ha $x < 0$ (negatív szám esetén annak ellentettje).

Az abszolút érték legfontosabb **műveleti tulajdonságai** a források alapján:
*   **Azonosság:** $|-x| = |x|$.
*   **Szorzatra és hányadosra vonatkozó szabály:** $|xy| = |x| \cdot |y|$ és $\left| \frac{x}{y} \right| = \frac{|x|}{|y|}$ (ha $y \neq 0$).
*   **Háromszög-egyenlőtlenség:** Bármely két valós számra igaz, hogy **$|x + y| \leq |x| + |y|$**.
*   **„Másik” háromszög-egyenlőtlenség:** Az abszolút értékek különbsége nem nagyobb a különbség abszolút értékénél: **$||x| - |y|| \leq |x - y|$**.
*   **Kapcsolat a rendezéssel:** $|x| \leq y$ akkor és csak akkor teljesül, ha $-y \leq x \leq y$.

**Geometriai értelmezés:** A valós számegyenesen két pont, $x$ és $y$ **távolságát** (metrikáját) a $d(x, y) := |x - y|$ képlettel definiáljuk. Ezt használjuk fel a pontok környezeteinek (nyílt gömbök) megadásakor is: $K(a, r) = \{x \in \mathbb{R} \mid |x - a| < r\}$.

---

### 2. Intervallumok jelölése és értelmezése

Az intervallumok a valós számok halmazának olyan speciális részhalmazai, amelyeket a rendezési relációval határozunk meg. Legyen $a, b \in \mathbb{R}$ és $a \leq b$. Az alábbi fő típusokat különböztetjük meg:

| Típus | Jelölés | Értelmezés (Halmazmegadás) |
| :--- | :--- | :--- |
| **Nyílt intervallum** | $]a, b[$ | $\{x \in \mathbb{R} \mid a < x < b\}$ |
| **Zárt intervallum** | $[a, b]$ | $\{x \in \mathbb{R} \mid a \leq x \leq b\}$ |
| **Balról zárt, jobbról nyílt** | $[a, b[$ | $\{x \in \mathbb{R} \mid a \leq x < b\}$ |
| **Balról nyílt, jobbról zárt** | $]a, b]$ | $\{x \in \mathbb{R} \mid a < x \leq b\}$ |

**Végtelen (nem korlátos) intervallumok:**
Amennyiben a halmaz egyik irányból nem korlátos, a $\pm\infty$ szimbólumokat használjuk a jelölésben:
*   **Félegyenesek:** $[a, +\infty[ = \{x \mid a \leq x\}$ vagy $]-\infty, b] = \{x \mid x \leq b\}$.
*   **Nyílt félegyenesek:** $]a, +\infty[ = \{x \mid a < x\}$ vagy $]-\infty, b[ = \{x \mid x < b\}$.
*   **A teljes valós számegyenes:** $]-\infty, +\infty[ = \mathbb{R}$.

**Fontos összefüggések:**
*   **Végpontok:** Az $a$ és $b$ számokat az intervallum végpontjainak nevezzük.
*   **Topológiai jelleg:** A nyílt intervallumok **nyílt halmazok**, míg a zárt intervallumok **zárt halmazok** az $\mathbb{R}$ szokásos topológiájában.
*   **Összefüggőség:** A források kiemelik, hogy a valós számok halmazának összefüggő részhalmazai pontosan az intervallumok (beleértve az egyelemű halmazokat és az üres halmazt is).
*   **Intervallumskatulyázás:** A zárt intervallumok egymásba skatulyázott rendszereire vonatkozik a **Cantor-féle metszettétel**, amely szerint ha $I_n = [a_n, b_n]$ olyan rendszer, ahol $I_{n+1} \subset I_n$, akkor ezek metszete nem üres. Ez a tulajdonság a valós számok teljességének egyik fontos kifejeződése.
