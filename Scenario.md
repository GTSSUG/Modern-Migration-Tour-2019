![Header](images/header.jpg)

# PASS Modern Migration Tour - Escenario de Modernizacion


**NOTA:** Si aun no has preparado tu maquina para el laboratorio, por favor sigue la [guia aqui](Workshop.md).


Eres el DBA senior para Contoso Inc. Tu y tu equipo de DBAs han sido asignados con el proyecto de migracion para la aplicacion AdventureWorks desde SQL Server 2008 R2 hacia SQL Server 2017.
Dado que el fin de soporte para SQL Server 2008 esta cerca, es necesario realizar este proyecto rapida y eficientemente.

Tomando en cuenta que la Aplicacion AdventureWorks es la que mas ganancias genera a la compañia, el negocio cuenta con su habilidad para poder planear una estrategia de modernizacion confiable, y llevarla a cabo en un tiempo rasonable y a su vez minimizando los riesgos al desempeño y estabilidad de la aplicacion.

---
La aplicacion AdventureWorks actualmente incluye una base de datos en un servidor SQL Server 2008 R2 con un Compatibility Level de 100.

Esta base de datos debe de ser actualizada hacia SQL Server 2017 sin ningun impacto a la funcionalidad de la aplicacion y con un desempeño igual o mejor que en la version anterior.

Idealmente, una vez la base de datos sea migrada a SQL Server 2017 y la aplicacion sea totalmente funcional, el Compatibility Level de la base de datos debe de ser actualizado a 140 para que pueda hacer uso de las mejoras disponibles en esta version.

Para alcanzar este objetivo, se tienen disponibles las siguientes herramientas:

- Data Migration Assistant (DMA)
- Database Experimentation Assistant (DEA)
- Query Tuning Assistant (QTA), el cual es parte de SQL Server Management Studio 18.0 o superior
- Todas las nuevas funcionalidades de SQL Server 2017 que puedan ser de utilidad (Query Store, nuevas DMVs, Intelligent Query Processing, nuevos query hints etc.)


---
El equipo mas exitoso sera aquel que sea capaz de migrar la base de datos hacia SQL Server 2017 y el compatibility level de 140 con el mayor grado de mejora de desempeño, el cual sera medido con el OStress workload.

La herramienta debe de completarse sin errores.