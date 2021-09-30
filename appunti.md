ho trovato all'interno della documentazione la tipologia di sticky-top ovvero un header fisso, per far in modo che il contenuto scorra

d-inline d-sm-none 
display inline e display small none ovvero che quando entriamo nella small non verra piuù visualizzato

d-none d-sm-inline-block 
invece questo caso al contrario di default non viene visualizzato quando si entra nella small verrà visualizzato


container invece si adatta alla dimensione della responsive ovvero nella situazione base ha il 100% per dimensioni inferiori a 576px nella sezione dei dispositivi small ovvero quelli maggiori di 576px e minori di 767px ha una dimensione di 540px per e così via https://getbootstrap.com/docs/5.0/layout/containers/
sticky-top = header fixed

py-3 =padding top bottom default

align-items-center 

py-4 = padding top bottom *1.5

text-light = color white

py-5 = padding top bottom *3

g-4 gutter


w-100 larghezza dell'immagine

col-12 col-sm-6 col-md-4 sono le varie porzioni che la colonna assume nel responsive
funziona che partendo dalla visualizzazione più piccola per poi ingrandirsi sempre di più, la grandezza base sarà di 12/12, nella sezione small "sm" sara 6/12 ovvero la metà quindi si implireanno in due colonne. e nella sezione medium "md" 4/12 ovvero 1/3 quindi si incolonneranno per 3 colonne

pb-3 padding bottom - default
btn btn-outline-light
crea  un bottone con solo linee bianche 

mb-0 leva il margine al bottom 

list-unstyled serve per rimuovere lo stile alla lista
list-inline allinea gli elementi della lista 
    ricordati che va messo in combinazione con list-inline-item all'interno dell'li

mx-1 margine left e right *.25rem
text-dark testo nero




<!-------------------
HO INIZIATO I BONUS
-------------------->

NON RIESCO A RENDERE INVISIBILE LA COVER_IMAGE