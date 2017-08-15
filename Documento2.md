Atributos de calidad seleccionados:
QA1: _Disponibilidad de servicio_ Estudiante: _Jonathan Zapata Castaño_
QA2: _Seguridad de la Aplicación_ Estudiante: __________________________
QA3: ____________________________ Estudiante: __________________________

* QA1:
    
# Marco de referencia:

a. ¿Qué es?

- La alta disponibilidad del servicio es la capacidad de un sistema de soportar gran número de peticiones concurrentes sin perder su habilidad de reacción. La alta disponibilidad es crítica para esta capa, pues es donde se realizan las operaciones concernientes a la lógica del negocio, y es la única que tiene acceso a los datos, por lo que es crucial propiciar un uptime lo más alto posible, el cual se mide en concurrencia de usuarios por segundo, y por lo general es del 99.xxx %, y la cantidad de 9's en la parte decimal depende principalmente de las necesidades del negocio.

b. ¿Qué patrones se pueden emplear?

- Según los patrones de disponibilidad definidos por [Microsoft](https://docs.microsoft.com/en-us/azure/architecture/patterns/category/availability), se pueden listar al menos 3: Health Endpoint Monitoring, Queue-Based Load Leveling y Throttling

| Patrón | Resumen |
|:--:|:--:|
| Health Endpoint Monitoring | |
| Queue-Based Load Leveling | |
| Throttling | | 

c. Especificación mediante escenarios
d. ¿Qué tácticas se pueden emplear?
e. Qué herramientas se pueden utilizar para lograrlo

* QA2:

a. ¿Qué es?

- El atributo de seguridad se refiere a como la aplicación es protegida de perder o suministrar información a equipos, personas o servicios no autorizados por la aplicación, a través de este atributo de calidad se busca que la aplicación tenga una alta probabilidad de que sus activos (datos e información) resista a los ataques de hackers. En general dentro de este atributo se deben de tener en cuenta siempre tres simples atributos que son:
    -	Confidencialidad: el acceso a los activos del sistema está limitado a usuarios autorizados.
    -	Integridad: los activos del sistema sólo pueden ser borrados o modificados por usuarios autorizados.
    -	Disponibilidad: el acceso a los activos en un tiempo razonable está garantizado para usuarios autorizados.

d. ¿Qué tácticas se pueden emplear?

-	Autenticación: los clientes de nuestras aplicaciones o servicios deben ser identificados de forma única, sean usuarios finales,         otros servicios o computadoras externas.
-	Autorización: no solo es necesario saber quiénes acceden a nuestros activos, también es necesario establecer que es lo que pueden       hacer con ellos. Un nivel de autorización dado determina que tipo de operaciones o transacciones puede efectuar un cliente dado         sobre un recurso dado.
-	Registro y Auditoria: luego de efectuada una operación, es importante que esta sea registrada adecuadamente, en particular es           esencial si queremos evitar el repudio de transacciones efectuada por un cliente.
