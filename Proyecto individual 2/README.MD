                                         ANALISIS DEL MERCADO DE INTERNET EN ARGENTINA 

*********
INTRODUCCIÓN


El siguiente trabajo utiliza de hojas de Excel que contienen todo tipo de informacion sobre el mercado de Internet en Argentina y productos complementarios o substitutos. Las hojas tiene gran alcance porque no solo se limita a datos evidentes como accesos, poblacion y tipo de tecnologias sino que también tienen informacion como TV, Telefonia movil desagregada por Provincias que nos ayudará a crear una estrategia focalizada para dos segmentos de la poblacion en el corto plazo.

La fuente de la información es ENACOM- Ente Nacional de Comunicaciones





**********
ESTRUCTURA DEL PROYECTO


1. Creamos la carpeta DATA, donde estan todas las hojas de Excel.

2. Creamos el archivo EDA donde exploramos la data. En este archivo, está escrito las anotaciones y revelaciones de la data. Cabe anotar que no hubo proceso de ETL debido a que la informacion no estaba anidada o que requiriera procesos extensos. Los problemas de digitacion de las provincias con tildes y/o mayúsculas se realizó de acuerdo a cada análisis.

3. Contexto del mercado- esta sección toma las evidencias resumidas de cada hoja de excel.

4. Conclusiones- este documento se encuentra en el README donde concluimos lo que consideramos los KPI mas importantes para una estrategia de una empresa que presta servicios de telecolumincaciones, en especial brindar el acceso a internet. 





*********
CONTEXTO DEL MERCADO ARGENTINO:

Sobre el nivel de accesos y velocidad en el momento actual de Argentina se puede evidenciar en el PROMEDIO:

    1. CABA tiene 27.731 accesos en promedio- es un OUTLYER fuerte. Usando del Z-score eso equivale a 4,69 desviaciones estandar.
    2. A la vez CABA tiene la más baja velocidad. La calidad es la peor de Argentina en términos de velocidad. 
    3. Tierra de Fuego tiene una alta velocidad y usando del Z-score es 1,62 veces la desviacion estandar. No obstante, cuando se compara entre CABA y Tierra de Fuego, es muy grande la diferente. CABA tiene una velocidad de 2M de Mbps mientras que Tierra de Fuego tiene 90M de Mbps.
    4. Tierra de Fuego tiene la mejor velocidad y es el SEGUNDO partido con mas accesos- algo está bien allá.

Sobre la evolución de los Accesos y la Velocidad en PROMEDIO de las provincias se crean 5 grupos para facilitar la visualizacion. Se pudo observar:

    1. Los unicos datos de CABA corresponden al segundo trimestre del 2024 por lo que no entra en analisis. No obstante, si están los datos de CAPITAL FEDERAL. Al investigar, se asume que CABA es igual a Capital Federal (nombre histórico y político).
    2. Es evidente que en la mayoria de las provincias hubo un pico pronunciado en la velocidad durante el periodo del segundo trimestre de 2020 y tercer trimestre de 2021. Este periodo corresponde a la pandemia del COVID-19- ¿el estado intervino para mejorar la velocidad debido a la pandemia?. En muchos casos se triplica la velocidad durante la pandemia y luego cae a los mismos niveles antes de la pandemia.
    3. Quitando el pico de la pandemia, la velocidad entre 2018-2024 ha subido ligeramente en todas las provincias con una volatilidad considerable.
    4. Los accesos han caido en la mayoria de provincias durante 2018-2024 o se han mantenido en los mismos niveles. En Buenos Aires, en 2019 habían alrededor de 100 mil accesos y para el 2024 eran 60 mil. Lo más probable se deba a que se ha movido la demanda hacia portabilidad o telefonia movil.    

Sobre la composición tecnológica en la SUMA total:
** Para este análisis, es importante saber que Fibra Óptica es la mejor tecnología para internet dado que permite altas velocidades, estabilidad, mejor calidad de transmision y mejor desempeño con multiples dispositivos. 

    1. Buenos Aires tiene mas accesos que cualquier otra provincia en Fibra Optica. 
    2. Cable Modem es la tecnologia dominante del mercado argentino seguida por Fibra Óptica. Solo en pequeñas provincias no se sigue este patrón.
    3. En CABA hay una disparidad considerable entre el uso de Cable Modem (78.2%) y Fibra Optica (15.7%)- acá hay una oportunidad de crecimiento del negocio.
    4. Tucuman tiene un comportamiento diferente- Fibra Óptica tiene 80.1% de los accesos y Cable Modem solo el 7.8%. Esta provincia sirve como referente para saber que se realizó y poder replicarlo en más provincias. 

Sobre el consumo de descargas de internet en el PROMEDIO de Mbps bajados entre 2014-2024
    1. Es un crecimiento exponencial. Se paso en promedio de 3.85 Mbps en 2014 a 139.2 Mbps en 2024.
    2. Es un producto con mucho futuro debido a su alta demanda.

Sobre la evolución de tecnologías durante el periodo de 2014-2024.
    1. La tecnologia ADSL ha caido considerable. Esto es bueno porque es una tecnología obsoleta para el momento actual.
    2. La fibra optica es la tecnolgía con mayor crecimiento desde el 2019 hasta el momento.
    3. Cable Modem dejó de crecer desde el 2022 y se mantiene plano desde entonces (con una pequeña disminucion en el último dato). No obstante sigue siendo la tecnología predominante de Argentina.

Sobre la evolución de la tecnología en las provincias de acuerdo al Cable Modem y Fibra Óptica entre 2014-2024 observamos que:
    1. En la gran mayoria de provincias se mantiene plana la evolucion de Cable Modem entre las fechas a excepcion de Buenos Aires que es el que mayor jalona al alza los accesos. En 2014 tenia por trimestre accesos de 1 millon y paso a 2.7 millones en 2024. No obstante el último dato parece dar un punto de inflexión hacia la baja.
    2. Capital Federal (CABA) que es la segunda provincia con mayor uso de Cable Modem tiene un comportamiento mas plano. De 820 mil en 2014 a 1.1M en 2024 y de igual manera con tendencia a la baja dado los últimos datos. 
    3. Sobre la Fibra Optica- es Buenos Aires quien tiene un mayor crecimiento de accesos. Esta generado una correcta transicion de pasar de CableModem a Fibra Optica.
    4. CABA paso de 17.767 accesos en 2014 a 230.402 en 2024. Aunque es un crecimiento exponencial, se podría crecer mucho mas dado que el mercado es grande en CABA- no es un mercado saturado. 
    5. En Fibra Optica hay un punto de inflexión despues de la pandemia donde se observa un crecimiento mayor por el uso de Fibra Optica en la gran mayoria de Provincias (Cordoba es la provincia con mayor crecimiento).

SACAMOS NUESTRO PRIMER KPI- El crecimiento de Fibra Optica en CABA. La idea es potencializar la Fibra Óptica en CABA dado que mejoramos la calidad (velocidad) y hay mucho mercado para crecer ahí- hay una alta probabilidad de rentabilidad.

Sobre la evolucion de la banda ancha y dial up en PROMEDIO de Argentina y observando su evolucion entre 2014-2024 observamos que:
    1. CABA tiene un comportamiento plano a lo largo del tiempo. Su crecimiento a lo largo de 10 años ha sido casi nulo.
    2. Buenos Aires es la provincia con mayor crecimiento de la Banda Ancha- va por buen camino.
    3. Todas las provincias han mejorado en su servicio de internet dado que en todas ha caido el uso de la tecnologia "Dial Up" que es obsolota para la actualidad. La tendencia es que va a llegar a cero.

Sobre la evolucion en PROMEDIO de accesos por cada 100 habitantes entre 2014-2024, observamos que:
    1. Es muy bajo el crecimiento en la penetracion de los habitantes a lo largo de la decada. Se ha mantenido con una pendiente positiva pero pequeña en la gran mayoría de provincias. 
    2. La mayoría de provincias se encuentra en el rango entre 10-30 habitantes por cada 100. Buenos Aires y Catamarca son los únicos que rompen la barrera de 30.
    3. CABA (Capital Federal) lleva una alta ventaja en penetración pero con caídas y subidas y siempre arriba de 40. Su máximo es en 2017 cuando llego a 52.24 y en la actualidad está a 47.44.

    Se considera que hay mucho trabajo en el campo de la penetración, dado que el crecimiento es muy leve y en CABA ha caido. Acá se puede motivar la portabilidad móvil.

Sobre la evolución en PROMEDIO de accesos por cada 100 hogares entre 2014-2021, observamos que:
    1. Es mucho mas alto el acceso por hogar que por habitante. Es decir, en promedio, la gente espera llegar a su hogar para entrar a internet que tener internet móvil.
    2. Su crecimiento (la pendiente) es más notable durante la última década que la penetracion por habitante.
    3. 4 provincias rompen el nivel de 100- CABA, Buenos Aires, Catamarca y Formosa. Es decir dentro de un hogar hay más de 1 acceso.
    3. Los niveles mas bajos rondan el 40%.
 
    Se considera que el mercado por hogar está saturado en las provincias más grandes y que su crecimiento solo se limita a localidades pequeñas que rondan el 40% de penetración.

Sobre la evolucion total de accesos por hogares y habitantes entre 2014-2024, observamos que:
    1. La correlación es casi de 1; son casi identicas las dos curvas a excepción de los niveles. Las dos caidas son correlacionadas en la misma fecha- 2016 y 2019.
    2. El mercado de hogares empezó en 2014 en 50 y termina el 2024 en 78.13- con una leve caída al final. Esto significa que el mercado está saturado.
    3. El mercado de habitantes empezó en 2014 en 15 y termina el 2024 en 24.57- un crecimiento del 10% solamente. Este mercado inicia su ciclo de crecimiento.

SACAMOS NUESTRO SEGUNDO KPI- Observamos que el mercado por habitante está en un ciclo de crecimiento y a este queremos llegar.

Sobre la evolucion de la velocidad en el internet durante 2014-2024, se encuentra que:
    1. La calidad en Argentina ha mejorado notablemente durante la última década dado que la categoría con más capacidad es la que ha crecido exponencialmente (mas de 30 Mbps) mientras que las demás categorias han caido exponencialemente y estar cercanas a 0. 
    2. La categoria de entre 1 Mbps - 6 Mbps ha sido la categoria con mayor caída- desde 5 millones hasta 800mil. Demuestra que este tipo de producto va en declive.

    
Sobre la evolución de velocidad por pronvincia durante 2014-2024, se encuentra que:
    1. La caida de la categoria 1Mbps-6Mbps se debe principalmente a Buenos Aires.
    2. El aumento de la categoria de 30Mbps se debe a Buenos Aires. En segunda instancia es CABA.

Buenos Aires ha hecho el mejor trabajo para transicionar a una mejor calidad de internet.

Sobre la evolución de los ingresos durante 2014-2024, se encuentra que:
    1. Es ascendente pero no tiene los datos de inflacion por lo que su analisis es corto. Lo que realmente importa es que haya un crecimiento descontando la inflación. Es de poca utilidad la gráfica.

Sobre la composicion de tecnologia por provincia observamos que:
    1. Teniendo en cuenta que la tecnologia ADSL es de mala calidad, la localidad más crítica es Eldorado (Misiones) que tiene 57.323 personas y solo existe conexion a internet ADSL y no tiene Cable Modem o Fibra Optica que son de mejor calidad. Existen 24 localidades criticas que solo tienen ADSL y que su población es más alta que el promedio. 
    2. Las Provincias por poblaciones más criticas son: Tucuman, Misiones y San Juan- (no tienen Cable Modem o Fibra Optica)
    3. Todas estas localidades críticas tienen 3G o 4G.
    4. Las localidades que están en transición- las localidades que tienen Cablemodem pero no tienen Fibra Óptica y tienen una población mayor al promedio son 22 localidades. Buenos Aires por población es la Provincia con más potencial para crecer en Fibra Óptica con la localidad Ciudad Jardin con 63.479 personas.

Sobre la portabilidad entre 2012-2024, observamos que:
    1. Existe una alta volatilidad especialmente despues de Pandemia. Los niveles actuales de 2024 son similares al 2016.
    2. No hay una clara estrategia para aumentar la portabilidad.

Sobre la evolución de Telefonía Fija en las provincias críticas y transitorias, observamos que:
    1. En todas las provincias ha habido un acelerado descenso de telefonía fija.
    2. Utilizar de telefonía fija como medio para transicionar a Fibra Óptica no tiene sentido.

Sobre la evolución de suscripcion por TV, observamos que:
    1. Existe una estabilidad en la demanda por TV en las provincias transitorias- el rango de demanda cambia poco, tanto para hogares como para habitantes, especialmente en Buenos Aires- la demanda en 2024 es igual que en 2014 y se situa alrededor de 50%
    2. En las provincias críticas los niveles son bajos pero de igual manera estable. Es curioso el pico que ocurre en TUCUMAN- una campaña que tuvo exito en el corto plazo.
    3. San Juan y Tucumán tienen niveles bajos con respecto a las demás provincias.
    
    Se esperaba un mayor dinamismo en la suscripcion por TV para ver fútbol, dado que es parte de la idiosincracia argentina. No obstante, parece un mercado ya maduro y de poco crecimiento. Ni siquiera en las provincias pequeñas parece claro su dinamismo.

Sobre la evolución de telefonía móvil entre 2013-2024, se observa que:
    1. Es un mercado grande de 64 millones de accesos que se ha mantenido muy estable en proporciones casi identicas entre pospago y prepago.
    2. El mercado de preprago es alrededor de 7 veces mayor que el pospago.

    Se puede considerar que hay mucho potencial en el mercado de pospago para acceder a internet, dado que por via Bluetooth se pueden conectar con diferentes dispositivos.

Sobre la evolucion de la penetracion movil entre 2013-2024, se observa que:
    1. El mercado fue completamente penetrado al inicio de la decada hasta alcanzar niveles de 160 telefonos por cada 100 habitantes, es decir cada individuo en promedio tenia 1.6 celulares.
    2. Ha habido un descenso para llegar a su minimo de 120 por cada 100 habitantes. Es un mercado que culminó su crecimiento.

Sacamos nuestro tercer KPI, el crecimiento de la telefonía móvil en la categoria Pospago. Ya que el mercado esta saturado de telefonía movil, la idea es crear un producto diferenciado y de mejor calidad.


*****
CONCLUSIONES:

Primer KPI es CABA a fibra optica enfatizando calidad con velocidad- está saturado. Hogares tienen mas de 1 acceso por lo que estan dispuestos a pasarse a 1 acceso po rhogar de calidad. 

Segundo KPI es enfatizar las provincias de transicion a Fibra Optica con poblaciones mayores al promedio de pobalcion- enfatizado al mercado 

Tercer KPI crear un producto de internet telefonia movil pospago.


Argentina tiene disparidad en su distribución demográfica que tiene un efecto directo en el ciclo de vida del producto. Es muy diferente el ciclo de vida para el mismo producto de internet en CABA que en Tucumán o Entre Rios. Por lo tanto, la segmentación va a ser clave para crear un producto rentable y eficaz, dado que no es igual para todas las provincias. 

En nuestro analisis partimos que el producto de internet en toda Argentina pasó una fase introductoria (en todas las localidades hay banda ancha 3g y 4g- a excepcion de 1 localidad). Por otra parte, descartamos la telefonía fija o servicios postales porque están en una fase de declive como lo muestran los datos mientras que el consumo de datos tienen un crecimiento exponencial- Se paso en promedio de 3.85 Mbps en 2014 a 139.2 Mbps en 2024. Por esta razón proponemos a la empresa de telecomunicaciones 2 KPI´s enfocados en mejorar la velocidad (calidad) del producto segmentado y 1 KPI para aumentar la portabilidad de internet usando de planes pospago.


PRIMER KPI-

Nuestro primer KPI surge de una coyuntura que refleja CABA- es la provincia numero 1 en accesos (y por 4.7 desviaciones estandar usando el Z-score) pero a la vez con la menor velocidad en Mbps de toda Argentina (es el numero 1 en accesos y el ultimo en velocidad). Además el mercado no ha hecho gran cosa durante la última decada para mejorar la velocidad lo cual puede tener buena acogida en el mercado de CABA al encontrar un producto que mejore la velocidad. La razón se debe a que la tecnología predominante en CABA es cablemodem por un gran margen (78.2%) mientras que Fibra Óptica es (15.7%). Para dar un contexto, el maximo de cablemodem para transmision de datos está entre 300-500   Mbps y su estabilidad no es tan buena porque depende del numero de usuarios (se puede caer en horas pico y es una posible razón de la baja velocidad en CABA). Por lo tanto, para mejorar la velocidad y crear un producto nuevo que entre en una fase de crecimiento es crear un producto de Fibra Optica- su transmision puede llegar a 1Gps y estabilidad es mucho mas alta que Cable Modem y sacudir el mercado dado que la velocidad es muy mala en CABA. ¿Cómo podemos vender Fibra Óptica en CABA cuando los accesos por hogar es mas de 1? La idea es potencializar los beneficios de mejorar la velocidad a traves de Fibra Óptica que de tener más accesos a internet como ocurre actualmente. Para esta campaña sólo se requiere explotar los beneficios de tener un internet de alta velocidad con respecto a cable modeme. La idea es duplicar la transicion actual de Fibra Optica en CABA para el proximo año.

![Alt text](https://github.com/davidparamo12/Mercado-Argentina/blob/main/FOTOS/Captura%20de%20pantalla%202025-04-25%20194257-1.png)

![Alt text](https://github.com/davidparamo12/Mercado-Argentina/blob/main/FOTOS/Captura%20de%20pantalla%202025-04-25%20194845.png)




SEGUNDO KPI-

Luego de crear un analisis por Localidades, concluimos como segmento localidades que tuvieran una población mayor al promedio pero donde no hay acceso a Fibra Optica, es decir para introducir el producto. Esto genera beneficios como ganar mercado sin competir y fidelidad- el CVL global de la compañia aumentará inevitablemente dado que son nuevos clientes al que la competencia no le ha llegado. Además esta estrategia es una manera de adelantarse al mercado- evitar el problema de saturacion de cable modem. Para estas localidades, se usará de un producto mixto para el hogar: Internet de alta velocidad + TV de alta calidad para ver Futbol, dado que con esta tecnología se puede pasar los dos tipos de productos con el mismo cable. Esto se debe a que en algunas provincias la velocidad es buena por lo que no se daría ningún valor agregado al consumidor. No obstante, una suscribcion a TV puede dar el beneficio adecuado para pasarse a Fibra Optica. Nuestro KPI es tener el crecimiento maximo en un año de cable modem de la provincia ... y obtener este crecimiento a través de Fibra Óptica.

![Alt text](https://github.com/davidparamo12/Mercado-Argentina/blob/main/FOTOS/Captura%20de%20pantalla%202025-04-25%20194921.png)

![Alt text](https://github.com/davidparamo12/Mercado-Argentina/blob/main/FOTOS/Captura%20de%20pantalla%202025-04-25%20194933.png)


TERCER KPI-

Nuestro tercer KPI surge de la coyuntura que el mercado de hogares esta en un ciclo más maduro que el mercado de portabilidad (los niveles de accesos por habitante vs hogar tienen una spread de ... % en promedio). Por esta razón proponemos crear un producto de alta portabilidad via celulares con planes pospago. La tecnología red movil 4g/LTE o 5G que siga la tendencia de alta portabilidad. De igual manera consideramos que es mejor ser pionero para obtener un mercado grande sin tanta competencia

![Alt text](https://github.com/davidparamo12/Mercado-Argentina/blob/main/FOTOS/Captura%20de%20pantalla%202025-04-25%20194947.png)

![Alt text](https://github.com/davidparamo12/Mercado-Argentina/blob/main/FOTOS/Captura%20de%20pantalla%202025-04-25%20195055.png)
