# 5: ++CURA/Basic++
---

######CAPITOLO 5
###### QUALITY / FILL / SPEED AND TEMPERATURE / ++SUPPORT++ / FILAMENT

# 


#### **SUPPORT**
A volte servono degli “aiuti” al pezzo 3D per la riuscita di una buona stampa: 
Il materiale di supporto **(Support type)** e una buona adesione al piano **(Platform adhesion type)**

# 

*	**SupportType:**
	
    Il supporto serve in caso di pareti più inclinate di 60° per superfici sospese sul nulla. Ad esempio una figura umana con le braccia aperte ha sicuramente bisogno del supporto sotto le braccia, o in un ponte troppo lungo la parte centrale collasserebbero durante la stampa.
[fig. 16](img/figura16.jpg)


*	**Platform Adhesion Type:**
	La plastica è soggetta a ritiri e deformazioni durante il raffreddamento. Questo porta a distaccamenti dal piano di stampa, con conseguenti problemi sul pezzo finale. Cura offre due possibilità per limitare la cosa:
    Il *brim* e il *raft*.
[fig. 17](img/figura17.jpg)

# 


_ _ _
#######NOTA BENE
* *Support Type*
	*Cura ha due tipi di supporto:*
	*  ***TOUCHING BUILDPLATE***
	 *Il primo andrà a sostenere solo le pareti esterne*
	* ***EVERYWHERE***
	 *il secondo andrà a cercare e sostenere tutti
     i possibili punti di crollo, anche quelli interni.*

* *Platform Adhesion Type*
	* *Il **BRIM** è una estensione del primo layer di stampa.
	 Essendo più ampio ne migliora l’adesione generale al piano.*
	* *Il **RAFT** è un metodo di adesione più aggressivo del brim. In pratica, prima di stampare il pezzo crea una maglia di
filamento che permette una migliore adesione. Adatto per
basi molto piccole (per evitare distaccamenti) o superfici molto larghe (per evitare distorsioni).
Purtroppo, a differenza del brim, è più difficile da rimuovere.*

_ _ _ 

# 

Esempio di situazione con supporto 
[touching buildplate](img/support/touching.jpg) ed [everywere](img/support/every.jpg).

Comparazione tra [BRIM](img/support/brim.jpg) e [RAFT](img/support/raft.jpg).


