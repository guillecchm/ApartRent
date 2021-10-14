# ApartRent
## Descripción del problema
Los propietarios de apartamentos vacacionales suelen tener dudas acerca de cual es el mejor momento para poner su inmueble en alquiler. Existen numerosos factores a tener en cuenta, como la cantidad de clientes que pueden demandar su inmueble en un periodo concreto, tiempo de estancia de los inquilinos o el precio por persona y día que le permita ser competitivo con respecto a otros inmuebles cercanos.

Por otra parte, en lo que respecta a los clientes es habitual que tengan dudas con respecto a que inmueble alquilar o el momento óptimo para realizarlo. Tienen que tener en cuenta aspectos como el precio de los inmuebles, fechas, disponibilidad, actividades que quieren desarrollar, como los monumentos o sitios que visitar y la cercanía a una plaza de aparcamiento que le resulte lo más asequible posible. Otra incertidumbre usual es la calidad del inmueble y tratamiento del arrendador. Lo mismo sucede con los arrendadores, los cuales desean tener la seguridad de que los arrendatarios se comportarán de forma adecuada y cumplirán lo pactado.

## Solución propuesta
Para solucionar la problemática anteriormente expuesta, se propone el desarrollo de una plataforma web que ofrezca la siguiente funcionalidad para los diferentes tipos de usuarios:

* Arrendadores:
    * Publicar un anuncio sobre un inmueble para alquilar.
    * Obtener información sobre el potencial interés de los clientes basandose en las búsquedas recientes de clientes o alquileres de inmuebles cercanos, así como el análisis del histórico anual para predecir los periodos de mayor actividad.
    * Obtener una aproximación sobre el precio por persona/día que permita al inmueble ser competitivo con respecto a su entorno y maximizar el beneficio.
    * Obtener información sobre el periodo de tiempo de alquiler recomendado, de tal forma que se pueda optimizar el ratio beneficio/arrendatario durante el periodo vacacional. Esta información se calcula en base a los potenciales alquileres que se puede producir a lo largo del periodo vacacional y los precios que se pueden llegar a pagar en cada uno de ellos.
    * Realizar una valoración de los arrendatarios. Estas valoraciones influenciarán sobre posteriores alquileres para otros arrendadores de la plataforma.
* Arrendatarios:
    * Realizar una búsqueda que filtre inmuebles en base a intereses personales, como el lugar, fechas en la que realizar el viaje, actividad turística, actividades que realizar, plazas de aparcamiento cercanas al inmueble o las valoraciones del inmueble y el arrendador.
    * Obtener información sobre la disponibilidad de los inmuebles en los que estaría interesado alquilar para el periodo concreto. Este cálculo se basa en alquileres de periodos anteriores, alquileres realizados por la zona históricamente y la cantidad de búsquedas que se estén realizando en ese instante concreto.
    * Realizar una oferta por la reserva del inmueble. El arrendador establece un precio/día y periodo máximo de estancia en el propio anuncio que publica, pero se le permite al cliente que realice una oferta alternativa que será valorada por el arrendador.
    * Realizar una valoración del arrendador e inmueble. Esta valoración permite a otros usuarios conocer diferentes aspectos relevantes previo al alquiler o priorizar las búsquedas que realicen dentro de la plataforma.

En lo que respecta al sistema de ofertas, el arrendador dispone de un buzón por cada uno de los inmuebles. Las ofertas estarán priorizadas en base al precio/día que los arrendatarios están dispuestos a pagar y la valoración de estos, de tal forma que aquellos que ofrezcan una oferta mayor y tengan buenas valoraciones de arrendadores anteriores sean los primeros en ser atendidos para obtener el inmueble.

# Documentación adicional
* [Configuración inicial del repositorio](docs/repo/github_config.md), en el que se describe el proceso de configuración de claves, configuración del nombre y correo para realizar los commits, se completa la información del perfil y se establece la autenticación en dos pasos para incrementar la seguridad de la cuenta.

* Licencia utilizada: [GPL-3.0](LICENSE).