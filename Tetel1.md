## 1.tétel: Halmazműveletek (unió metszet, különbség, komplementer, hatványhalmaz) és azonosságaik; tartalmazás és egyenlőség.

### 1. Tartalmazás és egyenlőség
*   **Halmazok egyenlősége:** Legyen $A = \{1, 2, 3\}$ és $B = \{3, 1, 2\}$. A két halmaz **egyenlő ($A = B$)**, mert elemeik – a sorrendtől függetlenül – pontosan ugyanazok.
*   **Tartalmazás (Részhalmaz):** Ha $A = \{1, 2\}$ és $B = \{1, 2, 3\}$, akkor **$A \subset B$**, mivel $A$ minden eleme eleme $B$-nek is.
*   **Valódi részhalmaz:** Az előző példában $A$ **valódi részhalmaza** $B$-nek ($A \subsetneq B$), mivel $A \subset B$, de $B$-nek van olyan eleme (a 3-as), amely nem szerepel $A$-ban.
*   **Üres halmaz:** Az $\emptyset$ halmaznak nincs eleme, és minden halmaznak, például a $C = \{a, b\}$ halmaznak is részhalmaza ($\emptyset \subset C$).

### 2. Halmazműveletek
*   **Unió (Egyesítés):** Legyen $A = \{a, b\}$ és $B = \{b, c\}$. Ekkor **$A \cup B = \{a, b, c\}$**, mivel ide tartozik minden olyan elem, amely legalább az egyik halmaznak eleme.
*   **Metszet (Közös rész):** Ugyanezen halmazok esetén **$A \cap B = \{b\}$**, mert csak a "b" elem szerepel mindkét halmazban egyszerre.
    *   **Diszjunkt halmazok:** Ha $A = \{1, 2\}$ és $C = \{3, 4\}$, akkor $A \cap C = \emptyset$, tehát a két halmaz diszjunkt.
*   **Különbség:** Ha $A = \{1, 2, 3\}$ és $B = \{2, 3, 4\}$, akkor **$A \setminus B = \{1\}$**, mert csak az 1-es az az elem, amely $A$-ban benne van, de $B$-ben nincs.
*   **Komplementer:** Legyen az alaphalmaz $X = \{1, 2, 3, 4, 5\}$ és $A = \{1, 2\}$. Ekkor az $A$ halmaz $X$-re vonatkozó komplementere **$A^c$ (vagy $C_X A$) $= \{3, 4, 5\}$**, azaz minden olyan $X$-beli elem, ami nincs benne $A$-ban.
*   **Hatványhalmaz:** Ha $X = \{0, 1\}$, akkor annak hatványhalmaza **$P(X) = \{\emptyset, \{0\}, \{1\}, \{0, 1\}\}$**, amely az összes lehetséges részhalmazt tartalmazza elemként.

### 3. Műveleti azonosságok
*   **Kommutativitás:** $A \cup B = B \cup A$. Példa: $\{1\} \cup \{2\} = \{2\} \cup \{1\} = \{1, 2\}$.
*   **Asszociativitás:** $(A \cap B) \cap C = A \cap (B \cap C)$. Példa: $(\{1, 2\} \cap \{2, 3\}) \cap \{2, 4\} = \{2\} \cap \{2, 4\} = \{2\}$.
*   **Disztributivitás:** $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$. Példa: $\{1\} \cup (\{2\} \cap \{1, 2\}) = \{1\} \cup \{2\} = \{1, 2\}$. A másik oldalról: $(\{1\} \cup \{2\}) \cap (\{1\} \cup \{1, 2\}) = \{1, 2\} \cap \{1, 2\} = \{1, 2\}$.
*   **Idempotencia:** **$A \cap A = A$**. Példa: $\{a, b\} \cap \{a, b\} = \{a, b\}$.
*   **Abszorpció (Elnyelési tulajdonság):** **$A \cup (A \cap B) = A$**. Példa: $\{1, 2\} \cup (\{1, 2\} \cap \{2, 3\}) = \{1, 2\} \cup \{2\} = \{1, 2\}$.
*   **De Morgan-azonosságok:** $(A \cup B)^c = A^c \cap B^c$. Példa: Ha $X = \{1, 2, 3, 4\}$, $A = \{1\}$ és $B = \{2\}$, akkor $(A \cup B) = \{1, 2\}$, aminek a komplementere $\{3, 4\}$. Külön-külön: $A^c = \{2, 3, 4\}$, $B^c = \{1, 3, 4\}$, ezek metszete szintén $\{3, 4\}$.

### 4. Összefüggés a tartalmazás és a műveletek között
*   **$A \cup B = B \iff A \subset B$:** Ha $A = \{1\}$ és $B = \{1, 2\}$, akkor $\{1\} \cup \{1, 2\} = \{1, 2\}$, ami igazolja, hogy $A$ részhalmaza $B$-nek.
*   **$A \setminus B = \emptyset \iff A \subset B$:** Ha $A = \{1, 2\}$ és $B = \{1, 2, 3\}$, akkor $A \setminus B$ nem tartalmaz elemet, tehát $A \subset B$.
