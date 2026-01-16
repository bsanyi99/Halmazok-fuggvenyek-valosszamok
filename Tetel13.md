# 13. Tétel

### 1. A p-adikus törtbefejtés fogalma és előállítása

Legyen $p > 1$ természetes szám. Egy tetszőleges $x \in [0, 1[$ valós szám **reguláris p-adikus törtbefejtésének** nevezzük az $(a_n)$ sorozatot, amelyet az alábbi rekurzióval állítunk elő:
*   $a_1 = [px]$ (ahol $[.]$ az egészrész függvényt jelöli),
*   $a_{n+1} = [p^{n+1}x - (a_1p^{n-1} + \dots + a_n p)]$ minden $n \in \mathbb{N}$ esetén.

Ezt a törtbefejtést szimbolikusan az $x = (0, a_1a_2 \dots)_p$ alakban jelöljük. Amennyiben $x \ge 0$ tetszőleges valós szám, úgy felbontható az egészrészére és a törtrészére ($x = [x] + (x - [x])$), így a jelölés: $x = ([x], a_1a_2 \dots)_p$.

**A p-adikus törtek tulajdonságai:**
*   **Jegyek:** A sorozat elemei (a "jegyek") a $\{0, 1, \dots, p-1\}$ halmazból kerülnek ki.
*   **Visszanyerés:** Az $x$ számot a törtbefejtése egyértelműen meghatározza a következő összegformában (szuprémumként definiálva):
    $x = \sum_{n=1}^{\infty} \frac{a_n}{p^n}$ (illetve a forrásban szuprémumként megadva: $x = \sup \{ \frac{a_1}{p} + \dots + \frac{a_n}{p^n} : n \in \mathbb{N} \}$),.
*   **Reguláris vs. Irreguláris:** A fenti rekurzióval előállított **reguláris** törtbefejtésben nem fordulhat elő, hogy egy bizonyos indextől kezdve minden jegy $p-1$ legyen (azaz nincs csupa $p-1$-esből álló végtelen "farok").
    *   Ha megengedjük a csupa $p-1$-re végződő sorozatokat is, akkor **irreguláris** törtbefejtésről beszélünk. Például $p=10$ esetén az $1/10$ felírható $0,1$ (reguláris) és $0,0999\dots$ (irreguláris) alakban is.

**Nevezetes esetek:**
*   $p=2$: Diadikus törtbefejtés.
*   $p=3$: Triadikus törtbefejtés.
*   $p=10$: Tizedes törtbefejtés.

### 2. A racionális számok jellemzése

A racionális számok és a p-adikus (speciálisan a tizedes) törtek kapcsolata a szakaszosság (periodicitás) fogalmán alapul.

*   **Szakaszos tört:** Egy p-adikus törtbefejtést szakaszosnak nevezünk, ha egy indextől kezdve periodikus, azaz létezik $n_0$ küszöbindex és $q \in \mathbb{N}$ periódushossz, hogy $a_{n+q} = a_n$ minden $n > n_0$ esetén,.
*   **Jellemzési tétel:** Egy $x$ valós szám akkor és csak akkor **racionális**, ha a p-adikus törtbefejtése (egy indextől kezdve) **szakaszos**,.
    *   Speciálisan a véges tizedes törtek (ahol egy indextől kezdve minden jegy 0) is racionális számok, hiszen felírhatók két egész szám hányadosaként.
*   **Irracionális számok:** Ebből következik, hogy egy szám pontosan akkor irracionális, ha a p-adikus törtbefejtése nem szakaszos (és nem is véges).
