# 10.tétel

### 1. Az Arkhimédészi tulajdonság

Ez a tulajdonság a valós számok rendezésének és műveleteinek kapcsolatát írja le, biztosítva, hogy nincsenek "végtelenül kicsi" vagy "végtelenül nagy" (a természetes számokhoz képest elérhetetlen) valós számok.

*   **A tétel kimondása:** Bármely $x$ pozitív valós szám ($x \in \mathbb{R}^+$) és tetszőleges $y$ valós szám ($y \in \mathbb{R}$) esetén létezik olyan $n$ természetes szám ($n \in \mathbb{N}$), amelyre igaz, hogy **$y < nx$**,.
*   **Jelentése:** Ha veszünk egy tetszőlegesen kicsi pozitív $x$ számot, azt elegendően sokszor összeadva ($n$-szeresét véve) bármilyen nagy $y$ számnál nagyobbat kaphatunk.
*   **Következmény:** A tételből következik, hogy a természetes számok halmaza ($\mathbb{N}$) felülről nem korlátos a valós számok halmazában,.

### 2. A Cantor-féle metszet-tétel

Ez a tétel a valós számok teljességének egyik fontos következménye, amely a zárt intervallumok sorozataira vonatkozik.

*   **Egymásba skatulyázott intervallumok:** Legyen $I = \{[a_i, b_i] \subset \mathbb{R} \mid i \in \mathbb{N}\}$ zárt intervallumoknak egy olyan rendszere, ahol minden $i$-re teljesül, hogy az $i+1$-edik intervallum része az $i$-ediknek, azaz **$[a_{i+1}, b_{i+1}] \subset [a_i, b_i]$** (vagyis $a_i \le a_{i+1} \le b_{i+1} \le b_i$),.
*   **A tétel kimondása:** Ha $H = \{[a_i, b_i]\}$ egy egymásba skatulyázott, nemüres **zárt** intervallumokból álló rendszer (intervallumlánc), akkor ezek metszete nem üres, azaz:
    **$\bigcap_{i=1}^{\infty} [a_i, b_i] \neq \emptyset$**,.
*   **Bizonyítási alapgondolat:** Az intervallumok végpontjai korlátos halmazokat alkotnak. Az $A = \{a_i\}$ bal oldali végpontok halmazának szuprémuma ($\alpha = \sup A$) és a $B = \{b_i\}$ jobb oldali végpontok halmazának infimuma ($\beta = \inf B$) létezik a valós számok teljessége miatt. Igazolható, hogy $\alpha \le \beta$, és az $[\alpha, \beta]$ intervallum része az összes $[a_i, b_i]$ intervallumnak, így a metszet nem üres,.
*   **Kiterjesztés:** A tétel igaz a komplex számok halmazán ($\mathbb{C}$) értelmezett egymásba skatulyázott zárt téglalapokra (intervallumokra) is.

### 3. Példák és ellenpéldák intervallum-sorozatokra

A Cantor-tétel feltételei (zártság, korlátosság) elengedhetetlenek. Ha ezek nem teljesülnek, a metszet lehet üres.

**a) Példa egymásba skatulyázott zárt intervallumokra (A tétel teljesül):**
*   A tizedes törtek előállításánál használt intervallum-sorozat: Az eljárás során egyre szűkebb zárt intervallumokat határozunk meg (pl. $[a_n, b_n]$), amelyek hossza tart a nullához. Ekkor a metszet pontosan egyetlen valós számot tartalmaz,-.
*   A Bolzano-Weierstrass tétel bizonyításánál használt intervallumfelezési eljárás szintén egymásba skatulyázott zárt intervallumokat állít elő, amelyek metszete egyetlen pont (a torlódási pont)-.

**b) Ellenpélda: Nem zárt (nyílt) intervallumok:**
*   Tekintsük az $I_n = ]0, \frac{1}{n}]$ (balról nyílt, jobbról zárt) vagy az $I_n = ]0, \frac{1}{n}[$ intervallumokat. Bár ezek egymásba skatulyázottak ($I_{n+1} \subset I_n$), a metszetük üres:
    **$\bigcap_{n \in \mathbb{N}} ]0, \frac{1}{n}] = \emptyset$**
    Ez azért van, mert nincs olyan pozitív valós szám, amely minden $1/n$-nél kisebb lenne (az Arkhimédészi tulajdonság miatt), a 0 pedig nem eleme az intervallumoknak,.

**c) Ellenpélda: Nem korlátos intervallumok:**
*   Tekintsük az $I_n = [n, \infty[$ zárt, de nem korlátos intervallumokat. Bár $I_{n+1} \subset I_n$, a metszetük üres:
    **$\bigcap_{n \in \mathbb{N}} [n, \infty[ = \emptyset$**
    Ez szintén az Arkhimédészi tulajdonságból következik (bármely valós számnál van nagyobb természetes szám, így egyetlen szám sem lehet benne minden $I_n$-ben),.
