# 7: ++CURA: PLUGINS++
---

######CAPITOLO 7
###### PAUSE AT HEIGHT / ++TWEAK AT Z++

# 

---

####Tweak At Z
Con questo plugin al raggiungimento di una determinata altezza si possono variare molti parametri inerenti la stampa.

Il plugin si attiva al raggiungimento di uno dei primi due parametri: O Z height to tweak at, oppure Layer no. to tweak at, rispettivamente inserendo il valore nel primo si ottiene un cambiamento a partire da una certa altezza in mm, con il secondo il cambiamento avviene a partire da un certo layer in poi.
Raggiunto uno dei valori, si attivano tutti i successivi: Con New Speed si va a cambiare in percentuale la velocità di movimento, con New Flow rate si cambia sempre in percentuale la quantità di materiale estruso.

Si passa poi a tre valori di temperatura:
*New Bed temp.*, *New extruder 1 Temp.*, *New extruder 2 Temp.*, che vanno rispettivamente a cambiare la temperatura del piano di stampa, del primo e del secondo estrusore.
Con l’ultimo valore si va a variare la velocità della ventola di raffreddamento, con un valore che può andare da 0 e 255.

E’ bene sapere che i valori non impostati rimaranno invariati. 
[fig.34](img/figura34.jpg)