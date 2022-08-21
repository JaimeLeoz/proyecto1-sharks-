# proyecto-sharks

empezamos abriendo el csv con un utf - diferente porque no me funcionaba utf-8

Nos hemos quedado con 2.357 filas y 24 columnas. En muchos de los casos se han limpiado con bucles FOR y condicionales. Al igual Replace.


al explorar el CSV se han tomado decisiones en base a la representatividad de los datos. Entre esas decisiones estan varias columnas importantes

Date: se cambia el formato a mes.

Year: se limpia, convierte a integer, y se eliminan aquellas filas menores de 1960. Debido a que las anteriores dejan mucho que desear en calidad y formato.

Country: Hay 5 representativas pero al revisar areas acaban quedando 3 importantes USA, Australia y South Africa. Se mejora el formato.

Areas: Se eliminan todas aquellas con baja calidad, acaba afectando al número de paises

Typeattack categories: Se limpian y agrupan en 4 categorias

Unprovoked      4595
Provoked         574
Boat             340
Sea Disaster     239

    Sea disasters means , high seas accidents where sharks took advantadge of planes and boat crashes - eaten remains
    Boat: means attacks closer to land, in little boats, kayaks ..etc.


Activity: Al igual sufre de baja calidad en la agrupación y distorsiona los datos. POr lo que se agrupan lo mejor que se puede
Quedando agrupadas en las mas importantes. Se han agrupado a mano y con un bucle FOR.
Surfing           863
Swimming          675
Fishing           483
unknown           202
Diving            139
Body Boarding     108
Standing          76
Bathing           49
Snorkeling        48
Scuba diving      34
Walking           32
Treading water    27
Boogie boarding   23

Fatality : limpiado 

Species : Bucle For donde se ha reemplazado los nombres con un bucle FOR y find.

El problema surge que al no poder hacer una limpia mas completa nos quedamos con muchos Unknown. 
Haciendo los datos poco representativos. Pero los  mantenemos para evitar eliminar demasiadas filas las cuales pueden tener otros datos beneficiosos en otras columnas.

unknown             1998
Shark White          140
Shark Small           42
Shark Blacktip        32
Shark Nurse           27
Shark Bull            24
Shark Reef            21
Shark Tiger           15
Shark Spinner         14
Shark Hammerhead      14
Shark Sand             8
Shark Dusky            8
Shark Bronze           4


CON ESTO ACABAMOS LA LIMPIA. Y PASAMOS A LA PPT.

En la PPT veremos representados:

Años que mas ataques ha habido
Paises donde más ataques ha habido y por edad
Tipo de Ataque , Area y actividad
Sexo y edad