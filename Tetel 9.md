## 9. tétel

A források alapján az alábbiakban összefoglalom a számhalmazokra, sorozatokra, valamint a rekurzióra és teljes indukcióra vonatkozó ismereteket:

### 1. Természetes, egész és racionális számok
*   **Természetes számok ($\mathbb{N}$):** Az $\mathbb{R}$ azon legszűkebb **induktív részhalmazát** nevezzük így, amely tartalmazza az 1-et, és minden $n$ elemével együtt az $n+1$ is eleme. A természetes számok halmaza teljesíti a **Peano-axiómákat**, és alulról korlátos (infimuma 1), de felülről nem.
*   **Egész számok ($\mathbb{Z}$):** A természetes számok különbségeként előálló számok halmaza: $\mathbb{Z} = \{n - m \mid n, m \in \mathbb{N}\}$. Ez felbontható a pozitív egészek ($\mathbb{N}$), a nulla ({0}) és a negatív egészek halmazára. A $\mathbb{Z}$ halmaz **zárt az összeadásra, szorzásra és kivonásra**.
*   **Racionális számok ($\mathbb{Q}$):** Azon valós számok, amelyek felírhatók két egész szám hányadosaként ($k/l$, ahol $l \neq 0$). A racionális számok halmaza **testet alkot**, és ez a valós számok legszűkebb részteste. $\mathbb{Q}$ mindenütt **sűrű** $\mathbb{R}$-ben, azaz bármely két valós szám között van racionális szám.

### 2. Számsorozat és halmazsorozat
*   **Számsorozat:** Olyan $f: \mathbb{N} \to \mathbb{R}$ (vagy $\mathbb{C}$) függvény, amely a természetes számokhoz valós (vagy komplex) számokat rendel. A sorozat $n$-edik tagját $x_n, a_n$ vagy $f(n)$ jelöli, magát a sorozatot pedig $\langle x_n \rangle$ vagy $(x_n)_{n \in \mathbb{N}}$ szimbólummal adjuk meg.
*   **Halmazsorozat (indexelt halmazrendszer):** Ha egy $I \neq \emptyset$ indexhalmaz (például $I = \mathbb{N}$) minden $i$ eleméhez hozzárendelünk egy $A_i$ halmazt, akkor az $\{A_i \mid i \in I\}$ halmazt **indexelt halmazcsaládnak** (vagy halmazrendszernek) nevezzük.

### 3. Rekurzív definíció és teljes indukció
*   **Rekurzív definíció elve:** Lehetővé teszi egy sorozat elemeinek meghatározását úgy, hogy megadjuk az első elemet ($x_1 = a$), majd a rákövetkező elemeket az előző tag(ok) függvényében fejezzük ki ($x_{m+1} = a_m(x_1, \dots, x_m)$). Így definiáljuk például a hatványozást ($x^{n+1} = x^n \cdot x$) vagy a faktoriálist ($n!$).
*   **A teljes indukció elve:** Ha egy $T_n$ állításra igaz, hogy $T_1$ teljesül, és abból, hogy $T_n$ igaz, következik $T_{n+1}$ igazsága, akkor az állítás **minden $n \in \mathbb{N}$ esetén igaz**. Ez az elv a természetes számok definíciójából (indukciós axióma) következik.

### 4. Véges sok valós szám összege és szorzata
A véges összegeket és szorzatokat a rekurzív definíció segítségével értelmezzük egy $(x_n)$ számsorozat esetén:
*   **Összeg ($\sum_{i=1}^n x_i$):** 
    *   $\sum_{i=1}^1 x_i = x_1$
    *   $\sum_{i=1}^{n+1} x_i = (\sum_{i=1}^n x_i) + x_{n+1}$.
*   **Szorzat ($\prod_{i=1}^n x_i$):**
    *   $\prod_{i=1}^1 x_i = x_1$
    *   $\prod_{i=1}^{n+1} x_i = (\prod_{i=1}^n x_i) \cdot x_{n+1}$.

A források megjegyzik, hogy ezek a műveletek öröklik a valós számok tulajdonságait, például a szorzás disztributivitását az összeadásra nézve ($c \sum x_i = \sum cx_i$).
