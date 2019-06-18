# REDISEÑO DE LA APP FINANCIERA: TUS FINANZAS

## 1. INTRODUCIÓN
El Product Manager de un banco se puso en contacto con nosotras y nos solicitó que los ayudemos en el rediseño de un app que el equipo del laboratorio de innovación el bancó diseñó desde cero, empezaron entrevistando a algunos usuarios y revisando los resultados de un estudio de mercado que les proporcionó el área de marketing. En base a ello identificaron funcionalidades más relevantes, crearon sus primeros user personas una primaria y una secundaria y diseñaron y desarrollaron un ‘Producto mínimo viable’ (MVP) en 2 meses en iOS. Ese MVP lo han lanzado y tienen alrededor de 6 meses de data. Buscaban entender los resultados iniciales y de sacar una segunda iteración del producto, para lo que nos enviaron los siguientes recursos en [Google Drive](http://bit.ly/uxd-reto-2).

Ellos necesitaban traer una propuesta del nuevo diseño en dos semanas porque tenían que presentarla a su Gerente General en la reunión trimestral y pidieron que ya tenga feedback de testing con usuarios. Adicionalmente  nos pidieron que analicemos la data generada desde el primer contacto desde Facebook Ads, donde no saben si deben duplicar la inversión, hasta el uso del app.

Este era el prototipo inicial:

![preview app de finanzas](https://lh3.googleusercontent.com/WyfUPurRuoXyyeZScQtdLhk063ZozToVlujoljul3TDwJW5KZy3Om_LvuB-TB9IcG2r_BCSpoXtXL-bZjIeGBFxQmL4GYEM2QXnQovq6EvixYaO_Z5-gFMvljM9jye7bVofendMteBI)

## 2. OBJETIVOS DEL PROYECTO
Es por ello que nuestro equipo se propuso:
- Validar los datos brindados como los user personas mediante investigación y entrevistas a posibles usuarios.
- Construir nuevos user personas.
- Prototipar una nueva versión de la app, que incluyan los nuevos requerimientos encontrados.
- Analizar la data proporcionada para sustentar la inversión en Facebook Adds.

## 3. DESCUBRIMIENTO E INVESTIGACIÓN

![image](https://user-images.githubusercontent.com/47748753/58359563-b66fbf80-7e49-11e9-9391-d83396a4519b.png)

### 3.1 Investigación del contexto de la Industria
Las nuevas tecnologías han creado formas de hacer negocio financiero y los clientes por su parte, exigen soluciones inmediatas, así como una atención personalizada y omnicanal.

En general, se observa que el número de operaciones efectuadas a través de canales virtuales -que no requieren la presencia física del cliente (banca móvil, e-commerce, banca por internet, software corporativo)- en el primer semestre del 2018 totalizaron 106.7 millones y alcanzaron un incremento de 23.97% frente a similar periodo del 2017, según ASBANC.

##### a) Tipos de clientes de la banca actual
En la actualidad existen tres tipos clientes en las entidades financieras:

###### El cliente tradicional
Acude a su oficina habitual en busca de una atención y trato personalizado.

###### El cliente omnicanal
Se mueve entre ambos entornos (off y online), en función de sus circunstancias y necesidades.

###### El cliente 100% digital 
Apuesta por una banca totalmente digital, sencilla, ágil y transparente, aunque quizás con productos menos especializados.

##### b) Banca móvil

Según Asbanc: 
El aumento de la participación en algunos canales de atención como banca móvil o e-commerce refleja su mayor uso en el último año como puntos transaccionales para los clientes financieros.
En el primer semestre se realizaron 22.6 millones de operaciones monetarias a través de la banca móvil, superando en 111.37% al nivel observado en igual periodo del 2017.

Cada uno tiene un perfil diferente,pero un punto en común: la búsqueda de una experiencia de usuario positiva.

##### c) Estadísticas:

Según un estudio de la consultora Brillio.
- El 73% de las mujeres están insatisfechas con la industria bancaria.
- 2 de cada 5 clientes se irán tras una mala experiencia.
- Desde 2012, la expectativa de que los bancos inviertan en servicios móviles ha aumentado en un 50%.
- El 70% de lo millennials, ha usado herramientas móviles a comparación de un 40% de los adultos
- El 77% de los millennials han realizado transacciones en banca móvil.
### 3.2. Análisis de la Data
Nos proporcionaron una data en excel donde lo primero que nos dimos cuenta fue la desproporción de la cantidad de impresiones con los anunciones de fb y el registro en el app, por lo que quisimos validar esa relación.
Lo hicimos mediante una técnica estadística conocidad como el Chi-cuadrado:
#### a) Impresiones de Facebook vs  registros
Primero comparamos la correlación entre las impresiones de Facebook y los registros que era lo que nos importaba y la conclusión fue que con un 95% de confiabilidad y un grado de libertad no existía correlación entre ambas, y esto se puede verificar en la siguiente gráfica, donde a pesar que aumente las impresiones, no se  ven reflejadas en la cantidad de registros:

![image](https://user-images.githubusercontent.com/47748753/59647760-0fc5c880-9142-11e9-9c2a-dcce644b993a.png)


En conclusión comprobamos que no existía correlación entre ambas variables.

#### b) Impresiones de Landing page vs  registros
Luego al realizar un análisis de correlación entre las visitas al Landing page y los registros vimos que con un 95% de confiabilidad, sí existía correlación entre ambas variables y además se puede comprobar con la siguiente gráfica de doble columna:

![image](https://user-images.githubusercontent.com/47748753/59647745-fb81cb80-9141-11e9-8b72-5ff281c75139.png)

En conclusión a medida que las visitas en el landing suban los registro suben y en caso contrario también existe una relación directa.

#### c) Descarga del app vs  registros
Finalmente comparamos las descargas del app con los registro y encontramos que tampoco existía correlación, ambas son variables independientes y la variación de la primera no influye en la segunda como gráficamente se ve a continuación, en un cuadro de dos columnas :

![image](https://user-images.githubusercontent.com/47748753/59647575-5ebf2e00-9141-11e9-86e1-83071b43e851.png)
### 3.3. Benchmark
Dentro de nuestra investigación pudimos comparar entre 7 apps, y descubrimos que la app TUS FINANZAS tenía ciertos errores que iremos mejorando con el avance de nuestro proyecto.

Compartimos el link donde mostramos a más detalle las apps que pudimos encontrar [aquí](https://docs.google.com/document/d/17e3ViL6ajh4CaWRA74A85SFNiW9eOlz-MjGIf1lhfHE/edit).

### 3.4. Entrevista al cliente
Durante la entrevista con Lalo el product manager del app pudimos inferir los siguientes objetivos del app:
- El app está enfocado al ahorro
- Quieren ser como un asistente para aprender ahorrar.
- Quieren crear metas para ahorrar (ahorro con objetivos).
- Quieren conocer las motivaciones para ahorrar.

### 3.5. Entrevista a posibles Usuarios

Luego de haber hecho nuestro benchmark procedimos a reclutar a nuestros entrevistados, decidimos agruparlos por un cierto rango de edades. 
- De 18 a 24 años: Entrevistamos a 4 personas que cumplian con el perfil que necesitábamos y aceptaron cordialmente a darnos la entrevistas y a ser grabadas. Pudimos descubrir que tenían noción de lo que es el ahorro más no podían hacerlo porque en su mayoría eran subsidiados por sus padres.

- De 25 a 30 años: Entrevistamos a 4 personas, tambien cumplian con el perfil que necesitamos. Descubrimos que en este rango de personas, sabían que era el ahorro, pero sus gastos le impiden ahorrar y lo que ahorraban eran para algunos imprevistos. También descubrimos que tenían metas de viajar, estudiar un postgrado o comprarse a futuro un departamento.

- De 31 a 40 años: De igual manera, entrevistamos a 4 personas, decidimos optar por este rango de personas para descubrir cómo eran sus formas de ahorro y para que ahorraban. En su mayoría todos ahorraban , pero sus ahorros ya no eran únicamente para sus metas de viaje o estudias sino que también eran para un futuro seguro de sus hijos o invertirlo en una empresa.

Les compartimos el Link de los audios:
[en este enlace](https://drive.google.com/drive/folders/1mfyuvUdI9sJvAJiyxlTfpHpc8UXoSbVD?usp=sharing).

También les compartimos el link de las síntesis de las mismas:
[en este enlace](https://drive.google.com/open?id=1dnhwYoqVH9G8Y4NMdg4MLQ_NE6eyOF06m_0bAGi8nGg).

### 3.6. Testeo Virtual
Para el testeo online utilizamos Maze una programa que permite crear tareas de testeo con un prototipo que ya cuente con interacción.
Propusimos 4 misiones:
- #### 1ra Misión: Registrate en la app.
  - #### ¿Cúantos iniciaron el test?
  - Fueron 93 personas. 
  - #### ¿Cúantos terminaron la tarea?
  - Terminó el 67.7% de los que la iniciaron.
  - #### ¿Cúantos siguieron la ruta o camino que nosotros esperábamos que tomaran?
  -  Fue solo 30.1% de los que iniciaron la tarea.
  - #### ¿Cúantos  siguieron otra ruta o camino?
  - Fue el 37.6% del total.
  - #### ¿Cúantos abortaron misión o se rindieron?
  - El 32.3% renunció.

- #### 2da Misión: Verifica tus movimientos del mes de Agosto.
  - #### ¿Cúantos iniciaron el test?
  - Fueron 54 personas. 
  - #### ¿Cúantos terminaron la tarea?
  - Terminó el 44.4% de los que la iniciaron.
  - #### ¿Cúantos siguieron la ruta o camino que nosotros esperábamos que tomaran?
  -  Fue solo 7.4% de los que iniciaron la tarea.
  - #### ¿Cúantos  siguieron otra ruta o camino?
  - Fue el 37% del total.
  - #### ¿Cúantos abortaron misión o se rindieron?
  - El 55.6% renunció.

 - #### 3ra Misión: Crea una cuenta de ahorros  para navidad.
  - #### ¿Cúantos iniciaron el test?
  - Fueron 42 personas. 
  - #### ¿Cúantos terminaron la tarea?
  - Terminó el 78.6% de los que la iniciaron.
  - #### ¿Cúantos siguieron la ruta o camino que nosotros esperábamos que tomaran?
  -  Fue solo 28.6% de los que iniciaron la tarea.
  - #### ¿Cúantos  siguieron otra ruta o camino?
  - Fue el 50% del total.
  - #### ¿Cúantos abortaron misión o se rindieron?
  - El 21.4% renunció.
- #### 4ta Misión: Encuentra la sección.
  - #### ¿Cúantos iniciaron el test?
  - Fueron 35 personas. 
  - #### ¿Cúantos terminaron la tarea?
  - Terminó el 71.4% de los que la iniciaron.
  - #### ¿Cúantos siguieron la ruta o camino que nosotros esperábamos que tomaran?
  -  Fue solo 25.7% de los que iniciaron la tarea.
  - #### ¿Cúantos  siguieron otra ruta o camino?
  - Fue el 45.7% del total.
  - #### ¿Cúantos abortaron misión o se rindieron?
  - El 28.6% renunció.

## 4. SÍNTESIS Y DEFINICIÓN

![image](https://user-images.githubusercontent.com/47748753/58359572-bff92780-7e49-11e9-9869-dd908f95d10f.png)

En base a todo lo observado obtuvimos datos sumamente importantes, para ello realizamos el Affinity Map y el Customer Journey Map e identificamos a nuestro User Persona.

### 4.1. Affinity Map
Nuestro afinity map lo desarrollamos en la ayuda online MIRO, al que pueden tener acceso desde [aquí](https://miro.com/app/board/o9J_kxHORbg=/)

### 4.2. User Personas
#### 4.2.1. User Personas presentados el cliente:
El cliente nos presentó a dos user personas, el User persona primario que fue Fiorela:

Y el User persona secundario fue Diego 

#### 4.2.2. Análisis para el cambio de User personas:
Luego de las entrevistas clasificamos a los posibles usuarios en tres grupos:
##### a) Estudiantes y dependientes econónomicamente de sus padres
- Rango de edad: 18 a 24 años
- Hobbies: Salir con amigos, leer, aprender autodidácticamente y divertirse.
- Ideas sobre el ahorro: Es muy necesario para tener un respaldo a futuro y comprar o conseguir metas personales o familiare.
- ¿Ahorran? Tienen la intención pero como dependen económicamente de sus padres no pueden hacerlo.
##### b) Independientes y sin carga familiar
- Rango de edad: 25 a 30 años.
- Hobbies: Viajar individualmente y con amigos, aprender cosas nuevas, salir con amigos los fines de semana.
- Ideas sobre el ahorro: Saben que es vital ahorrar para tener un respaldo en caso de emergencias y eventos no previstos.
- ¿Ahorran? Sí, lo que les sobra del sueldo y para viajes.
##### c) Independientes con carga familiar
- Rango de edad: 31 a 40 años.
- Hobbies: Pasar tiempo en familia, mantener contacto con posibles clientes y manntenerse al tanto de las nuevas tendencias
- Ideas sobre el ahorro: Es vital para la estabilidad personal, familiar y el crecimiento de sus empresas o para planes o calma futura.
- ¿Ahorran? Sí, ahorran con seguros con débito automáticos, para la seguridad de la educación de sus hijos y salud de toda su familia.
#### 4.2.3. User personas propuesto
#####  a) User Persona principal
Luego de este análisis, replanteamos los users personas y construimos a Kiara, nuestra USER PERSONA PRINCIPAL, que pertenece al segundo grupo de los "Independientes y sin carga familiar" y la denominamos como la "VIAJERA":
![USER PERSONA](https://user-images.githubusercontent.com/47748753/59630320-a8d8ed00-910a-11e9-8992-dd43c8b4eb4b.png)
#####  b) User Persona secundario
También propusimos a Mateo del tercer grupo de los "Independiente y con carga familiar" y lo denominamos como el "PROTECTOR"

![User PERSONA SECUNDARIO](https://user-images.githubusercontent.com/47748753/59643384-0d597380-912e-11e9-84ff-a1bedc0d1908.png)

### 4.3. Customer Journey Map
Presentamos el Customer Journey de Kiara, al momento de usar el app financiera que el banco nos propuso, donde el principal dolor lo sintió al regresar al menú principal, entre otros que se pueden ver a continuación:
![image](https://user-images.githubusercontent.com/47748753/59632107-02431b00-910f-11e9-92d7-f8c2f0fe0b41.png)
### 4.4. Problem Statements


### 4.5. How Might We

### 4.6. Priorización
### 4.7. Minimun Viable Product (MVP)
## 5. IDEACIÓN

![image](https://user-images.githubusercontent.com/47748753/58359586-cdaead00-7e49-11e9-8d49-d164296d7c03.png)

En esta etapa buscamos las mejores maneras para desarrollar las funcionalidades definidas en la etapa de síntesis, volvimos a recurrir al benchmark de la etapa de descubrimiento e investigación y a Pinterest para ver tendencias de diseño.

## 6. PROTOTIPADO

![image](https://user-images.githubusercontent.com/47748753/58359983-bffa2700-7e4b-11e9-9ee2-ac64c78335c1.png)

Realizamos el prototipo de alta fidelidad en Figma, de acuerdo a la priorización.

Para continuar viendo nuestro prototipo en InVision dale click al  siguiente
[link](https://invis.io/WZS37D3UCJ5#/365291028_Andi_Presentaci-n_Final_-5-).


## 7. CONCLUSIONES

Las nuevas funcionalidades responden a los problem statements del proyecto encontrados en la investigación.

- ##### Problem Statement 1:
  * ##### Propuesta:
- ##### Problem Statement 2:
  * ##### Propuesta:
- ##### Problem Statement 3:
  * ##### Propuesta:
- ##### Problem Statement 4:
  * ##### Propuesta:




## Entrega

El proyecto será entregado en un repositorio de GitHub. En él deberás agregar
lo siguiente:

README.md  detallando:

* Objetivos iniciales del proyecto
* Problemas encontrados tanto a nivel de negocio como a nivel de usuario
* Recomendaciones de próximos pasos para el banco con respecto al app (estas
  recomendaciones tendrán que ser sustentadas por tu investigación):
  * Qué modificaciones se deberían hacer
  * Cuáles deberían ser los próximos desarrollos
  * En qué se debería invertir el presupuesto de marketing
* De acuerdo al punto anterior, de requerirse cambios y desarrollos nuevos,
  estos deberán ser diseñados y entregados en un prototipo de alta definición.
* Link de Zeplin, InVision inspects o Marvel Hand-offs para compartir tus
  diseños con desarrolladores

Un video en Loom de máximo 5 minutos explicando tu documento.
* Estos 5 minutos tienes que utilizarlos para explicar los puntos indicados en
  el `README.md` y para hacer un demo de la solución propuesta.

En las otras carpetas del repositorio o en las carpetas de Google Drive podrás
agregar los documentos complementarios que sustenten tu proceso.

### Hacker edition

Para el hacker edition puedes elegir una o varias de estas opciones:

- Antes de empezar a desarrollar este proyecto, lista cuáles fueron tus
  aprendizajes durante el proyecto 1 y en qué cosas te gustaría mejorar durante 
  el proyecto 2. Al terminar el proyecto 2 vuelve a esta lista y chequea cómo te 
  fue con esos retos, ¿los cumpliste? Muestrános esta lista y esta reflexión
  en un documento adicional (en el formato que prefieras).
- Investiga sobre chatbots y sustenta si sería bueno incluir uno en alguna parte
  del journey del uso del producto. Si crees que un chatbot añadiría valor,
  prototípalo usando [Botsociety](http://bit.ly/ux-chatbot).
- Adapta el diseño del app para iPhone X/XS/XR.
- Diseña un app para Apple Watch que complemente tu propuesta.
- En lugar de usar Github para documentar tu proceso de trabajo, documéntalo en
  su propia web, puedes usar Wix, Instapage, Squarespace, Google Sites o crear
  tu propia web desde 0. 
- Escribe un post en Medium contando tu proceso de investigación.
- Crea un video mostrando el demo del app, aquí algunos ejemplos:
  - [Nequi](https://www.youtube.com/watch?v=BDLAXvSQCZ8)
  - [Simple Bank](https://www.youtube.com/watch?v=0eqD5o6422M)
  - [Pocket](https://www.youtube.com/watch?v=MoJHYNKmS2U)
  - [Hip Money](https://www.youtube.com/watch?v=BIesWRESgAc)

## Otras consideraciones

### 1) Planeamiento y presupuesto

En el reto del marketplace te entregamos una lista de tareas que podías
realizar y le asignamos un valor en puntos a cada tarea. Además, te dimos un
presupuesto de 300 puntos para que los utilices en esas tareas. Para este reto,
la lista de tareas, el valor en puntos de cada tarea y el presupuesto total
de las actividades a realizar lo crearás tú y lo tendrás que sustentar con tu
coach. Adicionalmente, deberás sustentar con tu coach qué entregables harás
llegar al banco al final de tu investigación y por qué. El coach te aprobará
estos entregables o te dará feedback para mejorarlos.

Cuando hagas tu presupuesto y pienses en los entregables recuerda que el tiempo
de desarrollo de este proyecto es de dos semanas. También, recuerda qué partes
te tomaron más tiempo en el desarrollo del proyecto 1 y los aprendizajes que
tuviste al desarrollar el proyecto 1.

### 2) Prototipo de alta fidelidad

Existen varias herramientas que puedes utilizar para diseñar el producto,
en este caso el diseño viene en Figma y el prototipo en Marvel, así que puedes
seguir usando esas herramientas. Sin embargo, eres libre de utilizar otras
como Adobe XD e Invision. Para el prototipo intenta utilizar Marvel o Invision,
ya que para el testing tendrás que usar una herramienta llamada
[Maze](https://maze.design/) que funciona mejor con estas.

Recuerda que el diseño que trabajes debe seguir los fundamentos de diseño visual
como: contraste, alineación, jerarquía, entre otros.
