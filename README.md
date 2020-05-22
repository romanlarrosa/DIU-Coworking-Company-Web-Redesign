# DIU-Coworking-Company-Web-Redesign
 Repositorio dedicado a la realizacion del ejercicio entregable de DIU basado en el rediseño de un portal web de una empresa de coworking

:boy:  [ Román L. L](http://github.com/romanlarrosa)    :octocat:

---
## 1. Introducción

Un espacio de coworking es una oficina en la que profesionales de todo tipo pueden alquilar ciertos recursos para organizar reuniones, eventos, o simplemente desarrollar su actividad en un ambiente de trabajo. Apostar por el uso de espacios de coworking es una tendencia en alza, puesto que aquellos trabajadores que no precisan de una oficina concreta tales como autónomos o freelances, pueden optar por un espacio de trabajo económico y muy lucrativo.
Una importante ventaja indirecta que se obvserva del uso de espacios de coworking es la gran diversidad de profesionales de los que te puedes ver rodeado, y que en mayor o en menor medida se convierten en tus compañeros, aportando un gran valor ya que en estos espacios el intercambio de ideas, y los puntos de vista diferentes sobre una activdad en concreto se convierten en el nexo de unión de todos los trabajadores, que ven sus proyectos o ideas mejoradso en gran medida por este importante punto de vista externo.

Durante las siguientes líneas, haré un análisis y propondré algunas mejoras de las funcionalidades o la usabilidad de la web de alguna empresa de coworking de Granada, de manera resumida y compacta.

La empresa elegida es [Cubikate](https://cubikate.es/), un espacio de coworking y oficina virtual situado en el centro de la ciudad de Granada. Me ha parecido que tienen una localización muy competitiva y una web que en principio parece muy atractiva, y quiero ver si tiene características fácilmente mejorables.



---
## 2.1 Análisis competitivo

Cuando queremos mejorar cualquier tipo de producto ya existente, es muy importante fijarse en qué cosas está haciendo bien la competencia, ya que al no tratarse de una idea original y estar siendo ya desarrollada por multitud de empresas, es fácil ver qué cosas están haciendo el resto de empresas bien para partir de un mismo nivel, antes de aportar nuevas ideas que den valor a nuestro producto.

Para ello voy a hacer una comparativa con algunas empresas de coworking, tanto de granada (principales competidores) como del resto de España, ya que podrían aportar información muy importante de cómo desarrollar este tipo de actividad que empresas locales no estén explotando.

Una herramienta interesante para encontrar locales que ofrecen el servicio de oficinas coworking es [Coworking Spain](https://coworkingspain.es/), web desde la cual podemos buscar este tipo de servicio basándonos en la ubicación.

Las empresas que he elgido para comparar sus servicios con los de [Cubikate](https://cubikate.es/) son **[ErranT](https://www.errant.es/es/)**, en Granada, y **[LaRaum](https://www.laraum.com/)** en Madrid.

La elección de estos dos servicios ha sido por presentar características muy diferentes pero que entran dentro de la filosofía de [Cubikate](https://cubikate.es/). Mientras que [ErranT](https://www.errant.es/es/) es una empresa que se enfoca en llegar a un número grande de personas y mantener un espacio con muchos puestos, [LaRaum](https://www.laraum.com/) ofrece un servicio más "premium" con unos espacios más amplios y una estética más minimalista y elegante, sobre todo porque una de las opciones que ofrece son salas de reuniones y pretenden dar una imagen muy profesional a los usuarios que hagan uso de estas para tener por ejemplo reuniones con clientes potenciales.

Estas dos características principales que señalo en estas dos empresas son características de las que [Cubikate](https://cubikate.es/) puede sacar provecho puesto que sus instalaciones le permiten en mayor o menor medida el desarrollo de ambas.

| Utilidades / Funcionalidades  | [erranT] | [LaRaum] | [Cubikate]
|--|--|--|--|
|Oficina virtual                |❌	 |❌     |✔️
|Domiciliación comercial        |❌	 |❌     |✔️
|Version web móvil              |✔️	  |✔️     |✔️
|Alquiler por dias              |✔️	  |✔️     |No se sabe
|Alquiler puesto flexible       |✔️	  |✔️     |No se sabe
|Alquiler puesto fijo           |❌ 	 |✔️     |No se sabe
|Precios visibles               |✔️	  |✔️     |❌
|Chat online                    |❌	 |❌     |✔️
|FAQ                            |❌	 |❌     |❌
|Contacto directo sin formularios|✔️  |✔️     |✔️
|Servicios 24/7                 |❌ 	 |✔️     |✔️
|Comunidad                      |✔️	  |✔️     |❌
|Opiniones de usuarios          |✔️	  |❌     |✔️
|Galería de fotos               |✔️	  |✔️     |✔️
|Desglose de servicios          |✔️	  |✔️     |No se detallan todos
|Accesibilidad                  |❌	 |❌     |❌
|Idiomas                        |✔️	  |❌     |❌

Como podemos ver, Cubikate ofrece servicios distintivos a las demás alternativas de coworking. Sin embargo, muchas de las características básicas no las ofrece o lo hace de forma indirecta a través de correo electrónico o llamadas telefónicas (precios, tarifas, etc.).

## 2.2 Interaccion con los usuarios

Para esta sección utilizaré a una de las personas ficticias que fueron creadas durante el desarrollo del proyecto de servicio colaborativo de la parte práctica de la asignatura DIU. La persona es Guillermo y presenta las siguientes características:

![](/img/Plantilla_Guillermo.png)

### Journey map:
Cuando Guillermo vuelve a Granada para visitar a sus padres, necesita seguir trabajando en la distancia, pero en su casa no dispone de conexión a internet ni de las comodidades y los servicios que necesita para desempeñar correctamente su actividad. 

Es por ello que, unos días antes de viajar a la ciudad, se dispone a buscar una oficina de coworking, con las que está familiarizado ya que en Madrid las ha usado alguna vez.

Guillermo encuentra la web de Cubikate, y observa que se encuentra en una localización muy interesante. Los servicios que ofrecen en cuanto a instalaciones y herramientas son justo los que necesita para el tiempo que estará en la ciudad. 

Cuando intenta ver las tarifas para comparar con otras opciones de la ciudad, Guillermo se encuentra con que los precios no son visibles en la web, y ni siquiera puede ver las diferentes tarifas existentes y sus condiciones. Por tanto, tampoco se puede reservar un puesto de manera online para los días que él necesita.

Tras sopesar las distintas opciones, decide contactar con la oficina a través del teléfono, porque no puede permitirse no tener un lugar de trabajo durante los días que estará en Granada.

Guillermo encuentra que aunque el servicio que ofrecen como coworking es espléndido y se siente muy cómodo en el espacio, el proceso para alquilar un puesto le ha sido muy tedioso, y en un mundo digital como el que vivimos debería de poder haber alquilado un puesto de manera online, y conocer la oferta de tarifas de la empresa.

## 2.3 Usabilidad

De manera resumida, la web de Cubikate funciona de manera correcta. Sin embargo encuentro algunos errores básicos como la ocultación de información a los usuarios (precios, tarifas...), la poca interacción que el usuario puede hacer con la web (hay muy poca información disponible y no existe un apartado de preguntas frecuentes. Todas las cuestiones hay que resolverlas vía telefónica o contactando a través de formularios o correo electrónico). Estos aspectos, aunque la web sea atractiva y fácil de entender, hacen que el usuario busque otras alternativas que le faciliten esta información antes de tener que contactar de manera directa con los responsables del sitio.

No hay un mapa del sitio claro, pero no se me hace necesario dada la simplicidad del sitio. Aunque también referente a esta simplicidad, todos los menús y el contenido de cada página deberían estar mejor distribuidos para tener una vista general que aporte más información en un primer vistazo a la web. Para ofrecer una información tan escuenta y simple, considero que ésta no se encuentra muy bien distribuida a través de las diferentes secciones de la web

Una parte interesante es la referente a la ayuda una vez estamos en la web. Aunque no se incluye una página con las preguntas frecuentes, si que disponemos de un chat online en el que consultar lo que necesitemos. Me parece una funcionalidad muy atractiva pero si se ofrece este servicio hay que tener en cuenta que debe estar siempre activo, o indicar en algún sitio qué horario de operabilidad tiene y cual es el tiempo medio de respuesta.

---
## 3. UX Design

### 3.1 Feedback capture grid

#### Interesante / relevante:
* Chat online para responder dudas
* Servicio de oficina online con domiciliación fiscal
* Web muy simple y amigable

#### Críticas
* Interacción unicamente a través de formulario
* No se describen las tarifas ni los servicios asociados
* No hay posibilidad de hacer una reserva online

#### Preguntas
* ¿Qué tarifas hay disponibles?
* ¿Qué servicios y a que precios se ofertan?
* ¿Cómo son las salas de reuniones?

#### Nuevas ideas
* COMUNICACIÓN: Mostrar información sore las tarifas y los precios de éstas. Añadir más idiomas a la web.
* NAVEGACIÓN: Realizar una sección en el menú para detallar los servicios, qué tarifas los incluyen y los precios de las mismas
* ENGAGEMENT: Posibilitar la adquisición de las distintas tarifas a través de internet en los horarios que aún quedan disponibles.

### 3.2 Propuesta de valor

La propuesta de valor se basaría en:
* La inclusión de un espacio en la web para mostrar las tarifas disponibles
* Realizar la adquisición de las tarifas y el alquiler de los espaicos disponibles según el horario.
* Traducir la web a diferentes idiomas, como mínimo el inglés.

### 3.3 Sitemap

El sitemap del sitio quedaría tal que así, incluyendo las secciones de tarifas y de reserva:
![](/img/sitemap.png)

### 3.4 Labelling

El labelling del sitio quedaría igual, incluyendo únicamente los términos:

|Término|Descripción|
|--|--|
|Tarifas| Los diferentes packs de servicios disponibles para su adquisición, y el coste de los mismos
|Alquiler|Pasarela de pago para adquirir una de las tarifas o el uso de la sala de reuniones.

### 3.5 Wireframes
Los wireframes de las dos paginas que necesitariamos para implementar las nuevas funcionalidades serían así:

![](/img/tarifas.png)

![](/img/alquiler.png)

## 4. Decisiones de diseño

El diseño de la web y su iconografía son constistentes y están adaptados a la actualidad dando una impresión moderna y elegante, por lo que las nuevas funcionalidades seguirían estos mismos patrones y guidelines para integrarse de manera correcta en el sitio web.

Cubikate ya tiene trabajada su imagen de marca, y estas nuevas funcionalidades únicamente tienen que integrarse para formar parte del diseño que ya hay implementado.







[Cubikate]:(https://cubikate.es/)
[Coworking Spain]:(https://coworkingspain.es/)
[ErranT]:(https://www.errant.es/es/)
[LaRaum]:(https://www.laraum.com/)