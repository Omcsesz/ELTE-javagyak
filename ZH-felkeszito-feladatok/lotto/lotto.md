# Pr�baZH #

K�sz�ts�nk egy minim�lis �t�slott�-elemz� alkalmaz�st!

# Lott�elemz� alkalmaz�s #

Mell�kelten tal�lhat� egy [input f�jl](lotto.csv) (CSV form�tumban), amely az �sszes eddigi h�z�s eredm�ny�t tartalmazza. Az elemek `;` karakterrel vannak elv�lasztva.

Tetsz�leges adatszerkezetben t�roland� adatok:

- H�z�sd�tum (3. oszlop)
- 5 tal�lat nyerem�ny�nek �sszege (5. oszlop)
- Sz�mok (utols� 5 oszlop)

Az inputban csak a 2004 ut�ni adatokkal foglalkozzatok.

## Megval�s�tand� lek�rdez�sek ##

- Mennyi volt az �tlagnyerem�ny 5 tal�lat eset�n?

- Mikor vitt�k el a legnagyobb nyerem�nyt, mekkora �sszeg volt, �s milyen sz�mokkal?

- Rendezz�tek az inputot d�tum szerint cs�kken�en (Comparable)

- Ments�tek a feldolgoz�s eredm�ny�t egy f�jlba, ahol a f�jl nev�t parancssori argumentumk�nt lehessen megadni, form�tuma pedig a k�vetkez� legyen:
  
		# Average: xxx
		# Max: yyy
		Sorted elements (one per line)
		... 

