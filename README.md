# Capitulo V: Product Implementation, Validation and Deployment 
### 5.2.1. Sprint 1
Durante el Sprint 1 se planifico y se definió la implementación de la primera versión del landing page de HydroSmart. En este se establecio la propuesta de valor además de información necesaria para convencer al cliente. El trabajo planificado incluyó tanto la orgnización de la estructura y diseño visual, cómo funcionalidades esenciales como la internacionalización y sistema responsivo. 

#### 5.2.1.1. Sprint Planning n.

| Sprint #                          | Sprint 1                                                                                                                                                                                                                                                                                                               |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**    |                                                                                                                                                                                                                                                                                                                        |
| **Date**                          | 2026-04-19                                                                                                                                                                                                                                                                                                             |
| **Time**                          | 8:00 PM                                                                                                                                                                                                                                                                                                                |
| **Location**                      | Reunion virutal (Google Meet)                                                                                                                                                                                                                                                                                          |
| **Prepared By**                   | Yeira Shari Huaman Olivos                                                                                                                                                                                                                                                                                              |
| **Attendees to Planning Meeting** | - Angelo Stephano Moscoso Bejar <br/> - Keyner Ivan Hancco Poma<br/> - Gabriela Luciana Tirado Carrera<br/> - Yeira Shari Huaman Olivos<br/> - Diego Ismael Guevara Serrano                                                                                                                                                         |
| **Sprint 1 Goal**                 | La meta para este sprint es que la landing page MVP DE HydroSmart sea atractiva, informativa, responsiva e internacionalizada.<br/>Creemos que esto aportará confianza y afianzará a nuestros usuarios. Esto se confirmará cuando los usuraios puedan navegar y registrarse satisfactoriamente mediante la landing page. |
| **Sprint 1 Velocity**             | 8 story points                                                                                                                                                                                                                                                                                                         |
| **Sum of Story Points**           | 8                                                                                                                                                                                                                                                                                                                      |

### 5.2.1.2. Aspect Leaders and Collaborators
| Team Member                      | GitHub Username | Header | Hero + Beneficios | Características | Planes | Nosotros | FAQ+ Footer |
|----------------------------------|-------------|--------|-------------------|-----------------|--------|----------|-------------|
| Huaman Olivos, Yeira Shari       | YeiShari    | L      | L                 | C               | C      | C        | C           |
| Moscoso Bejar, Angelo Stephano   | StephanoDang| C      | C                 | L               | C      | C        | C           |
| Tirado Carrera, Gabriela Luciana | Gaby0443    | C      | C                 | C               | L      | C        | C           |
| Hancco Poma, Keyner Ivan         | 1Kanan2| C      | C                 | C               | C      | C        | L           |
| Guevara Serrano,Diego Ismael     | Digetto     | C      | C                 | C               | C      | L        | C           |

### 5.2.1.3. Sprint Backlog 1
El Sprint 1 se enfocó en el desarrollo e implementación del Landing Page MVP de HydroSmart, desplegado en un entorno web, utilizando HTML, CSS y JavaScript.

El objetivo principal fue entregar una solución mínima viable que permita a los usuarios comprender claramente la propuesta de valor de la plataforma, junto con una interfaz adaptable a distintos dispositivos y capaz de soportar otro idioma mediante un enfoque de internacionalización.

<table border="1" cellspacing="0" cellpadding="8" style="border-collapse: collapse; width: 100%; text-align: center; font-family: Arial, sans-serif;">
  <thead>
    <tr>
      <th colspan="2">Sprint #</th>
      <th colspan="6">Sprint 1</th>
    </tr>
    <tr>
      <th colspan="2">User Story</th>
      <th colspan="5">Work-Item / Task</th>
      <th rowspan="2">Status<br>(To-do / In-Process / To-Review / Done)</th>
    </tr>
    <tr>
      <th>Id</th>
      <th>Title</th>
      <th>Id</th>
      <th>Title</th>
      <th>Description</th>
      <th>Estimation (Hours)</th>
      <th>Assigned To</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td >US18</td>
      <td>Visualización de propuesta de valor</td>
      <td>T01</td>
      <td>Diseño de Hero</td>
      <td>Implementar la sección principal con título, mensaje de valor y llamada inicial de HydroSmart.</td>
      <td>3</td>
      <td>Huaman Olivos, Yeira Shari</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US18</td>
      <td>Visualización de propuesta de valor</td>
      <td>T02</td>
      <td>Implementación de beneficios clave</td>
      <td>Agregar los beneficios principales del producto dentro de la sección Hero para reforzar la propuesta de valor.</td>
      <td>2</td>
      <td>Huaman Olivos, Yeira Shari</td>
      <td>Done</td>
    </tr>
<tr>
      <td>US19</td>
      <td>Visualización de funcionalidades</td>
      <td>T03</td>
      <td>Diseño de sección de características</td>
      <td>Construir la sección visual donde se presentan las funcionalidades principales de HydroSmart.</td>
      <td>3</td>
      <td>Moscoso Bejar, Angelo Stephano</td>
      <td>Done</td>
    </tr>
<tr>
      <td>US20</td>
      <td>Visualización de segmentos objetivo</td>
      <td>T05</td>
      <td>Diseño de sección de segmentos</td>
      <td>Implementar la sección que muestra los perfiles objetivo de la plataforma y sus beneficios asociados.</td>
      <td>3</td>
      <td>Guevara Serrano, Diego Ismael</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US20</td>
      <td>Visualización de segmentos objetivo</td>
      <td>T06</td>
      <td>Integración de FAQ relacionado</td>
      <td>Agregar preguntas frecuentes vinculadas a los segmentos objetivo para reforzar la comprensión del usuario.</td>
      <td>2</td>
      <td>Hancco Poma, Keyner Ivan</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Navegación por secciones</td>
      <td>T07</td>
      <td>Implementación de header</td>
      <td>Desarrollar el encabezado principal con enlaces a las secciones de la landing page.</td>
      <td>2</td>
      <td>Huaman Olivos, Yeira Shari</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Navegación por secciones</td>
      <td>T09</td>
      <td>Integración de footer navegable</td>
      <td>Agregar enlaces de navegación en el footer para reforzar el acceso a las secciones principales.</td>
      <td>2</td>
      <td>Hancco Poma, Keyner Ivan</td>
      <td>Done</td>
    </tr><tr>
      <td>US22</td>
      <td>Acceso al registro desde la landing page</td>
      <td>T10</td>
      <td>Implementación de CTA principal</td>
      <td>Agregar botón principal de registro en la sección Hero para redirigir al usuario al proceso de registro.</td>
      <td>2</td>
      <td>Huaman Olivos, Yeira Shari</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US22</td>
      <td>Acceso al registro desde la landing page</td>
      <td>T11</td>
      <td>Implementación de sección de planes</td>
      <td>Agregar acciones en la sección de planes para facilitar el acceso al registro.</td>
      <td>2</td>
      <td>Tirado Carrera, Gabriela Luciana</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Visualización en dispositivos móviles</td>
      <td>T12</td>
      <td>Adaptación responsive de Hero y Header</td>
      <td>Ajustar la visualización del encabezado y la sección principal para pantallas móviles.</td>
      <td>3</td>
      <td>Huaman Olivos, Yeira Shari</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Visualización en dispositivos móviles</td>
      <td>T13</td>
      <td>Adaptación responsive de características</td>
      <td>Optimizar la disposición de la sección de funcionalidades para dispositivos móviles.</td>
      <td>2</td>
      <td>Moscoso Bejar, Angelo Stephano</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Visualización en dispositivos móviles</td>
      <td>T14</td>
      <td>Adaptación responsive de planes</td>
      <td>Modificar la sección de planes para asegurar correcta legibilidad e interacción en móviles.</td>
      <td>2</td>
      <td>Tirado Carrera, Gabriela Luciana</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Visualización en dispositivos móviles</td>
      <td>T15</td>
      <td>Adaptación responsive de FAQ y Footer</td>
      <td>Ajustar la sección de preguntas frecuentes y el pie de página para visualización móvil.</td>
      <td>2</td>
      <td>Hancco Poma, Keyner Ivan</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Visualización en dispositivos móviles</td>
      <td>T16</td>
      <td>Adaptación responsive de Nosotros</td>
      <td>Optimizar la sección Nosotros y segmentos objetivo para correcta visualización en dispositivos móviles.</td>
      <td>2</td>
      <td>Guevara Serrano, Diego Ismael</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US18-US23</td>
      <td>Internacionalización de la landing page</td>
      <td>T18</td>
      <td>Integración de textos traducibles</td>
      <td>Adaptar las secciones principales para consumir contenido en más de un idioma.</td>
      <td>2</td>
      <td>Todos los colaboradores</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US18-US23</td>
      <td>Pruebas y ajustes finales</td>
      <td>T19</td>
      <td>Validación funcional del sprint</td>
      <td>Verificar navegación, responsive, textos, enlaces y consistencia visual antes del despliegue.</td>
      <td>3</td>
      <td>Todos los colaboradores</td>
      <td>Done</td>
    </tr>
  </tbody>
</table>


### 5.2.1.4. Development Evidence for Sprint Review

|Repository| Branch  | Commit id | Commit message                                           | Commited on (Date) |
|-|---------|-----------|----------------------------------------------------------|--------------------|
| HydroSmart-Landing-Page| develop | cd5fbec   | feat(home): add header and initial section html.         | 19/04/2026         |
| HydroSmart-Landing-Page| develop | d1173e4   | feat(home): add header and initial section css.          | 19/04/2026         |
| HydroSmart-Landing-Page| develop | 853ccfa   | feat(home): add i18n.feat(home): add i18n.               | 19/04/2026         |
| HydroSmart-Landing-Page| develop | 86776fa   | feat(benefits): add benefits section html.               | 19/04/2026         |
| HydroSmart-Landing-Page| develop | 9662781   | feat(benefits): add benefits section css.                | 19/04/2026         |
| HydroSmart-Landing-Page| develop | 99a1ed3   | feat(suscription): add suscription plans                 | 20/04/2026         |
| HydroSmart-Landing-Page| develop | b9722ab   | feat(suscription): clean up suscription css              | 20/04/2026         |
| HydroSmart-Landing-Page| develop | a54e72c   | feat(subscription): add responsive styles to suscription | 20/04/2026         |
| HydroSmart-Landing-Page| develop | fe0ad44   | feat(suscription): updated stylesSuscription             | 20/04/2026         |
