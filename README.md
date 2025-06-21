# Data-Science-2
Proyecto de ciencia de datos para aplicar lo aprendido en el curso de coderhouse
## Indice
  1.  Introduccion
  2. Analisis descriptivo y EDA (exploratory data analysis)
  3. Analisis de cluster
  4. Prediccion del churn de clientes
  5. Acciones de retención

## Introduccion
A partir de una base de datos de clientes de una empresa de telecomunicaciones, se analizará su comportamiento para predecir la factibilidad de que permanezcan o cambien de proveedor de servicios.
El análisis tendrá en cuenta toda la información relevante de los clientes, y se segmentará su comportamiento, de manera de generar acciones de retención especificas para cada subgrupo.
Ademas, se buscará determinar las causas por las que los clientes dejan de contratar los servicios, pudiendo identificar interes en nuevos servicios, presencia de nuevos competidores, o mejoras en sistemas comerciales, entre otros.
El dataset contiene los grupos cualitativos y cuantitativos de informacion que se detallan a continuación.

**Fuente de datos utilizada:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn
**Demografía de los clientes:**   Genero, Rango de edad, si tienen pareja o dependientes

**Servicios a los que está suscripto:**
telefonia, multiples lineas, internet, seguridad online,backup online, proteccion para los dispositivos, soporte tecnico, TV por streaming y peliculas

**Tipo de cuenta:** Clientes que dejaron la compañia durante el ultimo mes (el campo se llama churn), Tipo de contrato (mensual, por 2 años)
, si está suscripto a la factura electronica, Metodo de pago que utiliza

### Hipotesis planteadas
*  ¿Por qué los clientes dejan la compañia?   
Determinar si la decision de dejar la compañia, está relacionada con un alto costo de los servicios, si la competencia tiene mejores ofertas, si estpa relacionado con una mala experiencia con el area de atención al cliente, o identificar si existen otras razones menos aparentes.
*   ¿Como detectar a un cliente a punto de dejar la compañia?
Monitorear si está utilizando los servicios contratados, si hizo reclamos, analizar la oferta de la competencia
*   ¿Cómo evitar que los clientes dejen la compañia? Cuando detectamos a alguien que cumple con el perfil de cliente en riesgo de abandonar la compañia, se deben implementar acciones de retención. Es sabido que retener a un cliente, es mas economico y genera mayores ganancias, que sumar a un cliente. Las acciones de retencion pueden ser ofrecerle descuento en la suscripcion a sus servicios o mejorar el servicio de atencion al cliente.
