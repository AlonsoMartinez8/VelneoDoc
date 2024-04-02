# VELNEO DOC
**Velneo** es un *software ERP para PYMES*.

En éste artículo se proporcionará una **guía** para comenzar a crear **soluciones desde cero**.

La guía está **basada en el [tutorial oficial](https://www.youtube.com/watch?v=hyis3F4YMaY&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&pp=iAQB) de Velneo** y aportará un **contenido esquematizado** que ayudará a ubicar rápidamente las respuestas a nuestras dudas.

Para ejemplificar, estaremos creando una *App* que gestiona las **facturas de venta de una empresa**.
### Requisitos
- Estar registrados en **miVelneo**
> En primer lugar nos registraremos en **miVelneo**.
- Velneo Server
> Tras ello, en el apartado de **Velneo Cloud**, crearemos un nuevo servidor.
- Datos de ejemplo
> Necesitaremos descargar los **datos de ejemplo** adjuntados en el repositorio.
- Velneo VClient
- Velneo VDevelop
- Velneo VAdmin
> Por último, descargaremos los componentes software necesarios en el apartado de **Descargas**.
### Índice
1. Administrar y crear usuario
2. Editar y crear solución
3. Crear tablas y procesos de importación
4. Crear esquema e iconos
5. Crear relaciones de tablas
6. Generar la interfaz y ejecutar la aplicación
7. Configurar contenidos iniciales de campos
8. Crear actualizaciones para realizar cálculos
9. Ajustar rejilla de facturas
10. Ajustar formulario de facturas
11. Crear configuración con variables globales
12. Ajustar interfaz de artículos
13. Ajustar interfaz de clientes
14. Tabla estática de formas de pago
15. Ajustar interfaz de suscripciones
16. Ajustar interfaz de líneas
17.  Crear tabla de años y resolver el número de factura
18. Alta de año si no existe
19. Crear estadísticas por año
20. Crear estadísticas por cliente y año
21. Crear gráficos top 5 clientes y ventas por año
22. Crear informe de factura
23. Añadir verificaciones a formularios
24. Eliminar las líneas antes de eliminar la factura
25. Variación de precio de artículos seleccionados
26. Generar facturas de suscripciones
27. Crear rejillas avanzadas y copiar datos al portapapeles
28. Crear multivista de clientes
29. Crear búsqueda de facturas por cliente y entre fechas
30. Crear lupa de facturas pendientes de cobro
31. Añadir cobro de facturas seleccionadas
32. Arrancar con las facturas
33. Ejecutar en web

## 1. Administrar y crear usuario
> [Administrar y crear usuario - Tutorial oficial](https://www.youtube.com/watch?v=8OvJ26DkngM&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=5&pp=iAQB)

Conectar a VAdmin con el usuario **velneo**.
Tras ello, en el apartado usuarios pulsar en '**+**':
- Rellenar campos: *nombre*, *mail*...
- Determinar **rol** del usuario en **estilos**: (*supervisor*, *cuenta desactivada*...)
- Asignar a un **grupo** (opcional)
## 2. Editar y crear solución
> [Editar y crear solución - Tutorial oficial](https://www.youtube.com/watch?v=fLT8Cb2u8Vg&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=6&pp=iAQB)

1. Conectar con el servidor
2. Crear solución
	- Establecer nombre de la solución
	- Check en compartido para poder reutilizar la solución
	- Plantilla de datos, aplicación o datos y aplicación
	-  Idiomas
3. Eliminar objetos predeterminados del proyecto de aplicación
## 3. Crear tablas y procesos de importación
> [Crear tablas y procesos de importación - Tutorial oficial](https://www.youtube.com/watch?v=dIlU1iYypSk&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=8&pp=iAQB)

1. Abrir proyecto de **datos**
2. **Importador de tablas**
3. **Tipo** de fichero, **separador** y **formato** numérico
4. Seleccionar **fichero** a importar
5. **Check** en *Al importar, preguntar si se vacía la tabla*
6. Revisar *nombre*, *tipo*, *tamaño* de los campos
7. Revisar si **indexar** y añadir a *trozos* y/o *palabras*
> Al indexar por **trozos**, indexa por tercios : 
> Julio -> [Jul, uli, lio]

>Al indexar por **palabras**, indexa cada palabra:
>Julio Gómez -> [Julio, Gómez]
## 4. Crear esquema e iconos
> [Crear esquema e iconos - Tutorial oficial](https://www.youtube.com/watch?v=OtQl9py5CVk&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=9&pp=iAQB)
## 5. Crear relaciones de tablas
> [Crear relaciones de tablas - Tutorial oficial](https://www.youtube.com/watch?v=-P7tPOB-6eQ&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=10&pp=iAQB)
## 6. Generar la interfaz y ejecutar la aplicación
> [Generar la interfaz y ejecutar la aplicación - Tutorial oficial](https://www.youtube.com/watch?v=7rhx_Qej0RU&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=11&pp=iAQB)
## 7. Configurar contenidos iniciales de campos
> [Configurar contenidos iniciales de campos - Tutorial oficial](https://www.youtube.com/watch?v=MrCyk5G5F4s&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=12&pp=iAQB)
## 8. Crear actualizaciones para realizar cálculos
> [Crear actualizaciones para realizar cálculos - Tutorial oficial](https://www.youtube.com/watch?v=F0ZDD-wIOUY&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=13&pp=iAQB)
## 9. Ajustar rejilla de facturas
> [Ajustar rejilla de facturas - Tutorial oficial](https://www.youtube.com/watch?v=uQYpqe14Sao&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=14&pp=iAQB)
## 10. Ajustar formulario de facturas
> [Ajustar formulario de facturas - Tutorial oficial](https://www.youtube.com/watch?v=wjzv8PItXWs&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=15&pp=iAQB)
## 11. Crear configuración con variables globales
> [Crear configuración con variables globales - Tutorial oficial](https://www.youtube.com/watch?v=fTD_r8WUVlw&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=16&pp=iAQB)
## 12. Ajustar interfaz de artículos
> [Ajustar interfaz de artículos - Tutorial oficial](https://www.youtube.com/watch?v=TEl3v5vluig&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=17&pp=iAQB)
## 13. Ajustar interfaz de clientes
> [Ajustar interfaz de clientes - Tutorial oficial](https://www.youtube.com/watch?v=PRZaNKrsjq0&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=18&pp=iAQB)
## 14. Tabla estática de formas de pago
> [Tabla estática de formas de pago - Tutorial oficial](https://www.youtube.com/watch?v=Y5eGGpQROKs&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=19&pp=iAQB)
## 15. Ajustar interfaz de suscripciones
> [Ajustar interfaz de suscripciones - Tutorial oficial](https://www.youtube.com/watch?v=TVVMPRxLoHY&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=20&pp=iAQB)
## 16. Ajustar interfaz de líneas
> [Ajustar interfaz de líneas - Tutorial oficial](https://www.youtube.com/watch?v=PkptSrO__Gk&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=21&pp=iAQB)
## 17.  Crear tabla de años y resolver el número de factura
> [Crear tabla de años y resolver el número de factura - Tutorial oficial](https://www.youtube.com/watch?v=qcWTNegCwmg&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=22&pp=iAQB)
## 18. Alta de año si no existe
> [Alta de año si no existe - Tutorial oficial](https://www.youtube.com/watch?v=Jc2JY2cY8UI&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=23&pp=iAQB)
## 19. Crear estadísticas por año
> [Crear estadísticas por año - Tutorial oficial](https://www.youtube.com/watch?v=fBCEeFw9AME&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=24&pp=iAQB)
## 20. Crear estadísticas por cliente y año
> [Crear estadísticas por cliente y año - Tutorial oficial](https://www.youtube.com/watch?v=N80HVHrmRyQ&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=25&pp=iAQB)
## 21. Crear gráficos top 5 clientes y ventas por año
> [Crear gráficos top 5 clientes y ventas por año - Tutorial oficial](https://www.youtube.com/watch?v=MdSMDVrqFQE&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=26&pp=iAQB)
## 22. Crear informe de factura
> [Crear informe de factura - Tutorial oficial](https://www.youtube.com/watch?v=Daa72YpGKFo&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=27&pp=iAQB)
## 23. Añadir verificaciones a formularios
> [Añadir verificaciones a formularios - Tutorial oficial](https://www.youtube.com/watch?v=xyw3zPBoLh8&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=28&pp=iAQB)
## 24. Eliminar las líneas antes de eliminar la factura
> [Eliminar las líneas antes de eliminar la factura - Tutorial oficial](https://www.youtube.com/watch?v=nvZ44q1uzIY&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=29&pp=iAQB)
## 25. Variación de precio de artículos seleccionados
> [Variación de precio de artículos seleccionados - Tutorial oficial](https://www.youtube.com/watch?v=WpbQaQfreHI&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=30&pp=iAQB)
## 26. Generar facturas de suscripciones
> [Generar facturas de suscripciones - Tutorial oficial](https://www.youtube.com/watch?v=LrXV1JHpeyo&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=31&pp=iAQB)
## 27. Crear rejillas avanzadas y copiar datos al portapapeles
> [Crear rejillas avanzadas y copiar datos al portapapeles - Tutorial oficial](https://www.youtube.com/watch?v=nWYt0Y-uzKc&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=32&pp=iAQB)
## 28. Crear multivista de clientes
> [Crear multivista de clientes - Tutorial oficial](https://www.youtube.com/watch?v=w3MDo3Jp0uM&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=33&pp=iAQB)
## 29. Crear búsqueda de facturas por cliente y entre fechas
> [Crear búsqueda de facturas por cliente y entre fechas - Tutorial oficial](https://www.youtube.com/watch?v=UwJ9N_am_w4&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=34&pp=iAQB)
## 30. Crear lupa de facturas pendientes de cobro
> [Crear lupa de facturas pendientes de cobro - Tutorial oficial](https://www.youtube.com/watch?v=npjtxiUn0f0&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=35&pp=iAQB)
## 31. Añadir cobro de facturas seleccionadas
> [Añadir cobro de facturas seleccionadas - Tutorial oficial](https://www.youtube.com/watch?v=hyr6YbUlR7o&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=36&pp=iAQB)
## 32. Arrancar con las facturas
> [Arrancar con las facturas - Tutorial oficial](https://www.youtube.com/watch?v=aFnaOK3Lbvs&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=37&pp=iAQB)
## 33. Ejecutar en web
> [Ejecutar en web - Tutorial oficial](https://www.youtube.com/watch?v=eFJB_X99mwo&list=PL-bVpgNOlmiqRMSzdjXg3oLHsUymwkKfX&index=38&pp=iAQB)
