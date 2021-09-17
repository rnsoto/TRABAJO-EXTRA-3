# TRABAJO-EXTRA-3

INFORME DE TRABAJO ADICIONAL

Trabajo Adicional

UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE

#DEPARTAMENTO DE ELÉCTRICA Y ELECTRÓNICA

FUNDAMENTOS DE CIRCUITOS ELÉCTRICOS 

Trabajo Adicional

Integrante: Nicolás Soto

NRC: 5416

Fecha: 14/09/2021

Informe de Trabajo adicional.

REDES IoT (Internet of things)

1.OBJETIVO 

A continuación, vamos a definir los objetivos planteados en el informe, de acuerdo con los temas sobre el trabajo adicional:
• Adaptar fácilmente una red hiperconectada que combine datos de IoT con análisis contextuales habilitados para redes.
• Reconocer que durante un incidente se necesita información de seguridad en tiempo real que se puede enviar a sus dispositivos móviles y los servicios de emergencias que necesitan comunicarse con las personas que están en peligro.
• La siguiente práctica nos ayudará a comprender de mejor manera el uso de capacidades de IA nativas para crear modelos de simulación en tiempo real que cambian y aprenden en colaboración con la estructura.
•La realización de esta práctica le permitirá al estudiante fortalecer y aplicar los conocimientos teóricos de red en malla.

2. MARCO TEÓRICO 

INTERNET DE LAS COSAS

En la investigación se conoce el origen de este término que aparece en el año 1999 por Kevin Asthon quien estaba realizando investigaciones en el campo RFID y dio a conocer esta idea en una conferencia. En 2005 la ITU comenzó a realizar un estudio sobre el tema y en 2009 este término se convertiría en el título de todo, por la conexión de las cosas y ejecución de redes dinámicas con conectividad desde cualquier momento y lugar, generando facilidades en todos los campos desde Salud, Smart home, Smart city, oficina, automóviles, logística, navegación, medio ambiente, farmacéutica, agricultura y ganadería entre otros, con uso de tecnologías basadas en radiofrecuencia como es el mismo RFID, redes inalámbricas de sensores como WSN, uso de redes de área personal, redes Wlan en conjunto con tecnologías como el uso de la nube, big data, desde luego la cantidad de dispositivos aumenta, así que de tal modo aparece el protocolo ipv6 con 128 bits a diferencia de ipv4 que carece de 32 bits, permitiendo así lograr más conectividad de dispositivos en las redes y hacia internet todo esto administrado por IANA, encargada de la coordinación mundial de los sistemas de direccionamiento del protocolo de internet.
El Internet de las cosas (IoT) fue concebido en un mundo donde los dispositivos que lo conforman pueden ser identificados en el Internet y además están creciendo a un ritmo sumamente acelerado con nuevos dispositivos que se van conectando. Por lo cual las redes de sensores inalámbricos son importantes para incrementar la ubicación de las redes con dispositivos inteligentes de bajo costo y fácil implementación, con estándares como IEEE 802.15.4 en la capa física, 6LoWPAN en la capa de red, y RPL como protocolo de enrutamiento ( Cama, 2012), que se integran en el concepto de IoT para traer nuevas experiencias en las actividades de la vida diaria, como por ejemplo en aplicaciones para hogares y oficinas confortables, salud, vigilancia del medio ambiente y ciudades inteligentes. En el presente artículo se relacionará a la red de sensores inalámbricos con el Internet de las cosas a través de estándares y protocolos.

2.1. REDES DE SENSORES INALÁMBRICAS (WSN) E INTERNET DE LAS COSAS (IoT)

son dos áreas de estudio que comparten entre sí ser una infraestructura de red autónoma, en la cual se interconectan objetos para medir variables físicas y dar solución a problemas en una variedad de escenarios de aplicación, como logística, industria, construcciones inteligentes, seguridad, agricultura, entre otros. Esta semejanza suscita una ambigüedad en el uso que la comunidad académica hace de los términos, WSN e IoT, y hace borrosa la línea de dónde pertenecen las contribuciones que se realizan en cada una de estas áreas. En consecuencia, el objetivo de este artículo es analizar la relación, similitud y diferencias entre WSN e IoT en torno a cinco temas: conceptos, requisitos generales, arquitecturas, aplicaciones y tratamiento de datos. A pesar de que WSN e IoT tienen un origen en común, sus enfoques son diferentes en varios aspectos que permiten aclarar la ambigüedad suscita entre la comunidad académica.

3. EXPLICACIÓN DEL PROCEDIMIENTO
  
A continuación de manera práctica vamos a explicar el funcionamiento de una red en malla.

3.1 MATERIAL Y EQUIPO REQUERIDO 

![image](https://user-images.githubusercontent.com/85181723/133823735-656849b0-6248-4d55-9908-d84e2e279b65.png)

3.2 PROCEDIMIENTO 

A continuación, vamos a enseñar paso por paso la realización de una red IoT en el programa Packet Tracer. 
3.2.1 CISCO PACKET TRACER 
Cisco Packet Tracer es una aplicación a través de la cual se puede realizar una gran variedad de funciones relacionadas con las redes, como diseñar y construir una red desde cero, trabajar sobre proyectos preconstruidos (incluye una gran variedad de ejemplos interesantes), probar nuevos diseños y topologías de red, probar cambios en la red antes de aplicarlos a la misma, examinar el flujo de datos a través de una red, hacer simulaciones de Internet of things (internet de las cosas) o preparar exámenes de certificación en redes.
3.2.2 INTERFAZ DE PACKET TRACER
•	Menú Principal: dispone de opciones como File, Edit, Options, View, Tools, Extensions y Help.

![image](https://user-images.githubusercontent.com/85181723/133823782-da1e669b-dc8c-4672-8d99-86922819c780.png)

•	Main Toolbar: con las típicas funciones como abrir, guardar, imprimir, zoom in/out, deshacer, rehacer, etc.

![image](https://user-images.githubusercontent.com/85181723/133823815-82ca9cde-8e66-49af-a334-ee309614c128.png)

•	Secondary Toolbar: son las opciones de Packet Tracer, como seleccionar, borrar, añadir formas o enviar datos.

![image](https://user-images.githubusercontent.com/85181723/133824260-0e83ad55-40b8-43cc-8a67-f9754b16111f.png)

•	Button Toolbar: contiene todos los dispositivos y conexiones que dispone el programa y que se añaden en el diseño y configuración de una red. Esta barra se divide en dos partes, la primera de la izquierda, donde están las distintas categorías de los dispositivos, y una segunda donde se despliegan los dispositivos y conexiones para añadirlos.

 ![image](https://user-images.githubusercontent.com/85181723/133824316-74b28bf3-9b42-4595-8753-ced7a0c92362.png)
 
•	Área de Trabajo: la zona más amplia de la interfaz, donde se realiza el diseño de la red, añadiendo los dispositivos y conexiones, y donde se visualiza la simulación.

![image](https://user-images.githubusercontent.com/85181723/133824352-74c42299-9dd8-45f1-bbcf-e929ef06773b.png)

3.2.3 GENERACIÓN DE UNA RED IOT EN PACKET TRACER PASO A PASO 
1.	Procedemos abriendo nuestro simulador packet tracer para empezar con la simulación.

![image](https://user-images.githubusercontent.com/85181723/133824378-b2289259-0ed5-437d-81a9-0246d3350699.png)

2.	A continuación, preparamos los materiales que vamos a utilizar para la generación de nuestra red IoT tales como un Servidor, un Access point wifi y una Tablet. 
3.	
![image](https://user-images.githubusercontent.com/85181723/133824427-d708f444-a213-4d25-ae19-e01f52d6a4b5.png)

3.	Comenzamos con las respectivas modificaciones en el servidor, tales como quitar el proctocolo DHCP ya que un servidor no puede contar con direccioness ip dinamicas  si no estaticas. En  la siguiente imagen se muestra la ip del servidor. 

![image](https://user-images.githubusercontent.com/85181723/133824461-252b9773-80b6-40a4-8a92-ed64d1a3f923.png)

En el caso del accespoint procedemos a la generación de una red wifi con su clave de acceso. 

![image](https://user-images.githubusercontent.com/85181723/133824525-c98a84ad-8f28-4e5a-a74a-12edd7430461.png)

4.	Una vez hechas estas modificaciones, el siguiente paso seria por comenzar a ubicar nuestros dispositivos IoT en este caso tenemos el plano de una casa de una sola planta, vamos a utilizar una lampara, cámaras web, puertas con cerrojos Wifi, ventanas con seguros Wifi y unos sensores con detectores de movimiento y humo, las conectaríamos en este caso a nuestra red Wifi.

![image](https://user-images.githubusercontent.com/85181723/133824557-f8ae01fd-81e4-4326-9fc5-5c2e02604704.png)

![image](https://user-images.githubusercontent.com/85181723/133824585-4692374d-c795-426c-a9be-d19903e3eb52.png)

5.	Nuestro servidor deberá estar habilitado la opción de monitor IoT, una vez hecho esto a través de nuestra Tablet tendremos el control de todo los dispositivos por  lo cual podremos abrir y cerrar puertas solo con un toque, nuestra cámara web grabara todo en tiempo real y mediante un sensor de movimiento con la ayuda de la cámara web me notificará directamente a mi celular si tenemos intrusos en nuestra casa, por lo cual yo procederé a cerrar todas las puertas y ventanas mediante mi celular, teniendo tiempo de alertar a la policía y que mi familia no este en riesgo. 

![image](https://user-images.githubusercontent.com/85181723/133824629-cc4e3fae-b07c-4a28-a768-3a21272bc855.png)

6.	Finalmente hemos generado nuestra red IoT con los diferentes dispositivos Iot conectados a una red Wifi y con la posibilidad de controlarlo remotamente desde mi celular desde cualquier parte del mundo.

![image](https://user-images.githubusercontent.com/85181723/133824659-469c482d-8da6-4e6b-903a-adce29928c1d.png)

4. ANALISIS DE RESULTADOS 

Para cada uno de los circuitos anteriores, elabore una tabla con los resultados de las diferentes mediciones de voltaje realizadas con el osciloscopio y multímetro. Compare y comente los resultados obtenidos tomando en cuenta las distintas frecuencias utilizadas. 

4.1. VENTAJAS
•	Costo bajo: Protocolo de acceso gratuito, tarifas de suscripción baratas y tecnología fácil de integrar. 
•	Bajo consumo: Comunicaciones optimizadas que reducen significativamente el consumo de los dispositivos conectados. 
•	Dispositivos conectados: Sigfox ya ha dado conexión a su red a más de 10 millones de dispositivos.
•	Regiones: Actualmente, 60 países están cubiertos con la red de la empresa Sigfox. (No existente en el Ecuador).

![image](https://user-images.githubusercontent.com/85181723/133824693-314bc390-ce3c-4b02-9907-8699e91b6d9d.png)

•	Población: 803 millones de personas están cubiertas por la red alrededor del mundo.
•	Cobertura flexible: Puedes añadir puntos Wi-fi adicionales para tener mejor cobertura en zonas en las que normalmente no tienes, como en los pasillos, o cerca de las paredes para tener cobertura en el exterior.
•	Ruta directa: Dado que todos los puntos Wifi están conectados entre ellos, los datos pueden tomar distintos caminos para llegar a su destino. El sistema siempre escogerá el mejor camino para ir del punto A al punto B.

5. PREGUNTAS 
5.1. ¿Qué es una red en malla?
Una red en malla es un grupo de dispositivos que actúan como una sola red Wi Fi, es decir, que habrá varias fuentes de Wi Fi en tu casa en lugar de un solo router. Estas fuentes de Wi-Fi adicionales se denominan puntos Wifi.
5.2. ¿En qué se diferencia de una red Wi‑Fi tradicional?
En una red Wi Fi tradicional, tus dispositivos se conectan a un solo router. De este modo, toda la comunicación pasa por ese router. Cuanto más lejos estás del router, más débil es la señal.
5.3. ¿Qué conexión se debe usar para diferentes dispositivos? 
Si se usan dispositivos conectados a una velocidad de 1 Mbps cada uno. Se necesita una conexión a Internet que tenga el ancho de banda suficiente. Además, los dispositivos conectados deben encontrarse dentro de las áreas de cobertura Wi Fi.
5.4. ¿Qué obstáculos impiden una buena señal de Wi-fi?
 El tamaño, los materiales y la distribución de la casa pueden afectar a la transmisión de la señal Wi Fi. Es posible que las casas más grandes, con paredes más gruesas o con una disposición estrecha y alargada necesiten más puntos de acceso Wifi para disponer de una cobertura completa. 
 
6. VIDEO DE LA PRÁCTICA
https://youtu.be/IMmL_uUJIu4  

7. CONCLUSIONES 
•	En la actualidad aparecen cada día más objetos inteligentes con la capacidad de comunicarse entre sí, normalmente con el objetivo de resolver una tarea o actividad. Por lo que se ha vuelto una tendencia el sistema conocido como Internet of Things. 
•	La generación de nuevas tecnologías obliga a los países del mundo a tomar acción sobre los sistemas que integran y se comunican, con diferentes protocolos, características técnicas, servicios, etc. 
•	El fin principal al desarrollar esta tecnología es que los usuarios no expertos en el dominio sean capaces de desarrollar de forma rápida aplicaciones que integren la funcionalidad de varios de estos dispositivos. 

8. RECOMENDACIONES
•	La intensidad y la velocidad de la señal también dependen de tu proveedor de Internet.
•	Hacer la conexión en las diferentes estructuras, permitirán una correcta distribución de la señal Wi-fi para el correcto funcionamiento de los dispositivos interconectados.
•	Si el router o el punto Wifi principal pierde la conexión, la perderá toda la red. En una red en malla, si un punto Wifi deja de funcionar, la comunicación se desvía a otro por lo cual se debe verificar su conexión correcta para evitar problemas a futuro. 

9. BIBLIOGRAFÍA
Cama-Pinto, A., De la Hoz, E., & Cama-Pinto, D. (2012). Las redes de sensores      inalámbricos y el internet de las cosas. Inge Cuc.
González García, C. (2013). MIDGAR: Plataforma para la generación dinámica de   aplicaciones distribuidas basadas en la integración de redes de sensores y dispositivos electrónicos IoT.
Hernández, B. A., & Ortiz Galeano, D. P. (2019). Análisis general del enfoque IOT en redes (Doctoral dissertation, Editorial Universitaria San Mateo).
 Rueda, J. S., & Portocarrero, J. M. T. (2017). Similitudes y diferencias entre Redes de Sensores Inalámbricas e Internet de las Cosas: Hacia una postura clarificadora. Revista colombiana de computación, 18(2), 58-74.






























