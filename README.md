# Inventari forestal nacional. models d'aprenentatge automàtic
l'Inventari forestal nacional (IFN) és el projecte que proporciona informació a nivell nacional de l'estat dels boscos. La seva metodologia es basa en la presa de dades en parcel·les resultants d'un mostreig estratificat realitzat en la superfície forestal arbrada. Aquests inventaris es solen renovar amb certa periodicitat (cada 10 anys), actualment les dades més recents publicades són les de l'IFN3 i s'està realitzant l'IFN4. Les dades obtingudes en els inventaris de camp estan, en part, informatitzades en bases de dades, a nivell de provincia, descarregables desde la web institucional a:
https://www.miteco.gob.es/es/biodiversidad/servicios/banco-datos-naturaleza/informacion-disponible/ifn3_bbdd_descargas.htm.aspx

En aquest treball s'han escollit les dades de la provincia de lleida per a:
1. Aplicar un model de generació de regles a partir de **Regles d'associació**.  
2. Aplicar un model **no supervisat** i basat en el concepte de **distància**, sobre el joc de dades.  
3. Aplica de nou el model anterior, però utilitzant una **mètrica diferent** i compara els resultats.  
4. Aplicar un **model supervisat** sobre el joc de dades **sense** haver aplicat prèviament **PCA/SVD**.  
5. Aplicar un **model supervisat** sobre el joc de dades havent aplicat prèviament **PCA/SVD** i comparar-lo amb els resultats previs
