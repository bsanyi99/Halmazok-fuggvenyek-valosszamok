# 11. tétel

### 1. Az egész rész függvény

**Definíció és létezés:**
Az egész számok halmazának ($\mathbb{Z}$) bármely felülről korlátos nemüres részhalmazának van maximuma. Ezen tulajdonság alapján definiálható egy valós szám egész része:
*   Egy $x \in \mathbb{R}$ szám **egész részének** nevezzük és $[x]$-szel jelöljük a $\{k \in \mathbb{Z} : k \le x\}$ halmaz maximumát.
*   A definíció ekvivalens azzal az állítással, hogy bármely $x \in \mathbb{R}$ esetén létezik egy **egyértelműen meghatározott** $l \in \mathbb{Z}$ egész szám (ahol $l = [x]$), amelyre teljesül, hogy:
    $$l \le x < l + 1$$ (vagy $[x] \le x < [x] + 1$),.

**Törtrész:**
Az egész rész segítségével minden valós szám felbontható egy egész szám és egy 0-nál nem kisebb, de 1-nél kisebb szám összegére.
*   Az $y = x - [x]$ számot az $x$ **törtrészének** nevezzük, amelyre igaz, hogy $y \in [0, 1[$.
*   Ez a felbontás ($x = [x] + (x - [x])$) alapvető szerepet játszik például a valós számok $p$-adikus (pl. tizedes) törtbefejtésénél is,.

**Tulajdonságok:**
A források említik az egész rész függvény néhány egyenlőtlenségét feladatként:
*   $[x] + [y] \le [x+y] < [x] + [y] + 2$.
*   $x, y > 0$ esetén $[x][y] \le [xy] \le [x][y] + [x] + [y] + 1$.

---

### 2. A racionális számok sűrűsége

**A sűrűség fogalma:**
Egy $H \subset \mathbb{R}$ halmazt $\mathbb{R}$-ben **mindenütt sűrűnek** nevezünk, ha bármely két különböző valós szám között található $H$-beli elem. Formálisan: bármely $x, y \in \mathbb{R}$ és $x < y$ esetén létezik $h \in H$, amelyre $x < h < y$ teljesül,.

**Tétel:**
A racionális számok halmaza ($\mathbb{Q}$) mindenütt sűrű $\mathbb{R}$-ben,.

**Bizonyítás menete:**
A tétel bizonyítása az Arkhimédészi tulajdonságon és az egész rész fogalmán alapul. Legyen $x, y \in \mathbb{R}$ és $x < y$.
1.  Mivel $y - x > 0$, az **Arkhimédészi tulajdonság** biztosítja, hogy létezik olyan $n \in \mathbb{N}$ természetes szám, amelyre $n(y - x) > 1$, azaz $nx + 1 < ny$,.
2.  Az egész rész tulajdonságát alkalmazva az $nx$ valós számra: létezik olyan $l \in \mathbb{Z}$ (ahol $l = [nx]$), amelyre $l \le nx < l + 1$. Páles Zsolt jegyzete ezt $k = [nx] + 1$ választással tárgyalja, ahol $0 < k - nx \le 1$.
3.  Ezt az egyenlőtlenséget kombinálva az első lépés eredményével:
    $$nx < l + 1 \le nx + 1 < ny$$
4.  Az egyenlőtlenséget $n$-nel osztva ($n > 0$) kapjuk:
    $$x < \frac{l + 1}{n} < y$$
5.  Mivel $l + 1 \in \mathbb{Z}$ és $n \in \mathbb{N}$, a $h = \frac{l+1}{n}$ szám racionális ($h \in \mathbb{Q}$), és az $x$ és $y$ közé esik,.

**Kapcsolódó eredmény:**
Az **irracionális számok halmaza** ($\mathbb{R} \setminus \mathbb{Q}$) szintén mindenütt sűrű $\mathbb{R}$-ben,. Ennek bizonyítása visszavezethető a racionális számok sűrűségére, felhasználva például a $\sqrt{2}$ irracionalitását vagy intervallumskatulyázást.
