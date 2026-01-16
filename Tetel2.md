## 2.tétel 
## Rendezett elempár, két halmaz Descartes-szorzata; kapcsolat a tartalmazással és a műveletekkel. Reláció fogalma, jelölése.

### 1. Rendezett elempár
*   **Definíció:** Az $a$ és $b$ elemekből (mint halmazokból) képzett **rendezett elempárnak** nevezzük az **$(a, b) = \{\{a\}, \{a, b\}\}$** halmazt. Ebben az elrendezésben $a$ az első, $b$ pedig a második komponens.
*   **Alaptulajdonság:** Két rendezett elempár akkor és csak akkor egyenlő, ha a megfelelő komponenseik megegyeznek: **$(a, b) = (c, d) \iff a = c$ és $b = d$**.
    *   *Példa:* Az $(1, 2)$ és $(2, 1)$ elempárok nem egyenlők, mert bár az elemeik ugyanazok, a sorrendjük (komponenseik értéke) eltér.

### 2. Két halmaz Descartes-szorzata
*   **Definíció:** Az $A$ és $B$ halmazok **Descartes-szorzatán ($A \times B$)** azon összes rendezett elempárok halmazát értjük, amelyeknek első komponense $A$-beli, második komponense pedig $B$-beli elem: **$A \times B = \{(a, b) \mid a \in A, b \in B\}$**.
*   **Tulajdonságok:**
    *   **Üres halmaz:** A szorzat akkor és csak akkor üres, ha legalább az egyik tényezője üres halmaz: **$A \times B = \emptyset \iff A = \emptyset$ vagy $B = \emptyset$**.
    *   **Kommutativitás hiánya:** A Descartes-szorzás általában nem kommutatív művelet ($A \times B \neq B \times A$), kivéve ha $A=B$, vagy ha az egyik halmaz üres.
    *   *Példa:* Ha $A = \{1, 2\}$ és $B = \{a\}$, akkor $A \times B = \{(1, a), (2, a)\}$, míg $B \times A = \{(a, 1), (a, 2)\}$.

### 3. Kapcsolat a tartalmazással és a műveletekkel
A Descartes-szorzat és a halmazműveletek között az alábbi azonosságok állnak fenn:
*   **Tartalmazás:**
    *   $A \times C \subset B \times C \iff A \subset B$ vagy $C = \emptyset$.
    *   $A \times B \subset A \times C \iff A = \emptyset$ vagy $B \subset C$.
*   **Disztributivitás (széttagolhatóság):**
    *   **Unióra:** $(A \cup B) \times C = (A \times C) \cup (B \times C)$.
    *   **Metszetre:** $(A \cap B) \times C = (A \times C) \cap (B \times C)$.
*   **Különbség:**
    *   $(A \setminus B) \times C = (A \times C) \setminus (B \times C)$.
    *   $A \times (B \setminus C) = (A \times B) \setminus (A \times C)$.
*   **Általánosítás indexelt halmazcsaládokra:**
    *   $A \times \bigcup_{j \in J} D_j = \bigcup_{j \in J} (A \times D_j)$.
    *   $A \times \bigcap_{j \in J} D_j = \bigcap_{j \in J} (A \times D_j)$.

### 4. Reláció fogalma és jelölése
*   **Definíció:** Tetszőleges $X$ és $Y$ halmazok esetén az **$X \times Y$ Descartes-szorzat bármely $F$ részhalmazát** (binér) **relációnak** (vagy leképezésnek) nevezzük ($F \subset X \times Y$).
*   **Jelölés:**
    *   Ha az $(x, y)$ elempár eleme az $R$ relációnak, azt gyakran az **$xRy$** rövidítéssel jelöljük (olvasva: "$x$ az $R$ relációban van $y$-nal").
    *   Speciálisan, ha $X = Y$, akkor $R$ egy **$X$-en értelmezett reláció**.
*   **Kapcsolódó fogalmak:**
    *   **Értelmezési tartomány ($D_R$):** Azon első komponensek halmaza, amelyekhez tartozik legalább egy $y$ elem a relációban.
    *   **Értékkészlet ($R_R$):** Azon második komponensek halmaza, amelyekhez tartozik legalább egy $x$ elem a relációban.
    *   **Inverz reláció ($R^{-1}$):** Az a reláció, amely az elempárok felcserélésével adódik: $R^{-1} = \{(y, x) \in Y \times X \mid (x, y) \in R\}$.
    *   *Példa:* Legyen $X = \{1, 2, 3\}$. A "kisebb" reláció $X$-en: $R = \{(1, 2), (1, 3), (2, 3)\}$. Itt például $1R2$ teljesül.
