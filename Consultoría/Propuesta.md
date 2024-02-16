<p align="center">
  <img src="https://github.com/ProyectosMCD/Dieta_Codornices/assets/5826577/fd3ad789-7ef0-422c-879b-5549b413aff2" alt="drawing" width="500"/>
</p>


# PROYECTO: ANÁLISIS ESTADÍSTICO DE FACTORES QUE DETERMINAN ABUNDANCIA, DIETA Y DISTRIBUCIÓN DE LA CODORNIZ MOCTEZUMA

<p align="right"> Hermosillo, Sonora, 17 de Febrero de 2024 </p>


### Índice
1. Introducción 
2. Objetivos, metas, estrategias y acciones 
3. Planificación de la secuencia de trabajo 
4. Equipo de trabajo 
5. Requerimientos
6. Entregables 
7. Presupuesto 
8. Términos de la participación de DataAnalytics
9. Anexo: Información general sobre DataAnalytics


### 1. Introducción

La Comisión Nacional para el Conocimiento y Uso de la Biodiversidad (CONABIO) es una entidad gubernamental a nivel federal cuyo principal objetivo es gestionar el Sistema Nacional de Información sobre Biodiversidad (SNIB). Esto implica proporcionar datos, información y asesoramiento a una variedad de usuarios, así como implementar redes de información a nivel nacional y global sobre biodiversidad. 

La CONABIO tiene la misión de promover, coordinar, apoyar y realizar actividades dirigidas al conocimiento de la diversidad biológica, así como a su conservación y uso sustentable para beneficio de la sociedad.

En las últimas décadas, un tema de interés para la CONABIO han sido las codornices de Norte América, cuya conservación representa un reto actualmente debido a la disminución de sus poblaciones. Es posible que los cambios climáticos y la pérdida del hábitat afecten negativamente en la disponibilidad y calidad de los alimentos, especialmente en zonas áridas donde el alimento puede ser escaso. Bajo este contexto, se pretende investigar qué factores determinan la abundancia, dieta y distribución de la codorniz moctezuma (Cyrtonyx montezumae), un ave que se encuentra en los pastizales desérticos y los bosques de encinos, cuyos resultados podrían ser clave para entender la persistencia de la codorniz moctezuma en el suroeste de los Estados Unidos y norte de México.

El alcance de este proyecto, propone en una primera fase desarrollar un análisis estadístico descriptivo, con base en los datos que proporcione la CONABIO sobre la codorniz moctezuma. De encontrar resultados favorables y de interés para la CONABIO, se plantea en una segunda fase desarrollar un modelo que permita la creación de indicadores relacionados a la abundancia, distribución y dieta de la codorniz moctezuma, dando a su vez lugar para que la CONABIO pueda implementar políticas públicas basadas en conocimiento confiable para conservar la riqueza natural de México.



### 2. Objetivos, metas, estrategias y acciones

<table class="table table-bordered">
  <thead class="thead-dark">
    <tr>
      <th>Fase</th>
      <th>Objetivo</th>
      <th>Meta</th>
      <th>Estrategia</th>
      <th>Acción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Fase 1</td>
      <td style="vertical-align: top;">
        <ol>
          <li>Revisión del documento "Dieta invernal de la codorniz Moctezuma (Cyrtonyx montezumae) en Arizona y Nuevo México" que contiene el marco teórico y el trabajo de investigación proporcionado por la CONABIO.</li>
          <li>Revisión exploratoria de la base de datos, proporcionada en un archivo Excel, respecto a las cosechas de codornices que se han realizado.</li>
          <li>Conceptualización y análisis estadístico inicial de manera general y rápida.</li>
          <li>Diseño y construcción de análisis exploratorio de datos, haciendo un análisis más profundo de la información.</li>
          <li>Reunión para revisión de resultados y formalización de los siguientes pasos a partir de lo encontrado y planeado en las siguientes fases.</li>
        </ol>
      </td>
      <td style="vertical-align: top;">
        <ol>
          <li>Reporte inicial de los resultados obtenidos del análisis estadístico.</li>
          <li>Presentación inicial de los primeros hallazgos estadísticos.</li>
          <li>Reporte formal de los resultados obtenidos a partir del análisis exploratorio de datos.</li>
          <li>Reunión y presentación de los datos obtenidos de una revisión a detalle y profunda.</li>
          <li>Plan de acción y el paso concreto a seguir en las siguientes etapas del proyecto.</li>
        </ol>
      </td>
      <td style="vertical-align: top;">
        <ol>
          <li>Entender la razón principal del proyecto, así como todas las partes involucradas que ayuden a determinar las técnicas estadísticas pertinentes que se utilizarán.</li>
          <li>Trabajar en lo máximo posible con los datos que se tengan actualmente y aprovecharlos de manera responsable y óptima para llegar a un resultado que apoye a la investigación.</li>
          <li>Aplicar técnicas de limpieza y transformación de los datos sin alterar su esencia, para con esto lograr una mejor interpretación y preparación para la estadística a utilizar.</li>
        </ol>
      </td>
      <td style="vertical-align: top;">
        <ol>
          <li>Reunión con el equipo interno de trabajo de DataAnalytics para plantear las estrategias a seguir.</li>
          <li>Reuniones con el equipo asesor de la CONABIO, quienes requieren la solución.</li>
          <li>Uso de herramientas y librerías para estadística y lenguajes como Python para implementar la solución y visualización de los datos.</li>
          <li>Determinación de las formas y línea de entrega y recepción de los datos.</li>
          <li>Se dejará a disposición las diferentes tablas $tidy$ que pudiesen ser creadas.</li>
          <li>Elaboracón de los distintos entregables.</li>
        </ol>
      </td>
    </tr>
    <!-- Aqui va la fase 2 o las otras fases, agregando más filas según sea necesario -->
    <tr>
  <td>Fase 2</td>
  <td style="vertical-align: top;">
    <ol>
      <li>Aplicar métodos de remuestreo y bootstrapping, para estimar incertidumbres en las estimaciones, en especial al trabajar con muestras pequeñas como es el caso.</li>
      <li>Realizar análisis multivariado y de series temporales, para identificar patrones, tendencias en la dieta de la codorniz y su relación con variables climáticas, ambientales y de sujeto.</li>
      <li>Desarrollar Modelo de preferencia alimentaria: que identifique las preferencias alimentarias de la codorniz Moctezuma en función de variables ambientales y de sujeto.</li>
    </ol>
  </td>
  <td style="vertical-align: top;">
    <ol>
      <li>Reporte formal, que documente todos los resultados obtenidos en la fase 2 del proyecto.</li>
      <li>Preparar una presentación para compartir los resultados obtenidos con el cliente y otros interesados.</li>
    </ol>
  </td>
  <td style="vertical-align: top;">
    <ol>
      <li>Identificar las variables clave, patrones y tendencias en los datos.</li>
      <li>Interpretar los resultados y extraer conclusiones significativas sobre la dieta de la codorniz Moctezuma.</li>
      <li>Desarrollar, ajustar y validar el modelo (Validación Cruzada, etc).</li>
    </ol>
  </td>
  <td style="vertical-align: top;">
    <ol>
      <li>Reuniones con el equipo asesor de la CONABIO para discutir el progreso del proyecto, revisar los resultados obtenidos y recibir retroalimentación sobre las decisiones.</li>
      <li>Utilizar herramientas y librerías para estadística en lenguajes Python para implementar el modelo de preferencia alimentaria.</li>
      <li>Diseñar y llevar a cabo sesiones de capacitación para el personal de CONABIO sobre el uso y la interpretación del modelo desarrollado.</li>
      <li>Elaboración de los distintos entregables.</li>
    </ol>
  </td>
</tr>

  </tbody>
</table>

### 3. Planificación de la secuencia de trabajo



### 4. Equipo de trabajo 



### 5. Requerimientos

- Asesor experto de la CONABIO que proporcione información necesaria y mantenga el flujo de comunicación con el equipo de DataAnalytics.  

- Fuentes de datos: bases de datos, archivos excel, o cualquier documento que contenga los datos a analizar.
  
- Documentación adicional que enriquezca el contexto del problema y propocione detalles de utilidad para la realización de este proyecto.
  
### 6. Entregables 

- Plan de Proyecto: documento formal que detalla los objetivos del proyecto, los datos disponibles, las preguntas de investigación y los requisitos específicos del cliente. 
  
- Base de Datos $tidy$: datos limpios y preparados con los que se realiza el análisis.
  
- Análisis Exploratorio de Datos (EDA): documento que incluye gráficos y estadísticas descriptivas para explorar la distribución y la relación entre variables de los datos.
  
- Código en Python: código generado para la realización del análisis que incluye gráficos y visualizaciones, así como también de los modelos desarrollados (en caso de aplicar).
  
- Informe de Resultados: documento formal y detallado que presenta los resultados del análisis, incluyendo interpretaciones, conclusiones y recomendaciones basadas en los hallazgos.

- Presentación Ejecutiva de Resultados

- Transferencia de Conocimientos: sesiones de capacitación para el personal de la CONABIO sobre el uso de los resultados del análisis estadístico y la interpretación de los modelos desarrollados (en caso de aplicar).

### 7. Presupuesto 



### 8. Términos de la participación de DataAnalytics

#### Proceso de Pago de los Servicios
El procedimiento de pago para los servicios prestados por DataAnalytics se realiza de la siguiente forma: 
- Pago inicial del 50%
- Liquidación del 50% restante al concluir el proyecto. 



### 9. Anexo: Información general sobre DataAnalytics

DataAnalytics es una empresa que proporciona soluciones estadísticas precisas y estratégicas para satisfacer las necesidades de nuestros clientes en la toma de decisiones, aportando valor mediante el análisis y la interpretación de datos.

Dentro de los servicios que ofrecemos se encuentran: análisis estadístico de datos, desarrollo de modelos predictivos y descriptivos, diseño experimental, desarrollo de software tales como visualizaciones interactivas y gráficos informativos, capacitación y asesoramiento personalizado en estadística y análisis de datos, entre otros.

En DataAnalytics contamos con un equipo de trabajo multidisciplinario que nos permite abordar problemas de distintas áreas y diferente complejidad, para ofrecer soluciones a medida, eficientes e innovadoras, que cumplan con los objetivos y expectativas de nuestros clientes.




