<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/12_de_octubre_2018_Vuelve_el_tren_a_Ranelagh_-_Diaz_De_Vivar_Gustavo.jpg/1200px-12_de_octubre_2018_Vuelve_el_tren_a_Ranelagh_-_Diaz_De_Vivar_Gustavo.jpg">

# CONOCIENDO UNA PARTE DE LA HISTORIA DE LOS TRENES ARGENTINOS
### PyDARG-GBA-trenes_argentinos

Uno de los retos para encarar un proyecto de opendata es encontrar un punto de partida, es decir, tenemos diversas fuentes de información y la pregunta inicial que podemos hacernos es `¿qué podemos hacer con ellos?`, entonces, ante una pregunta tan abierta una apróximación podría ser el setear un contexto y usarlo como punto de inicial para ir haciendo un análisis simple que se va haciendo cada vez más riguroso.

Luego es importante tomar en cuenta que, especialmente al trabajar con open data podemos encontrarnos facilmente con problemas de estandarización, enconding, data sets que por si solos no aportan nada, pero que al combinarlos con otras fuentes de datos podrían ser útiles y que todo esto se va volciendo un proceso iterativo que debemos acompañar de un proceso de validación constante, para verificar si cada paso que damos es seguro o si debemos exigir que sea reparada la fuente de información.

En este caso, nuestro punto de partida sera conocer desde varios puntos de vista el sistema de Trenes Argentinos y que sean los datos o al menos el registro histórico actualmente publicado quienes nos cuenten esta história, para ello estaremos intentando responder a las siguientes preguntas: 


- ¿Cómo se invierten los recursos del estado para mantener operativas las redes ferroviarias? ¿Qué actividades representan el mayor costo?
- ¿Cómo es el flujo total poblacional en términos del uso de la línea? ¿Cuántos subsidios se reciben en esas operaciones?
- ¿Cómo están distribuidos los puntos de recarga y venta de boletos a traves del territorio nacional?
- ¿Que patrones se pueden detectar en el flujo de los usuarios de tren?


Para ellos vamos a trabajar con los siguientes datos que podemos encontrar en la página oficial del ["Ministerio de Transporte Argentina"](https://servicios.transporte.gob.ar/gobierno_abierto/):

- **01-TRENES-SUBSIDIOS.csv:** contiene el registo histórico del monto invertido en pesos argentinos como subsidios al transporte público de pasajeros de los trenes estado nacional.

- **02-TRENES-OPERACIONES.csv:** contiene el registro de todas las operaciones SUBE mensuales por línea y por tipo de pasaje.

- **03-TRENES-PUNTOS-RECARGAS.csv:** contiene la ubicación georeferenciada de puntos de recarga.

- **04-TRENES-PUNTOS-RECARGAS.csv:** contiene la ubicación georeferenciada de puntos de venta.

- **07-TRENES-PASAJEROS.csv:** contiene el detalle del paso del los pasajeros por estación. 

