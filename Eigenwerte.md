
Vektoren die beim anwenden einer Transformation auf ihrer eigenen Spanne bleiben (von der normalen Basis aus). D.h. der Vektor wird lediglich skaliert, aber zeigt immernoch in die selbe "Richtung") -> Eigenvektor | Skalierungsfaktor = Eigenwert

###### Algebraische Vielfachheit
Algebraische Vielfachheit $m_{a}(\lambda)$ von $\lambda$ ist die Vielfachheit der Nullstelle $\lambda$ im characteristischen Polynom. D.h.: Wie oft die Nullstelle vorkommt.
Beispiel: 
	$f(x) = x - 5$ | Nullstelle: $x=5$, Vielfachheit: $1$ (einfache Nullstelle)
	$f(x) = {(x-5)}^{2}$ | Nullstelle: $x=5$, Vielfachheit: $2$ (zweifache Nullstelle)
	usw
(Vorsicht: Diese Eigenschaft ist nicht graphisch ersichtlich wenn der Graph geplottet werden würde)
Polynom sollte hierfür in idealfall in Linearfaktoren (dh alle Terme der Form $(X-Zahl)$) zerlegt werden. Die alebraische Vielfachheit der Nullstelle entspricht dann der Häufigkeit des Vorkommen eines bestimmten Linearfaktor.


###### Geometrische Vielfachheit
$m_{g}(\lambda) := dim(E_{\lambda})$ , d.h. die geometrische Vielfachheit eines Eigenwerts entspricht der Dimension des Eigenraums zu dem Eigenwert (=Anzahl der linear unabhängigen Eigenvektoren zu einem Eigenwert, ersichtlich aus der Definition von Basis und Dimension). Das ist äquivalent zur Aussage:  
- Die geometrische Vielfachheit eines Eigenwerts entspricht der der Dimension des Kerns (aka Defekt) der Matrix $(A - \lambda \cdot I)$
- Geometrische Vielfachheit = $n-Rang(A-\lambda \cdot I)$ 

- Für $A \in K^{nxn}$:
	- (a) A hat höchstens n Eigenwerte (d.h. maximal so viele wie die Matrix breit bzw. host ist)
	- Falls K algebraisch abgeschlossen (K = $\mathbb{C}$) hat A Eigenwerte

- Es gilt: $1 \leq m_g(\lambda) \leq m_a(\lambda)$ wenn $\lambda$ ein Eigenwert ist. Folglich entspricht die geometrische Vielfachheit eines Eigenwert (aka wie viele Eigenvektoren es zu diesem gibt) automatisch der algebraischen Vielfachheit falls dieser ein einfacher Eigenwert ist (algebraische Vielfachheit 1). (Hilfreich zum diagonalisieren da algebraische und geometrische Vielfachheit aller Eigenwerte übereinstimmen muss).

# Eigenraum

Zu jedem Eigenwert $\lambda$ gibt es einen Eigenraum. Der Eigenraum ist die Menge aller Eigenvektoren zu einem Eigenwert kombiniert mit dem Nullvektor:
	$E_{\lambda}:=\{v \in K^{n} | A \cdot v = \lambda \cdot v\}$[^1]
Alle Vektoren $v \in K^{n}\setminus\{0\}$ (der Nullvektor als triviale Lösung zählt nicht als Eigenvektor), welche die Gleichung $\{A \cdot v = \lambda \cdot v\}$ erfüllen sind Eigenvektoren zu einem Eigenwert $\lambda$. 

- Jeder Eigenraum ist ein Unterraum des Raums seiner zugehörigen Matrix $Fuer A \in K^{nxn} und \lambda \in K ist E_{\lambda} \subseteq K^{n} ein Unterraum$



# Diagonalisieren























[^1]: Die Gleichung ist auch definiert wenn lambda kein Eigenwert ist