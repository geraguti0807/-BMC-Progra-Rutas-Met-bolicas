Proyecto #2 Comparación de Rutas Metabólicas 

IC-8022 Introducción a la Biología Molecular Computacional 

Tecnológico de Costa Rica, Sede Central Cartago 

Escuela de Computación, Ingeniería en Computación 

I Semestre 2019 

Prof. Ing. Esteban Arias Méndez

La comparación de rutas metabólicas es una operación importante hoy en día para el estudio de metabolismo aplicable en múltiples áreas de interés como medicina, agricultura, farmacia, biotecnología y otros.

INTRODUCCIÓN

Propósitos

➢ Aplicar conocimientos aprendidos sobre alineamiento y comparación en estructuras de datos más complejas a las lineales como las usadas hasta ahora.
➢ Poner en práctica la evaluación de algoritmos para su validación, uso y pruebas. 

DESARROLLO 

Utilizando los algoritmos propuestos por el profesor deberá evaluarlos para verificar su utilidad como mecanismo para comparar rutas metabólicas. 
Se trabajará sólo sobre el Sistema Operativo Linux, usando solamente lenguajes C o Python. Se recomienda trabajar su código en módulos, funciones o procedimientos, incluso en varios archivos para facilitar el trabajo. Debe hacer uso del git de la Escuela de Computación para llevar todo el desarrollo de su proyecto: git.ec.tec.ac.cr 
Este trabajo es para ser desarrollado por parejas de 2 personas máximo. 
Para su proyecto deberá trabajar realizando las siguientes actividades: 
1. Investigar sobre el problema de comparación de rutas metabólicas, indicar porqué el mismo es importante. Refiérase con fuentes documentadas al costo computacional que se ha descrito y herramientas que se han usado hasta ahora para tal fin. Incluya esta información en su marco teórico en la introducción. 
2. Se deben consultar Bases de Datos de rutas metabólicas y documentar los formatos en que se pueda accesar dicha información de forma automática (textual). Si bien se trabajará con la base de datos Kegg, consulte sobre otras bases de datos e indique ventajas de la base Kegg sobre las otras. 
3. Buscar rutas metabólicas de ejemplo (preferiblemente de la base Kegg), al menos 6 rutas, obtener su diagrama gráfico y su formato descrito en texto (las reacciones). Debe considerar rutas que tengan similitud (procesos similares) y rutas diferentes, para evaluar las comparaciones. 
4. Las versiones de los algoritmos 1.1 a 1.5 están pensados en grafos generales y no exclusivamente en rutas. Sin embargo, aplique las 5 versiones de los algoritmos a los grafos asociados a las rutas metabólicas. En el caso de los algoritmos que reciben parámetros, haga al menos 3 pruebas con parámetros diferentes con cada algoritmo para cada par de grafos de entrada. Luego de trabajar con las rutas, diseñe 3 sets de pares de grafos, un par de grafos con pocos nodos (menos de 10), un segundo par de tamaño mediano de (20 a 40 nodos), un último set de grafos grandes (más de 60 nodos cada uno) y aplique las 5 versiones de algoritmos a todos los pares de grafos creados, tenga en cuenta usar varios parámetros en cada ejecución (al menos 3). Mezcle grafos de distinto tamaño y vuelva a aplicar los algoritmos. Tabule sus resultados y haga observaciones al respecto de los resultados. 
5. Cada ruta y grafo de trabajo deberá escribirlos en un formato de archivo de texto tipo json o similar, para que sea fácil crearlos, guardarlos y cargar los datos a los programas. Describa en su documentación el formato de archivo creado y cómo procesarlo. 
6. Implemente y aplique los algoritmos provistos a sus archivos de entrada a sus 6 rutas para obtener similitudes y diferencias entre todas las rutas, todas las posibles combinaciones. Igualmente para los grafos creados como se indicó previamente. 
7. Investigar sobre herramientas actuales de comparación (al menos 2 más, tanto de rutas metabólicas como de grafos) y hacer pruebas de comparación de sus 6 rutas y los 6 grafos creados en estas herramientas de software existentes, de forma tal que pueda comparar los resultados de los algoritmos implementados y el de las herramientas existentes. 
8. Compare los datos obtenidos de similitud entre las herramientas encontradas y los algoritmos propuestos. Debe plantear una forma de tomar los datos de valoración y normalizarlos para poder compararlos. Explique sus procedimientos. 
9. Luego de las pruebas realizadas, deberá tabular la información y generar conclusiones al respecto de los algoritmos dados y los usados por otras herramientas. 10. Brinde recomendaciones de mejora sobre los algoritmos. ¿Hay alteraciones en los resultados con datos con pocos nodos o muchos nodos? Indique que otros aspectos deben considerarse sobre el comportamiento de los algoritmos. Al utilizar como parámetros de entrada los mismos datos para el grafo A como para el grafo B, los algoritmos deben indicar que las rutas son prácticamente idénticas, ¿se logra obtener dichos resultados?, explique sus pruebas, valores y comentarios al respecto. 
11. Proponga una modificación a los algoritmos 1 y 2 que permita considerar pesos en los arcos de los grados descritos. Implemente las propuestas y realice comparaciones con 3 rutas y 3 grafos (2 que sean similares y 1 diferente) para que pueda comparar los resultados. Entre los datos a mostrar debe indicar el valor total de los pesos al sumarlos, como parte de la información al usuario. 
12. Debe hacer pruebas de alineamiento con los 3 métodos (global, local y semiglobal) y con ambos tipos de recorrido (anchura y profundidad), para cada posible combinación de las 6 rutas y los 6 grafos de trabajo y para cada cambio de parámetros que realice, para validar la información. El programa puede mostrar los datos usando los nombres originales en las rutas o bien nombres codificados usando letras para simplificar el alineamiento, en cuyo caso debe brindar el diccionario de datos de traducción de nombres para comprensión del usuario. 
13. Puede usar un programa de terceros para generar automáticamente las imágenes de sus grafos como archivos, por ejemplo, la biblioteca Graphviz o similar. 
Notas: 
Como se indicó, para las rutas de trabajo debe usar rutas de procesos similares entre organismos distintos, por ejemplo, y de procesos diferentes para realizar las comparaciones. Los grafos deben ser todos diferentes entre los grupos de trabajo. 
Cada pareja de trabajo debe usar 6 rutas diferentes entre sí. Pueden ponerse de acuerdo entre parejas si quieren compartir datos entre rutas similares corridas entre cada pareja, por ejemplo, para trabajar una ruta en común o un organismo en particular. Pero los grupos deben usar rutas 
diferentes. Los grafos pueden compartirlos para comparaciones adicionales, pero cada pareja debe tener grafos distintos 
Tome como referencia para los algoritmos las presentaciones vistas en clase, disponibles en el material digital del curso: 
- 07 - 20170509 - comparación de rutas metabólicas.pptx - 08 - 20180718_Simple_Graph_Comparison.pptx 
Los algoritmos por implementar son el 1 y 2 descritos en la presentación 07, y las versiones 1.1 a 1.5 de la presentación 08. 
No se proveen los algoritmos de alineamiento. Deberá coordinar con sus compañeros de curso, para que todos usen el mismo código de alineamientos global, local y semiglobal en Python o C. Todos deben usar el mismo código para que las pruebas y resultados obtenidos entre todos sean homólogas. 
Use recorridos de los grafos por anchura o por profundidad, tanto para las rutas como para los grafos. 
EVALUACIÓN 
1. Rúbrica de evaluación: 
- El proyecto se calificará con los siguientes criterios: 
i. 80% - Pruebas completas de sus rutas y grafos, comparación entre todas ellas usando ambos recorridos de grafos y los 3 tipos de alineamientos para cada par de rutas y grafos comparados, con sus respectivos cambios de parámetros cuando se requiere. Proveer conclusiones relevantes sobre el proceso y recomendaciones sobre los algoritmos, resultados, implementación y el texto dado. ii. 20% - Documentación completa del trabajo. 
2. El proyecto debe resolverse, implementándolo de la mejor manera. 
3. De forma global, se evaluará la presentación del trabajo según los parámetros solicitados, estrategias empleadas y la calidad, la entrega a tiempo del trabajo y la documentación completa correspondiente. 
4. Sobre la documentación y presentación: 
a. 2pts - El subject del correo a ser enviado debe ser: 
[BMC] – Proyecto 2 Rutas Metabólicas – Sus Nombres Completos b. 2pts - El correo debe contener de forma separada: 
i. los archivos de texto de los códigos fuentes que permiten 
la solución y funcionalidad de este. ii. un archivo PDF con la documentación completa 
No envíe archivos ejecutables o binarios. 
c. La documentación en PDF con el nombre de archivo igual al subject del correo enviado. Esta documentación debe tener un apartado, que indique los pasos a seguir, para poder ejecutar el código (librerías a instalar y otros). 
i. 5pts – La documentación debe incluir una portada con los datos completos: TEC, carrera, sede, curso y código, profesor, periodo, fecha de entrega, número de proyecto, título del 
proyecto, nombres completos con número de carnet de la pareja de trabajo y un abstract en inglés en la misma portada. ii. 5pts – La introducción del documento es una descripción breve del trabajo realizado y herramientas usadas. Como mini-marco teórico incluya las referencias a los algoritmos implementados y las herramientas empleadas, así como otras fuentes de consulta utilizadas. iii. 10pts – Como desarrollo debe explicar, los procedimientos, rutinas, la lógica que utilizo para resolver el problema. indicar los ejemplos de código que ha usado como guía para el desarrollo de los mismos usando las referencias bibliográficas correspondientes. Explicar el uso y funcionamiento. iv. 20pts – Análisis de resultados, explicando el trabajo implementado, la forma de realización, funcionamiento, general, ejemplos documentados, problemas presentados, estructuras de datos empleadas, algoritmos usados, etc. v. 10pts – Una sección de conclusiones y/o observaciones sobre el 
proyecto. vi. 10pts – En una sección de Apéndices incluya el código fuente documentado del proyecto y su explicación. Explique la estructura del código empleada en su proyecto, módulos, etc. antes de incluir su código. 
5. La tarea puede realizarse de forma individual o en parejas de 2 
máximo. 
6. Se debe entregar en digital a más tardar el Lunes 6 de Mayo, antes de la media noche. Debe hacerlo de forma simultánea al correo siguiente y copiarse usted mismo y su compañero de trabajo. Cada día de atraso serán 15pts menos de la nota de la tarea: 
a. earias@ic-itcr.ac.cr 
7. Cualquier consulta puede hacerla al foro, o personalmente en clase o al correo del profesor con copia al asistente a los correos anteriores. 
8. Durante la revisión del proyecto deben estar presentes ambos miembros de la pareja de trabajo, la no presentación les restará 10pts a cada uno de los ausentes. 
