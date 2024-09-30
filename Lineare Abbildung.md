#Defekt #Bild #Kern #Dimensionssatz

Eine Abbildung (oder auch Funktion) $f:D \rightarrow Z$, ist eine Relation zwischen zwei Mengen. Jedem Element der Definitionsmenge D wird genau ein Element der Zielmenge Z zugeordnet. (Andersrum muss dies nicht gegeben sein.) (Prosa: Es wäre ja irgendwie bescheuert wenn ich meine Funktion ausrechne und einfach zwei Ergebnisse bekomme, wie soll das überhaupt funktionieren.)
Das Bild eines Elements $x$ der Definitionsmenge $D$ ist der zugehörige Funktionswert $f(x)$. Das Bild der Funktion bzw. Abbildung ist die Menge der Bilder aller Element aus der Definitionsmenge $D$.

Gegeben eine Abbildung $f: X \rightarrow Y$
###### Injektiv
Zu jedem Element der Zielmenge gibt es höchstens ein Element der Defintionsmenge (kein Element ist auch möglich). (=> Zielmenge größer gleich Definitionsmenge)
TODO Bild und Formeln
###### Surjektiv
Eine Abbildung ist surjektiv wenn es zu jedem Element der Zielmenge mindestens ein Element aus der Definitionsmenge X gibt. (=> Zielmenge kleiner gleich Definitionsmenge).
Gleichbedeutend zu: Bild(X) = Y
###### Bijektiv
Eine Abbildung welche Injektiv und Surjektiv gleichzeitig ist. (=> Zielmenge und Definitionsmenge sind gleich groß).



Für zwei Vektorräume $V,W$ über dem selben Körper $K$: Abbildung $\varphi : V \mapsto W$ 
- (1) $\forall v,v \in V$


#### Bild & Kern
*Es sei* $\varphi : V \rightarrow W$ *linear*.
###### Bild
Das Bild einer Matrix ist die Menge der linear unabhängigen Spalten bzw. Die Menge an Vektoren welche eine Lösung der Abbildung sein können. Die Teilmenge von W welche alle Bilder von Elementen aus V enthält. Elemente von V welche nicht in W abgebildet werden, werden auf den Nullvektor abgebildet (siehe Kern). 
> $Bild(\varphi) := \varphi(V) = \{\varphi(v) | v \in V\} \subseteq W$
- $Bild(\varphi) \subseteq$ ist ein Unterraum
###### Kern
Der Kern einer Matrix ist die Menge der Vektoren im V welche auf den Nullvektor (von W) abgebildet werden.

>$Kern(\varphi):=\{v \in V | \varphi(v) = 0\} \subseteq V$

Vorsicht: Der Kern ist eine Teilmenge von V nicht von W. (Interessant ist schließlich nicht die Menge in W da dies hier immer den Nullvektor wäre, sondern welche Vektoren alle auf den Nullvektor abgebildet werden).
- **Defekt**: Die Dimension des Kerns einer Matrix ist ihr Defekt
- $Kern(\varphi) \subseteq V$ ist ein ein Unterraum
	- -> Kern ist Unterraum von der Menge aus der abgebildet wird

###### Dimensionssatz für lineare Abbildungen
- Sei $\varphi : V \rightarrow W$ linear, dann: $dim(V) = dim(Kern(\varphi) + dim(Bild(\varphi)))$ 
- Die Dimension des Vektorraums aus dem dem abgebildet wird ist die Summe von Bild und Kern der Abbildung

TODO Isomorphismus und so
Wenn ich Dimension von Bild und oder Kern kenne habe ich doch eiegentlich automatisch eine möglichkeit das bild bzw den kern anzugeben indem ich einfach eine beliebiege basis von passender dimension wähle.