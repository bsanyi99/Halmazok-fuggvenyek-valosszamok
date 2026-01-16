## 7. tétel

### 1. Testaxiómák
A valós számok halmazán értelmezve van két művelet, az **összeadás ($+$)** és a **szorzás ($\cdot$)**, amelyek az alábbi kilenc tulajdonsággal rendelkeznek,:

*   **Kommutativitás:** $x + y = y + x$ és $x \cdot y = y \cdot x$ minden $x, y \in \mathbb{R}$ esetén,.
*   **Asszociativitás:** $(x + y) + z = x + (y + z)$ és $(x \cdot y) \cdot z = x \cdot (y \cdot z)$,.
*   **Disztributivitás:** A szorzás disztributív az összeadásra nézve: $x \cdot (y + z) = x \cdot y + x \cdot z$,.
*   **Zérus- és egységelem létezése:** Létezik egy $0 \in \mathbb{R}$ (nullelem) és egy $1 \in \mathbb{R}$ ($1 \neq 0$, egységelem), amelyre minden $x \in \mathbb{R}$ esetén $x + 0 = x$ és $x \cdot 1 = x$,.
*   **Inverzek létezése:**
    *   Minden $x \in \mathbb{R}$ esetén létezik **additív inverz** (jelölése: $-x$), hogy $x + (-x) = 0$,.
    *   Minden $0 \neq x \in \mathbb{R}$ esetén létezik **multiplikatív inverz** (jelölése: $x^{-1}$ vagy $1/x$), hogy $x \cdot x^{-1} = 1$,.

### 2. Rendezési axiómák és a műveletek monotonitása
A valós számok teste **rendezett test**, mivel létezik rajta egy $\le$ reláció, amely reflexív, antiszimmetrikus, tranzitív és lineáris (bármely két elem összehasonlítható),. A rendezés és a műveletek kapcsolatát a **monotonitási axiómák** rögzítik:
*   **Az összeadás monotonitása:** Ha $x \le y$, akkor $x + z \le y + z$ minden $z \in \mathbb{R}$ esetén,.
*   **A szorzás monotonitása:** Ha $0 \le x$ és $0 \le y$, akkor **$0 \le x \cdot y$**,.

### 3. A teljességi axióma
Az $\mathbb{R}$ (mint rendezett halmaz) **teljes**, ami azt jelenti, hogy **minden nemüres, felülről korlátos részhalmazának létezik pontos felső korlátja (supremuma)** a valós számok körében,. 
*   **Következmény:** Ebből következik, hogy minden nemüres, alulról korlátos részhalmaznak létezik pontos alsó korlátja (**infimuma**) is,.

### 4. A testaxiómák fontosabb következményei
A fenti alapvető szabályokból számos tétel levezethető:
*   **Egyértelműség:** A nullelem (0) és az egységelem (1) egyértelműen meghatározott,. Hasonlóan, minden elemnek pontosan egy additív és (nemnulla esetén) egy multiplikatív inverze van,.
*   **Egyszerűsítési szabály:** Ha $x + y = x + z$, akkor $y = z$. Ha $x \neq 0$ és $xy = xz$, akkor $y = z$,.
*   **Zérusosztó-mentesség:** $x \cdot y = 0$ akkor és csak akkor teljesül, ha **$x = 0$ vagy $y = 0$**,.
*   **Kivonás és osztás:** E műveletek az inverzek segítségével egyértelműen definiálhatók: $x - y = x + (-y)$ és $x/y = x \cdot y^{-1}$,.

### 5. Rendezett testek további tulajdonságai
A rendezett testekben (így $\mathbb{R}$-ben is) érvényesek az alábbiak:
*   **$0 < 1$:** Az egységelem mindig nagyobb a nullelemnél,. (Bizonyítás: Ha $1 < 0$ lenne, akkor $(-1) \cdot (-1) = 1 > 0$ adódna, ami ellentmondás,).
*   **A szorzás és a negatív számok:** Ha $x < y$ és **$z > 0$, akkor $xz < yz$**; de ha **$z < 0$, akkor a reláció megfordul: $xz > yz$**,.
*   **Négyzetszámok:** Bármely $x \neq 0$ esetén $x^2 > 0$,.
*   **Abszolútérték:** Értelmezhető az $|x| = \max\{x, -x\}$ függvény, amelyre teljesül a háromszög-egyenlőtlenség: **$|x + y| \le |x| + |y|$**,.
*   **Arkhimédészi tulajdonság:** Minden valós számhoz található nálánál nagyobb természetes szám (azaz a természetes számok halmaza felülről nem korlátos),.
