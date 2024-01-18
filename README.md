# DB first

Tabella che rappresenta le auto usate vendute da un concessionario e i relativi dati, formata dalle seguenti colonne:

- ID: Nella colonna ID si trova l'indice identificativo delle auto che incrementa all'aggiuta di ogni elemento (AUTO_INCREMENT).

- Marca: con la marca dell auto, attributo VARCHAR(20) in quanto stringa
- Modello: con il modello dell'auto, attributo VARCHAR(20) in quanto stringa
- Versione: dato che può non essere specificato in quanto alcuni modelli non hanno versioni specifiche, attributi VARCHAR(50) - NULL
- Motore: cilidrata del motore, attributi VARCHAR(20) in quanto stringa, e NULL in quanto è un dato che non sempre si ha sottomano
- Carburante: alimentazione dell'auto, attributo VARCHAR(20) in quanto stringa
- Potenza: potenza espressa in cavalli, attributi TINYINT in quanto un numero non superiore a 255 e NULL in quanto è un dato che non sempre si ha sottomano
- Cambio: il tipo di cambio, se non viene passato nessun argomento il valore di default è Manuale - DAFAULT(MANUALE), attributo VARCHAR(20) in quanto stringa
- Km: i chilometri percorsi, attributo MEDIUMINT in quanto può essere un numero fino a sei cifre
- Anno: anno di immatricolazione, attributo YEAR
- Prezzo: il prezzo di vendita, attributo SMALLINT in quanto numero ben oltre 255 e DOUBLE(7,2) in quanto il prezzo può avere facilmente cinque cifre inter e due decimali.   
 