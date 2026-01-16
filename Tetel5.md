## 5.Tétel

### 1. (Részben)rendezett halmazok
*   **Parciális rendezés (Féligrendezés):** Egy $X$ halmazon értelmezett $\preceq$ relációt **parciális rendezésnek** nevezünk, ha:
    *   **Reflexív:** $x \preceq x$ minden $x \in X$ esetén.
    *   **Antiszimmetrikus:** Ha $x \preceq y$ és $y \preceq x$, akkor $x = y$.
    *   **Tranzitív:** Ha $x \preceq y$ és $y \preceq z$, akkor $x \preceq z$.
*   **Rendezett halmaz (Lineáris rendezés):** Ha a fenti tulajdonságok mellett a reláció **lineáris** is (azaz bármely $x, y \in X$ esetén $x \preceq y$ vagy $y \preceq x$ teljesül), akkor **rendezésről** beszélünk.

### 2. Korlátok és nevezetes elemek
Legyen $(X, \preceq)$ egy féligrendezett halmaz és $A \subset X$:
*   **Alsó és felső korlát:** $b \in X$ **felső korlátja** $A$-nak, ha minden $a \in A$ esetén $a \preceq b$. Hasonlóan $b$ **alsó korlát**, ha minden $a \in A$ esetén $b \preceq a$.
*   **Maximális és minimális elem:** $b \in A$ **maximális eleme** $A$-nak, ha **nem létezik olyan $a \in A$, amelyre $b \prec a$**. Hasonlóan $b$ **minimális elem**, ha nincs nála kisebb $A$-beli elem. (Fontos: egy halmaznak több maximális eleme is lehet, és nem biztos, hogy ezek összehasonlíthatóak).
*   **Maximum és minimum:** $b = \max A$, ha $b \in A$ és $b$ felső korlátja $A$-nak. $b = \min A$, ha $b \in A$ és $b$ alsó korlátja $A$-nak.
*   **Supremum és infimum:** A **supremum ($sup A$)** a felső korlátok halmazának legkisebb eleme (pontos felső korlát). Az **infimum ($inf A$)** az alsó korlátok halmazának legnagyobb eleme (pontos alsó korlát).

### 3. Teljesség és példák
*   **Teljesség:** Egy féligrendezett halmaz **teljes**, ha minden nemüres, felülről korlátos részhalmazának létezik pontos felső korlátja (supremuma) a halmazban. Ha egy halmaz teljes, akkor minden nemüres alulról korlátos részhalmazának is van pontos alsó korlátja.

**Példák:**
1.  **$(\mathbb{R}, \leq)$:** A valós számok a szokásos rendezéssel **teljes rendezett testet** alkotnak.
2.  **$(\mathbb{R}^n, \preceq)$:** Valós szám $n$-esek, ahol az összehasonlítás komponensenként történik ($x_j \leq y_j$ minden $j$-re). Ez féligrendezett halmaz.
3.  **$(P(X), \subset)$:** Egy halmaz hatványhalmaza a tartalmazás relációval féligrendezett halmaz, és egyben teljes is (mivel bármely részhalmaz-család supremuma az uniójuk).
4.  **Lexikografikus rendezés $\mathbb{R}^2$-en:** $(x_1, x_2) \preceq (y_1, y_2)$, ha $x_1 < y_1$ vagy ($x_1 = y_1$ és $x_2 \leq y_2$). Ez rendezett halmaz, de **nem teljes**.

### 4. Kiválasztási axióma, Zorn-lemma és Zermelo-tétel
A források kiemelik, hogy az alábbi három állítás **egymással ekvivalens**:

*   **Kiválasztási axióma:** Ha adott egy nemüres halmazokból álló $(A_\gamma)_{\gamma \in \Gamma}$ halmazcsalád, akkor létezik egy olyan kiválasztási függvény, amely minden $A_\gamma$ halmazból pontosan egy elemet választ ki.
*   **Zorn-lemma:** Ha egy nemüres féligrendezett halmazban **minden (lineárisan) rendezett részhalmaznak (láncnak) van felső korlátja**, akkor a halmaznak **van legalább egy maximális eleme**.
*   **Zermelo jólrendezhetőségi tétele:** **Minden nemüres halmaz jólrendezhető**, azaz megadható rajta egy olyan rendezés, amelyben a halmaz minden nemüres részhalmazának van legkisebb eleme.
