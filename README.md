# APP FINANCIERA
### Objetivos iniciales del proyecto

El cliente sacó una nueva aplicación financiera, creando una app desde cero -en lugar de modificar la aplicación actual. Tienen dos user personas: una primaria y una secundaria. La app tiene alrededor de 6 mese de data. Con base a la información que nos han dado y lo que requiere el cliente partimos de los siguientes puntos:
* Analizar la data y entender los resultados iniciales
* Sacar una segunda iteración del producto
* Rediseño del producto
* Analizar si es necesario duplicar el presupuesto de Facebook Ads

### Investigación
Contexto actual en México

Datos extraídos de la Comisión Nacional Bancaria y de Valores (CNBV) en conjunto con  el Instituto Nacional de Estadísticas y Geografía (INEGI). ⋅⋅
* Del 2012 al 2018 aumentó la cantidad de personas incluidas en el sistema financiero de 39.4 a 54 millones de personas
* El número de adultos con una cuenta individual de ahorro para el retiro creció 11.7 millones de adultos (de 19.6 a 31.3 millones).
* A nivel regional. La Edición 2018 de la ENIF es la primera que brinda datos a nivel regional, y revela que la región Noroeste presenta la mayor proporción de población financieramente incluida, con 82%; seguida por la Noreste, 75%; Occidente y Bajío, 67%; Sur, 68%, y la región de Centro, Sur y Oriente, 60%. El 72% de la población adulta que vive en la Ciudad de México está incluida financieramente.
* El número de adultos que tienen contratado el servicio de banca móvil se incrementó casi seis veces más respecto de 2012. 
* No hay confianza en las instituciones financieras formales
* En la investigación encontré que los jóvenes tienen metas financiera a plazo inmediato
* La mayoría no piensa en el retiro 
* 34% ahorra suficiente cada mes y está seguro de su futuro financiero, mientras que el 48% no lo está y el 18% no ahorra para el futuro.

En enero del 2019 El banco de México anunció la introducción del sistema CoDi (Cobro digital de seguridad) las personas podrán transferir de un teléfono digital a otro con las mismas características cualquier pago que se requiera. Acceso de crédito de nóminas de cualquier nómina. Permitir que jóvenes entre 15 a 17 años puedan abrir cuentas bancarias a su nombre y sin tutor. 

Los bajos niveles de inclusión financiera afectan sobre todo a la población de menores recursos.  El gobierno y las instituciones financieras tienen que trabajar para lograr avances en materia de inclusión. Además de que existe un gran problema en el acceso a servicios financieros en las zonas rurales, llevar infraestructura bancaria tradicional no es económicamente viable, una solución es ofertar estos servicios mediante tecnologías digitales. El teléfono móvil permitirá ofrecer productos financieros a menor costo. 


Según cifras de la Comisión Nacional para la Protección y Defensa de los Usuarios de Servicios Financieros (Condusef), el 30% de los jóvenes mexicanos no tienen ningún interés por adquirir cultura financiera y les gusta gastar el dinero en comida, tecnología, ropa y entretenimiento. Solo el 13% de los jóvenes ahorran una parte de su paga. 
 
Todas estas cifras son alarmantes, por medio de esta app se pretende ayudar a que la educación financiera mejore. La educación financiera se aprende, sobre todo, con la práctica. Por eso, es importante que los adolescentes vayan adquiriendo hábitos saludables para su bolsillo de una forma positiva, que les haga sentirse importantes. Estos son algunos ejemplos para conseguirlo. ⋅⋅

#### Referencias
https://www.eluniversal.com.mx/columna/ignacio-ibarra-lopez/nacion/inclusion-financiera-en-mexico-adios-al-uso-de-efectivo
https://www.gob.mx/cnbv/articulos/resultados-de-la-encuesta-nacional-de-inclusion-financiera-enif2018?idiom=es
https://www.gob.mx/cms/uploads/attachment/file/414831/Cuadr_ptico_2018_verimpresa.pdf
https://www.elfinanciero.com.mx/opinion/carlos-serrano-herrera/inclusion-financiera-sin-avances-significativos
https://www.bbva.com/es/educacion-financiera-adolescentes-asi-gastan-dinero/
https://www.condusef.gob.mx/Revista/index.php/presupuesto-familiar/plan-de-vida-financiero/416-como-manejan-su-dinero-los-jovenes-en-mexico

### Análisis de la Data

#### Insight
* El número de personas que ven publicidad en Facebook es demasiado alto en comparación con quienes ven landing page, el uso de esta publicidad no está funcionando
* Después de descargar la aplicación no se realiza con éxito el registro
* Impedimento para completar el registro ¿Por que?
* La aplicación es más usada para ver gastos más que para ahorrar, no está cumpliendo su propósito
* La app si es usada una vez descargada
* De las personas que consulta landing page el sistema operativo más utilizado es Android 
* Es necesario meter Android


### Análisis Heurístico de la app
![LFP_1](https://github.com/Andrea0611/APP-FINACIERA/blob/master/Heuristica.jpg)

##### Insight Heurística
* Visibilidad del estado de sistema: No tiene informado en todo momento la sección en que se encuentra
* Consistencia y estándares: inconsistencia en los nombre de títulos y de secciones
* Botón de “Crear cuenta”: es confuso, no es clara la función que se quiere realizar; crear un ahorro, además por la ubicación tampoco se entiende como botón

##### Berchmarker
![LFP_2](https://github.com/Andrea0611/APP-FINACIERA/blob/master/benchmark.jpg)

##### Insights
* Generan un presupuesto basado en el comportamiento
* Permite poner límite de gasto
* Envío de notificaciones
* Recordatorio de tus metas
* Te paga el 1% por ahorrar cada tres meses

##### Primer testeo de la aplicación

###### Planificación de la prueba

Se realizará un guión donde se especifíque al usuario las tareas que debe realizar y las preguntas de interés.
###### Guión: 

Hola, estamos realizando el test de una app y  me gustaría que me ayudaras con una prueba de usabilidad. El objetivo de esta prueba es evaluar la usabilidad de uso del sitio web, nunca la evaluación del participante. Si cometes algún fallo no será tu culpa sino del diseño de la aplicación

###### Tareas del Usuario:
* Podrías navegar en esta app
* Podrías realizar un ahorro

¿La forma en que se muestran los datos te parece útil?

###### Insights
* El registro les parece muy largo
* La fotografía no les da confianza, la gente no quiere que sepan quienes son
* Botón de “Crear cuenta”: las personas no lo entienden como un botón, o piensan que es un botón para crear una nueva cuenta bancaria
* No muestra mensajes de error
* Hay confusión en la huella del dedo

#### Delimitación y entendimiento del problema
###### Cliente
Objetivo iniciales del proyecto 
* Herramienta financiera fresca
* Que los usuarios lo perciban como un banco  moderno, transparente sin tantos procesos
* Atraer más clientes con la mejoras de experiencia digital
* Retener a sus usuarios con buenas experiencias
* Saber para donde debe de ir la app

Problemas encontrados tanto a nivel de negocio como a nivel de usuario

Negocios
* La aplicación solo existe para IOS, perdiendo a una gran cantidad de posibles usuarios, ya que la mayoría de los usuarios tienen android
* No cuenta con los recursos tecnológicos para desarrollar una app que abarque las dos aplicaciones
* Sus programadores en su mayoría solo manejas ios

###### Usuario
* Los usuarios no quieren tener tantas app
* Rango perfiles usuarios 18-35
* +25-35
> Tenían miedo de meter los datos
> Les gustaría enlazar tarjetas de diferentes bancos
> La aplicación les parece muy básicas
> Quisieran poder hacer pagos
> Quieren tener un desglose más específico de sus gastos
> Tips de ahorro
> Predicción de gastos
> No ven necesario poner foto de perfil
> Tope de gasto
* 18-25
> Quieren tener un desglose más específico de sus gastos
> Tips de ahorro
> No tienen una cuenta bancaria
> No reciben tantos recursos monetario

##### User Persona

![LFP_3](https://github.com/Andrea0611/APP-FINACIERA/blob/master/UserPerson.png)

###### Fernando
Perfil 1
Edad 20 
Ocupación: estudiante
Fernando es estudiante de Derecho, es soltero. Vive con sus padres. Le gusta salir todo los viernes con sus amigos y conocer nuevos lugares. Recibe una cuota semanal fija, que el debe administrar. Acaba de abrir una cuenta en un banco para poder realizar compras en amazon por lo general de productos electrónicos, como unos audífonos. No sabe administrarse y no tiene control de sus gastos, por lo que le gustaría saber en qué gasta. Quiere comprarse  el último iwatch que saldrá en 6 meses.

###### Frustraciones 
Al recibir una cuota fija, se gasta todo su dinero a veces sin saber en que. 
Ahorrar le parece complicado tedioso y aburrido

###### Necesidades
Aprender a administrarse para que le rinda mejor el dinero.
Ahorrar de una manera sencilla y dinámica para poder comprar su iwatch

### Propuestas de Reto de Diseño

##### Objetivo del usuario
* Aprender a administrarse
* Ahorrar para cumplir una meta
* Saber cuánto gasta

#### Reto de diseño
Generar una experiencia divertida de ahorro
Enseñarle al usuario de manera lúdica y rápida a ahorrar, por medio de tips, se busca generar una cultura de ahorro en los usuarios

#### Definición del reto de diseño

1.Se modifico algunos elementos que afectaban la usabilidad del usuario, como el botón de crear cuenta y se le agrego los terminos y condiciones.

![LFP_4](https://github.com/Andrea0611/APP-FINACIERA/blob/master/Sign%20Up%20%235.png)

2. Cuando entren a la aplicación, les aparecera un tip, recomendación, o dato para aprender a ahorrar. Que podrás cerrar de inmediato si no te interesa o leerlo con detenimiento. Además de acuerdo a tus gastos te dará recomendaciones para ahorrar.

![LFP_5](https://github.com/Andrea0611/APP-FINACIERA/blob/master/Ahorros%202.2.jpg)



###### Propuesta de valor
“Gana más, ahorrando más”
2. Gamificación. Por medio de puntos equivalentes a dinero se recompensará al usuario cada vez que termine una meta de ahorro (+5pts). Además cuando junte 5 metas recibirá un premio de puntos y subirá de nivel, cada nivel tendrá un aumento de puntos por meta individual terminada, y así sucesivamente. A continuación se muestra la tabla de niveles. Llegando al nivel 5. Las metas deben tener un mínimo de ahorro de 5 mil pesos para entrar en recompensas.
* Nivel 1 (0-5 metas) +5 por meta terminada. Al concluir este nivel se te otorgaran +5pts.
* Nivel 2 (6-10 metas) +7 por meta terminada. Al concluir este nivel se te otorgaran +10pts.
* Nivel 3 (11-15 metas) +9 por meta terminada. Al concluir este nivel se te otorgaran +15pts.
* Nivel 4 (16-20 metas) +11 por meta terminada. Al concluir este nivel se te otorgaran +20pts.
* Nivel 5 (21 metas en adelante) +15 por meta terminada. 

![LFP_6](https://github.com/Andrea0611/APP-FINACIERA/blob/master/Ahorros%201.jpg)
![LFP_7](https://github.com/Andrea0611/APP-FINACIERA/blob/master/Ahorros.1.jpg)


###### Propuestas
3. Se propone implementar la app en la plataforma Android, para generar más usuarios. Con base a la investigación se detectó que desde la landing page se pierde gran cantidad de usuarios debido a que la app solo existe para Android.
4. Además se detectó que otra gran pérdida de usuarios sucede al momento de registrarse, ya que es muy largo el proceso. Por lo que se modifica el registro: por medio de una contraseña y si el usuario lo prefiere, es opcional el registro de la huella digital y de el uso de fotografía.

![LFP_8](https://github.com/Andrea0611/APP-FINACIERA/blob/master/Sign%20Up%20-%20Photo%20%231.png)
![LFP_9](https://github.com/Andrea0611/APP-FINACIERA/blob/master/Sign%20Up%20-%20Touch%20ID%20%231.png)


#### Prototipado
Se realizo el prototipado en figma para modificar el diseño https://www.figma.com/file/kwoF0tHvii6hTyARfWWIQ2/proyecto-2-banca-(AndreaParrilla)?node-id=0%3A477 y para darle usabilida se realizo un prototipo en marvel https://marvelapp.com/b31cahe/screen/55356262

#### Programas usados
* Figma
* Marvel
* Illustrator
* Photoshop
* Miro
