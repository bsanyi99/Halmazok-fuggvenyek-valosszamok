# 12. Tétel

### 1. Egész kitevőjű hatványozás
A valós számok körében a hatványozást rekurzív módon definiálják:
*   **Természetes kitevő:** Legyen $x \in \mathbb{R}$. Ekkor $x^1 := x$, és $n \in \mathbb{N}$ esetén $x^{n+1} := x^n \cdot x$,.
*   **Nulla és negatív kitevő:** Ha $x \neq 0$, akkor $x^0 := 1$, és $n \in \mathbb{N}$ esetén $x^{-n} := \frac{1}{x^n}$,.

**Azonosságok egész kitevőkre ($n, m \in \mathbb{Z}, x, y \neq 0$):**
*   $(xy)^n = x^n y^n$,.
*   $\left(\frac{x}{y}\right)^n = \frac{x^n}{y^n}$,.
*   $x^n x^m = x^{n+m}$,.
*   **Hatvány hatványa:** $(x^n)^m = x^{nm}$,.

### 2. Az n-edik gyök
**Létezése és egyértelműsége:**
Bármely $a \in [0, \infty[$ nemnegatív valós szám és $n \in \mathbb{N}$ természetes szám esetén **pontosan egy** olyan $b \in [0, \infty[$ nemnegatív valós szám létezik, amelyre $b^n = a$,.
*   Ezt a $b$ számot az $a$ szám $n$-edik gyökének nevezzük.
*   Jelölése: $\sqrt[n]{a}$ vagy $a^{\frac{1}{n}}$,.
*   A létezés bizonyítása a valós számok teljességi axiómáján (a szuprémum tulajdonságon) alapul. A bizonyítás során az $A := \{x \in [0, \infty[ : x^n \le a\}$ halmaz szuprémumáról ($b := \sup A$) mutatják meg, hogy teljesíti a $b^n = a$ feltételt,.

**Kiterjesztés negatív alapra:**
Ha $n$ páratlan természetes szám és $x < 0$, akkor az $n$-edik gyököt a következőképpen értelmezzük: $\sqrt[n]{x} := -\sqrt[n]{-x}$,.

**Gyökvonás azonosságai ($x, y \in \mathbb{R}^+, n, m \in \mathbb{N}, k \in \mathbb{Z}$):**
*   $\sqrt[n]{xy} = \sqrt[n]{x} \sqrt[n]{y}$,.
*   $\sqrt[n]{\frac{x}{y}} = \frac{\sqrt[n]{x}}{\sqrt[n]{y}}$,.
*   $\sqrt[m]{\sqrt[n]{x}} = \sqrt[nm]{x}$,.
*   $\sqrt[n]{x^k} = (\sqrt[n]{x})^k$,.
*   Monotonitás: $x \le y \iff \sqrt[n]{x} \le \sqrt[n]{y}$,.

### 3. Racionális kitevőjű hatványok
**Definíció:**
Legyen $x \in \mathbb{R}^+$ (pozitív valós szám), $k \in \mathbb{Z}$ és $n \in \mathbb{N}$. Ha a racionális kitevő $r = \frac{k}{n}$, akkor az $x$ szám $r$-edik hatványa:
$$x^r := x^{\frac{k}{n}} := \sqrt[n]{x^k}$$
,.
A források hangsúlyozzák, hogy a definíció független a tört $r = \frac{k}{n} = \frac{l}{m}$ reprezentációjától, azaz az érték ugyanaz marad,.

**Azonosságok racionális kitevőkre ($x, y \in \mathbb{R}^+, r, s \in \mathbb{Q}$):**
A racionális kitevőjű hatványozás örökli az egész kitevőjű hatványozás tulajdonságait:
*   $(xy)^r = x^r y^r$,.
*   $\left(\frac{x}{y}\right)^r = \frac{x^r}{y^r}$,.
*   $x^{r+s} = x^r x^s$,.
*   **Hatvány hatványa:** $(x^r)^s = x^{rs}$,.

**Monotonitás:**
*   Ha $x > 1$ és $r \le s$, akkor $x^r \le x^s$.
*   Ha $p > 0$ és $x < y$, akkor $x^p < y^p$.
