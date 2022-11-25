# MCPP_Project - Efecto de los discursos presidenciales en las fuerzas militares (En proceso)

Proyecto para Métodos Computacionales para Políticas Públicas - Universidad del Rosario

25-11-2022

---

## Descripción  y motivación

El actual documento surge, en un principio, como parte del curso de Métodos Computacionales para Políticas Públicas. Sin embargo, la temática misma tiene importancia puesto que el análisis de las relaciones de productividad a partir de procesos de supervisión en el Estado y, principalmente en las fuerzas militares, presenta una nueva forma de analizar las relaciones entre los agentes que hacen parte del gobierno. Así pues, este proyecto muestra un análisis descriptivo de los discursos dados por el ex-presidente Álvaro Uribe Vélez entre 2002 y 2010. Además, se presentan los datos de asesinatos selectivos recolectados por el Centro Nacional de Memoria Histórica (CNMH) como resultado y variable proxy de la productividad de los agentes del Estado. Es preciso mencionar que este proyeccto tomó como base el resentado por Santiago Matallana sobre los discrusos del ex-presidente Juan Manual Santos en el marco del [Acuerdo de Paz](https://github.com/smatallana/presidential_speeches).

Algunos elementos que surgen de la motivación y del análisis de este proyecto están relacionado con las siguientes ideas:

-¿Qué efecto tuvo la mención de palabras como "seguridad", "guerrilla" y "criminales" en la ejecución de asesinatos selectivos en búsqueda de presentar mayores bajas como resultado o muestra de productividad?
- ¿Cuál era la dinámica discursiva del ex-presidente Álvaro Uribe Vélez en el marco del conflicto en Colombia?
- ¿Qué efecto tuvo la Directiva Ministerial N. 29 del 17 de Noviembre de 2005, correspondiente al Ministerio de Defensa Nacional donde se prpone la "Política Ministerial que desarrolla criterios para el pago de recompensas por la captura o abatimiento en combate de cabecillas de las organizaciones armadas al margen de la ley, material de guerra, intendencia o comunicaciones e informacion sobre actividades relacionadas con el narcotrafico y pago de informacion que sirva de fundamento para la de labores de inteligencia y el posterior planeamiento de operaciones"?
- ¿De qué manera se pueden generar bases de datos a partir de fuentes no tradicionales de tal forma que se generen análisis alternativos de las políticas públicas?

---

## Resultados (Preliminares)

Los resultados encontrados muestran que:

- Luego de la Directiva Ministerial N.29 de 2005 hay un aumento de los asesintaos selectivos en Colombia por parte de Agentes del Estado.
- Una de las palabras más repetidas por el ex-presidente en sus discursos es seguridad y, por tanto, esto muestra la importancia que tenía para él transmitir ideas sobre el tema en cuestión.
- Los asesinatos selectivos por parte de los agentes del Estado muestran un comportamiento similar al de la mención de la palabra seguridad, lo que puede sugerir dos hipótesis: había más bajas y, por tanto, el presidente hablaba del tema o, por lo contrario, (causalidad reversa) cuando el presidente de hablaba de seguridad se producían más bajas
- Bases de datos a partir de fuentes no tradicionales, como los discursos, permiten dar una mirada desde un aspecto no tradicional que puede dar cuentas del enfoque de políticas públicas y la relación entre el supervisor, en este caso el presidente, respecto a sus subordinados, los militares. De esta manera, la mención y presión a través del discurso luego de la generación de incentivos a través de la directiva ministrial ya mencionada (en conjunto) pueden dar paso a la generación de reportes de productividad individual que pueden generar resultados adversos.


---

## Metodología

Las metodologías usadas en este proyecto están basadas en análisis de datos con base en la información extraída a partir de Web Scraping de los [discrusos realizados por el ex-presidente Álvaro Uribe Vélez entre 2002 y 2003](http://historico.presidencia.gov.co/discursos/index.htm). La demás información se ha visualizado a partir de los paquetes Seaborn y Matplotlib de Python.

---

## Documentación

La documentación de este documento se encuentra almacenada en los siguientes vínculos:

- [Scraping](https://github.com/mpedrazaa/MCPP_Project/blob/main/Uribe%20-%20Scrapping.ipynb)
- [Visualización](https://github.com/mpedrazaa/MCPP_Project/blob/main/Visualizaci%C3%B3n%20de%20Datos.ipynb)
- [Base de datos de asesinatos selectivos (CNMH)](https://github.com/mpedrazaa/MCPP_Project/blob/main/asesinatos_month.csv)
