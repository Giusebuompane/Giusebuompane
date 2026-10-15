# 👋 Hola, soy Giuseppe Buompane

**Analista de datos (Data Engineering & BI)** · ETL · Migraciones de datos · SQL · Python · Power BI · Snowflake · Microsoft Fabric · IA aplicada a datos (agentes, MCP, automatización)

Llevo los datos de principio a fin: los extraigo de donde estén (ERP, bases de datos, APIs, ficheros), los transformo con Python y SQL, los cargo donde tienen que estar y los convierto en informes que se actualizan solos. Me gusta entender bien el modelo de origen antes de tocar nada y no doy un dato por bueno hasta que cuadra con la realidad.

Trabajo a diario con **agentes de IA** para automatizar ese trabajo: analizar modelos de datos que no conozco, preparar migraciones, escribir y revisar ETL, consultas SQL y medidas DAX, y validar los resultados. La IA me hace ir más rápido, pero cada cifra la sigo comprobando contra los datos reales.

He trabajado con empresas de sectores muy distintos: salud y estética, peluquería, comercio electrónico, hostelería y restauración, asesoría contable y financiera, y recursos humanos. Cada proyecto me obliga a entender un negocio y un modelo de datos nuevos.

En cada proyecto me reúno con los clientes para entender qué necesitan, acordar los KPI y explicar los resultados a personas que no son técnicas. Antes de dedicarme a los datos trabajé más de diez años en atención al cliente y operaciones en entornos internacionales, soy licenciado en Economía y hablo italiano, español, inglés y portugués, así que trabajo con clientes de varios países sin problema.

### En cifras

- **Más de 60 migraciones de datos** de clínicas desde **15 sistemas de origen distintos** (SQL Server, MySQL, Access, Excel, XML, JSON y exports de aplicaciones en la nube).
- La migración más grande: **12.000 clientes, 48.000 notas de historia clínica y 85.000 documentos y fotos**.
- **ETL en producción con actualización diaria** para el dashboard financiero de una asesoría que lleva unas 500 empresas.
- **ETL e informes de Power BI para empresas de varios sectores**, moviendo los datos entre bases de datos y servidores: una cadena de restaurantes (ventas y reservas desde la API de CoverManager, con informes semanales y mensuales) y un grupo de clínicas y peluquerías con venta en Amazon (un informe de muchas páginas con los KPI de ventas, clientes, agenda y stock).
- **Una base de conocimiento para agentes de IA**, organizada en 4 capas, con 29 reglas de protocolo aprendidas de errores reales y 15 sistemas de origen documentados. Diseñé yo el proceso de automatización y ahora lo usan también mis compañeros del equipo de migraciones.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Firebird](https://img.shields.io/badge/Firebird-F40F02?style=flat)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-0078D4?style=flat)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-000000?style=flat)

---

## 🚀 Lo que hago

- **ETL y bases de datos analíticas.** Diseño ETL que extraen datos de ERP y software de gestión (Sage, Holded, Microdata, Factorial, entre otros), los transforman con Python y SQL y los cargan en bases de datos SQL Server o MySQL que diseño y creo desde cero, en el mismo servidor del cliente o en otro. Las dejo automatizadas con Jobs de SQL Server o tareas programadas.
- **Power BI con varias fuentes.** Construyo modelos que combinan bases de datos, APIs y Excel en un mismo informe, por ejemplo ventas de tienda física y de marketplaces como Amazon. Diseño los KPI con negocio: comparativas con el año anterior, ticket medio, clientes nuevos y recurrentes, vida del cliente, canales de captación, ocupación de cabinas por día y hora, previsión de cierre de mes, acumulados del año, cobros frente a ventas, stock y rentabilidad por producto y proveedor. Escribo las medidas en DAX, las valido contra las cifras reales y publico los informes en Power BI Service con gateway de datos y refresco automático.
- **Integración de APIs.** Conecto APIs REST (Holded, Factorial, CoverManager y otras) con paginación y autenticación por API key u OAuth2, y llevo los datos a una base de datos para analizarlos.
- **Migraciones de datos.** Paso datos de un sistema a otro: análisis de un modelo que no conozco, mapeo de catálogos, carga con tablas de staging y backup previo, migración de documentos y fotos a la nube y verificación final.
- **Automatización con IA.** Las primeras migraciones y ETL las hice a mano, de principio a fin. A partir de esa experiencia he escrito la documentación del proceso (cómo analizo un modelo de origen, cómo mapeo campos y catálogos, cómo cargo con staging y cómo valido) y la he convertido en skills e instrucciones para agentes de IA. Además, en cada proyecto mantengo una memoria en Markdown con la información que el agente necesita: el contexto del cliente, el modelo de datos, las reglas de negocio, las decisiones tomadas y lo que queda pendiente. Ahora los agentes siguen ese mismo método y hacen la parte repetitiva: exploran el modelo de origen, proponen el mapeo y generan los scripts de extracción, transformación y carga. Yo reviso cada mapeo y valido el resultado con comprobaciones deterministas: recuentos de filas, sumas de control y cuadres contra el origen. En Power BI hago lo mismo: el agente consulta el modelo semántico por MCP, ejecuta consultas DAX y documenta el modelo, y yo valido las cifras. Este proceso de automatización lo diseñé yo, y ahora lo usan también mis compañeros del equipo para sus propias migraciones.
- **Análisis exploratorio y estadístico.** Hago EDA y estudios estadísticos para responder preguntas concretas: pruebas de normalidad, ANOVA y Kruskal-Wallis con pruebas post-hoc, correlaciones y regresión. Presento las conclusiones con visualizaciones claras, en Power BI o en Python, pensadas también para perfiles no técnicos.
- **Servidores.** Preparo el entorno en el servidor del cliente (SQL Server, Python, gateway de datos, acceso remoto) y resuelvo lo que surja por el camino: drivers, DNS, permisos o firewall.
- **Trabajo en equipo.** He trabajado en equipos de analistas con metodología ágil: sprints, tablero Kanban, retrospectivas y control de versiones en GitHub.

---

## 🤖 IA aplicada a datos

Trabajo con **Claude Code** como entorno de desarrollo con agentes y lo adapto a cada tipo de proyecto:

- **Skills.** Creo skills propias con las instrucciones y los pasos de tareas que repito en muchos proyectos (por ejemplo, el análisis de un modelo de origen o la validación de una migración), para que el agente las haga siempre igual.
- **Agentes y subagentes.** Reparto el trabajo entre subagentes especializados que trabajan en paralelo: uno explora el código o la base de datos, otro escribe y otro revisa. Así el agente principal no se satura de contexto y cada tarea queda acotada.
- **MCP (Model Context Protocol).** Conecto el agente a las herramientas reales con servidores MCP: el de modelado de Power BI para leer y modificar el modelo semántico y ejecutar DAX, bases de datos y el navegador (Playwright) para probar aplicaciones web.
- **Plugins y hooks.** Instalo y configuro los plugins que necesita cada proyecto y uso hooks para automatizar comprobaciones antes y después de cada acción del agente.
- **Memoria de proyecto.** Junto con las skills y los agentes, creo en cada proyecto una memoria en Markdown y unas instrucciones de proyecto (`CLAUDE.md`) con la información necesaria: contexto del cliente, origen y modelo de datos, criterios de cálculo validados con negocio, decisiones tomadas y tareas pendientes. Así el agente retoma el trabajo en cualquier sesión sin tener que explicárselo todo de nuevo, y el proyecto queda documentado para cualquier compañero.
- **Uso responsable.** No paso datos sensibles a la IA sin necesidad, dejo las credenciales fuera del código y no doy por bueno nada generado sin revisarlo. Para publicar proyectos genero **datos sintéticos** con la misma estructura que los reales, en lugar de exponer datos de clientes.

---

## 🛠 Habilidades Técnicas

- **Gestión de Datos:** Procesos ETL (extracción, transformación y carga de datos), diseño de ETL complejas, limpieza y preparación de datos, calidad y validación de datos, creación y automatización de procesos con Jobs de SQL Server (SQL Server Agent) y ETL automatizadas en producción con ejecución programada
- **Migración de Datos:** Migraciones entre sistemas, análisis de modelos de datos desconocidos, mapeo de esquemas y catálogos (también asistido por IA), carga con tablas de staging y backup previo, migración de ficheros a Google Cloud Storage
- **Bases de Datos:** SQL Server, MySQL, Firebird y MongoDB (diseño y creación de bases de datos, consultas avanzadas, vistas, procedimientos almacenados, manipulación y análisis de datos)
- **Lenguajes y Librerías:** Python (Pandas, NumPy, SciPy, statsmodels, SQLAlchemy, pyodbc, mysql-connector, Requests, Seaborn, Matplotlib, Plotly, GeoPandas)
- **Visualización de Datos:** Power BI Desktop y Power BI Service (dashboards interactivos, storytelling con datos, DAX, Power Query, modelado en estrella, integración de varias fuentes, proyectos PBIP/TMDL versionados en Git, publicación con gateway de datos y refresco programado), gráficos y mapas con Matplotlib, Seaborn, Plotly y GeoPandas
- **IA Generativa y Agentes:** Claude Code (skills, agentes y subagentes, hooks, plugins, servidores MCP), automatización de flujos de trabajo con agentes de IA, prompt y context engineering, revisión y validación de código, SQL y DAX generados por IA, generación de datos sintéticos y anonimización
- **Análisis Estadístico:** EDA, pruebas de normalidad (Shapiro-Wilk), ANOVA, Kruskal-Wallis, pruebas post-hoc (Tukey HSD, Dunn), correlaciones (Pearson, Spearman, Kendall), regresión, inferencia estadística
- **Cloud y Plataformas de Datos:** Snowflake (stages, COPY INTO, JSON/VARIANT, Streamlit), Databricks, Microsoft Fabric (lakehouse, Delta Lake, publicación de informes), Microsoft Azure y Google Cloud Storage
- **Integración de APIs:** Consumo de APIs REST (paginación, autenticación con API key y OAuth2) y carga de los datos en un data warehouse
- **Servidores y Automatización:** Windows Server, SQL Server, Programador de tareas de Windows, PowerShell, On-premises Data Gateway, Microsoft Entra ID y acceso remoto desatendido
- **Metodología y Control de Versiones:** Scrum (sprints, Kanban, retrospectivas), Git y GitHub

---

## 🎓 Formación y certificaciones

- **Bootcamp en Data Analytics**, IT Academy (Barcelona Activa), 2024–2025
- **Licenciatura en Economía**, Università degli Studi di Napoli Parthenope
- **Snowflake Hands-On Essentials: Data Warehousing Workshop**, Snowflake, 2025
- **Databricks Fundamentals**, Databricks, 2025
- **Formación en Microsoft Fabric y Azure** (lakehouse, Delta Lake), Microsoft Learn, 2025

---

## 📂 Proyectos

- [Automatización de migraciones de datos con agentes de IA](https://github.com/Giusebuompane/automatizacion-migraciones-ia): el método con el que hago migraciones con Claude Code. Incluye la documentación en 4 capas para los agentes, el protocolo con reglas aprendidas de errores reales, un prompt de arranque, una skill de validación y un validador automático de CSV.
- [Dashboard financiero para los clientes de una asesoría](https://github.com/Giusebuompane/dashboard-contable-powerbi-firebird-sqlserver): ETL en Python de Microdata (Firebird) a SQL Server con ejecución diaria, modelo semántico y medidas DAX (IVA a liquidar, saldo en bancos, márgenes), publicación con gateway y datos de demostración sintéticos. Incluye el `.pbix` para probarlo.
- [Migración de datos de una clínica: de Cliniwin a Flowww](https://github.com/Giusebuompane/migracion-datos-clinica-sqlserver-mysql): migración completa de SQL Server a MySQL, con análisis del origen, ETL en Python y SQL, carga con staging y migración de documentos y fotos.
- [Huellas del Mundo](https://github.com/Giusebuompane/Proyecto-Huellas-del-Mundo): análisis del turismo extranjero en España con datos oficiales del INE: ETL de varios datasets, EDA, pruebas estadísticas, mapas con GeoPandas y dashboard en Power BI.
- [ProjecteData](https://github.com/Giusebuompane/ProjecteData): simulador empresarial de IT Academy, trabajando como analista en un departamento de datos con sprints semanales.

---

## 📫 Contacto

- 🌐 [LinkedIn](https://www.linkedin.com/in/giuseppebuompane/)
