# Aplicación financiera: Tus Finanzas

## Resumen 
Una de las compañías bancarias más importantes del país, lanzó al mercado una aplicación móvil para sus usuarios, ésta pretende visualizar sus gastos mensuales y fomentar el ahorro. Luego de tener unos meses de posicionamiento en el mercado, el equipo, encargado del proyecto, me seleccionó como líder de UX para colaborar en la definición de la dirección y la evolución del producto. Por medio del Mindset Design Thinkin realicé un diagnóstico de la aplicación con la finalidad de brindar un rediseño que mejorara el flujo de la información y detallara el contenido de las secciones al indicar la ubicación, la fecha y el tipo de operación que el usuario lleve a cabo. De igual forma, profundicé en el UX Writing y en la estética, basada en las heurísticas de usabilidad. Como propuesta de valor, busco incentivar la cultura de ahorro, a través de bonificaciones por cada meta lograda.

- Rol: UX Reseach / UI Designer
- Duración: Tres sprints
 
## Preámbulo
En los últimos años, EEUU y Europa han lanzado nuevas aplicaciones financieras que se enfocan en darle a sus usuarios visibilidad sobre sus propios gastos, accesibilidad de pagos a terceros, así como al fomento del ahorro. Inspirados en un par de ellas, el banco tomó la decisión de lleva a cabo el lanzamiento de una nueva aplicación, misma que se cronstruyó desde cero.

El Producto Mínimo Viable (MVP) fue diseñado y desarrollado en dos meses para iOS, sin embargo, el banco requiere una propuesta de nuevo diseño y conocer si es necesario duplicar el presupuesto de Facebook Ads, con base en la data recolectada durnate en seis meses.

## Objetivo del proyecto
Realizar un diagnóstico, evaluar el desempeño de la aplicación y proponer los cambios necesarios para la optimización del producto.

# Primer sprint

## Contexto del problema

Durante el primer sprint, se realizó la entrevista con la Product Manager del proyecto, misma que brindó el contexto de la aplicación. Los aspectos a identificar fueron los siguientes:

#### Pains
- La aplicación sólo está disponible para iOS.
- Los usuarios no se registran en la aplicación.
- Los usuarios ingresan sólo a la sección de gastos.

#### Gains
- Las impresiones en Facebook Ads incrementaron de febrero a julio.
- La aplicación puede vincularse con las tarjetas del banco.
- La aplicación tiene como medida de seguridad el touch ID.
- Facilita la visualización de salud financiera y metas de ahorro.
- El banco permite retirar el dinero ahorrado.

#### Documentación
La documentación  del producto está en una carpeta de [Google Drive](https://drive.google.com/drive/u/0/folders/1NWf4701uKDsCK0eLNI8RXEocrI1g1zqd). 

- Los user persona primario y secundario del proyecto
- Los user flows iniciales y actuales del proyecto del MVP
- El [diseño del app en Figma](https://www.figma.com/file/Gr5GEIRrjF9eIplIeEHUSJNt/proyecto-2-banca?node-id=0%3A477)
  , con una guía de componentes y el [Prototipo navegable](https://marvelapp.com/e9h245e)
- Funnel Analytics de los primeros 6 meses del MVP
- Data de uso del MVP de los primeros 6 meses
- [Landing Page](http://fintechapp-laboratoria.pagedemo.co/) inicial del producto


![preview app de finanzas](https://lh3.googleusercontent.com/WyfUPurRuoXyyeZScQtdLhk063ZozToVlujoljul3TDwJW5KZy3Om_LvuB-TB9IcG2r_BCSpoXtXL-bZjIeGBFxQmL4GYEM2QXnQovq6EvixYaO_Z5-gFMvljM9jye7bVofendMteBI)

### Investigación de escritorio 
A través de revisar la documentación pertinente entorno a las aplicaciones financieras, la cultura del ahorro en México y las áreas de oportunidad en el país se identificaron insights entorno al mercado financiero.  
![Contexto](https://github.com/Cristalgarcia/FinancialAPPCDMX007/blob/master/Imagenes/Contexto.jpg)
Fuente: [Estudio de consumo de medios y dispositivos 2018. Corte Financiero](https://drive.google.com/file/d/1BWRq19LnMxY7g7x5F-KhYbfg1EzI8nTK/view?usp=sharing)

### Benchmarck 
Los principales competidores de la aplicación corresponden a la banca tradicional y a las digitalmente nativas. Para encontrar áreas de oportunidad, se analizaron a diez bancos (nacionales e internacionales) para conocer su target, sus beneficios, el proceso de registro, las medidas de seguridad, el contenido, en qué dispositivos están disponibles, así como sus gains y pains.

![Benchmark](https://github.com/Cristalgarcia/FinancialAPPCDMX007/blob/master/Imagenes/Benchmarck.jpg)

## Diagnóstico
### Análisis de la data

La aplicación, durante los seis meses que estuvo disponible generó data correspondiente a Ads y el uso del MVP. El análisis de la información arrojó lo siguiente.

#### Campaña en Facebook
- Las impresiones en Facebook presentan un incremento del 47% de febrero a julio.
- El promedio de las impresiones de febrero a julio fue de 77M, sin embargo, obtuvo un promedio de 29M instalaciones y 3K de registros, es decir, la campaña en Facebook no presenta una captación positiva de nuevos usuarios.

#### Landing Page
- El 89% de los usuarios ingresan a la landing page a través de dispositivos Android y el 4% ingresa en dispositivos iOS. Es recomendable realizar un diseño para dispositivos Android.
- La tasa de rebote es mayor en dispositivos Android con un promedio de 77.19%, mientras que en iOS fue del 70%.
- El usuario que ingresa a la aplicación en dispositivos Android dura en promedio 1:43 minutos; mientras que con iOS el tiempo es de 2:31 minutos. El comportamiento se debe a que la aplicación está diseñada para iOS, y hace que la navegación para otros dispositivos sea más complicada.

#### Comportamiento en la aplicación
- Las sesiones de febrero a julio incrementaron 55%, con un promedio de 200K sesiones al mes y 7K al día.
- El promedio de dispositivos activos de iPhones en el periodo febrero a julio es de 8.1K, con un promedio de de sesiones de 7.2K, es decir, 12.5% de los dispositivos no realizan inicio de sesión.

### Análisis Heurístico

Los touchpoints que se tomaron en cuenta para el análisis de usabilidad de Tus Finanzas fueron pagina de carga, registro, inicio de sesión, home, gastos, ahorros y movimientos. Los pains fueron:

- Registro: La aplicación no indica cuál es su objetivo. En el proceso de la huella digital falta un mensaje de lo que ocurre. Agregar una fotografía de perfil es confuso. La interfaz no tiene una consistencia en el idioma ni en el diseño de los elementos, principalmente en los botones. El usuario no puede ver términos y condiciones.
- Inicio de sesión: Inconsistencia en el idioma y hacen falta elementos para reconocer que se está en la sección.
- Home: La sesión no se puede cerrar; hacen faltan elementos para reconocer que se está en la sección, el menú tiene una mala distribución de los elementos; carece de una sección de contacto y ayuda.
- Gastos: El usuaro no sabe en dónde está ubicado por falta de información. Hay una inconsistencia en la paleta de color. La información no está desglosada.
- Ahorro: La pantalla se queda en blanco y no informa al usuario que su acción está siendo procesada. Hay una inconsistencia en el color de los elementos. El botón de crear cuenta no se ve y la instrucción es confusa. El formulario no tiene información de cómo llenarlo.
- Movimientos: El botón del menú se queda a la mitad de la pantalla al dar scroll. No presenta información de notificaciones para reconocer cargos. Falta información para saber en qué sección el usuario está ubicado. 

***[análisis heurístico](https://docs.google.com/spreadsheets/d/1CwpM3RXDBQZytdJBXpfiUY4Qw1lqOffqr3Xgh617gRo/edit?usp=sharing)***

### Testing del MVP

El prototipo navegable fue testeado con 33 usuarios con base en las dos user personas que el cliente me compartió. El total fueron 15 mujeres y 18 hombres. El 75% de las personas utilizan dispositivos Android. El 72% está activamente laborando. Las hallazgos del testeo fueron:

#### Pains
- Los usuarios no saben cómo seleccionar la foto de perfil y terminar la tarea.
- La aplicación no tiene la opción de realizar pagos y transferencias.
- El botón de crear cuenta es confuso tanto en su ubicación, y el objetivo.
- El menú del perfil no tiene información de valor.
- La tarjeta no se puede bloquear desde la aplicación.
- La app no brinda predicciones.
- Las personas, en la sección de ahorro no pueden conocer la cantidad bruta que llevan ahorrada.
- Los usuarios quiene un método de contraseña más segura.
- El botón redondo del menú fijo no tiene una funcionalidad clara.
- La aplicación no da la fecha de las operaiones realizadas.
- Los ahorros no se pueden editar manualmente.
- La app no tiene alerta de movimientos.

#### Gains
- La navegación es intuitiva.
- El registro sencillo de hacer.
- El diseño es bueno, destacan los colores.
- La opción de generar una meta de ahorro automático es de gran valor.
- La huella de seguridad da confianza, debido a que lo han visto en otras aplicaciones.

## Coustomer Journey Map
El Coustomer Journey Map arrojó que, los usuarios tienen dificultad en agregar una fotografía para el perfil y el crear una cuenta de ahorro.
![CJM]()

## User Persona 
El user persona se estableció con base en [los ejes de comportamiento](https://github.com/Cristalgarcia/FinancialAPPCDMX007/blob/master/Imagenes/Ejes.jpg) y arquetipos.
![User persona]()

# Segundo Sprint 
Los objetivos de la segunda iteración se basan  en generar una propuesta de rediseño con base a la información recabada en el primer sprint, prototipado de rediseño, realizar pruebas de usabilidad y establecer los siguientes pasos. 

## Reto de diseño

La propuesta de rediseño está centrada en mejorar el flujo de la navegación, generar consistencia en los elementos visuales y desglozar la información de los movimientos. 
![Propuesta de diseño](https://github.com/Cristalgarcia/FinancialAPPCDMX007/blob/master/Imagenes/Reto%20de%20dise%C3%B1o.jpg)

###  Mockups

Los mockups de la aplicación están disponibles [aquí](https://docs.google.com/document/d/15fOJTfhHzOB4uaYPKWaqjzjbOLOoa4z8h0t6v7GxhaI/edit?usp=sharing)

## Prototipado 
El prototipo de la aplicación, Tus Finanzas, está realizada en Figma y el flujo de la navegación en Marvel.

### Primer testing

El rediseño del home se testeo con tres personas para evaluar si el contenido era claro y si los iconos del navegador fijo eran entendibles. Los comentarios fueron que la pantalla de inicio contenía mucha información; mostraron confusión debido a que la información parecían botones y era tomada como un navegador extra, por tal motivo, la información fue modificada. Asimismo, los usuarios indicaron que los iconos eran simples pero no sabían la funcionalidad de cada uno, para identificarlos se optó por incluir el titulo de cada uno.
![Primer testing]()

### Primera iteración

El prototipo de la primera iteración puede ser consultado [aquí](https://www.loom.com/share/1704d1bcbe844b2786a926c8fc853c6d).

### Segundo testing
La aplicación fue testeada con cinco personas. Los usuarios indicaron que la navegación es fácil y sencilla; el inicio de sesión es ágil, los iconos son amigables, y los detalles de los movimientos tienen valor. Además, los usuarios lograron terminar las tareas asignadas. Los pains fueron que hay tecnicismos en los textos; los usuarios esperan que la tarjeta de home tenga una funcionalidad, desean tener la oportunidad de consultar su estado de cuenta y contar con un apartado que indique cuándo hay que pagar los servicios.

## Prototipo de alta fidelidad

El rediseño de la aplicación tuvo una primera iteración con base en los hallazgos antes mencionados.

## Flujo de la información
![arquitectura](https://github.com/Cristalgarcia/FinancialAPPCDMX007/blob/master/Imagenes/flowmap_tus%20finanzas.png)

## Propuesta
El copy de la aplicación era "El banco contigo a donde vayas". Para transmitir un mensaje más claro se cambio por “Ahorra desde ahora”.

Antes del registró, la aplicación muestra tres slides con los objetivos principales de Tus Finanzas.

Las medidas de seguridad implementadas son dos, password y touch ID; y las cuales pueden ser elegidas acorde a las preferencias del usuario y el diseño del dispositivo a usar.
![REGISTRO]()

El home de la aplicación muestra el saldo disponible en la tarjeta y el estatus de sus metas de ahorro. Por cada meta cumplida, el usuario optendrá un incentivo para alentar la conducta de ahorrar.
![HOME]()

El usuario tiene la posibilidad de ver los detalles de sus movimientos como ubicación, fecha y tipo de operación.
![DETALLES]()

En la sección de Ahorro, el botón de crear una nueva meta es más grande y está centrado. El formulario de crear una meta de ahorro, tiene instrucciones en los imput para dirigir de forma correcta el llenado. Además, los usuarios tienen la posibilidad de ver el estatus de sus metas de ahorro, transferirlas, editarlas y pausarlas.
![AHORRO]()

## Propuesta de valor

Como adicional, la aplicación cuenta con un chat para ofrecer atención inmediata a cualquier duda o problema y un apartado de balance de su salud financiera.

- El prototipo de alta fidelidad está disponible [aquí](https://marvelapp.com/b687j2e/screen/55362427).
- El flujo del prototipo está disponible [aquí](https://www.loom.com/share/028d1129a8b34a1fbc8a782b3f906876).





